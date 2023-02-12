<script setup>
const items = [
  {
    title: 'One',
    src: 'snowhist1thumb.jpg',
  },
  {
    title: 'Two',
    src: 'snowhist2thumb.jpg',
  },
  {
    title: 'Three',
    src: 'snowhist3thumb.jpg',
  },
  {
    title: 'Four',
    src: 'snowhist4thumb.jpg',
  },
  {
    title: 'Five',
    src: 'snowhist5thumb.jpg',
  },
  {
    title: 'Six',
    src: 'snowhist6thumb.jpg',
  },
  {
    title: 'Seven',
    src: 'snowhist7thumb.jpg',
  },
  {
    title: 'Eight',
    src: 'snowhist8thumb.jpg',
  },
]

function getImage(src){
    return new URL(`../assets/imgs/thumbnails/snowhill/${src}`, import.meta.url).href
}
</script>

<template>
  <masonry-wall :items="items" :ssr-columns="1" :column-width="300" :gap="16">
    <template #default="{ item, index }">
      <div>
        <h1>{{ item.title }}</h1>
        <img :src="getImage(item.src)" style="width:100%"/>
      </div>
    </template>
  </masonry-wall>
</template>
