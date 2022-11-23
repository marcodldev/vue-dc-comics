<template>
  <div class="mainDiv flex">

    <div class="secDiv">
      <img src="../assets/img/dc-logo.png" alt="logo">
    </div>

    <div class="flex alignC">
      <nav >
        <ul class="flex">
          <li>CHARACTERS</li>
          <li>COMICS</li>
          <li>MOVIES</li>
          <li>TV</li>
          <li>GAMES</li>
          <li>COLLECTIBLES</li>
          <li>VIDEOS</li>
          <li>FANS</li>
          <li>NEWS</li>
          <li>SHOP</li>
        </ul>
      </nav>
    </div>
    
    
  </div>
</template>

<script>
export default {
    name: 'HeaderComp',
}
</script>


<style lang="scss" scoped>

.mainDiv {
  justify-content: space-between;

  width: 80%;
  margin: auto;

  height: 100%;

  padding: 10px;

  img {
    height: 100%;
  }
}

nav {
  

    ul {
      text-align: center;
    }
  
    li {
      margin: 0 10px;
      padding: 10px;
      font-weight: bold;
      
    }
  


}

.secDiv {
  display: flex;
}

.flex {
  display: flex;
}

.alignC {
  align-items: center;
}

</style>