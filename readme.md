```bash


  ######                                        ####  ####        ##            ####
##      ##                                      ####  ####                        ##
##      ##                                      ####  ####                        ##
##      ##      ####  ####      ########        ####  ####      ####              ##  ######    ####  ####      
##      ##        ####              ##          ##  ##  ##        ##              ##  ##          ##    ##      
##      ##        ##              ##            ##  ##  ##        ##              ######          ##    ##      
##      ##        ##              ##            ##  ##  ##        ##              ##    ##        ##    ##      
  ######        ######          ########        ##  ##  ##      ######          ######
```

!!!
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miku Head</title>
    <style>
        :root {
            --headsize: 256px; /*设置头颅大小*/
            --pixelsize: calc(var(--headsize)/8);
        }
        *{
            padding: 0;
            margin: 0;
        }
        .head{
            margin: 30px auto;
            width: var(--headsize);
            height: var(--headsize);
            background-color: grey;
            box-shadow: 0 0 15px lightgrey;
        }
        .p{
            width: var(--pixelsize);
            height: var(--pixelsize);
            float: left;
            /* display: inline-block; */
        }
    </style>
</head>
<body>
    <div class="head" id="open">
        <!-- 第一行 -->
        <div class="p" style="background:#28DBDE"></div>
        <div class="p" style="background:#22DADD"> </div>
        <div class="p" style="background:#D1D1D1"> </div>
        <div class="p" style="background:#C9C9C9"> </div>
        <div class="p" style="background:#C2C2C2"> </div>
        <div class="p" style="background:#A1A1A1"> </div>
        <div class="p" style="background:#BFBFBF"> </div>
        <div class="p" style="background:#C7C7C7"> </div>
        <!-- 第二行 -->
        <div class="p" style="background:#22D5D8"> </div>
        <div class="p" style="background:#D1D1D1"> </div>
        <div class="p" style="background:#21D1D4"> </div>
        <div class="p" style="background:#30DCDF"> </div>
        <div class="p" style="background:#41DEE1"> </div>
        <div class="p" style="background:#FF29B6"> </div>
        <div class="p" style="background:#A6A6A6"> </div>
        <div class="p" style="background:#B0B0B0"> </div>
        <!-- 第三行 -->
        <div class="p" style="background:#D6D6D6"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#1EBFC2"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#22D5D8"> </div>
        <div class="p" style="background:#1FC4C7"> </div>
        <div class="p" style="background:#2E2E2E"> </div>
        <div class="p" style="background:#FF33BA"> </div>
        <!-- 第四行 -->
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#1EBBBE"> </div>
        <div class="p" style="background:#FFCCB0"> </div>
        <div class="p" style="background:#1CB2B5"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#FFC8AB"> </div>
        <div class="p" style="background:#1EBBBE"> </div>
        <div class="p" style="background:#21D1D4"> </div>
        <!-- 第五行 -->
        <div class="p" style="background:#1FC4C7"> </div>
        <div class="p" style="background:#134F4F"> </div>
        <div class="p" style="background:#104242"> </div>
        <div class="p" style="background:#FFE1D3"> </div>
        <div class="p" style="background:#1CB2B5"> </div>
        <div class="p" style="background:#104242"> </div>
        <div class="p" style="background:#134F4F"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <!-- 第六行 -->
        <div class="p" style="background:#134F4F"> </div>
        <div class="p" style="background:#E8D9E4"> </div>
        <div class="p" style="background:#319FA0"> </div>
        <div class="p" style="background:#FFFAF0"> </div>
        <div class="p" style="background:#FFF3DD"> </div>
        <div class="p" style="background:#2F9798"> </div>
        <div class="p" style="background:#E6D6E2"> </div>
        <div class="p" style="background:#134F4F"> </div>
        <!-- 第七行 -->
        <div class="p" style="background:#199D9F"> </div>
        <div class="p" style="background:#D8FFEC"> </div>
        <div class="p" style="background:#3BBDBF"> </div>
        <div class="p" style="background:#FFF7E8"> </div>
        <div class="p" style="background:#FFEFD3"> </div>
        <div class="p" style="background:#3BBDBF"> </div>
        <div class="p" style="background:#CEFFE8"> </div>
        <div class="p" style="background:#199D9F"> </div>
        <!-- 第八行 -->
        <div class="p" style="background:#199D9F"> </div>
        <div class="p" style="background:#FFD0CF"> </div>
        <div class="p" style="background:#FFE0D9"> </div>
        <div class="p" style="background:#FFF3DD"> </div>
        <div class="p" style="background:#FFEFD3"> </div>
        <div class="p" style="background:#FFDCD4"> </div>
        <div class="p" style="background:#FFCBCA"> </div>
        <div class="p" style="background:#199D9F"> </div>
    </div>


    <div class="head" id="close" style="display: none;">
      <!-- 第一行 -->
        <div class="p" style="background:#28DBDE"></div>
        <div class="p" style="background:#22DADD"> </div>
        <div class="p" style="background:#D1D1D1"> </div>
        <div class="p" style="background:#C9C9C9"> </div>
        <div class="p" style="background:#C2C2C2"> </div>
        <div class="p" style="background:#A1A1A1"> </div>
        <div class="p" style="background:#BFBFBF"> </div>
        <div class="p" style="background:#C7C7C7"> </div>
        <!-- 第二行 -->
        <div class="p" style="background:#22D5D8"> </div>
        <div class="p" style="background:#D1D1D1"> </div>
        <div class="p" style="background:#21D1D4"> </div>
        <div class="p" style="background:#30DCDF"> </div>
        <div class="p" style="background:#41DEE1"> </div>
        <div class="p" style="background:#FF29B6"> </div>
        <div class="p" style="background:#A6A6A6"> </div>
        <div class="p" style="background:#B0B0B0"> </div>
        <!-- 第三行 -->
        <div class="p" style="background:#D6D6D6"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#1EBFC2"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#22D5D8"> </div>
        <div class="p" style="background:#1FC4C7"> </div>
        <div class="p" style="background:#2E2E2E"> </div>
        <div class="p" style="background:#FF33BA"> </div>
        <!-- 第四行 -->
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#1EBBBE"> </div>
        <div class="p" style="background:#FFCCB0"> </div>
        <div class="p" style="background:#1CB2B5"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <div class="p" style="background:#FFC8AB"> </div>
        <div class="p" style="background:#1EBBBE"> </div>
        <div class="p" style="background:#21D1D4"> </div>
        <!-- 第五行 -->
        <div class="p" style="background:#1FC4C7"> </div>
        <div class="p" style="background:#FFCCB0"> </div>
        <div class="p" style="background:#FFE1D3"> </div>
        <div class="p" style="background:#FFE1D3"> </div>
        <div class="p" style="background:#1CB2B5"> </div>
        <div class="p" style="background:#FFE1D3"> </div>
        <div class="p" style="background:#FFCCB0"> </div>
        <div class="p" style="background:#20CCCF"> </div>
        <!-- 第六行 -->
        <div class="p" style="background:#134F4F"> </div>
        <div class="p" style="background:#134F4F"> </div>
        <div class="p" style="background:#104242"> </div>
        <div class="p" style="background:#FFFAF0"> </div>
        <div class="p" style="background:#FFF3DD"> </div>
        <div class="p" style="background:#134F4F"> </div>
        <div class="p" style="background:#104242"> </div>
        <div class="p" style="background:#134F4F"> </div>
        <!-- 第七行 -->
        <div class="p" style="background:#199D9F"> </div>
        <div class="p" style="background:#FFD0CF"> </div>
        <div class="p" style="background:#FFE0D9"> </div>
        <div class="p" style="background:#FFF7E8"> </div>
        <div class="p" style="background:#FFEFD3"> </div>
        <div class="p" style="background:#FFDCD4"> </div>
        <div class="p" style="background:#FFCBCA"> </div>
        <div class="p" style="background:#199D9F"> </div>
        <!-- 第八行 -->
        <div class="p" style="background:#199D9F"> </div>
        <div class="p" style="background:#FFD0CF"> </div>
        <div class="p" style="background:#FFE0D9"> </div>
        <div class="p" style="background:#FFF3DD"> </div>
        <div class="p" style="background:#FFEFD3"> </div>
        <div class="p" style="background:#FFDCD4"> </div>
        <div class="p" style="background:#FFCBCA"> </div>
        <div class="p" style="background:#199D9F"> </div>
    </div>

    <script>
        var open = document.getElementById("open");
        var close = document.getElementById("close");
        open.addEventListener("click",toClose);
        function toOpen(){
            close.style.display = "none";
            open.style.display = "block";
        }
        function toClose(){
            open.style.display = "none";
            close.style.display = "block";
            setTimeout(()=>{toOpen()},300);
        }
    </script>
</body>
</html>
!!!
