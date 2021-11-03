<template>
  <div class="main" id="content">
    <header>
      <div class="header-inner-bottom">
        <div class="bottom-left">
          <nav class="header-nav">
            <div class="header-nav-inner">
              <a href="xxx" class="header-nav-item">Home</a>
              <a href="xxx" class="header-nav-item">Solutions</a>
              <a href="xxx" class="header-nav-item">Projects</a>
              <a href="xxx" class="header-nav-item">References</a>
            </div>
          </nav>
          <a href="/" class="header-branding">
            <img src="#" alt="BIM SY" class="header-branding-logo">
          </a>
        </div>
        <div class="bottom-center"></div>
        <div class="bottom-right">
          <nav class="header-nav header-nav--secondary">
            <div class="header-nav-inner">
              <a href="xxx" class="header-nav-item">Contact</a>
                <a href="xxx" class="header-nav-item">News</a>
            </div>
          </nav>
        </div>


      </div>
    </header>

    <main class="main-1">
      <article class="article-1">
        <h2>type something here</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Animi, corporis dolor fugit iste libero natus odio praesentium
          quaerat ut. Assumenda corporis, dicta facilis iusto minus molestiae
          neque quisquam similique voluptas. Lorem ipsum dolor sit amet,
          consectetur adipisicing elit. Aliquam animi aspernatur consectetur
          distinctio ea enim fugiat incidunt laboriosam, magnam natus odio
          praesentium quae quaerat, ratione sit totam ullam vel voluptas? </p>
      </article>
    </main>
    <section class="section-1">
      <h2>another section here</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus
        accusantium corporis ducimus, ipsa magnam quis quo repudiandae suscipit
        ut voluptatum. Corporis illo iure labore nam necessitatibus perferendis
        quo sunt tempora. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
        Aliquam aut deleniti dolorum numquam. A culpa dolores esse ex illum magnam,
        nemo officiis rem voluptas voluptatum. Doloribus hic incidunt maiores recusandae!</p>
    </section>
    <footer>copyright 2021 KKY</footer>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>


#content {
  display: grid;
  grid-template-columns: repeat(12, 1fr);
  grid-auto-rows: auto;
  /*grid-auto-rows: minmax(150px, auto);*/
  grid-gap: 10px;
  max-width: 960px;
  margin: 0 auto;

}




header-inner-bottom {
  align-items: center;
  box-sizing: border-box;
  color: rgb(115, 115, 115);
  display: flex;
  font-family: Roboto;
  font-size: 15px;
  font-style: normal;
  font-weight: 300;
  height: 86.8875px;
  justify-content: center;
  letter-spacing: 0.45px;
  line-height: 19.5px;
  padding-left: 66.5px;
  padding-right: 66.5px;
  padding-top: 21px;
  pointer-events: auto;
  text-align: center;
  text-size-adjust: 100%;
  text-transform: none;
  width: 1519.2px;
  -webkit-box-align: center;
  -webkit-box-pack: center;
  -webkit-font-smoothing: antialiased;

}

bottom-left{
  align-items: center;
  color: rgb(115, 115, 115);
  display: flex;
  flex-basis: auto;
  flex-grow: 1;
  flex-shrink: 1;
  justify-content: flex-start;
  max-width: 100%;
  min-width: 0px;
  opacity: 1;
  pointer-events: auto;
  text-align: left;
  text-size-adjust: 100%;
  transition-delay: 0.6s;
  transition-duration: 0.2s;
  transition-property: opacity;
  transition-timing-function: ease-out;
  width: 856.4px;

}

nav{
   grid-column: 1 / 13;
   padding: 0 30px;



}

nav ul{
  justify-content: space-between;
}

.navigation{


}

.navigation li{


}

main.main-1 {
  grid-column: 1 / 13;
  padding: 0 30px;
  /*display: inline-block;*/
}


section.section-1{
  grid-column: 1 / 13;
  padding: 0 30px;
}

footer {
  grid-column: 1 / 13;
  padding: 0 30px;
  /*display: inline-block;*/
}


/*nav {*/
/*  width: 100%;*/
/*  height: 50px;*/
/*  background-color: rgba(115, 115, 115, 0.4);*/
/*  !*line-height: 20px;*!*/
/*  display: flex;*/
/*  align-items: center;*/
/*  justify-content: space-between;*/
/*  !*margin: auto;*!*/
/*  margin: 0;*/
/*  padding: 0;*/
/*  !*color: hotpink;*!*/
/*  font-family: din-2014, Roboto, sans-serif;*/
/*  font-size: 12px;*/
/*  font-style: normal;*/
/*  font-weight: 600;*/
/*  letter-spacing: 0.42px;*/

/*}*/

/*nav ul {*/
/*  margin-right: 30px;*/
/*  !*list-style-type: none;*!*/
/*  !*display: inline-block;*!*/
/*  !*padding: 0 20px;*!*/

/*}*/

/*nav ul li {*/
/*  list-style-type: none;*/
/*  display: inline-block;*/
/*  padding: 0 20px;*/
/*}*/


/*nav ul li a {*/
/*  text-decoration: none;*/
/*  color: #fff;*/
/*  padding: 0px;*/
/*  text-transform: uppercase;*/
/*  padding: 0;*/


/*}*/




</style>
