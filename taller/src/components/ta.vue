<template>
<footer>
    <div class="container-footer-all">
    <div class="container-body">

        <div class="colum1">
            <h1>Mas informacion de la empresa</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.
            Provident optio inventore magnam? Explicabo deserunt alias eos cum, incidunt nulla amet temporibus totam omnis
            harum delectus! Minus nostrum saepe quis corrupti.</p>
        </div>
        <div class="colum2">
            <h1>Redes Sociales</h1>

            <div class="row">
                <img src="@/assets/logo.png">
                <label>Siguenos en Facebook</label>
            </div>
             <div class="row">
                <img src="@/assets/logo.png">
                <label>Siguenos en Instagram</label>
            </div>
             <div class="row">
                <img src="@/assets/logo.png">
                <label>Siguenos en Whatsapp </label>
            </div>
        </div>
        <div class="colum3">
            <h1>informacion de contacto</h1>

            <div class="row2">
                <img src="@/assets/casa.jpg">
                <label>
                    direccion,calles y numero de casa
                </label>
            </div>
            <div class="row2">
                <img src="@/assets/cellphone_79786.png">
                <label>
                    Numero de Telefonos
                </label>
            </div>
            <div class="row2">
                <img src="@/assets/correo.png">
                <label>
                   Correo electronico
                </label>
            </div>
        </div>
    </div>
    </div>
</footer>
</template>

<script>
export default {

}
</script>

<style>
*{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
    font-family: sans-serif;
}
footer{
    width: 100%;
    background: #202020;
    color: white;
    padding: 40px;
}
.container-footer-all{
    width: 100%;
    max-width: 1200px;
    margin: auto;
}
.container-body{
    display: flex;
    justify-content: space-between;
}
.colum1{
    max-width: 400px;
}
.colum1 h1{
    font-size: 24px;
}
.colum1 p{
    font-size: 14px;
    color: #c7c7c7;
    margin-top: 20px;
}
.colum2{
    max-width: 400px;
}
.colum2 h1{
    font-size: 24px;
}
.row{
    margin-top: 20px;
}
.row img{
    width: 35px;
    height: 35px;
}
.row label{
    margin-top: 10px;
    margin-left: 20px;
    color: #c7c7c7;
}
.colum3{
    max-width: 400px;
}
.colum3 h1{
    font-size: 24px;
}
.row2{
    margin-top: 20px;
    display: flex;
}
.row2 img{
    width: 35px;
    height: 35px;
}
.row2 label{
    margin-top: 10px;
    margin-left: 20px;
    max-width: 150px;
    color: #c7c7c7;
}
@media screen and (max-width: 1100px) {
    .container-body{
        flex-wrap: wrap;
    }

}
@media screen and (max-width: 715px) {
    .colum1{
        max-width: 100%;
    }
    .colum2,
    .colum3{
        margin-top: 40px;
    }
}
</style>
