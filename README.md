# html2wxml-java

This is an open source Java library that converts HTML to WeChat WXML.

*** Please note that this project is still WIP ***

## Examples

### Convert a web page to WXML
```sh
WXmlDoc doc = Converter.connect("https://www.example.com").getWXML();
```

### Convert using Custom Configuration
```sh
WXmlDoc doc = Converter.connect("https://www.example.com").getWXML(new File("custom-conversion.json"));
```

### Working with WXML nodes
```sh
Node rootView = doc.root();
```

## API Reference
Java Doc

## Configuration Reference
Conversion rules are defined using configuration JSON.

## Known Limitation
* Tables
* Inline CSS

## TODO List
* HTML to WeChat WXML conversion
* Inline CSS to WXSS conversion
* CSS to WXSS Conversion
