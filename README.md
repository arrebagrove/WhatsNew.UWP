# WhatsNew.UWP
A UWP Control that show whats new message once the app version is updated
 
Targeting Platform
------------
- Windows 10 Build 10586+
- Windows 10 Mobile Build 10586+

Usage
-----------

Install WhatsNew.UWP from NuGet:

`
Install-Package WhatsNew.UWP
`

Add a WhatsNewPopup control to your layout page. (e.g. MainPage.xaml)

<pre>
&lt;controls:WhatsNewPopup 
ApplicationName=&quot;Another Funking App&quot; 
WhatsNewMessage=&quot;Funk Something Up.&quot; 
WhatsNewYes=&quot;Got it!&quot; /&gt;
</pre>

When a newer version of the app is deployed, the popup will show up on the first launch of the app.

![First Launch Of New Package](https://raw.githubusercontent.com/EdiWang/WhatsNew.UWP/master/Screenshots/1.png)

License
--------------------

The MIT License (MIT)

Copyright (c) 2016 edi.wang

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.