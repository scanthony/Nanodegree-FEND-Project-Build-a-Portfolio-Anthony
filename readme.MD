# Update 2017-02-19 11:45 AM
Bootstrap grid implementation issue seemed to be addressed. 

# 更新：问题已解决
不能正常工作的代码：
~~~~
<img src="/assets/images/logo.png" alt="Site logo">
~~~~
能够正常工作的代码：
~~~~
<img src="assets/images/logo.png" alt="Site logo">
~~~~
或者：
~~~~
<img src="./assets/images/logo.png" alt="Site logo">
~~~~
# Update: Issue addressed
Code that is not working:
~~~~
<img src="/assets/images/logo.png" alt="Site logo">
~~~~
Code that works: 
~~~~
<img src="assets/images/logo.png" alt="Site logo">
~~~~
or: 
~~~~
<img src="./assets/images/logo.png" alt="Site logo">
~~~~

# 网页显示问题求解

网页只能在本地的Web服务器上才能正常显示（比如Adobe Brackets 的实时预览，或者通过Windows内置的IIS访问），如果直接从本地磁盘打开，将无法看到图片显示。

# Web page display troubleshoting

I was using Adobe Brackets to editing html and css files. And then I used Brakets’ live preview function for testing.

My web page looks good in Brackets’ live review, but if the web page is accessed directly from local hard disk, the page will become wired, even with no images displayed.

I think if you opened the page directly, you will see no images.

If you open the page with, say, Brackets or hosted on Windows’ IIS, the page will work well.
