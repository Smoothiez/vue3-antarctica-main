<template>
    <div id="viewer" style="width:800px;height:600px;"></div>
</template>

<script>
import Openseadragon from 'openseadragon'
export default {
  mounted() {
    var viewer = new Openseadragon({
        id: 'viewer',
        tileSources: {
            type: 'image',
            url: 'https://placedog.net/1000/1000',
        },
    });
  }
}
</script>
