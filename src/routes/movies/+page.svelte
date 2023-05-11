<script>

    let title1 = "A New Hope";
    let title2 = "The Empire Strikes Back";
    let title3 = "Return of the Jedi";

    let title4 = "The Force Awakens";

    let img1 = "https://prod-ripcut-delivery.disney-plus.net/v1/variant/disney/BCED452AF9DF94603B00DC7FAFD4269F7360A16D0C9E8590950F3BC27183682D/scale?width=1200&aspectRatio=1.78&format=jpeg";
    let img2 = "https://prod-ripcut-delivery.disney-plus.net/v1/variant/disney/B92552B7CE9B7BB39BB3BDC551F35DB98C04740118F5B30975134814DF7A4E62/scale?width=1200&aspectRatio=1.78&format=jpeg";
    let img3 = "https://prod-ripcut-delivery.disney-plus.net/v1/variant/disney/56FEAB4863C5914FC8DF3C03D4B61607BCFF7A81BA6C701430572B450EAE9B89/scale?width=1200&aspectRatio=1.78&format=jpeg";

    let img4 = "https://prod-ripcut-delivery.disney-plus.net/v1/variant/disney/8E729B41E4F07EF71CB94C778A0734F0FE1DE37E87A78150CB8E997DC9BD3290/scale?width=1200&aspectRatio=1.78&format=jpeg";

</script>

<style>

    *{
        box-sizing:border-box;
    }

    .cards{
        height:400px;        
    }

    .card1{
        border:1px solid black;
        width:200px;
        float:left;
        height:400px;
        position:relative;
        background:maroon;
        color:white;
    }

    .card2{
        border:1px solid black;
        width:200px;
        float:left;
        height:400px;
        position:relative;
        background:darkblue;
        color:white;
    }

    .card3{
        border:1px solid black;
        width:200px;
        float:left;
        height:400px;
        position:relative;
        background:darkgreen;
        color:white;
    }

    .card4{
        border:1px solid black;
        width:200px;
        float:left;
        height:400px;
        position:relative;
        background:black;
        color:white;
    }

    .img1{
        width:200px;
        position:absolute;
        top:50%;
         margin-top:-56.5px;
    }

    .img2{
        width:200px;
        position:absolute;
        top:50%;
        margin-top:-56.5px;
    }

    .img3{
        width:200px;
        position:absolute;
        top:50%;
        margin-top:-56.5px;
    }

    .img4{
        width:200px;
        position:absolute;
        top:50%;
        margin-top:-56.5px;
    }

</style>

<h1>All Movies</h1>

<nav>
    <ul>
        <li><a href="/">Home</a></li>
        <li><a href="/movies">All Movies</a></li>
    </ul>
</nav>

<div class="cards">
    <div class="card1">
        <h1>{title1}</h1>
        <img class="img1" src="{img1}" />
    </div>

    <div class="card2">
        <h1>{title2}</h1>
        <img class="img2" src="{img2}" />
    </div>

    <div class="card3">
        <h1>{title3}</h1>
        <img class="img3" src="{img3}" />
    </div>

    <div class="card4">
        <h1>{title4}</h1>
        <img class="img4" src="{img4}" />
    </div>
</div>