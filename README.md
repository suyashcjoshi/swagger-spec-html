## Swagger Spec to HTML Generator
Simple python script that generates html doc from open API spec file like .yml / .yaml file.

### Steps to run this

### Format
```
python swagger-yaml-to-html.py <name of your YAML file> name of your HTML file
```

### Example:
```
python swagger-yaml-to-html.py <demo.yml> index.html
```

### Markdown format

Once you get the HTML file, if you want to represent that as markdown, just replace the extension from *.html* to *.md* and it will render as markdown since markdown is ultimately converted to html.


### Credit

This file is based on https://github.com/swagger-api/swagger-ui/blob/4f1772f6544699bc748299bd65f7ae2112777abc/dist/index.html (Copyright 2017 SmartBear Software, Licensed under Apache 2.0)
