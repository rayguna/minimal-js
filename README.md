# minimal-js

Notes:

1. Javascript console is available on Chrome. To access it, open a Chrome browser > View > Developer > Javascript Console. 
2. Remember to put a semicolon after each command line.
3. In a html file, write Javascript into a `<script>` tag.  
4. You only see the print statement in the background when you open the developer console (see #1 to open the console). 
5. To show the javascript messages, modify the script with the `<script>` tag in the views/misc/home.html.erb file.
6. String: use back ticks to create strings.

Unlike CSS, JavaScript runs asynchronously in the browser, so there’s no guarantee that just because the `<script>` tag appears in the document after the element that the element will have been fully loaded in time for the code within the `<script>` to affect it.

Read more about $(document).ready here, if you’re interested.

To solve this problem, jQuery adds a .ready method to the $(document) object that we can, you guessed it, provide a callback to. If we put all our code that binds event handlers to elements within this callback, it will execute only after the document has been fully loaded.

<hr>
