<template>
    <div class="navbox">
        <div class="nav1">
            <span class="general">GENERAL</span>
            <span class="libros">MIS LIBROS</span>
            <span class="favoritos">MIS FAVORITOS</span>

            <div class="midnav">
                <span class="biblioteca">BIBLIOTECAS DE SOFIA XT</span>
                <img class="arrow" src="../assets/icons/downarrow.png" alt="arrow">
            </div>
        </div>
        <div class="nav2">
            <img class="filter" src="../assets/icons/filter.png" alt="filter">
            <div class="searchbox">
                <img class="lens" src="../assets/icons/lens.png" alt="lens">
                <input type="text" name="book" id="book" class="inputbook" placeholder="Buscar tema, libro, nivel, autor">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>


<style scoped>
.navbox {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    height: 120px;
    font-size: 14px;
    max-width: 85vw;
    background-color: white;
}


.nav1 {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    margin-left: 25px;
    margin-right: 100px;
    margin-top: 15px;
    width: 70%;
    letter-spacing: 1px;

}

.general,
.libros,
.favoritos,
.midnav {
    cursor: pointer;
    padding: 5px 10px 5px 10px;
}

.general:hover,
.libros:hover,
.favoritos:hover,
.midnav:hover {
    pointer-events: painted;
    background-color: rgba(4, 158, 193, 1);
    color: white;
    border-radius: 5px;

}

.midnav {
    margin: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    align-content: center;
}


.nav2 {
    display: flex;
    flex-direction: row;
    align-items: center;
    margin-top: 15px;
    width: 30%;
}

.arrow {
    width: 10px;
    height: 10px;
}

.filter {
    width: 25px;
    height: 25px;
    margin-left: 80px;
    margin-right: 40px;
}

.searchbox {
    display: flex;
    margin-left: auto;
    align-items: center;
    border-radius: 3px;
    padding: 5px 140px 5px 0px;
    box-shadow: 0 0px 10px rgba(0, 0, 0, 0.15);

}

.lens {
    width: 15px;
    height: 15px;
    margin-right: 5px;
    cursor: pointer;
}

.inputbook {
    cursor: pointer;
    border: none;
    padding: 0;
    margin: 0;
    opacity: .7;
}
</style>