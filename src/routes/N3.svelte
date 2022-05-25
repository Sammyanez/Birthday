
<body>
<div class="bg">
    <h1>N is for...</h1>
    <h1>Now the sentimental part</h1>
    <small style="color: white;">Glad you've made it this far!<br>
        I can't wait to see what you create with that brain of yours.
        <br>Hope every year is better than the last, and that you accomplish everything you aim for.
       <br> Happy 26th Kannon!
        <br> and now a message from our sponsors
    </small>
        <AudioPlayer {src} />
</div>

</body>

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
        background: url('https://i.kym-cdn.com/photos/images/original/002/097/668/3e9.jpg') no-repeat center center fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        background-size: cover;
        -o-background-size: cover;
        font-family: 'Luckiest Guy', cursive;
        font-size: 100px;
    }

</style>

<script>
    import src from './Demo.mp3'
    import AudioPlayer from './AudioPlayer.svelte'

</script>
