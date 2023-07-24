</head>
<body>
<div class="bee-page-container">
<div class="bee-row bee-row-1">
<div class="bee-row-content">
<div class="bee-col bee-col-1 bee-col-w12">
<div class="bee-block bee-block-1 bee-heading">
<h1 style="color:#8a3c90;direction:ltr;font-family:Arial, Helvetica, sans-serif;font-size:38px;font-weight:700;letter-spacing:normal;line-height:120%;text-align:left;margin-top:0;margin-bottom:0;"><span class="tinyMce-placeholder">[GUIDE] HOW TO FIX BLOCKED IMEI ON GOOGLE PIXEL 5 PHONE</span> </h1>
</div>
<div class="bee-block bee-block-2 bee-divider">
<div class="center bee-separator" style="border-top:1px solid #dddddd;width:100%;"></div>
</div>
<div class="bee-block bee-block-3 bee-spacer">
<div class="spacer" style="height:60px;"></div>
</div>
<div class="bee-block bee-block-4 bee-paragraph">
<p>Yesterday i bought a second phone from local marketplace, after few days the phone brick and got signal lost. I try using another sim card but it still does't work. I try to give it back to the seller, but it takes one week till they give the phone back to me. So I decided to fix it by my self.<br/>All the files that i found here i got from deep dive on internet and all of them have been posted on several forums, so I thank everyone</p>
</div>
<div class="bee-block bee-block-5 bee-spacer">
<div class="spacer" style="height:35px;"></div>
</div>
<div class="bee-block bee-block-6 bee-heading">
<h3 style="color:#8a3c90;direction:ltr;font-family:Arial, Helvetica, sans-serif;font-size:24px;font-weight:700;letter-spacing:normal;line-height:120%;text-align:left;margin-top:0;margin-bottom:0;"><span class="tinyMce-placeholder">PREQUISITE</span> </h3>
</div>
<div class="bee-block bee-block-7 bee-paragraph">
<p><strong>IMEI </strong>is a unique identification number programmed onto your phone. It is required in order to be correctly identified on a mobile network. Without one, you cannot make calls, send SMS or use mobile data. Important stuff.</p>
<p><span style="color: #ff0808;">dealing with changing your imei is prohibited in some countries, and is a criminal act that may be charged with smuggling goods. Use this thread wisely. The author is not responsible for security and other matters that will be accepted by you. <strong>SO USE IT AT YOUR OWN RISK !!!</strong></span></p>
</div>
<div class="bee-block bee-block-8 bee-divider">
<div class="center bee-separator" style="border-top:2px solid #dddddd;width:65%;"></div>
</div>
<div class="bee-block bee-block-9 bee-spacer">
<div class="spacer" style="height:35px;"></div>
</div>
<div class="bee-block bee-block-10 bee-heading">
<h3 style="color:#8a3c90;direction:ltr;font-family:Arial, Helvetica, sans-serif;font-size:24px;font-weight:700;letter-spacing:normal;line-height:120%;text-align:left;margin-top:0;margin-bottom:0;"><span class="tinyMce-placeholder">NEEDED FILES</span> </h3>
</div>
<div class="bee-block bee-block-11 bee-list">
<ul>
<li>QPST (also included QFIL) you can download it <a href="https://terabox.com/s/1GQzmR3AdqY9oJT5MJcZqjA" rel="noopener" style="text-decoration: underline;" target="_blank">here,</a> thanks to @fathinafif </li>
<li>Qualqomm HS - USB Android QD loader, download <a href="https://terabox.com/s/1WJoiM-1HUm3fOf005JqWSQ" rel="noopener" style="text-decoration: underline;" target="_blank">here</a></li>
<li>Android SDK Platform tool, <a href="https://terabox.com/s/1xtVKtcIPAHwmU0ooy6X8vQ" rel="noopener" style="text-decoration: underline;" target="_blank">here</a> or if it doesn't work you can find another one in <a href="https://developer.android.com/tools/releases/platform-tools" style="text-decoration: underline;">SDK Platform Tools release notes  |  Android Studio  |  Android Developers</a></li>
<li>QCN IMEI writers, <a href="https://terabox.com/s/1hhxU1PmuSmDs7Hsb1IdxUw" rel="noopener" style="text-decoration: underline;" target="_blank">here</a></li>
<li><a href="https://github.com/topjohnwu/Magisk" rel="noopener" style="text-decoration: underline;" target="_blank">Magisk</a> for root </li>
<li>TWRP for pixel 5, u can find <a href="https://twrp.me/google/googlepixel5.html" rel="noopener" style="text-decoration: underline;" target="_blank">here</a></li>
</ul>
</div>
<div class="bee-block bee-block-12 bee-spacer">
<div class="spacer" style="height:35px;"></div>
</div>
<div class="bee-block bee-block-13 bee-heading">
<h3 style="color:#8a3c90;direction:ltr;font-family:Arial, Helvetica, sans-serif;font-size:24px;font-weight:700;letter-spacing:normal;line-height:120%;text-align:left;margin-top:0;margin-bottom:0;"><span class="tinyMce-placeholder">Installing all Tools</span> </h3>
</div>
<div class="bee-block bee-block-14 bee-paragraph">
<p><strong>Qualqomm Driver </strong></p>
<p>1. Open the files </p>
<p>2. Pick yes if it asking to run in administrator mode</p>
<p>3. Next, next, next go on trough to install window</p>
<p>4. Done</p>
</div>
<div class="bee-block bee-block-15 bee-paragraph">
<p><strong>QPST</strong></p>
<p>1. Just Unzip the file</p>
<p>2. The .exe file just located inside the folder</p>
</div>
<div class="bee-block bee-block-16 bee-paragraph">
<p><strong>ADB & Fastboot </strong></p>
<p>1. Locate the 👆 downloaded android sdk platform tool</p>
<p>2. Unzip it and put into local disk C or anywhere u want</p>
<p>3. The folder contain adb .exe and fastboot that we gonna need it later</p>
</div>
<div class="bee-block bee-block-17 bee-spacer">
<div class="spacer" style="height:30px;"></div>
</div>

<h3 style="color:#000000;direction:ltr;font-family:Arial, Helvetica, sans-serif;font-size:18px;font-weight:400;letter-spacing:normal;line-height:120%;text-align:left;margin-top:0;margin-bottom:0;"><span class="tinyMce-placeholder">1.  You need to unlock the bootloader & root your phone, please follow the guide in <a href="https://forum.xda-developers.com/t/guide-pixel-5-redfin-unlock-bootloader-update-root-pass-safetynet.4356219/" rel="noopener" style="text-decoration: underline; color: #0012ff;" target="_blank">here</a> </span> </h3>
