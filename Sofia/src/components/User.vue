<template>
    <div class="userbox">

        <img class="userimg" src="../assets/imgs/avatar.png" alt="avatar">
        <span class="name">Eduardo Mexía</span>
        <br>
        <div class="userdata">
            <img class="icon1" src="../assets/icons/star.png" alt="star">
            <span>3.3M</span>
            <img class="icon2" src="../assets/icons/crown.png" alt="crown">
            <span>Top 5: Mejores creadores de ejercicios</span>
        </div>


    </div>
</template>




<script>
export default {
    name: 'User'
}
</script>

<style>
.userbox {
    height: 105px;
    background-color: rgba(192, 207, 212, 0.3);
    border-radius: 5px;
    margin-top: 120px;
    padding-left: 30px;
}

.userimg {
    position: absolute;
    top: 90px;
    width: 75px;
    height: 75px;
}

.name {
    margin-left: 100px;
    color: rgb(0, 163, 200);
    font-weight: bolder;
    font-size: 18px;

}

.userdata {
    display: flex;
    flex-direction: row;
    align-content: center;
    align-items: center;
    text-align: center;
    font-size: 12px;
    opacity: 0.2;
    letter-spacing: 0.5px;
}

.icon1 {
    margin-left: 100px;
    width: 10px;
    height: 10px;


}

.icon2 {
    margin-left: 25px;
    width: 15px;
    height: 15px;

}
</style>
