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
