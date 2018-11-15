<!-- default file list -->
*Files to look at*:

* [Global.asax.cs](./CS/WebSolution.Web/Global.asax.cs) (VB: [Global.asax.vb](./VB/WebSolution.Web/Global.asax.vb))
<!-- default file list end -->
# How to add information about the current user in the log information


<p>This example demonstrates how to include information about the current security user and host into the log info. The solution lies in handling the NeedContextInformation event of the DevExpress.Persistent.Base.Tracing class.<br />
This solution is applicable only to Web applications, because by default, only one log file is filled on the web server.</p>

<br/>


