# Api Test v1.0

# Sails - Generate API

```
ember generate api recipes
```

#  Sails fixtures - Modified in config/local.js


```javascript
module.exports = {
  fixtures: {
    order: ['Recipes'],
    overwrite: ['Recipes'],
    Recipes: [
      {
        title: 'Breads',
        type: 'Salad',
        description: "The best recipe"
      },
      {
        title: 'Bakes',
        type: 'Sweet',
        description: "The best recipe"
      },
      {
        title: 'Pizza',
        type: 'Salad',
        description: "The best recipe"
      }
    ]
}
```

## Recursos
* [Sails.js] (http://sailsjs.org)

* [Sails hook fixtures] (https://github.com/arryon/sails-hook-fixtures)

* [Sails generate ember blueprints] (https://github.com/mphasize/sails-generate-ember-blueprints) Modify the json format

* [RESTClient Firefox] (https://addons.mozilla.org/es/firefox/addon/restclient/) Testing the services