<template>
<div class="search-result-item">
     <a class="search-result-link" :href="info.url">
        <div class="title">{{info.title}}</div>
        <div class="url">{{info.url}}</div>
        <div class="desc">{{info.date}}-{{info.desc}}</div>
        
    </a>
</div>
   
</template>

<script>
export default {
    props:["info"]
}
</script>

<style lang="sass" scoped>
.search-result-item
    // border: solid 2px red
    text-align: left
    padding: 20px
.title
    color: #190daa
    font-size: 1.15em
.url
    color: #006620
    font-weight: 600
.desc 
    color: #545454 
.search-result-link
    text-decoration: none      


</style>
