<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>台灣發展歷史網頁</title>
    <meta name="description" content="年的此網頁介紹台灣過去經濟發展與經濟政策">
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
    <!--google Curving the Lines圖表連結-->
    <script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
    <script type="text/javascript">
      google.charts.load('current', {'packages':['corechart']});
      google.charts.setOnLoadCallback(drawChart);

      function drawChart() {
        var data = google.visualization.arrayToDataTable([
          ['Year', 'GDP'],
          ['1960',  34394],
          ['1965',  114762],
          ['1970',  231397],
          ['1975',  601778],
          ['1980',  1522459],
          ['1985',  2535056],
          ['1990',  3537056],
       
        ]);

        var options = {
          title: '過去台灣60年GDP變化圖表',
          curveType: 'function',
          legend: { position: 'bottom' }
        };

        var chart = new google.visualization.LineChart(document.getElementById('curve_chart'));

        chart.draw(data, options);
      }
    </script>

    <!--style連結-->
    <link rel="stylesheet" href="./style.css">
    <!--台灣icon連結-->
    <link rel="stylesheet" href="./twicon/twicon.css">


</head>
<body>
    <!--標題-->
    <header>
        <h1 class="headerTitle"><i class="twicon-main-island"></i>台灣經濟發展歷史</h1>
        <h3 class="headerText">過去70年台灣經濟發展的歷史以及相關政策</h3>
    </header>
    <!--導覽列-->
    <nav>
        <ul>
            <li ><i class="twicon-main-island"></i><a class="active" href="#"> 首頁</a></li>
            <li><i class="twicon-lovers-brg"></i><a href="./seond.html"> 農業改革</a></li>
            <li><i class="twicon-grave-sense"></i><a href="./third.html"> 工業改革</a></li>
            <li><i class="twicon-tunghai-uni"></i><a href="./foruth.html"> 經濟起飛</a></li>
            <li><i class="twicon-queens-head"></i><a href="./fifth.html"> 關於作者</a></li>
        </ul>
    </nav>

    <!--主要內容-->
    <main>
        <section class="left">
            <p>
                台灣是太平洋中的一個島嶼。今天，這個島上生活著不同的人群，包括福建，客家，其他省份的中國人，台灣原住民和東南亞移民。第二次世界大戰之前，台灣是日本的殖民地。 
                1895年，由於第一次抗日戰爭失敗，中國將台灣，遼東半島等地賜予日本。第二次世界大戰後，中華民國政府移居台灣，並開始建造該島。中華民國政府在1949年到達台灣時，
                也有將近200萬士兵及其家屬也移居台灣。當時中華民國政府到達台灣時，有許多事情需要解決。 1945年第二次世界大戰結束時，台灣的經濟和衛生條件很低。中華民國政府對台灣的發展產生了重大影響，
                將經濟實體從農業轉變為高科技產業。
                在1960年代至1980年代期間，一系列嚴肅的新政策和發展計劃使台灣工業化。台灣國家統計局表示，1965年人均GDP為229美元，而30年後，1984年人均GDP增至3225美元。
                  
            </p>
<br>
            <p>
                當R.O.C. 政府到達台灣後，他們所做的第一件事是一系列的土地政策。 首先，他們修改了法案以減少與中國法案系統的聯繫，然後發行了台幣。
 之後，他們為農民建立了許多規則，以便他們能夠自給自足。 改善經濟狀況的第二步是發展“輕工業”。 政府開始幫助建立小工廠，生產紡織品，鞋和紙。 這幫助台灣準備轉移到“重工業”。 
為了刺激投資，政府鼓勵世界各地的投資者在台灣港口建立工廠。 這次是發展的第三步。 該網站將討論台灣發生了什麼，台灣的政策和變化以及誰來幫助並使所有這些事情發揮作用。 

            </p>
            <br>
            <div id="curve_chart"></div>
        </section>   
    <section class="right">
        <h4>台灣經濟發展小知識:
            <br>你知道台灣在哪裡嗎?</h4>
        <p>台灣是太平洋上的一個小島。 它毗鄰中國，在島上的原住民被認為是太平洋群島南島語族語系人民的起源。
            台灣的陸地面積為13972公里，島上約有2380萬人居住，最主要通用語言為中文、閩南語、客家話。 </p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d462524.84191359876!2d121.2820017223847!3d25.085766285302057!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3442ac6b61dbbd8b%3A0xbcd1baad5c06a482!2z5Y-w5YyX5biC!5e0!3m2!1szh-TW!2stw!4v1658988930633!5m2!1szh-TW!2stw"
             width="250" height="250" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>    
    </main>
</body>
# Web-application
