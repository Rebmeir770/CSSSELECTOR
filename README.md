# CSSSELECTOR
Matle Instagram 

html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram</title>
    <link rel="stylesheet" href="style.css">
</head>
<body class="insta">
    <div>

             <h1>Instagram</h1>
     <div class="warr">
    
        <div class="warrper">
   
             <img src="tree1.jpg" class="profile">
             <p>Meir Duvid Krykun</p>

        </div>
        <div class="content">
             <img { width="400px" height="300px"} src="Rebbe-1.jpg">
             <p>On Shevat 10 on the Jewish calendar, upon the passing of the sixth Lubavitcher Rebbe, Rabbi Yosef Yitzchak Schneersohn, of righteous memory, leadership of the Chabad-Lubavitch movement passed on to his illustrious son-in-law, Rabbi Menachem Mendel Schneerson, of righteous memory. In the decades that followed, the Rebbe revolutionized, inspired and guided the post-Holocaust transformation of the Jewish people that continues to this day.</p>
       </div>
       <div class="like-bar">
       <img src="https://img.icons8.com/ios-glyphs/2x/speech-bubble.png" id="like-bar" alt=""> 
       <img src="https://img.icons8.com/external-kiranshastry-lineal-color-kiranshastry/2x/external-share-interface-kiranshastry-lineal-color-kiranshastry.png" id="like-bar" alt=""> 
       <img src="https://img.icons8.com/material-sharp/2x/save-search.png" id="like-bar2" alt="">
       <img src="https://img.icons8.com/ios-filled/2x/like.png" id="like-bar" alt="">
       </div>

       <div>
           <h4>Liked by Tuvia and 180 others</h4>
        </div>
       <div>
           <h4>view all 280 comments</h4>
        </div>
       <div>
           <h4>8 day ago</h4>
        </div>
     
        <div class="text-area">
            <img src="https://img.icons8.com/ios-glyphs/2x/happy.png" id="emojis" alt="">
            <textarea name="" id="text-area" placeholder="add a commennt..." cols="50" rows="1"></textarea>
           <button>POST</button>

          </div>

        
        

     </div> 
    </div>  

    <div class="warr">
    
        <div class="warrper">
   
             <img src="tree1.jpg" class="profile">
             <p>Meir Duvid Krykun</p>

        </div>
        <div class="content">
             <img { width="400px" height="300px"} src="lavanda.jpg">
             <p>wake up in lavender field</p>
       </div>
       <div class="like-bar">
       <img src="https://img.icons8.com/ios-glyphs/2x/speech-bubble.png" id="like-bar" alt=""> 
       <img src="https://img.icons8.com/external-kiranshastry-lineal-color-kiranshastry/2x/external-share-interface-kiranshastry-lineal-color-kiranshastry.png" id="like-bar" alt=""> 
       <img src="https://img.icons8.com/material-sharp/2x/save-search.png" id="like-bar2" alt="">
       <img src="https://img.icons8.com/ios-filled/2x/like.png" id="like-bar" alt="">
       </div>

       <div>
           <h4>Liked by Meiital and 180 others</h4>
        </div>
       <div>
           <h4>view all 280 comments</h4>
        </div>
       <div>
           <h4>8 day ago</h4>
        </div>
     
        <div class="text-area">
            <img src="https://img.icons8.com/ios-glyphs/2x/happy.png" id="emojis" alt="">
            <textarea name="" id="text-area" placeholder="add a commennt..." cols="50" rows="1"></textarea>
           <button>POST</button>

          </div>

        
        

     </div> 
    </div>

    <div class="warr">
    
        <div class="warrper">
   
             <img src="tree1.jpg" class="profile">
             <p>Meir Duvid Krykun</p>

        </div>
        <div class="content">
             <img { width="400px" height="300px"} src="pexels-photo-7168996.jpg">
             <p>secret</p>
       </div>
       <div class="like-bar">
       <img src="https://img.icons8.com/ios-glyphs/2x/speech-bubble.png" id="like-bar" alt=""> 
       <img src="https://img.icons8.com/external-kiranshastry-lineal-color-kiranshastry/2x/external-share-interface-kiranshastry-lineal-color-kiranshastry.png" id="like-bar" alt=""> 
       <img src="https://img.icons8.com/material-sharp/2x/save-search.png" id="like-bar2" alt="">
       <img src="https://img.icons8.com/ios-filled/2x/like.png" id="like-bar" alt="">
       </div>

       <div>
           <h4>Liked by Adva and 180 others</h4>
        </div>
       <div>
           <h4>view all 280 comments</h4>
        </div>
       <div>
           <h4>8 day ago</h4>
        </div>
     
        <div class="text-area">
            <img src="https://img.icons8.com/ios-glyphs/2x/happy.png" id="emojis" alt="">
            <textarea name="" id="text-area" placeholder="add a commennt..." cols="50" rows="1"></textarea>
           <button>POST</button>

          </div>

        
        

     </div> 
    </div>
</body>
</html>

css :

.profile{
    width: 35px;
    height: 35px;
    border-radius: 50%;    
}

.warrper{
    display:inline-flex;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
}

h1{
    color: white;
    padding: 75px 0 75px 0;
    background: linear-gradient(45deg, pink, purple, darkBlue);
    border: solid 10px white;
    border-radius: 50px;
    text-align: center;
}

.warr{
    border: solid 3px black;
    border-radius: 12px;
    padding: 12px;
    margin-bottom: 12px;
}

.content{
    text-align: center;
}



body{
    width: 47%; 
    
    }
    
.like-bar{ 
    display: flex;
}
#emojis{
    height: auto;
     width: 30px;
}

#like-bar{
    height: auto;
     width: 30px;
      margin: 5px;
}

#like-bar2{ 
    margin: right 5px;
     margin-left: auto;
     width: 30px;
    }

#like-bar{
    height: auto;
     width: 30px;
     margin: 5px;
}
    

p{
    font-size: 15px;
}


.textarea{
    resize: none;
}
#emojis{

    height: auto;
    width: 30px;
}
.text-area{
    display: flex;
    align-items: center;
}
button{
color: rgb(8, 121, 121);
    height: 22px;
    background-color: white;

}

.insta{
    margin: auto;

}
