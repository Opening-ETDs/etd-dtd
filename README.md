# etd-dtd
## Document Type Definition for Electronic Theses and Dissertations

Based on the work by Neill A. Kipp, et al.  
For full  documentation, see [the original](http://etd.vt.edu/etd-ml/dtdetds.htm).

## Usage
### Contents
 - `etd.sgml.dtd` - Kipp's original DTD 
 - `etd.xml.dtd` - my converstion to XML 
 - `empty_etd_minimal` - sample ETD in XML with only the required elements
 - `empty_etd_optional` - sample ETD in XML with all the optional elements 

### Minimal ETD example
```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE etd SYSTEM "file:etd.xml.dtd">
<etd>
    <front>
        <title></title>
        <author>
            <given></given>
            <surname></surname>
            <suffix></suffix>
        </author>
        <submission></submission>
        <school></school>
        <degree></degree>
        <major></major>
        <approvals></approvals>
        <date></date>
        <city></city>
        <state></state>
        <keywords>
            <keyword></keyword>
        </keywords>
        <copyright></copyright>
        <abstract></abstract>
    </front>
    <body>
        <chapter></chapter>
    </body>
    <back>
        <bibliography></bibliography>
        <vita></vita>
    </back>
    <footnote id="x1"></footnote>
</etd>
```

## License
[BSD-3-Clause License](https://github.com/Opening-ETDs/etd-dtd/blob/LICENSE)