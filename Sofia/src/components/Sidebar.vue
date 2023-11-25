<template>
    <div class="side">

        <div class="sofia"><img class="icon" src="../assets/icons/cubo.png" alt="icon">
            <span>SofiaXT</span>
            <img class="arrow" src="../assets/icons/arrow.png" alt="arrow">
        </div>

        <div class="home"><img class="icons" src="../assets/icons/home.png" alt="home">
            <span>Home</span>
        </div>

        <div class="grupos"><img class="icons" src="../assets/icons/group.png" alt="group">
            <span>Grupos</span>
            <img class="arrow2" src="../assets/icons/arrow.png" alt="arrow">
        </div>

        <div class="books"> <img class="icons" src="../assets/icons/book.png" alt="book">
            <span>Smartbooks</span>
        </div>

        <div class="utilidades"> <img class="icons" src="../assets/icons/utilidades.png" alt="tool">
            <span>Utilidades</span>
        </div>

        <div class="tour"> <img class="icons" src="../assets/icons/tour.png" alt="pencil">
            <span>Tour Virtual</span>
        </div>

        <div class="soporte"> <img class="icons" src="../assets/icons/soporte.png" alt="suport">
            <span>Soporte</span>
        </div>

    </div>
</template>


<script>
export default {
    name: 'Sidebar'
}
</script>

<style scoped>
.side {
    display: flex;
    flex-direction: column;
    justify-content: baseline;
    justify-items: baseline;
    align-items: baseline;
    align-content: baseline;
    text-align: center;
    padding-left: 5px;
    width: 12vw;
    height: 100vh;
    background-color: white;
    font-size: 20px;
}

.side>.home,
.side>.books,
.side>.utilidades,
.side>.tour,
.side>.soporte {
    display: none;
}

.side:hover>.home,
.side:hover>.books,
.side:hover>.utilidades,
.side:hover>.tour,
.side:hover>.soporte {
    display: block;
}



.icon {
    width: 25px;
    height: 25px;
    margin-right: 5px;
}

.icons {
    width: 18px;
    height: 18px;
    margin-right: 8px;

}

.sofia {
    margin-top: 15px;
    margin-bottom: 15px;
    display: flex;
    align-items: center;
}

.sofia:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 7px;
}

.arrow {
    width: 9px;
    height: 9px;
    margin-left: 70px;
    border-radius: 50%;
    overflow: hidden;
    box-shadow: 5px 0px 12px 0px rgba(0, 0, 0, 0.5);

}

.home {
    margin-bottom: 45px;
    padding-left: 4px;
    display: flex;
    align-items: center;
}

.home:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 100px;
}

.grupos {
    margin-top: 5px;
    margin-bottom: 5px;
    padding-left: 4px;
    display: flex;
    align-items: center;
}

.grupos:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 7px;
}

.arrow2 {
    width: 9px;
    height: 9px;
    margin-left: 78px;
    opacity: .7;
}

.books {
    margin-top: 10px;
    margin-bottom: 5px;
    padding-left: 4px;
    display: flex;
    align-items: center;
}

.books:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 62px;
}

.utilidades {
    margin-top: 10px;
    margin-bottom: 5px;
    padding-left: 4px;
    display: flex;
    align-items: center;
}

.utilidades:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 72px;
}

.tour {
    margin-top: 10px;
    margin-bottom: 5px;
    padding-left: 4px;
    display: flex;
    align-items: center;
}

.tour:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 60px;
}

.soporte {
    margin-top: 10px;
    margin-bottom: 5px;
    padding-left: 4px;
    display: flex;
    align-items: center;
}

.soporte:hover {
    background-color: rgba(192, 207, 212, 1);
    border-radius: 5px;
    padding-right: 90px;
}
</style>