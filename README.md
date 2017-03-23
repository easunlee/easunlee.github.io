#win10系统下MarkdownPad2预览无法显示的解决

一直以来都是使用 [MarkdownPad 2](http://markdownpad.com/) 来写Blog。<br />
在win7系统下，这个是写 [Markdown](http://www.baidu.com/s?wd=Markdown&ie=UTF-8) 格式文档的利器，因为其的实时预览模式，实在是太强悍了。  
但是最近[升级到了win10](http://easun.org/blog/archives/windows_10_is_coming.html)，打开 [MarkdownPad 2](http://markdownpad.com/) 后，实时预览功能居然失效了，提示如图。

![](http://i.imgur.com/28AEzhH.png) 

难道要逼我换软件吗？ 在 [http://markdownpad.com/faq.html#livepreview-directx](http://markdownpad.com/faq.html#livepreview-directx) 这里发现了一些信息：

> **LivePreview is not working - it displays an error message stating This view has crashed!**
> 
> This issue has been specifically observed in Windows 8. You may see an error message as shown here, and no HTML will be rendered when you type in the Markdown Editor pane.
> 
> To fix this issue, please try installing the [Awesomium 1.6.6 SDK.](http://markdownpad.com/download/awesomium_v1.6.6_sdk_win.exe)
> 
> If you continue to experience issues, please install Microsoft's DirectX End-User Runtimes (June 2010).

OK， 那就先试试 [Awesomium 1.6.6 SDK.](http://markdownpad.com/download/awesomium_v1.6.6_sdk_win.exe)

下载，My God，居然 110 M。。。。

下载安装，再次打开，一切正常：） 
