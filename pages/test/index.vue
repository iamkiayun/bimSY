<template>
  <div class="main" id="content">
    <header>BIM Kho</header>
    <section class="banner">
      insert a banner image here

    </section>
    <nav>
      <ul class="navigation">
        <li><a href="xxx">Home</a></li>
        <li><a href="xxx">Solutions</a></li>
        <li><a href="xxx">Projects</a></li>
        <li><a href="xxx">References</a></li>
        <li><a href="xxx">News</a></li>
        <li><a href="xxx">Contact</a></li>
      </ul>
    </nav>
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

/*main{*/

/*  display: grid;*/
/*  grid-template-columns: repeat(12, 1fr);*/
/*  grid-auto-rows: auto;*/
/*  !*grid-auto-rows: minmax(150px, auto);*!*/
/*  grid-gap: 10px;*/
/*  max-width: 960px;*/
/*  margin: 0 auto;*/

/*}*/


.main{
  /*font-family: Segoe UI, Arial Black;*/
  font-family: SF Pro Text,Myriad Set Pro,SF Pro Icons,Helvetica Neue,Helvetica,Arial,sans-serif;
}

header {
  grid-column: 1 / 13;
  padding: 0 30px;
  font-weight: 600 ;
}

section.banner{
  grid-column: 1 / 13;
  padding: 0 30px;
}

nav{
   grid-column: 1 / 13;
   padding: 0 30px;



}

nav ul{
  justify-content: space-between;
}

.navigation{
   /*display: grid;*/
   /*grid-template-columns: 1fr;*/
   /*padding: 30px;*/
  display: inline-block;
  list-style-type: none;
  background: grey;
  cursor: default;
  margin: 0 -8px;
  width: auto;
  height: 44px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  webkit-box-pack: justify;
  ms-flex-pack: justify;
  justify-content: space-between;
  webkit-user-select: none;
  moz-user-select: none;
  ms-user-select: none;
  user-select: none;

}

.navigation li{
  display: inline-block;
  list-style-type: none;
  padding: 0 30px;
  font-size: 12px;
  line-height: 3.66667;
  font-weight: 400;
  letter-spacing: -.01em;
  font-family: SF Pro Text, Myriad Set Pro, SF Pro Icons, Helvetica Neue, Helvetica, Arial, sans-serif;
  color: #f5f5f7;
  position: relative;
  z-index: 1;
  display: inline-block;
  padding: 0 8px;
  height: 44px;
  opacity: .8;
  background: no-repeat;
  text-decoration: none;
  white-space: nowrap;
  -webkit-transition: opacity 0.3s cubic-bezier(0.25, 0.1, 0.25, 1);
  transition: opacity 0.3s cubic-bezier(0.25, 0.1, 0.25, 1);
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
  outline-offset: -7px;

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





</style>
