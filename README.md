go-xsd-pkg
==========


Contains various Go packages that have been auto-generated with the **go-xsd** ( http://github.com/metaleap/go-xsd ) package and that you can simply **go get**:

- To easily *encoding/xml.Unmarshal()* **Atom** documents:


        import atom "github.com/metaleap/go-xsd-pkg/kbcafe.com/rss/atom.xsd.xml_go"


- To easily *encoding/xml.Unmarshal()* **RSS 2.0** documents:


        import rss "github.com/metaleap/go-xsd-pkg/thearchitect.co.uk/schemas/rss-2_0.xsd_go"


- To easily *encoding/xml.Unmarshal()* **SVG** documents:


        import svg "github.com/metaleap/go-xsd-pkg/www.w3.org/TR/2002/WD-SVG11-20020108/SVG.xsd_go"


- To easily *encoding/xml.Unmarshal()* **XSLT** documents:


        import xslt "github.com/metaleap/go-xsd-pkg/www.w3.org/2007/schema-for-xslt20.xsd_go"


- To easily *encoding/xml.Unmarshal()* **KML** documents:


        import kml "github.com/metaleap/go-xsd-pkg/schemas.opengis.net/kml/2.2.0/ogckml22.xsd_go"


- To easily *encoding/xml.Unmarshal()* **MathML 2.0** documents:


        import mathml "github.com/metaleap/go-xsd-pkg/www.w3.org/Math/XMLSchema/mathml2/mathml2.xsd_go"


- To easily *encoding/xml.Unmarshal()* **Collada 1.4.1** documents:


        import collada14 "github.com/metaleap/go-xsd-pkg/khronos.org/files/collada_schema_1_4_go"


- To easily *encoding/xml.Unmarshal()* **Collada 1.5** documents:


        import collada15 "github.com/metaleap/go-xsd-pkg/khronos.org/files/collada_schema_1_5_go"


- To easily *encoding/xml.Unmarshal()* **DocBook** documents:


        import docbook "github.com/metaleap/go-xsd-pkg/docbook.org/xml/5.0/xsd/docbook.xsd_go"


For other XML formats: figure out the Schema location and generate a similar wrapper with the **go-xsd** package at http://github.com/metaleap/go-xsd

**Better yet:** --unless this is a really obscure, bespoke or in-house XML format-- let me know the format and I can maintain its generated package here in this repository. It then gets updated with the others whenever there are bug-fixes or improvements to go-xsd.
