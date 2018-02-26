# dropdown-menu

A Polymer Element showing a stylized dropdown menu.

### Example
```js
var data = [{
  title: 'Choice 1',
  value: '1'
}, {
  title: 'Choice 2',
  value: '2'
}];
```

```html
<dropdown-menu
  data="[[data]]"
  empty-item-title="No Choice"
  label="Choices"
  selected="{{selected}}">
</dropdown-menu>
```

### Styling

`<dropdown-menu>` provides the following custom properties and mixins for styling:

Custom property         | Description                                                      | Default
------------------------|------------------------------------------------------------------|--------
`--dropdown-menu-mixin` | The custom style mixin for the dropdown menu.                    | none
`--dropdown-menu-width` | The width for the dropdown menu.  Overrides `large` and `small`. | 120px

### Dependencies

Dependencies are installed using [Bower](http://bower.io/):

    npm install -g bower
    bower install

### Testing

Tests are run using [web-component-tester](https://github.com/Polymer/web-component-tester):

    npm install -g web-component-tester
    wct

### Demonstration & Documentation

Demonstration and documentation are viewed using [polyserve](https://github.com/PolymerLabs/polyserve):

    npm install -g polyserve
    polyserve

