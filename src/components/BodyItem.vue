<template>
<div class="articleContainer" style="margin-top:50px;">
            <div class="articleText" style="">
                The first Swedish Antarctic Expedition (1901-1903), led by Otto Nordenskjöld, sailed to Antarctica on the ship Antarctic captained by CA Larsen, and established a research station on Snow Hill Island. There six members overwintered and performed paleontological, meteorological, geomagnetic and geological studies, while the rest of the expedition set sail for South Orkney.
                <p>After the winter, on the way back to Snow Hill Island, the Antarctic got stuck in the ice and sank. At this point, the expedition members were divided into three groups. One of these overwintered an extra year on Snow Hill Island, whereas the other two groups were forced to build stone huts in order to overwinter at Hope Bay and Paulet Island. An Argentinean vessel, the Corbeta Uruguay, rescued the expedition in November 1903.</p>
                <p>This portal makes available documentation of the historical remains of the First Swedish Antarctic Expedition on the Antarctic Peninsula. The material was collected in January and February 2020 as part of the CHAQ2020 expedition. The Swedish National Heritage Board, the Swedish Research Council, and Instituto AntÃ¡rtico Argentino supported the project.</p>
            </div>
    </div>
 <a href="http://raa.diva-portal.org/smash/record.jsf?pid=diva2%3A1589121&dswid=4653"><div class="label" style="margin-right:auto; margin-left:auto; width:30px; height:30px; margin-top:60px;"></div></a>
        <div class="label" style="margin-top:5px;"><a href="http://raa.diva-portal.org/smash/record.jsf?pid=diva2%3A1589121&dswid=4653">Read Full Report</a></div>                                                      

		<div class="label" style="margin-top:10px; cursor:pointer;" onclick="scrollToSites()">Scroll down to documentation</div>

        <div class="scroll bounce" style=""></div>

    <div class="label" style="margin-top:100px;">The Voyage to Antarctica</div>
        <div class="voyage" style="margin-top:20px; background-image:url(../imgs/antarcticavoyage.jpg)">
    
            <video width="700" height="700" autoplay loop muted playsinline>
                <source src="../assets/imgs/antarcticavoyage.mp4" type="video/mp4">
                <source src="../assets/imgs/antarcticavoyage.webm" type="video/webm">
            </video>
        </div> 

    <div id="mapbg">
        <div id="SiteContainer">
            <div id="sites" style="margin-top:1400px;position:absolute;"> </div>

          <router-link to="/about">
            <div style="cursor:pointer; margin-top:2360px; height:auto; min-width:300px; margin-left:1020px; position: absolute;">
                <div class="siteLabelTitle" id="snowhill" style="text-align:left; ">Snow Hill Island</div>
                <div class="siteLabelSpanish" style="text-align:left; margin-top:5px;">Isla Cerro Nevado</div>
                <div class="siteLabelDescription" style="text-align:left; margin-top:0px;">Feb. 1902 - Nov. 1903</div>
            </div>
          </router-link>
    <router-link to="/about"><div style="margin-top: 2300px; margin-left: 710px; position: absolute;"><div class="MainCircle"></div></div></router-link>
        </div>
    </div>

</template>

<style scoped>
     .voyage {
        background-color: white;
        border-radius: 50%;
        width: 700px;
        height: 700px;
        margin-left: auto;
        margin-right: auto;
        overflow: hidden;
        opacity: 0.99;
        transform: translateZ(0);
    }

     .scroll {
        margin-left: auto;
        margin-right: auto;
        background: url(../assets/interface/scrollarrow2.png);
        background-size: 30px 30px;
        width: 30px;
        height: 30px;
        margin-top: 55px;
    }

     .bounce {
        animation: bounce 1s linear infinite;
    }

    @keyframes bounce {
        0%,100% {
            transform: translateY(0);
        }

        25% {
            transform: translateY(-10px);
        }

        50% {
            transform: translateY(-20px);
        }

        75% {
            transform: translateY(-10px);
        }
    }

    #mapbg {
        height: 2831px;
        width: 100%;
        background: url(../assets/imgs/bg-map.png);
        background-repeat: no-repeat;
        background-size: 1500px 2831px;
        opacity: 1.0;
        background-position: 0px 0px;
        z-index: 1;
        transition: all .2s ease-in-out;
    }

    @media screen and (max-width: 1440px) {
        #mapbg {
            background-position: -200px 0px;
        }
    }

    @media screen and (max-width: 1240px) {
        #mapbg {
            background-position: -400px 0px;
        }
    }

    @media screen and (max-width: 1040px) {
        #mapbg {
            background-position: -500px 0px;
        }
    }
</style>
