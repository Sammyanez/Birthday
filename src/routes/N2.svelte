
<body>
<div class="bg">
    <h1>N is for...</h1>
    <h1>N-word pass</h1>
    <small style="color: white;">You're not allowed to use this... <br>and I'm not allowed to give this to you... <br> but you can have it</small>
</div>

<Image alt="Landscape" src={image} />
</body>
<script lang="ts">
    import { Image } from 'sveltestrap';
    import image from './Pass.png'
</script>

<style>
    h1{
        font-size: 100px;
        background-color: aquamarine;
        background-image: linear-gradient(45deg, aquamarine, #af4261);
        background-size: 100%;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;

    }
    small{
        color: black;
    }
    body {
        background: url('https://64.media.tumblr.com/622d069fb05e58ee873fee96a9208919/2d3ab2a0909ca1fa-ff/s1280x1920/e0df7ac8d6e6f74b06fcf1bc4312d22264e676e8.jpg') no-repeat center center fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        background-size: cover;
        -o-background-size: cover;
        font-family: 'Luckiest Guy', cursive;
        font-size: 100px;
    }

</style>