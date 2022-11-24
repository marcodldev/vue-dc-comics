<template>
  <div class="mainDiv">
    <div class="sec2">
      <button class="relative button">CURRENT SERIES</button>
    </div>
    <section class="sec1">
      <div class="cards">
        <ContentComp
          v-for="(elem, index) in arrayFumetti"
          :key="index"
          :dettagliFumetto="elem"
        />
      </div>
      <div class="">
        <button class="button btn1">LOAD MORE</button>
      </div>
    </section>

    <section class="features">
      <div class="imgcontainer">
        <div class="flex">
          <img
            src="../assets/img/buy-comics-digital-comics.png"
            alt="digitalcomics"
          />
          <p>DIGITAL COMICS</p>
        </div>

        <div class="flex">
          <img
            src="../assets/img/buy-comics-merchandise.png"
            alt="merchandise"
          />
          <p>DC MERCHANDISE</p>
        </div>

        <div class="flex">
          <img
            src="../assets/img/buy-comics-subscriptions.png"
            alt="subscriptions"
          />
          <p>SUBSCRIPTION</p>
        </div>

        <div class="flex">
          <img
            src="../assets/img/buy-comics-shop-locator.png"
            alt="shoplocator"
          />
          <p>COMIC SHOP LOCATOR</p>
        </div>

        <div class="flex">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="powervisa" />
          <p>DC POWER VISA</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import ContentComp from "./ContentComp.vue";

export default {
  name: "MainComp",
  components: {
    ContentComp,
  },

  data() {
    return {
      arrayFumetti: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.cards {
  display: flex;
  flex-wrap: wrap;
  // gap: 5px;
}

.btn1 {
  justify-content: center;
  width: 15rem;
}
.button {
  padding: 10px;
  background-color: #0282f9;
  color: white;
  border: none;
}

.relative {
  position: absolute;
  top: 516px;
  left: 152px;
}
.flex {
  display: flex;
}

.sec2 {
  background-image: url("../assets/img/jumbotron.jpg");
  height: 25rem;
  background-repeat: no-repeat;
  background-size: cover;
}

.mainDiv {
  background-color: #1c1c1c;
  color: white;
}

.sec1 {
  background-color: #1c1c1c;

  padding: 100px;
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