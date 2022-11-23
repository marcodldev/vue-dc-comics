<template>
  <div class="mainDiv">
        <section class="sec1">
            <h1>..>Content goes here..</h1>
        </section>

        <section class="features">

            <div class="imgcontainer">
                <div class="flex">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="digitalcomics">
                    <p>DIGITAL COMICS</p>
                </div>

                <div class="flex">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
                    <p>DC MERCHANDISE</p>
                </div>

                <div class="flex">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                    <p>SUBSCRIPTION</p>
                </div>

                <div class="flex">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="shoplocator">
                    <p>COMIC SHOP LOCATOR</p>
                </div>

                <div class="flex">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="powervisa"> 
                    <p>DC POWER VISA</p>
                </div>
                
                
                
                
                
            </div>

        </section>
  </div>
</template>

<script>
export default {
    name: 'MainComp',
}
</script>

<style lang="scss" scoped>

.flex {
    display: flex;
}

.mainDiv {
    background-color: #1c1c1c;
    color: white;
}

.sec1 {

    background-color: #1c1c1c;

    padding: 100px;

    display: flex;
    justify-content: start;

    width: 80%;
    margin: auto;
}

.features {
    
    padding: 70px;
    background-color: #0282f9;


}

.imgcontainer {
    width: 80%;
    margin: auto;
    justify-content: space-around;
    display: flex;
    align-items: center;
    

        p {
            margin-left: 10px;
            align-self: center;
            cursor: pointer;
        }

        img {
                width: 70px;
                cursor: pointer;            
                
            }


}
</style>