<template>
  <main>
    <div class="container"></div>
      <header>
        <h1>Notes</h1>
        <button>+</button>
      </header>
      <div class="card-container">
        <div class="card">
          <p class="main-text"></p>
          <p class="date"></p>
        </div>
      </div>
  </main>
</template>

<style scoped>
  main {
    height: 100vh;
    width: 100wh;
  }

  .container {
    max-width: 1000px;
    padding: 10px;
    margin: 0 auto
  }

  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  h1 {
    font-weight: bold;
    margin-bottom: 25px;
    font-size: 75px;
  }

  button {
    border: none;
    padding: 10px ;
    width: 50px ;
    height: 50px ;
    cursor: pointer; 
    background-color: rgb(21,20,20);
    border-radius: 100%;
    color: white;
    font-size: 20px;
  }

  .card {
    width: 255px;
    height: 255px;
    background-color: rgb(237,182,44);
    padding: 10px;
    border-radius: 15px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-right: 20px;
    margin-left: 20px;
  }

</style>