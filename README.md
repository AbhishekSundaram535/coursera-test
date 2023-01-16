
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=\, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            box-sizing: border-box;
        }
        h1{
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: center;
            margin-bottom: 30px;
            background-color: rgb(254, 214, 165);
        }
        section{
            background-color: rgb(167, 191, 237);
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color: rgb(14, 22, 1);
            padding-bottom: 15px;
            padding-top: 25px;
            margin-bottom: 10px;
            border: 1px solid black;
            width: 100%;
            position: relative;
        }
        #sh1,#sh2,#sh3{
            text-align: center;
            border:1px solid black;
            color:black;
            margin: 0;
        }
        #sh1{
            background-color: rgb(245, 181, 203);
            width: 125px;
            position: absolute ;
            right: 0;
            top:0;
            
        }
        #sh2{
            background-color: rgb(134, 232, 139);
            width: 125px;
            position: absolute;
            right: 0;
            top:0px;
            
        }
        #sh3{
            background-color: rgb(244, 240, 110);
            width: 125px;
            position: absolute;
            right: 0;
            top:0;
            
        }
        @media(min-width:992px){
            .col-lg-1,.col-lg-2,.col-lg-3,.col-lg-4,.col-lg-5,.col-lg-6,.col-lg-7,.col-lg-8
            .col-lg-9,.col-lg-10,.col-lg-11,.col-lg-12{
                float: left;
                border: 1px solid black;   
            }
            .col-lg-1{
                width:8.33%;
            }
            .col-lg-2{
                width: 16.66%;
            }
            .col-lg-3{
                width: 25%;
            }
            .col-lg-4{
                width: 33.33%;
            }
            .col-lg-5{
                width: 41.66%;
            }
            .col-lg-6{
                width: 50%;
            }
            .col-lg-7{
                width: 58.33%;
            }
            .col-lg-8{
                width: 66.66%;
            }
            .col-lg-9{
                width: 75%;
            }
            .col-lg-10{
                width: 83.33%;
            }
            .col-lg-11{
                width: 91.66%;
            }
            .col-lg-12{
                width: 100%;
            }
        }
        @media(min-width:768px) and (max-width:991px){.col-md-1,.col-md-2,.col-md-3,.col-md-4,.col-ms-5,.col-md-6,.col-md-7,.col-md-8
            .col-md-9,.col-md-10,.col-md-11,.col-md-12{
                float: left;
                border: 1px solid black;
                
            }
            section{
                margin-bottom: 10px;
            }
            .col-md-1{
                width:8.33%;
            }
            .col-md-2{
                width: 16.66%;
            }
            .col-md-3{
                width: 25%;
            }
            .col-md-4{
                width: 33.33%;
            }
            .col-md-5{
                width: 41.66%;
            }
            .col-md-6{
                width: 50%;
            }
            .col-md-7{
                width: 58.33%;
            }
            .col-md-8{
                width: 66.66%;
            }
            .col-md-9{
                width: 75%;
            }
            .col-md-10{
                width: 83.33%;
            }
            .col-md-11{
                width: 91.66%;
            }
            .col-md-12{
                width: 100%;
            }

        }

    </style>
</head>
<body>
    <h1>THE SA</h1>
    <h1>Menu</h1>
    <div>
        <section class="col-lg-4 col-md-6">
            <h3 id="sh1">IDLY</h3>
            Lorem ipsum dolor sit amet, consectetur adipiscing
             elit, sed do eiusmod tempor incididunt ut labore 
             et dolore magna aliqua. Ut enim ad minim veniam, 
             quis nostrud exercitation ullamco laboris nisi 
             ut aliquip ex ea commodo consequat.
        </section>
        <section class="col-lg-4 col-md-6">
            <h3 id="sh2">DOSA</h3>
            Lorem ipsum dolor sit amet, consectetur adipiscing
             elit, sed do eiusmod tempor incididunt ut labore et
             dolore magna aliqua. Ut enim ad minim veniam, quis
             nostrud exercitation ullamco laboris nisi ut aliquip
             ex ea commodo consequat.
        </section>
        <section class="col-lg-4 col-md-12">
            <h3 id="sh3">PONGAL</h3>
            Lorem ipsum dolor sit amet, consectetur adipiscing
             elit, sed do eiusmod tempor incididunt ut labore et
             dolore magna aliqua. Ut enim ad minim veniam, quis 
             nostrud exercitation ullamco laboris nisi ut aliquip 
             ex ea commodo consequat.
        </section>

    </div>
</body>
</html>
