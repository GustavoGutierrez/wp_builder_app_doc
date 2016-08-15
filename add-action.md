# Add Action

Para agregar una acción desde la clase del plugin se debe seguir una convención de nombres esta convencion de nombre esta dada por lo siguiente:

![](/assets/add_action_in_plugin.jpg)

Donde la el nombre del metodo definido en la clase del plugin debe empesar con \(action\) el segundo es el nombre espesifico para organización de la acción, el tercero que es es opcional es el tag de la acción que por defecto es init; el ultimo parametro por convención en el nombre del metodo seria la prioridad que tambien es un parametro optional y que por defecto es 10.

De esta forma se pueden crear acciones dentro del cualquier plugin que seran ejecutadas por Wordpress en el momento que se ejecute la accion definida por el tag.

Un ejemplo seria el siguiente

```
class MyPlugin extends Plugin{ 

    action_myAccionPersonalizada_init_1000{
        //Aquí creamos todo los código necesario que se ejecute en esta acción
    }

}
```



