<script setup>
const image = {
    imageUrl : "https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSg-3382ZgdUhzsOz0VYE8KVNtX_HTwTxRSps08Nli1&s",
    alt: 'Logo'
}
const  link = {
    linkUrl: "https://google.com"
}
</script>


<template>
    <img :src="image.imageUrl" :alt="image.alt">
    <hr>
    <h1><a :href="link.linkUrl">Go to Google</a></h1>
</template>

