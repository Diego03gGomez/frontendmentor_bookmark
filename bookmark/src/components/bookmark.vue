<template lang="">
    <div>
<div class="menu_oculto">
<div class="header_oculto">
    <h1><img src="https://bookmarklandingpagezero.netlify.app/images/logo-bookmark-white.svg" alt=""></h1>

    <i v-on:click="cerrar_menu()" class="fa-solid fa-xmark cerrar"></i>
</div>

<div class="nav_oculto">
    <hr>
    <a >FEATURES</a>
<hr>
<a >PRICING</a>
<hr>

<a >CONTACT</a>
<hr>
<a class="login2"  >LOGIN</a>
</div>


<div class="redes_oculto">
    <i class="fa-brands fa-square-facebook"></i>
    <i class="fa-brands fa-twitter"></i>

</div>


</div>



        <header>
            <div class="cont_header">
                <h1><img src="https://bookmarklandingpagezero.netlify.app/images/logo-bookmark.svg" alt=""></h1>
            
            <nav>
                <a href="">FEATRES</a>
                <a href="">PRICING</a>
                <a href="">CONTACT</a>
                <a  class="login" href="">LOGIN</a>
            </nav>

            <i v-on:click="desplegar_menu()" class="fa-solid fa-bars menu"></i>
            
            </div>
        </header>







<div id="fondo1">
<div class="cont_fondo1">

<div class="div1">
<h1>A Simple Bookmark <br>
Manager</h1>
<p>A clean and simple interface to organize your favourite <br>
websites. Open a new browser tab and see your sites load <br>
instantly. Try it for free</p>
<div class="cont_botones">
    <a class="violeta"  href="">Get it on Chrome</a>
    <a href="">Get it on Firefox</a>
</div>

</div>


<div class="div2">
    <img src="https://bookmarklandingpagezero.netlify.app/images/illustration-hero.svg" alt="">
</div>



</div>


</div>


<div id="fondo2">
<div class="titulo_fondo2">
    <h1>Features</h1>
    <h3>Our aim is to make it quick and easy for you to access your <br>
favourite websites. Your bookmarks sync between your devices <br>
so you can access them on the go.</h3>
</div>

<div class="cont_filtros">
<a  class="estilo_link"   v-on:click="mostrar_div1($event)" >Simnple Bookmarking</a>
<a   v-on:click="mostrar_div2($event)" >Speddy Searching</a>
<a v-on:click="mostrar_div3($event)" >Easy Sharging</a>
</div>

<div class="cont_divs">

<div class="div_oculto1">

<div class="cont_imagen">
    <img src="https://bookmarklandingpagezero.netlify.app/images/illustration-features-tab-1.svg" alt="">
</div>
<div class="cont_desc">
    <h1>Bookmark in one click</h1>
    <h3>Organize your bookmarks however you like. Our <br>
    simple drag-and_drop interface gives you complete <br>
control over how you manage your favourites sites;</h3>
</div>


</div>


<div class="div_oculto2">

<div class="cont_imagen">
    <img src="https://bookmarklandingpagezero.netlify.app/images/illustration-features-tab-2.svg" alt="">
</div>

<div class="cont_desc">
    <h1>Inteligent search</h1>
    <h3>Our powerful search features will gelp you find saved <br>
    sites in no time at all. No need to trawl through all of <br>
your bookmarks</h3>
<a class="violeta">More Info</a>
</div>


</div>
















<div class="div_oculto3">

<div class="cont_imagen">
    <img src="https://bookmarklandingpagezero.netlify.app/images/illustration-features-tab-3.svg" alt="">
</div>

<div class="cont_desc">
    <h1>Share your bookmarks</h1>
    <h3>Easily share your bookmarks and collections with<br>
    others. Create a shareable link that you can send at<br>
the click of a button.</h3>
<a class="violeta">More Info</a>
</div>


</div>





</div>




</div>



<div id="fondo3">
    <div class="titulo_fondo3">
        <h1>Download the extension</h1>
        <h3>We’ve got more browsers in the pipeline. Please do let us know if <br>
            you’ve got a favourite you’d like us to prioritize.</h3>
    </div>






<div class="cont_fondo3">
<div class="card1_fondo3">
    <div class="img">
        <img src="https://bookmarklandingpagezero.netlify.app/images/logo-chrome.svg" alt="">
    </div>
    <div class="texto">
        <h2>Add to Chrome</h2>
        <p class="gris"  >Minimum version 62</p>
    </div>
    <h4>. . . . . . . . . . . . . .</h4>
    <a class="violeta" href="">Add & Install Extension</a>
</div>

<div class="card2_fondo3">
    <div class="img">
        <img src="https://bookmarklandingpagezero.netlify.app/images/logo-firefox.svg" alt="">
    </div>
    <div class="texto">
        <h2>Add to Firefox</h2>
        <p class="gris">Minimum version 55</p>
    </div>
    <h4>. . . . . . . . . . . . . .</h4>
    <a class="violeta"  href="">Add & Install Extension</a>
</div>


<div class="card3_fondo3">
    <div class="img">
        <img src="https://bookmarklandingpagezero.netlify.app/images/logo-opera.svg" alt="">
    </div>
    <div class="texto">
        <h2>Add to Opera</h2>
        <p class="gris"  >Minimum version 46</p>
    </div>
    <h4>. . . . . . . . . . . . . .</h4>
    <a class="violeta"  href="">Add & Install Extension</a>
</div>


</div>



</div>
    






<div id="fondo4">

<div class="titulo_fondo4">
    <h1>Frequentyl Asked Questions</h1>
    <h3>Here are some of our FAQs. If you have any other questions you d like ansquered please feel free to email us.</h3>
</div>



<div class="cont_acordeon">
<div class="opcion">
    <p>What is Bookmark?</p>
    <i v-on:click="m_acordeon1($event)" class="fa-solid fa-chevron-up icono_desplegable "></i>
</div>
<div class="acordeon1 eliminar ">
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce tincidunt justo <br>
        eget ultricies fringilla. Phasellus blandit ipsum quis quam ornare mattis.</p>
</div>


<div class="opcion">
    <p>How can i request a new browser?</p>
    <i v-on:click="m_acordeon2($event)" class="fa-solid fa-chevron-up icono_desplegable"></i>
</div>
<div class="acordeon2 eliminar">
    <p>Vivamus luctus eros aliquet convallis ultricies. Mauris augue massa, ultricies <br>
         non ligula. Suspendisse imperdiet. Vivamus luctus eros aliquet convallis <br>
         ultricies. Mauris augue massa, ultricies non ligula. Suspendisse imperdie <br>
          tVivamus luctus eros aliquet convallis ultricies. Mauris augue massa, ultricies <br>
           non ligula. Suspendisse imperdiet.</p>
</div>


<div class="opcion">
    <p>Is there a mobile app?</p>
    <i v-on:click="m_acordeon3($event)" class="fa-solid fa-chevron-up icono_desplegable"></i>
</div>
<div class="acordeon3 eliminar">
    <p>Sed consectetur quam id neque fermentum accumsan. Praesent luctus <br>
         vestibulum dolor, ut condimentum urna vulputate eget. Cras in ligula quis est <br>
          pharetra mattis sit amet pharetra purus. Sed sollicitudin ex et ultricies <br>
           bibendum.</p>
</div>



<div class="opcion">
    <p>What about other Chromium browsers?</p>
    <i v-on:click="m_acordeon4($event)"  class="fa-solid fa-chevron-up icono_desplegable"></i>
</div>
<div class="acordeon4 eliminar">
    <p>Integer condimentum ipsum id imperdiet finibus. Vivamus in placerat mi, at <br>
         euismod dui. Aliquam vitae neque eget nisl gravida pellentesque non ut velit.</p>
</div>



</div>



</div>

<div class="boton_info">
    <a class="violeta" >More Info</a>
</div>


<div id="fondo5">


<div class="titulo_fondo5">
<p>35,000+ ALREADY JOINED</p>
<h1>Stay up-to-date with what <br>
    we’re doing</h1>

</div>

<div class="cont_input">
    <input type="email" placeholder="Enter you email address."> <a >Contact Us</a>
</div>



</div>




<footer>

<div class="cont_footer">
    <div class="div1_cont_footer">
        <h1><img src="https://bookmarklandingpagezero.netlify.app/images/logo-bookmark-light.svg" alt=""></h1>
    <a >FEATURES</a>
    <a >PRICING</a>
    <a >CONTACT</a>
    </div>


    <div class="redes">
    <i class="fa-brands fa-square-facebook"></i>
    <i class="fa-brands fa-twitter"></i>
</div>
</div>




</footer>

























    </div>
</template>
<script>
export default {
    methods: {
        mostrar_div1(event) {
$(".div_oculto2").hide();;
$(".div_oculto3").hide();;
$(".div_oculto1").show();

let links = document.querySelector(".cont_filtros").querySelectorAll("a");
links.forEach((e) => {
  e.classList.remove("estilo_link")
});


let link = event.currentTarget;
link.classList.add("estilo_link")

        },
        mostrar_div2(event) {
$(".div_oculto1").hide();
$(".div_oculto3").hide();
$(".div_oculto2").show();
let links = document.querySelector(".cont_filtros").querySelectorAll("a");
links.forEach((e) => {
  e.classList.remove("estilo_link")
});

let link = event.currentTarget;
link.classList.add("estilo_link")

        },
        mostrar_div3(event) {
$(".div_oculto1").hide();
$(".div_oculto2").hide();
$(".div_oculto3").show();
let links = document.querySelector(".cont_filtros").querySelectorAll("a");
links.forEach((e) => {
  e.classList.remove("estilo_link")
});

let link = event.currentTarget;
link.classList.add("estilo_link")
        },

        desplegar_menu(){

let menu = document.querySelector(".menu_oculto");
menu.classList.add("trasladar");
        },
        cerrar_menu(){
            let menu = document.querySelector(".menu_oculto");
            menu.classList.remove("trasladar");
        },





        m_acordeon1(event){
let acordeon1 = document.querySelector(".acordeon1");
acordeon1.classList.toggle("eliminar")
let icon = event.currentTarget.parentNode.querySelector(".icono_desplegable");
icon.classList.toggle("rotacion")


        },
        m_acordeon2(event){
let acordeon1 = document.querySelector(".acordeon2");
acordeon1.classList.toggle("eliminar");
let icon = event.currentTarget.parentNode.querySelector(".icono_desplegable");
icon.classList.toggle("rotacion")
        },
        m_acordeon3(event){
let acordeon1 = document.querySelector(".acordeon3");
acordeon1.classList.toggle("eliminar");
let icon = event.currentTarget.parentNode.querySelector(".icono_desplegable");
icon.classList.toggle("rotacion")
        },

        m_acordeon4(event){
let acordeon1 = document.querySelector(".acordeon4");
acordeon1.classList.toggle("eliminar");
let icon = event.currentTarget.parentNode.querySelector(".icono_desplegable");
icon.classList.toggle("rotacion")
        },






    },

    mounted () {
        $(".div_oculto2").fadeOut();
        $(".div_oculto3").fadeOut();
    },
    
}
</script>
<style lang="">
    
</style>