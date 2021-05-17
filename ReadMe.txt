I created a new app which demonstrates Issues I am having trying to upload an VB ASP.Net website to a hosting site. The hosting site is IIS, and has .net version 4.7 and below. I created a brand now Visual Basic / Web / Previous Versions / ASP.NET Web Forms Site. Right out of the box, the site shows the error that it will not show errors on remote sites, and suggested I add Custom Errors statement to Web.Config. Following the errors suggestion, I added the Custom Errors to Web.Config.

The new error indicated it does not know how to handle the Compile directives. This is the error I brought to Host Gator, and they said that the compilers are not supported on shared hosts. The deleted the compile lines which brought up different errors, at which point they indicated they do not support codeing and recommend I consult a programmer.

Removing both compile lines it indicated it can not find ~/site.master, from code in Default.aspx. It can not find Site.master, which is in the root of my application. I guessed the tilde slash prefix might be the problem, so I removed it. It still ran in VS, but now it can not find WebApplication1.SiteMaster, which is a system generated Partial Public Class in Site.Master.designer.vb.

You can see the final error at: http://itjuggler.com/WebApplication1/default.aspx

That is where I am at.

The original code without modifications and final code with all changes are given in the attached zip files.
