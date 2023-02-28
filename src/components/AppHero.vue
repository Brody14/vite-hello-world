<template>
    <div class="jumbo">
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
    background-image: url('/img/vite-background.jpg');
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    height: 525px;
    width: 1084px;

}

.jumbo-title {
    position: absolute;
    top: 70%;
    left: 50%;
    transform: translateX(-50%);
    color: black;
    font-size: 21px;
    filter: drop-shadow(0px 8px 3px black)
}
</style>