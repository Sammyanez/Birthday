
<body>
<div class="bg">
    <h1>O is for...</h1>
    <h1>October</h1>
    <small style="color: white;">INKTOBER YOU DID THAT</small>
    <small style="color: white;"><br>Your art unsolicitedly retold by me</small>
    <CardColumns style=" display: grid; grid-template-columns: 1fr 1fr 1fr;grid-gap: 50px;">
        {#each photos as photo}
    <Card class="mb-3">
        <CardHeader>
            <CardTitle>{photo.title}</CardTitle>
            <CardImg  class="card-img-top" src={photo.src} alt="Card image cap"> </CardImg>
        </CardHeader>
        <CardBody>
            <CardText>
                {photo.description}
            </CardText>
        </CardBody>
        <CardFooter>By Kannon Rickell</CardFooter>
    </Card>
        {/each}
    </CardColumns>
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
        background: url('https://i.cbc.ca/1.6365400.1646148286!/fileImage/httpImage/image.jpg_gen/derivatives/original_780/liminal-digital-rendering-example.jpg') no-repeat center center fixed;
        -webkit-background-size: cover;
        -moz-background-size: cover;
        background-size: cover;
        -o-background-size: cover;
        font-family: 'Luckiest Guy', cursive;
        font-size: 100px;
    }


</style>

<script lang="ts">
    import photos from './inktober.js'
    import {
        CardColumns,
        CardImg,
        Button,
        Card,
        CardBody,
        CardFooter,
        CardHeader,
        CardSubtitle,
        CardText,
        CardTitle,
    } from 'sveltestrap';
</script>




