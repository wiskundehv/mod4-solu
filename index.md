<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.2/dist/css/bootstrap.min.css"
         rel="stylesheet" integrity="sha384-uWxY/CJNBR+1zjPWmfnSnVxwRheevXITnMqoEIeG1LJrdI0GlVs/9cVSyPYXdcSF" 
         crossorigin="anonymous">
         <title>Opdracht week 4</title>

    
    </head>
    <body>
        <h1>Opdracht van week 4 JS</h1>
        <script>
        (function () {
            var names = ["Houcine", "John", "Jen", "Jason", "Paul",
             "Frank", "Larry", "Paula", "Laura", "Jim"];
            for (var i = 0; i < names.length; i++) {
              var firstLetter = names[i].charAt(0).toLowerCase();
              if (firstLetter === 'j') {
                document.write ("Good Bye"+ " "+ names[i]+ "   ======   ");

                
              } else {
                document.write("Hello"+" " +names[i]+ "    ======   ");
                
              }
             
            }
            })();

        </SCript>
    </body>
   

</html>
