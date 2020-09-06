<template>
    <header class="site-navbar py-4 absolute transparent" role="banner">

      <div class="container">
        <div class="row align-items-center">
          

          <div class="col-3" data-aos="fade-down">
            <h1><a href="#" class="text-white h2">Podca</a></h1>
          </div>
          <div class="col-9" data-aos="fade-down">
            <nav class="site-navigation position-relative text-right text-md-right" role="navigation">

                

                <div class="d-inline-block ml-md-0 mr-auto py-3"><a href="#" class="site-menu-toggle js-menu-toggle text-white"><span class="icon-menu h3"></span></a></div>

                <ul class="site-menu js-clone-nav d-none">
                  <li class="has-children active">
                    <a href="index.html">Home</a>
                    <ul class="dropdown arrow-top">
                      <li><a href="#">Menu One</a></li>
                      <li><a href="#">Menu Two</a></li>
                      <li><a href="#">Menu Three</a></li>
                      <li class="has-children">
                        <a href="#">Sub Menu</a>
                        <ul class="dropdown">
                          <li><a href="#">Menu One</a></li>
                          <li><a href="#">Menu Two</a></li>
                          <li><a href="#">Menu Three</a></li>
                        </ul>
                      </li>
                    </ul>
                  </li>
                  <li class="has-children">
                    <a href="#">Dropdown</a>
                    <ul class="dropdown arrow-top">
                      <li><a href="#">Menu One</a></li>
                      <li><a href="#">Menu Two</a></li>
                      <li><a href="#">Menu Three</a></li>
                    </ul>
                  </li>
                  <li><a href="about.html">About</a></li>
                  <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>


          </div>

        </div>
      </div>
      
    </header>
</template>

<script>
export default {
  name: 'PodcaHeader'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
