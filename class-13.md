Cookies are included with every HTTP request, <br>
thereby slowing down your web application by needlessly transmitting the same data overand over<br>
Cookies are included with every HTTP request,<br>
thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)<br>
Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful<br>
What we really want is<br>

a lot of storage space on the client that persists beyond a page refresh and isn’t transmitted to the server<br>
Before HTML5, all attempts to achieve this were ultimately unsatisfactory in different ways.<br>

# So what is HTML5 Storage? <br>
Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser.<br>
Like cookies, this data persists even after you navigate away from the web site, <br>
close your browser tab, exit your browser, or what have you.<br>

## USING HTML5 STORAGE<br>
interface Storage {<br>
  getter any getItem(in DOMString key);<br>
  setter creator void setItem(in DOMString key, in any data);<br>
};<br>

# TRACKING CHANGES TO THE HTML5 STORAGE AREA<br>
If you want to keep track programmatically of when the storage area changes, you can trap the storage event.<br>
The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something.<br> 
For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire,<br>
because nothing actually changed in the storage area.<br>
