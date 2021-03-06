
# Context.touchEnabled property (JavaScript API for Office)
Gets whether the add-in is running in an Office host application that is touch enabled.

|||
|:-----|:-----|
|**Hosts:**|Excel, Word|
|**Last changed in**|1.1|

```
var isTouchEnabled = Office.context.touchEnabled;
```


## Return value

 ****Returns  **True** if the add-in is running on a touch device, such as an iPad; otherwise returns **False**.


## Remarks

Use the  **touchEnabled** property to determine when your add-in is running on a touch device and if necessary, adjust the kind of controls, and size and spacing of elements in your add-in's UI to accommodate touch interactions.


## Support details


A capital Y in the following matrix indicates that this method is supported in the corresponding Office host application. An empty cell indicates that the Office host application doesn't support this method.

For more information about Office host application and server requirements, see [Requirements for running Office Add-ins](http://msdn.microsoft.com/library/67340567-bb9a-498c-96d3-3f52f28c16bc%28Office.15%29.aspx).


|
|
||**Office for iPad**|
|:-----|:-----|
|**Excel**|Y|
|**PowerPoint**|Y|
|**Word**|Y|

|||
|:-----|:-----|
|**Minimum permission level**|[Restricted](http://msdn.microsoft.com/library/da2efadc-4ebf-45fe-be39-397ac1eb1dbd%28Office.15%29.aspx)|
|**Add-in types**|Content, task pane|
|**Library**|Office.js|
|**Namespace**|Office|

## Support history



****


|**Version**|**Changes**|
|:-----|:-----|
|1.1|Introduced.|
