<template>
    <div class="secundaria">
        <div class="titulo">
            <span>Secundaria</span>
        </div>

        <div class="libreria">

            <div class="libro">
                <div class="psuperior1">
                    <div><img class="pnumero" src="../assets/imgs/1.png" alt="numero1"></div>
                </div>
                <div class="pinferior">
                    <div><img class="favorito" src="../assets/imgs/favoritogray.png" alt="fav"></div>
                    <span class="titulolibro">Geografía Secundaria</span>
                    <small class="descripcion">Humberto Lopez</small>
                    <div class="footerlibro">
                        <img class="options" src="../assets/imgs/options.png" alt="options">
                        <small>20 temas</small>
                        <img class="download" src="../assets/imgs/download.png" alt="download">
                    </div>
                </div>
            </div>

            <div class="libro">
                <div class="psuperior2">
                    <div><img class="pnumero" src="../assets/imgs/2.png" alt="numero2"></div>
                </div>
                <div class="pinferior">
                    <div><img class="favorito" src="../assets/imgs/favoritogray.png" alt="fav"></div>
                    <span class="titulolibro">Historia Universal</span>
                    <small class="descripcion">Eduardo Mexía</small>
                    <div class="footerlibro">
                        <img class="options" src="../assets/imgs/options.png" alt="options">
                        <small>20 temas</small>
                        <img class="download" src="../assets/imgs/download.png" alt="download">
                    </div>
                </div>
            </div>

            <div class="libro">
                <div class="psuperior3">
                    <div><img class="pnumero" src="../assets/imgs/3.png" alt="numero3"></div>
                </div>
                <div class="pinferior">
                    <div><img class="favorito" src="../assets/imgs/favoritogray.png" alt="fav"></div>
                    <span class="titulolibro">Biología Secundaria</span>
                    <small class="descripcion">Diana Padilla</small>
                    <div class="footerlibro">
                        <img class="options" src="../assets/imgs/options.png" alt="options">
                        <small>20 temas</small>
                        <img class="download" src="../assets/imgs/download.png" alt="download">
                    </div>
                </div>
            </div>

            <div class="libro">
                <div class="psuperior4">
                    <div><img class="pnumero" src="../assets/imgs/1+.png" alt="numero1"></div>
                </div>
                <div class="pinferior">
                    <div><img class="favorito" src="../assets/imgs/favoritogray.png" alt="fav"></div>
                    <span class="titulolibro">Matemáticas Secundaria</span>
                    <small class="descripcion">HEctor Castro</small>
                    <div class="footerlibro">
                        <img class="options" src="../assets/imgs/options.png" alt="options">
                        <small>20 temas</small>
                        <img class="download" src="../assets/imgs/download.png" alt="download">
                    </div>
                </div>
            </div>


            <div class="libro">
                <div class="psuperior5">
                    <div><img class="pnumero" src="../assets/imgs/top1.png" alt="numero5"></div>
                </div>
                <div class="pinferior">
                    <div><img class="favorito" src="../assets/imgs/favoritogray.png" alt="fav"></div>
                    <span class="titulolibro">Atlas de México</span>
                    <small class="descripcion">Guillermina Gonzalez De Lemoine</small>
                    <div class="footerlibro">
                        <img class="options" src="../assets/imgs/options.png" alt="options">
                        <small>20 temas</small>
                        <img class="download" src="../assets/imgs/download.png" alt="download">
                    </div>
                </div>
            </div>

        </div>
        <img class="sidearrow" src="../assets/icons/arrow.png" alt="sidearrow">
        <img class="mas" src="../assets/icons/mas.png" alt="mas">
    </div>
</template>

<script>
export default {
    name: 'Secundaria'
}
</script>

<style scoped>
.secundaria {
    height: 420px;
    padding-top: 5px;
    padding-left: 35px;
    border-radius: 5px;
    background-color: white;
}

.titulo {
    font-size: 20px;
    font-weight: 400;
    margin-bottom: 15px;
}

.libreria {
    display: flex;
    flex-direction: row;
    height: 240px;
    margin-right: 100px;

}

.libro {
    width: 16.5%;
    margin-right: 48.4px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    overflow: hidden;
    background-color: rgba(192, 207, 212, 0.3);
    border-top-right-radius: 8px;
    border-top-left-radius: 8px;
}

.psuperior1 {
    background-image: url(../assets/imgs/geografia.jpg);
    background-position: 0% 0%;
    background-size: cover;
    height: 50%;

}

.psuperior2 {
    background-image: url(../assets/imgs/historia.jpg);
    background-position: 50% 60%;
    background-size: cover;
    height: 50%;
}

.psuperior3 {
    background-image: url(../assets/imgs/librox2.jpg);
    background-position: 50% 25%;
    background-size: cover;
    height: 50%;
}

.psuperior4 {
    background-image: url(../assets/imgs/matematicas.jpg);
    background-position: 50% 20%;
    background-size: cover;
    height: 50%;
}

.pnumero {
    background-color: white;
    border-top-left-radius: 5px;
    border-bottom-right-radius: 5px;
    border-bottom-left-radius: 5px;
    height: 45px;
    width: 50px;
    padding: 1px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
}



.pinferior {
    height: 50%;
    display: flex;
    flex-direction: column;
    font-size: 12px;
    border-bottom-right-radius: 8px;
    border-bottom-left-radius: 8px;
    overflow: hidden;
    background-color: white;
}

.favorito {
    display: flex;
    margin-left: auto;
    height: 30px;
    width: 30px;
}

.favorito:hover {
    cursor: pointer;
    background-color: gold;
    border-radius: 5px;
}

.titulolibro {
    margin-left: 5px;
    font-size: 18px;

}

.descripcion {
    margin-left: 5px;
    font-size: smaller;
    opacity: 0.4;

}

.footerlibro {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0 10px 5px 10px;
    margin-top: auto;
}

.options {
    width: 10px;
    height: 10px;
    margin-right: 1px;
}

.download {
    width: 12px;
    height: 12px;
    margin-left: auto;
}

.download:hover {
    cursor: pointer;
    background-color: rgba(39, 39, 187, 0.7);
}


.libreria {
    display: flex;
    flex-direction: row;
    height: 240px;
    margin-right: 100px;

}

.libro {
    width: 16.5%;
    height: 240px;
    margin-right: 48.4px;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
    overflow: hidden;
    background-color: rgba(192, 207, 212, 0.3);
    border-top-right-radius: 8px;
    border-top-left-radius: 8px;
}

.psuperior1 {
    background-image: url(../assets/imgs/geografia.jpg);
    background-position: 0% 0%;
    background-size: cover;
    height: 50%;

}

.psuperior2 {
    background-image: url(../assets/imgs/historia.jpg);
    background-position: 50% 60%;
    background-size: cover;
    height: 50%;
}

.psuperior3 {
    background-image: url(../assets/imgs/librox2.jpg);
    background-position: 50% 25%;
    background-size: cover;
    height: 50%;
}

.psuperior4 {
    background-image: url(../assets/imgs/matematicas.jpg);
    background-position: 50% 20%;
    background-size: cover;
    height: 50%;
}

.psuperior5 {
    background-image: url(../assets/imgs/atlas.jpg);
    background-position: 0%;
    background-size: cover;
    height: 50%;
}

.pnumero {
    background-color: white;
    border-top-left-radius: 5px;
    border-bottom-right-radius: 5px;
    border-bottom-left-radius: 5px;
    height: 45px;
    width: 50px;
    padding-right: 3px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
}

.pinferior {
    height: 50%;
    display: flex;
    flex-direction: column;
    font-size: 12px;
    border-bottom-right-radius: 8px;
    border-bottom-left-radius: 8px;
    overflow: hidden;
    background-color: white;
}

.favorito {
    display: flex;
    margin-left: auto;
    height: 30px;
    width: 30px;
}

.favorito:hover {
    cursor: pointer;
    background-color: gold;
    border-radius: 5px;
}

.titulolibro {
    margin-left: 5px;
    font-size: 18px;

}

.descripcion {
    margin-left: 5px;
    font-size: smaller;
    opacity: 0.4;

}

.footerlibro {
    display: flex;
    flex-direction: row;
    align-items: center;
    padding: 0 10px 5px 10px;
    margin-top: auto;
}

.options {
    width: 10px;
    height: 10px;
    margin-right: 1px;
}

.download {
    width: 18px;
    height: 18px;
    margin-left: auto;
}

.download:hover {
    cursor: pointer;
    background-color: rgba(39, 39, 187, 0.7);
}


.sidearrow {
    position: absolute;
    top: 720px;
    left: 1625px;
    width: 60px;
    height: 60px;
    opacity: .5;
}

.mas {
    position: absolute;
    top: 580px;
    left: 1610px;
    width: 50px;
    height: 50px;
}

.mas:hover {
    border-radius: 50%;
    overflow: hidden;
    box-shadow: 0 0 10px rgba(0, 195, 255, 1);
}
</style>