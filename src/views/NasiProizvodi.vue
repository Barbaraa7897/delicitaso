<template>
    <div>
        <div class="hero-image">
            <div class="button" style="color:#000;">
            <h2>Naši proizvodi</h2>
            </div>
            <div class="proizvodiBg" style="background-color:white;width:100%;">
                <div class="container">
                    <div class="row">
                        <div class="col-4">
                            <img src="https://via.placeholder.com/250">
                            <div class="button2" style="color:#000;">
                                <h2>Naši proizvodi</h2>
                            </div>
                        </div>
                        <div class="col-4">
                            <img src="https://via.placeholder.com/250">
                            <div class="button2" style="color:#000;">
                                <h2>Naši proizvodi</h2>
                            </div>
                        </div>
                        <div class="col-4">
                            <img src="https://via.placeholder.com/250">
                            <div class="button2" style="color:#000;">
                                <h2>Naši proizvodi</h2>
                            </div>
                           <router-link class="button3" to="/">Natrag</router-link> 
                              
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        
        
    </div>
</template>

<style lang="scss" scoped>
.button{
    display:inline-block;
    height: 80px;
    border-radius: 15px;
    width: 18em;
    margin-top: 50px;
      background-color: rgba(214, 248, 62, 0.918);
    font-size: 2em;
    box-shadow: 5px 10px 18px black;
    line-height: 5em;
}
.button2{
    height: 80px;
    text-align: center;
    border-radius: 15px;
    width: 8em;
    margin-top: 50px;
      background-color: rgba(214, 248, 62, 0.918);
    font-size: 2em;
    box-shadow: 5px 10px 18px black;

}
.hero-image{
    background-image: url("/images/pozadinaNasiProizvodi.png");
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: left;

}
.proizvodiBg{
    padding-top: 80px;
}
.button3{
    display:inline-block;
    height: 70px;
    border-radius: 15px;
    text-align: center;
    width: 7em;
    margin-top: 2em;
    background-color: rgba(214, 248, 62, 0.918);
    color: black;
    float:right;
    font-size:2.6em;
    box-shadow: 5px 10px 18px black;
    margin-right:0.1em;
  }
  
    .button2:hover{
    /*tu stoji kićasti stil koji M@Rk0 ne voli a moraće da trpi h3h3h3*/
    background-color: rgb(206, 255, 92);
    width:240px;
    transition: 2s;}

    
    .button3:hover{
    /*tu stoji kićasti stil koji M@Rk0 ne voli a moraće da trpi h3h3h3*/
    background-color: rgb(206, 255, 92);
    width:260px;
    transition: 2s;}

</style>