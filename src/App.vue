<template>
  <div id="app">
    <app-spinner v-show="loading"></app-spinner>
    <notifications group="message"/>
    <nav class="navbar navbar-expand-lg bg-primary navbar-dark fixed-top">
      <div class="container">
        <a href="#" class="navbar-brand">Aqua Blog</a>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <a href="#" class="nav-link">Posts</a>
            </li>
            <li class="nav-item">
              <a href="#" class="nav-link">Albums</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="container" style="margin-top:4em">
      <router-view/>
    </div>
  </div>
</template>

<style>
</style>
