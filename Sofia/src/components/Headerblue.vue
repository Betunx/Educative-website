<template>
  <div class="header">
    <div class="headcontent">
      <span class="name">Hi, Roshan</span>
      <img class="clock" src="../assets/icons/reloj.png" alt="clock">
      <img class="bell" src="../assets/icons/bell.png" alt="bell">
      <img class="avatar" src="../assets/imgs/avatar.png" alt="avatar">
    </div>
  </div>
</template>

<script>
export default {
  name: 'Headerblue'
}
</script>

<style scoped>
.header {
  position: fixed;
  margin: 0;
  padding: 0;
  width: 88vw;
  height: 50px;
  background: linear-gradient(to right, rgba(10, 100, 300, 1), rgba(42, 161, 217, 0.65));
}

.headcontent {
  display: flex;
  align-items: center;
  align-content: center;
  margin-left: auto;
  margin-right: 15px;
  margin-top: 10px;
  padding-right: 20px;
  padding-top: 5px;
  padding-bottom: 5px;
  width: fit-content;
  height: 30px;
  border-radius: 30px;
  background-color: rgba(42, 181, 217, 1);
}


.name {
  margin: 0;
  margin-left: 15px;
  margin-right: 15px;
  padding: 0;
  font-family: 'Times New Roman', Times, serif;
  font-size: 16px;
  font-weight: 100;
  color: white;
}

.clock,
.bell {
  width: 18px;
  height: 18px;
}

.clock {
  margin-right: 5px;
}

.avatar {
  margin-left: 15px;
  width: 18px;
  height: 21px;
  border-radius: 40%/50%;

}
</style>



