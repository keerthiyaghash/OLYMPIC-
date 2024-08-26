responsive_card
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-compatible" con tent="IE=edge">
    <meta name="viewport" content="width=device-width,initial-scale=1.0">
 

    <link rel="stylesheet" href="C:\Users\SKY\Desktop\DIVPROJECT1\DIVPROJECT1.css">

</head> 

<body>

    <div class="container">

        <h1 class="heading">OLYMPICS</h1>

        <div class="box-container">

            <div class="box">
                <img src="C:\Users\SKY\Desktop\DIVPROJECT1\LONDON2012.jpg">
                <h3>LONDON 2012</h3>
                <p>The London 2012 Games were centred around the Olympic Park in East London, which is the site of a number of new sports venues. Up to 180,000 spectators a day entered the Park to enjoy the Games, making it the principal focus of Olympic activity.</p>
                <a href="https://olympics.com/en/olympic-games/london-2012" class="btn">READ MORE</a>
            </div>

            <div class="box">
                <img src="C:\Users\SKY\Desktop\DIVPROJECT1\RIO2016.jpg">
                <h3> RIO 2016</h3>
                <p>The Rio 2016 Games provided the best possible environment for peak performances. Athletes enjoyed world-class facilities, including a superb village, all located in one of the world’s most beautiful cities, in a compact layout for maximum convenience. </p>
                <a href="https://olympics.com/en/olympic-games/rio-2016" class="btn"> READ MORE</a>
            </div>

            <div class="box">
                <img src="C:\Users\SKY\Desktop\DIVPROJECT1\TOKYO2020.jpg">
                <h3> TOKYO 2020</h3>
                <p>The Tokyo 2020 Games were an unprecedented demonstration of unity and solidarity as the world came together for the first time following the onset of the COVID-19 pandemic for an Olympic Games focused on the pure essentials: a celebration of athletes and sport. </p>
                <a href="https://olympics.com/en/olympic-games/tokyo-2020" class="btn"> READ MORE</a>
            </div>

            <div class="box">
                <img src="C:\Users\SKY\Desktop\DIVPROJECT1\PARIS2024.jpg">
                <h3> PARIS 2024</h3>
                <p>The 2024 Summer Olympics, officially the Games of the XXXIII Olympiad and branded as Paris 2024, was an international multi-sport event that occurred from 26 July to 11 August 2024 in France, with several events started from 24 July. </p>
                <a href="https://olympics.com/ioc/paris-2024" class="btn"> READ MORE</a>
            </div>
        </div>

    </div>

    <footer>
        &copy; 2024 Keerthi Yaghash. All rights reserved.
    </footer>
</body>
</html>




file:///C:/Users/SKY/Desktop/DIVPROJECT1/DIVPROJECT1.html




[Uploading DIVP@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;200;300;400;500;600;700&display=swap');

*{
    font-family: 'Poppins', sans-serif;
    margin:0; padding:0;
    box-sizing: border-box;
    outline: none; border:none;
    text-decoration: none;
    text-transform: capitalize;
    transition: .2s linear;
}


p {
    text-align: justify;
}


.container{
    background:linear-gradient(45deg, blueviolet, lightgreen);
    padding:15px 9%;
    padding-bottom: 100px;
}

.container .heading{
    text-align: center;
    padding-bottom: 15px;
    color:#fff;
    text-shadow: 0 5px 10px rgba(0,0,0,.2);
    font-size: 50px;
}

.container .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(270px, 1fr));
    gap:15px;
}

.container .box-container .box{
    box-shadow: 0 5px 10px rgba(0,0,0,.2);
    border-radius: 5px;
    background: #fff;
    text-align: center;
    padding:30px 20px;
}

.container .box-container .box img{
    height: 80px;
}

.container .box-container .box h3{
    color:#444;
    font-size: 22px;
    padding:10px 0;
}

.container .box-container .box p{
    color:#777;
    font-size: 15px;
    line-height: 1.8;
}

.container .box-container .box .btn{
    margin-top: 10px;
    display: inline-block;
    background:#333;
    color:#fff;
    font-size: 17px;
    border-radius: 5px;
    padding: 8px 25px;
}

.container .box-container .box .btn:hover{
    letter-spacing: 1px;
}

.container .box-container .box:hover{
    box-shadow: 0 10px 15px rgba(0,0,0,.3);
    transform: scale(1.03);
}

@media (max-width:768px){
    .container{
        padding:20px;
    }
}










ROJECT1.css…]()





