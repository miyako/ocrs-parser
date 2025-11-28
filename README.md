# ocrs-parser

## JSON

|Property|Level|Type|Description|
|-|-|-|-|
|document|0|||
|document.type|0|Text|"image" if input is `stdIn`|
|document.meta|0|Object||
|document.meta.height|1|Number||
|document.meta.width|1|Number||
|document.pages|0|Array||
|document.pages[].paragraphs|1|Array||
|document.pages[].paragraphs[].text|2|Text||
|document.pages[].paragraphs[].values|2|Array|words|
