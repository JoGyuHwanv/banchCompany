
<style>
    
</style>
<script>
    import { fade, blur, fly, slide, scale, draw } from 'svelte/transition';
</script>
<!-- <h1 transition:fade="{{delay: 1000, duration: 100}}">home</h1> -->
<div class="topBg" in:fade="{{delay: 1000}}" out:fade="{{duration: 1000}}">
    <strong>홈입니다 <br />온라인 서비스,</strong>
    <span>test여기에 제공하는 서비스에 대한 설명이 들어갑니다.ㅋㅋㅋ</span>
</div>