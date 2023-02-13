<template>

<div id="Site" style=""><div class="SiteCircle"></div></div>
    <div id="top" style="">

        <router-link to="/">
            <div id="Back"></div>
        </router-link>

        <div id="sitetitle" style="">SNOW<br> HILL<br> ISLAND</div>
            <div class="subTitle">Isla Cerro Nevado</div>
            <div class="subTitle"><a href="https://goo.gl/maps/JEU4t7GhyBppM6YbA">64&#186; 22&#39; 00&#34; S 56&#186; 59&#39; 00&#34; W</a></div>
            <div class="articleContainer" style="margin-top:50px;">
                        <div class="articleText" style="">
                            <p>The wooden hut (HSM 38) was prefabricated in Sweden to function as a research station and dwelling during the Antarctic winter. The hut was called "the Winter Station" by the expeditioners, but is today named "Nordenskjöld’s hut" or "Casa Suecia" or "Refugio Suecia". The Winter Station was erected in February 1902 on a hill between the sea and the mountains on the west side of Snow Hill Island. Six of the expedition members, including Otto Nordenskjöld and the Argentinian lieutenant José María Sobral, stayed in the hut for 22 months, until the Argentine ship Uruguay came for their rescue in November 1903.</p>
                            <p>During the stay, the group performed research in geography, geology, bacteriology and meteorology. The near surrounding landscape was set up like a laboratory with various sheds and installations for observation and measurements. The effects of climate change with meltwater erosion and land drift have destroyed and even erased many of these remains.</p>

                            <p>The Winter Station, a 4.0 x 6.3 metre wooden building, has, however, endured time and is well preserved, but the hill on which it stands is acutely threatened by the melting of permafrost and meltwater ero- sion. Efforts by the IAA from the 1990s up until the mid-2010s to reinforce the hill have probably kept the building from drifting and tumbling. Terraces were made of reused aluminium elements from temporary American aircraft runways used in Vietnam. The Winter Station has been maintained with many layers of tarred paper and new window sashes.</p>

                            <p>If the building is to stand for the next 30 to 50 years, the recommendation is to continue regular building maintenance and to resume to reinforce the hill using the same methods that the DNA-IAA have applied in the past. The sites with remains from Nordenskjöld's fieldwork are disappearing and require direct rescue archaeology.</p>
                        </div>
    </div>
        <a href="http://raa.diva-portal.org/smash/record.jsf?pid=diva2%3A1589121&dswid=4653"><div class="label" style="margin-right:auto; margin-left:auto; width:30px; height:30px; margin-top:60px;"></div></a>
        <div class="label" style="margin-top:5px;"><a href="http://raa.diva-portal.org/smash/record.jsf?pid=diva2%3A1589121&dswid=4653">Read Full Report</a></div>   
    </div>
    <div id="galleries">
    <div id="FancyArrowInv"></div>
    <div class="SectionTitle" style="">Plans and Drawings</div>
        <div class="documentationArticleSolo" style="">
            The drawings of the winter station were carried out using traditional methods and are available both as pencil originals with notes and cleaned up ink drawings. The plans were produced using scan data from the Faro Focus m70 on January 12, 13, and 19.
        </div>
        <div id="snowhilldrawings" style="width:100%;"></div>
    </div>


</template>

<style scoped>
  #galleries {
        color: white;
        width: 100%;
        padding: 20px 0 100px 0;
        background-color: RGBA(30, 30, 30, 3.0);
    }

     .SectionTitle {
        width: 80%;
        height: auto;
        text-align: left;
        margin-left: auto;
        margin-right: auto;
        margin-top: 70px;
        font-weight: 100;
        font-style: normal;
        font-size: 40px;
        line-height: 1.0;
    }

    .documentationArticle {
    width: 80%;
    font-size: 16px;
    text-align: justify;
    margin-top: 15px;
    margin-bottom: 10px;
    margin-left: auto;
    margin-right: auto;
    column-count: 2;
    column-gap: 40px;
    column-rule-style: solid;
    column-rule-width: 1px;
    column-rule-color: grey;
}

.documentationArticle span {
    color: #66CCFF;
}

@media screen and (max-width: 800px) {
    .documentationArticle {
        width: 80%;
        font-size: 22px;
        text-align: justify;
        margin-top: 15px;
        margin-bottom: 10px;
        margin-left: auto;
        margin-right: auto;
        column-count: 1;
      
    }

}

.documentationArticleSolo {
    max-width: 700px;
    font-size: 16px;
    margin-right: 40px;
    text-align: justify;
    margin-top: 15px;
    margin-bottom: 10px;
    margin-left: 10%;
}

@media screen and (max-width: 800px) {
    .documentationArticleSolo {
        font-size: 32px;
     
      
    }
}

.documentationArticleSolo span {
    color: #66CCFF;
}

 #FancyArrow {
        margin-top: -62px;
        height: 50px;
        width: 100px;
        margin-left: auto;
        margin-right: auto;
        background: url(../assets/interface/arrow.png);
        background-size: 70px 35px;
        background-repeat: no-repeat;
        background-position: center;
    }

    #FancyArrowInv {
        margin-top: -28px;
        height: 50px;
        width: 100px;
        margin-left: auto;
        margin-right: auto;
        background: url(../assets/interface/arrow2.png);
        background-size: 70px 35px;
        background-repeat: no-repeat;
        background-position: center;
    }

</style>
