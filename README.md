# takealook
<!doctype html>
<html>
    <head>
        <meta charset="utf-8">
        <title>d</title>
    </head>
    <body>
        <script>

            var n=new Array(5);
            var len=prompt("배열수 입력","")

            for(i=0;i<len;i++){
                n[i]=prompt("n["+i+"]배열입력","");
                var size=n[i];
                while(size>0){
                    document.write("*");
                    size--;
                }
                document.write(""+n[i]+"<br>");

            }
        </script>

    </body>
</html>
