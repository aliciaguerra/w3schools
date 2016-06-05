# onLoad Event
Execute a JavaScript immediately after a page has been loaded.

                      <body onload="myFunction()">
                      
#Definition and Usage 
The onload event occurs when the object has been loaded.
Onload is often used within the body element to execute a script once a web page has completely loaded all content
(inluding images, script files, CSS files, etc). 
The onload event can be used to check the visitor's browser type and browser version, and load the proper version 
of the web page based on the information.
Theonload event can also be used to deal with cookies.

#Syntax
In HTML:

                       <element onload="myScript">
                       
In JavaScript:

                       object.onload=function(){myScript};
                       
In JavaScript, using the addEventListener() method:

                       object.addEventListener("load", myScript);
                       
#More Examples

Using onload on an <img> event. Alert "image is unloaded" immediately after an image is loaded:

                        <img src="w3javascript.gif" onload="loadImage()" width="100" height="132">
                        <script>
                        function loadImage() {
                         alert("Image is unloaded");
                         }
                         </script>
                         
Using onload to deal with cookies:

                        <body onload="checkCookies()">
                        <script>
                        function checkCookies(){
                        var text="";
                        if(navigator.cookieEnabled==true) {
                        text="Cookies are enabled";
                        } else {
                        text="Cookies are enabled";
                        }
                        document.getElementById("demo").innerHTML = text;
                        }
                        </script>
                        
