# HTML5 Storage 
  it’s a way for web pages to store named key/value pairs locally, within the client web browser 
  * the data we stored persists even after you navigate away from the web site
  * and its never transmitted to the remote web server

 ## to access the HTML5 Storage 
   first we should detect if the browser support it or not using : 
     ```
            function supports_html5_storage() {
        try {
            return 'localStorage' in window && window['localStorage'] !== null;
        } catch (e) {
            return false;
        }
        }
     
     ```
 ## methods we can use in this database 
  - setItem(“key”,”value”)
  - removeItem(“key”)
  - getItem(“key”)
  - clear()