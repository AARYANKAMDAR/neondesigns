# neondesigns
I will be creating unique neon designs through the collective  usage of css and html.
<!DOCTYPE html>
<html lang="en">
<head>
    
    <title>Trying NEON TEXT</title>
    <style>
.neontext{
    animation: flicker 1.5s infinite alternate;
    color: #fff;
}

        @keyframes flicker {
            0%, 18%, 22%, 25%, 53%, 57%, 100% 
            {
        
                text-shadow:
         0 0 700px blue,
         0 0 10px blue,
         0 0 21px blue,
         0 0 2px blue,
         0 0 92px blue,
         0 0 92px blue,
         0 0 102px blue,
         0 0 151px blue;

    }
           20%, 24%, 55%{
               text-shadow: none;
           }
}

    

    body{
        font-size: 18px;
        font-family: "Yellowtail", sans-serif;
        background-color: black;
        
        
    }
     
    h1,h2{
        text-align: center;
        text-transform: uppercase;
        font-weight: 400;
    }

    h1{
        font-size: 4.2rem;
        

    }
    
    h2{
        font-size: 1.8rem;
    }
    .container{
        margin-top: 20vh;
        background-image:url(https://i.pinimg.com/564x/06/53/bb/0653bba07f479528b85722d8373957ca.jpg);
        border: 0.2rem solid #fff;
        border-radius: 2rem;
        padding: 0.4em;
        box-shadow: 0 0 .2rem #fff,
                    0 0 .2rem #fff,
                    0 0 2rem #bc13bc,
                    0 0 0.8rem #bc13bc,
                    0 0 2.8rem #bc13bc,
                    inset 0 0 1.3rem #bc13bc;
    }

    </style>
</head>
<body>
    <div class="container">
        <h1 class="neontext">
            PIZZERIA!
        </h1>
        <h2 class="neontext">
            Behold the world's tastiest flattened bread!
        </h2>
    </div>
</body>
</html>
