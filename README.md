<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Word Search Game</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #4800ff; 
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        h1 {
            text-align: center;
            color: white;
            font-size: 36px;
            margin: 20px 0;
        }

        .word-search-container {
            background-color: #fff;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 8px 15px rgba(0,0,0,0.3);
        }

        .letters-grid {
            display: flex;
            flex-wrap: wrap;
            grid-template-columns: repeat(12, 40px);
            grid-template-rows: repeat(10, 40px);
            gap: 5px;
            
        }

        .letters-grid div {
            width: 40px;
            height: 40px;
            display: flex;
            
            justify-content: center;
            font-weight: bold;
            font-size: 18px;
            background-color: #FDF5E6;
            border-radius: 5px;
        }

        .word-list {
            margin-top: 20px;
           
            justify-content: center;
            gap: 15px;
            font-weight: bold;
            color: #333;
        }

        .word-list span {
            background-color: #FFDEAD;
          
        }
    </style>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>TECH WORD SEARCH GAME</h1>
    <h2>Find 6 meaningful words related to "CODING"</h2>

    <div class="word-search-container">
       
    <b>
        <b>
               <div class="letters-grid">
    O  A P U C B U D W S A S D F A
</div>
    <div class="letters-grid">
    P  P C O D E A D D R D F G H B
</div>
    <div class="letters-grid">
    E  A E B B B D D D E H G Q P D
</div>
    <div class="letters-grid">
    R  A B F L O A T D A D E B N F
</div>
    <div class="letters-grid">
    A  A B B B B A D D K S D E B G
</div>
    <div class="letters-grid">
    T  A W E R B D D T B Q W N V H
</div>
    <div class="letters-grid">
    O  B S D F B D D C O M N B V K
</div>
    <div class="letters-grid">
    R  R B B P Y T H O N R C V D L
</div>
    <div class="letters-grid">
    R  E S D F G K D D B A S K L C
</div>
    <div class="letters-grid">
      S A B Q P A D D E B V C B X V
</div>
    <div class="letters-grid">
    S  K Q W R T Y P O X Z V Q H M
</div>
    <div class="letters-grid">
    R  A S W Q U P O Y B S E L S E
</div>



        </b>
    </b>
    </div>
</body>
</html>
