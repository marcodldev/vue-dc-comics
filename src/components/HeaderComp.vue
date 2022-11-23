<template>
  <div class="mainDiv flex">

    <div class="secDiv">
      <img src="../assets/img/dc-logo.png" alt="logo">
    </div>

    <div class="flex alignC">
      <nav >
        <ul class="flex">
          <li><a href="#">CHARACTERS</a> </li>
          <li><a href="#">COMICS</a> </li>
          <li><a href="#">MOVIES</a> </li>
          <li><a href="#">TV</a> </li>
          <li><a href="#">GAMES</a> </li>
          <li><a href="#">COLLECTIBLES</a> </li>
          <li><a href="#">VIDEOS</a> </li>
          <li><a href="#">FANS</a> </li>
          <li><a href="#">NEWS</a> </li>
          <li><a href="#">SHOP</a> </li>
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

        li {
          margin: 0 10px;
          padding: 10px;
          font-weight: bold;
          

          a {
            color: black;
            text-decoration: none;

            &:hover {
              color: #0282f9;

              
            }
          }
        }

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