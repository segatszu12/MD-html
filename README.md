<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: grey;
        }



        @media only screen and (max-width: 1200px) {



        }



        /* design for large screens */
        @media only screen and (max-width: 1200px) {
            .container {
                display: grid;
                grid-template-columns: repeat(5, 2fr);
                grid-template-rows: repeat(5, 2fr);
                gap: 5px;
            }

            .div1 {
                background-color: aqua;
                grid-column: 1/6;
                grid-row: 1/2;
            }

            .div2 {
                background-color: rgb(199, 93, 238);
                grid-column: 5/6;
                grid-row: 2/5;
            }

            .div5 {
                background-color: rgb(60, 29, 195);
                grid-column: 1/6;
                grid-row: 5/6;
                z-index: 2;
            }

            .div3 {
                background-color: rgb(145, 51, 71);
                grid-column: 1/2;
                grid-row: 2/5;
                z-index: 1;
            }

            .div4 {
                background-color: rgb(115, 220, 89);
                grid-column: 2/5;
                grid-row: 2/5;
            }
        }

     

        /* design for tablets */
        @media only screen and (max-width: 768px) {
            .container {
                display: grid;
                grid-template-columns: repeat(3, 2fr);
                grid-template-rows: repeat(5, 2fr);
                gap: 5px;
            }

            .div1 {
                background-color: aqua;
                grid-column: 1/6;
                grid-row: 1/2;
            }

            .div2 {
                background-color: rgb(199, 93, 238);
                grid-column: 1/6;
                grid-row: 2/3;
            }

            .div5 {
                background-color: rgb(60, 29, 195);
                grid-column: 1/6;
                grid-row: 5/6;
                z-index: 2;
            }

            .div3 {
                background-color: rgb(145, 51, 71);
                grid-column: 1/2;
                grid-row: 3/5;
                z-index: 1;
            }

            .div4 {
                background-color: rgb(115, 220, 89);
                grid-column: 2/5;
                grid-row: 3/5;
            }
        }

        /* design for mobile phones */
        @media only screen and (max-width: 7820px) {
            .container {
                display: grid;
                grid-template-columns: repeat(3, 2fr);
                grid-template-rows: repeat(5, 2fr);
                gap: 5px;
            }

            .div1 {
                background-color: aqua;
                grid-column: 1/6;
                grid-row: 1/2;
            }

            .div2 {
                background-color: rgb(199, 93, 238);
                grid-column: 1/6;
                grid-row: 2/3;
            }

            .div5 {
                background-color: rgb(60, 29, 195);
                grid-column: 1/6;
                grid-row: 5/6;
                z-index: 2;
            }

            .div3 {
                background-color: rgb(145, 51, 71);
                grid-column: 1/6;
                grid-row: 3/4;
                z-index: 1;
            }

            .div4 {
                background-color: rgb(115, 220, 89);
                grid-column: 1/6;
                grid-row: 4/5;
            }
        }

        /* 
        
          Extra small devices (phones, 600px and down) 
@media only screen and (max-width: 600px) {...}

 Small devices (portrait tablets and large phones, 600px and up) 
@media only screen and (min-width: 600px) {...}

 Medium devices (landscape tablets, 768px and up) 
@media only screen and (min-width: 768px) {...}

 Large devices (laptops/desktops, 992px and up) 
@media only screen and (min-width: 992px) {...}

 Extra large devices (large laptops and desktops, 1200px and up) 
@media only screen and (min-width: 1200px) {...}     
        */
    </style>
</head>

<body>
    <div class="container">
        <div class="div1">DIV1</div>
        <div class="div2">DIV2</div>
        <div class="div3">DIV3</div>
        <div class="div4">DIV4</div>
        <div class="div5">DIV5</div>
    </div>
</body>

</html>
