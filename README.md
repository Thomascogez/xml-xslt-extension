# xml-xsl-snippet
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/wedzyou.xml-xsl-snippet)

xml-xsl-snippet is a simple snippet vscode extension with a list of xml and xsl base snippet 


## Snippet list

### Xsl

> Snippet location ./snippet/xsl.json

<b>Commands overview : </b>

* !xsl
* !xsltemplate
* !xsltemplateMode
* !xslapplytemplate
* !xslapplytemplatemode
* !xslvalof
* !xslelement
* !xslatr
* !xslkey
* !xslvalofkey



#### Commands:

##### !xsl

```xml
<?xml version="1.0"  encoding ="UTF-8" ?>
<xsl:stylesheet version="1.0" xmlns:xsl="http://www.w3.org/1999/XSL/Transform">
    <xsl:template match="/">
        <html>
            <body>

            </body>
        </html>
    </xsl:template>
</xsl:stylesheet>
```

​	

##### !xsltemplate

```xml
<xsl:template match="xmlTag">
</xsl:template>
```



##### !xsltemplateMode

```xml
<xsl:template match="xmlTag" mode="modeName">
</xsl:template>
```



##### !xslapplytemplate

```xml
<xsl:apply-templates select="templateName"/>
```



##### !xslapplytemplatemode

```xml
<xsl:apply-templates select="templateName" mode="modeName"/>
```



##### !xslvalof

```xml
<xsl:value-of select="templateNameOrXmlTagName"/>
```



##### !xslelement

```xml
<xsl:element name="htmlElementName">
</xsl:element>
```



##### !xslatr

```xml
<xsl:attribute name="htmlAttributeName">
</xsl:attribute>
```



##### !xslkey

```xml
<xsl:key name="keyName" match="XmlTagToMatch" use="@xmlAttributeToSelect" />
```



##### !xslvalofkey

```xml
<xsl:value-of select="key('xslkeyName',@AttributeToMathWith})"/>
```



### XML

> Snippet location ./snippet/xml.json



<b> Commands overviews </b>

* !xml



#### Commands

##### !xml

```xml
<?xml version=\"1.0\" ?>
<?xml-stylesheet type=\"text/xsl\" href="file.xsl"?>
<!DOCTYPE dtdName SYSTEM "file.dtd">

<xmlTag>
    
</xmlTag>
```



## Contributing

```shell
git clone https://github.com/Thomascogez/xml-xslt-extension.git
```



> command format !xmlORxslcommandname

