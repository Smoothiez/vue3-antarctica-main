<template>
    <div id="viewer" style="width:100%;height:600px;"></div>
     <router-link to="/about">
            <div id="Back"></div>
        </router-link>
</template>

<script>
import Openseadragon from 'openseadragon'
export default {
  mounted() {
    var viewer = new Openseadragon({
        id: 'viewer',
        tileSources: {
            toolbar: "toolbarDiv",
            type: 'image',
            url: 'https://placedog.net/1000/1000',
        },
    });
  }
}
</script>

<style scoped>
   
  
</style>