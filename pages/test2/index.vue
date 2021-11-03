<template>
  <div class="main" id="content">

    <header class="navbar">
      <div class="logo">
        <a href="/">
          <img src="@/static/images/bimSYwhite.png" alt="BIM SY">
        </a>
      </div>
      <nav>
          <ul class="navigation-left">
            <li><a href="xxx">Home</a></li>
            <li><a href="xxx">Solutions</a></li>
            <li><a href="xxx">Projects</a></li>
            <li><a href="xxx">References</a></li>
          </ul>
      </nav>
      <nav>
          <ul class="navigation-right">
            <li><a href="xxx">News</a></li>
            <li><a href="xxx">Contact</a></li>
          </ul>
      </nav>

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

/**{*/
/*  padding:0;*/
/*  margin:0;*/
/*  box-sizing: border-box;*/




/*}*/


header.navbar {
  /*display: flex;*/
}


nav{

}

nav a{
  text-decoration: none;
  padding: 15px;
  color: #fff;
  display: block;
}

nav ul{
  display: flex;
  list-style: none;
}

ul.navigation-left{
  padding: 0;
}

header.navbar{
  display: flex;
  background-color: rgba(115, 115, 115, 0.3);
  font-family: din-2014, Roboto, sans-serif;
  font-size: 12px;
  font-style: normal;
  font-weight: 650;
  justify-content: ;
  text-transform: uppercase;
}

div.logo{
  max-width: 150px;
  width: 100%;
  line-height: 0;
  padding-top: 10px;
}

div.logo img{
  padding: auto 15px;
  width: 150px;
  border: 0;
}

nav ul li a::after {
  content: "";
  position: relative;
  width: 0px;
  border-bottom: 2px solid lime;
  display: block;
  transition: width .35s;
  padding: 0px;

}

nav ul li a:hover::after {
  width: 100%;
}

nav ul li a:hover {
  /*color: ;*/
}




</style>
