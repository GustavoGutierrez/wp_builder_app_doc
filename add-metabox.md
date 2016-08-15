# Add Metabox

Para agregar un metabox desde la clase del plugien se debe seguir la siguente convención de nombres que facilitan la implementación de metabox.

La convención en los nombres de los metodos que se agregaran como metabox se deben escribir de la siguiente manera:

![](/assets/add_metabox_in_plugin.jpg)

Como se ve en la grafica anterior el nombre del metodo debe empesar con metabox, el segundo parametro en el nombre es el titulo del metabox en camel case ademas este titulo se utilizara tambien para el id del metabox, el tercer parametro que se indica en el nombre son los post types que se quieren asociar al metabox en esta tercera parte del nombre se pueden proporcionar varios nombres de posttype tambien enformato camel case separados por guien bajo estos se agruparan en un array que se le proporcionará al metabox creado, el ultimo parametro que es opcional se trata de la prioridad que tendra el metabox que por defecto es default.

Teca presente que dependiendo de la prioridad que se proporcione estos metabox seran agregados en orden acendente entre todos los metodos que cree dentro de la clase del plugin.



