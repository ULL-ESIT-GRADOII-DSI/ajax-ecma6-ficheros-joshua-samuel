# Práctica 2: Comma separated values (CSV) with AJAX

#ETSII ULL Grado de Informatica

For more information look at:


**Dirección del campus virtual**

* [Enunciado de la práctica](https://campusvirtual.ull.es/1516/mod/page/view.php?id=189370)
* [Gitbook con el enunciado](https://casianorodriguezleon.gitbooks.io/pl1516/content/practicas/csv.html)

**Repositorio GitHuB**

* [FORK](https://github.com/Losnen/ajax-ecma6-ficheros-joshua-samuel)
* [Repositorio de entrega](https://github.com/ULL-ESIT-GRADOII-DSI/ajax-ecma6-ficheros-joshua-samuel)

**Página de la práctica**

* [Despliegue en Heroku](https://csv-ajac-dsi.herokuapp.com/)

**Página del autor**

* [Samuel Ramos Barroso](http://losnen.github.io/)
* [Joshua Pérez](http://joshuape.github.io/)

## jQuery.get( url [, data ] [, success ] [, dataType ] )
* url
  * Type: String
  * A string containing the URL to which the request is sent.
* data
  * Type: PlainObject or String
  * A plain object or string that is sent to the server with the request.
* success
  * Type: Function( PlainObject data, String textStatus, jqXHR jqXHR )
  * A callback function that is executed if the request succeeds.
    Required if `dataType` is provided, but you can use `null` or `jQuery.noop` as a placeholder.
* dataType
  * Type: String
  * The type of data expected from the server. Default: Intelligent Guess (xml, json, script, text, html).

## jQuery.get( [settings ] )
* settings
  * Type: PlainObject
  * A set of key/value pairs that configure the Ajax request.
  * All properties except for `url` are optional.
  * A default can be set for any option with `$.ajaxSetup()`.

This is a shorthand Ajax function, which is equivalent to:

```javascript
$.ajax({
  url: url,
  data: data,
  success: success,
  dataType: dataType
});
```

The success callback function is passed the returned data, which will be an XML root element, text string, JavaScript file, or JSON object, depending on the MIME type of the response. It is also passed the text status of the response.

# Heroku
https://cvsajax.herokuapp.com/
