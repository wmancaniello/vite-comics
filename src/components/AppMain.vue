<script>
export default {};
</script>

<template>
  <div class="main">
    <div class="content">
      <h2>!!! Content goes here !!!</h2>
    </div>
    <div class="icon-container">
      <div class="icon-main">
        <h2>!!!icone da inserire!!!</h2>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.main {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  .content {
    display: flex;
    justify-content: center;
    align-content: center;
    color: white;
    height: 15vh;

    h2 {
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }

  .icon-container {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    background-color: #0082F9;
    height: 15vh;
    width: 100%;

    h2 {
      display: flex;
      justify-content: center;
      align-items: center;
    }
  }
}
</style>
