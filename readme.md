fixed-table-header is a Stylus function which allows to add a fixed header to v-data-table.

## Install
```
$ npm install --save vuetify-stylus-fixed-table-header
```

## Usage
```styl
@import '~vuetify-stylus-fixed-table-header';
```

Call function inside your table selector and specify maximum height for table.
```styl
.fixed-header {
    fixed-table-header(65vh)
}
```

You can also specify different height for different media queries by providing hash to function argument.
```styl
$heights = {};

$heights['only screen'] = 65vh;
$heights['only screen and (max-width: 959px)'] = 50vh;

fixed-table-header($heights)
```
