<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128587601/13.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1498)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Global.asax.cs](./CS/WebSolution.Web/Global.asax.cs) (VB: [Global.asax.vb](./VB/WebSolution.Web/Global.asax.vb))
<!-- default file list end -->
# How to add information about the current user in the log information


<p>This example demonstrates how to include information about the current security user and host into the log info. The solution lies in handling the NeedContextInformation event of the DevExpress.Persistent.Base.Tracing class.<br />
This solution is applicable only to Web applications, because by default, only one log file is filled on the web server.</p>

<br/>


