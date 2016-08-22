# json-schema-elements

Some polymer elements for rendering a json schema

This is an early primitive version.

> Currently the element will only work with de-referenced schemas and only a subset of the schema definition.


# Install

```
git clone git@github.com:PieLabs/json-schema-elements.git
cd json-schema-elements
bower install
polyserve
```

Demo is located at http://localhost:8080/components/json-schema-elements/demo/index.html

## Usage

```html
  <link rel="import" href="../json-schema-elements/json-schema-elements.html"/>
  <json-schema schema="{{mySchema}}"></json-schema>
```
