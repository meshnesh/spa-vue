<template>
  <div class="nav">
    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-light center">
      <a class="navbar-brand text-dark" href="#">Adventure</a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarsExampleDefault">
        <ul class="navbar-nav mr-auto text-dark">
          <li class="nav-item active">
            <router-link class="nav-link text-dark" v-bind:to="'/'">Home <span class="sr-only">(current)</span></router-link>
          </li>
          <li class="nav-item">
             <router-link class="nav-link text-dark" v-bind:to="'/about'">About</router-link>
          </li>
          <!-- <li class="nav-item dropdown text-dark">
            <a class="nav-link dropdown-toggle text-dark" href="http://example.com" id="dropdown01" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">Dropdown</a>
            <div class="dropdown-menu" aria-labelledby="dropdown01">
              <a class="dropdown-item text-dark" href="#">Action</a>
              <a class="dropdown-item text-dark" href="#">Another action</a>
              <a class="dropdown-item text-dark" href="#">Something else here</a>
            </div>
          </li> -->
        </ul>
        <form class="form-inline my-2 my-lg-0">
          <input class="form-control mr-sm-2" type="text" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'nav'
}
</script>

