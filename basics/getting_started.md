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
    
Save this file as `.html` extension and run it on your favourite browser software. The output would be . . . yes ! you guessed correct ! 

    Hello world !

Let us understand the code, bit by bit ! First of all , in the head section, our JS code lies between the `<script> . . . </script>` tags. Now there's a attribute by the name 'type' in the script tag. Its tells the browser that we are using JavaScript. Then we have declared a variable ` a ` into which we stored our string ` "Hello world !"`.

    var a = "Hello world !";
    
Then we are writing the contents of variable ` a ` to the present HTML document !.

