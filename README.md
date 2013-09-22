pycharm-ide-settings
====================

useful PyCharm/Webstorm settings

# Live Templates
Live templates expand abbreviations to their source code template. Using live templates saves time writing code and makes you more productive.

## Backbone Live Templates:

### Views
* ```bvi``` - creates a Backbone View. See [template source code](https://github.com/sinnwerkstatt/pycharm-ide-settings/blob/master/config/templates/JavaScript.xml#L209).

```
var $VIEWNAME$View = Backbone.View.extend({
    tagName: '$TAG_NAME$',
    $CONTENT$
});
```

### Routers
* ```brou``` - creates a Backbone Router. See [template source code](https://github.com/sinnwerkstatt/pycharm-ide-settings/blob/master/config/templates/JavaScript.xml#L231).

```
var $ROUTNAME$Router = Backbone.Router.extend({
    routes: {
        "$ROUTE$" :   "$FUNCTION_NAME$"
    },

    $FUNCTION_NAME$: function(){

    }
});

```
