<template>
	<div id="intrographics" style=""></div>
    <p>BUILT CULTURAL HERITAGE IN</p>
    <h1><i>ANTARCTICA</i></h1>
    <div class="label" style="margin-top:10px; cursor:pointer;" onclick="$('#contacts').slideToggle('fast');scrollSmoothToBottom()"><i>Jonathan Westin, Gunnar Almevik,<br> Dag Avango & Kati Lindstr&ouml;m</i></div>
</template>

<script>
/*  export default {
    props: ['title']
 } */
</script> 


<style scoped>
    h1 {
        font-family: 'Playfair Display', serif;
        font-weight: 600;
        width: 100%;
        text-align: center;
        font-size: 140px;
        margin-bottom: 40px;
        margin-top: 0px;
    }

    p {
        width: 100%;
        text-align: center;
        font-size: 40px;
        line-height: 0.5;
    }

    #intrographics{
        position:absolute; 
        margin-top:-140px; 
        margin-left:-50px; 
        width:700px; 
        height:450px; 
        background-image:url(../assets/imgs/introislands.png); 
        background-size: cover;
        transition: all .2s ease-in-out;
	}

</style>
