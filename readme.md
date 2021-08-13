# Shoptet addon assets

# Installation
1. Install package `yarn add shoptet-addon-assets`
2. Import scss `@import "~shoptet-addon-assets/src/scss/shoptet"`
3. Import fonts in your <head>
    ```
    <style>
    @import url('https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700&display=swap&subset=latin-ext');
    @font-face {
      @import "{{ $baseUrl . '/temp/static/font/shoptet/shp.ttf?keh8vo' }}";
      @import "{{ $baseUrl . '/temp/static/font/shoptet/shp.woff?keh8vo' }}";
      @import "{{ $baseUrl . '/temp/static/font/shoptet/shp.svg?keh8vo' }}";
      font-family: 'shp';
      font-weight: normal;
      font-style: normal;
    }
    <style>
    ```