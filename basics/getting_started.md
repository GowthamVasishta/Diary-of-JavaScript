# Getting started with JS

JavaScript code can be executed within HTML documents using `<script>` tags. It can be done in two ways

1. Internal implementation or embedding code directly into the document.
2. External implementation or placing JS code into external file and then linking it to the HTML document.

### Internal implementation

JS code is directly embedded between the `<script> . . . </script>` tags. Let us consider the example.

    <html>
    <head>
    <title> Internal Javascript </title>
    <script type="text/javascript">
     var a = "hello world !";
     document.write(a);
    </script>
    </head>
    <body>
    </body>
    </html>
    
Save this file as `internal.html` and run it on your favorite browser software. The output would be . . . yes ! you guessed correct ! 

    Hello world !

Let us understand the code, bit by bit ! First of all , in the head section, our JS code lies between the `<script> . . . </script>` tags. Now there's a attribute by the name 'type' in the script tag. Its tells the browser that we are using JavaScript. Then we have declared a variable ` a ` into which we stored our string ` "Hello world !"`.

    var a = "Hello world !";
    
Then we are writing the contents of variable ` a ` to the present HTML document !. Alright let us have a look on external implementation.

### External implementation

Alright , here we deal with two files. One `.html` file to hold the HTML content and '.js` file to hold our JS code. Let's see its implementation part !

    <html>
    <head>
    <title> External javascript </title>
    <script type="text/javascript" src="ext.js" ></script>
    </head>
    <body>
    </body>
    </html>
    
Save it as `external.html`. Now lets us write our `ext.js` file. 

    /* ext.js 
       @ Diary of JS
    */
    
    //create a variable
    var a = "hello world !";
    
    // write to the document !
    document.write(a);
    
Now run `external.html, in your favorite browser. As expected, the output would be 

    hello world !
    
In script tag , a new attribute has been added that is `src` which tells the path of our external `JS` file. Coming to `ext.js` , we see first four lines as comments !

    /* ext.js 
       @ Diary of JS
    */
    
This is considered as multi-line comment whereas single line comments are denoted through double slash  `'//'` notation. for example in our code , following are the single line comments !

    //create a variable
    
    // write to the document
    
Comments are used for user-friendly description. They are not parsed by the browsers !
