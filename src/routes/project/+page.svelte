<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f4f4f4;
    }

    .gallery {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
        gap: 16px;
        padding: 16px;
    }

    .gallery img {
        width: 100%;
        height: 300px;
        border-radius: 8px;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        transition: transform 0.3s ease-in-out;
    }

    .gallery img:hover {
        transform: scale(2);
    }
</style>
<script>
    import { fade, blur, fly, slide, scale, draw } from 'svelte/transition';
</script>


<!-- <h1 in:fade="{{delay: 1000}}" out:fade="{{duration: 1000}}">project</h1> -->

<div class="gallery" in:fade="{{delay: 1000}}" out:fade="{{duration: 1000}}">
    <img class="topBg" src="/src/lib/images/inte1.jpeg" alt="사진 1">
    <img class="topBg" src="" alt="사진 2">
    <img class="topBg" src="" alt="사진 3">
    <img class="topBg" src="" alt="사진 4">
    <img class="topBg" src="" alt="사진 5">
    <img class="topBg" src="" alt="사진 6">
    <img class="topBg" src="" alt="사진 7">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <img class="topBg" src="" alt="사진 8">
    <!-- 필요한 만큼 사진 추가 -->
</div>