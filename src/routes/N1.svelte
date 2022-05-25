
<body>
<div class="bg">
    <h1>N is for...</h1>
    <h1>No Nut November</h1>
    <small>Remember when you demonstrated self control!</small>
</div>

<Image alt="Landscape" src={image} />
</body>
<script lang="ts">
    import { Image } from 'sveltestrap';
    import image from './NoNut.png'
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
        background: url('https://64.media.tumblr.com/bc4669592e816da39d1817a2d6e33c1e/9339393dd702b1d8-73/s1280x1920/3ddf8a735216f3b41c38e042713da8018f9b81ef.jpg') no-repeat center center fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        background-size: cover;
        -o-background-size: cover;
        font-family: 'Luckiest Guy', cursive;
        font-size: 100px;
    }

</style>