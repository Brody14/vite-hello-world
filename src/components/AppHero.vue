<template>
    <div class="jumbo">
        <img class="jumbo-img" src="/img/vite-background.jpg" alt="">
        <p class="jumbo-title"> {{ text }} </p>
    </div>
</template>
  
<script>
export default {
    data() {
        return {
            text: 'Una appassionante storia di fraintendimenti'
        }
    }
}
</script>
  
<style>
.jumbo {
    position: relative;
}

.jumbo-img {
    height: 500px;
}

.jumbo-title {
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translateX(-50%);
    color: black;
}
</style>