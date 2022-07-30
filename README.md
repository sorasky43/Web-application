<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>T</title>
    <meta name="description" content="Introduce S">
    
    *{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Noto Sans TC', sans-serif;
font-family: 'Noto Serif TC', serif;
}

h1,h2,h3,h4,h5,h6{
    font-weight: normal;
}

.headerTitle{
    font-size: 2.5rem;
}
.headerText{
    font-size: 1.5rem;
}

header{
    background-color: gray;
    width: 100%;  
    padding: 1rem;
}

nav{
    background-color: #1E1C1C;

}
nav ul{
    display: flex;
    list-style: none;
    padding-left: 1rem;

}

nav ul li{
    padding: 0.5rem 0.5rem ;
}

nav ul li a{
    color: grey;
    text-decoration: none;
    font-size: 1rem;
    transition: all 0.25ease ;
}

nav ul li a:hover{
    color: white;
}

nav ul li i{
    color: white;

}

main{
    width: 100%;
    display: flex;
    flex-wrap: wrap;  
}

section.left{
    flex: 4 1 350px;
}

section.left, section.right{
    padding: 1.5rem;
}


section.right h4{
    font-size: 1.25rem;
    text-align: center;
}



section.right p{
    margin: 1rem 0rem;
}

section.right{
    display: flex;
    flex-direction: column;
    align-items: center;
    flex: 1 1 250px;
}
.active{
    color: white;
}

#curve_chart{
  width: 100%;
  height: 80%;  
}

@media screen and (max-width: 650px) {
    nav ul{
        flex-direction: column;
    
    }  
}

@media screen and (max-width: 550px) {
    #curve_chart{
        width: 100%;
        height: 30%;
    }  
}
    <!--googlefont-->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@500;700&family=Noto+Serif+TC:wght@400;500&display=swap" rel="stylesheet">
    <link rel="shortcut Icon" href="./taiwanIcon.png">
    <link rel="bookmark" href="./taiwanIcon.png">


    <!--style連結-->
    <link rel="stylesheet" href="./style.css">
    <!--台灣icon連結-->
    <link rel="stylesheet" href="./twicon/twicon.css">


</head>
<body>
    <!--標題-->
    <header>
        <h1 class="headerTitle"><i class="twicon-main-island"></i>台灣好好玩</h1>
        <h3 class="headerText">有著你意想不到的美麗景點</h3>
    </header>
    <!--導覽列-->
    <nav>
        <ul>
            <li ><i class="twicon-main-island"></i><a class="active" href="#"> 首頁</a></li>
            <li><i class="twicon-lovers-brg"></i><a href="./seond.html"> 吃美食</a></li>
            <li><i class="twicon-grave-sense"></i><a href="./third.html"> 享住宿</a></li>
            <li><i class="twicon-tunghai-uni"></i><a href="./foruth.html"> Go交通</a></li>
            <li><i class="twicon-queens-head"></i><a href="./fifth.html"> 你不知道的台灣大小事</a></li>
        </ul>
    </nav>

    <!--主要內容-->
    <main>
        <section class="left">
            <p>
                台灣是太平洋中的一個島嶼。歷史沖刷下，讓台灣有著豐富的文化與各式美食、建築融合。走進台灣每個角落，你總會有不一樣的發現，就讓我們帶著好奇的心一步步尋睨。
                
                  
            </p>
<br>
            <p>
                這麼小的台灣有著許許多多的故事，一個環島你可能還意猶未盡。從北到南，從東到西，不論你怎麼走，都會有新的挑戰。如果你喜歡山，你可以查台灣百岳，夠你登頂無數。如果你喜歡海，除了墾丁、東岸的海邊也是美不盛收。就讓我們帶領你一步步探索。Go~ 
            </p>
            <br>
            <div id="curve_chart"></div>
        </section>   
    <section class="right">
        <h4>台灣小知識:
            <br>你知道台灣在哪裡嗎?</h4>
        <p>台灣是太平洋上的一個小島。 它毗鄰中國，在島上的原住民被認為是太平洋群島南島語族語系人民的起源。
            台灣的陸地面積為13972公里，島上約有2380萬人居住，最主要通用語言為中文、閩南語、客家話。 </p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d462524.84191359876!2d121.2820017223847!3d25.085766285302057!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442ac6b61dbbd8b%3A0xbcd1baad5c06a482!2z5Y-w5YyX5biC!5e0!3m2!1szh-TW!2stw!4v1658988930633!5m2!1szh-TW!2stw"
             width="250" height="250" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>    
    </main>
</body>
