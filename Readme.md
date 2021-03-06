<!-- default file list -->
*Files to look at*:

* **[Default.aspx](./CS/Default.aspx) (VB: [Default.aspx](./VB/Default.aspx))**
<!-- default file list end -->
# How to apply Bootstrap Form (form-control, btn) style to DevExpress editors in Native mode
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t263405/)**
<!-- run online end -->


This example illustrates how to enable the Native rendering mode (by setting the Native property to True) in order to produce the raw HTML elements and apply the Bootstrap <a href="http://getbootstrap.com/css/#forms">Form</a> (form-control, btn, etc.) style.<br />There is also a side-by-side comparison with the same set if editors in the DevExprss <a href="https://demos.devexpress.com/ASP/Themes/Default.aspx?Theme=Moderno&Control=1">Moderno</a> theme (applied in the Web.config) that has a similar color schema as the Bootstrap.<br /><br />The main requirement is to set the editor's <a href="https://documentation.devexpress.com/#AspNet/CustomDocument11893">Native</a> property in order to produce the raw HTML rendering and apply the Bootstrap style via the CssClass property:<br /><br />


```aspx
<dx:ASPxTextBox ... Native="true" CssClass="form-control"></dx:ASPxTextBox>

<dx:ASPxMemo ... Native="true" CssClass="form-control"></dx:ASPxMemo>

<dx:ASPxButton ... Native="true" CssClass="btn btn-primary"></dx:ASPxButton>
```


<br />Optionally, it may be necessary to specify the editor's Width and Height dimensions (in percent or pixels) in order to achieve a consistent/custom layout.<br /><br /><strong>MVC Version:</strong><br /><a href="https://www.devexpress.com/Support/Center/p/T263406">How to apply a Bootstrap Form (form-control, btn, etc.) style to the DevExpress editors in Native mode</a>

<br/>


