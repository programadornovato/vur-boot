<template>
  <div id="app">
    <b-navbar toggleable="md" type="dark" variant="info">
      <b-container>
        <b-navbar-brand href="#">Titulo</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item :to="{name:'home'}">Home</b-nav-item>
            <b-nav-item :to="{name:'about'}">About</b-nav-item>
            <b-nav-item :to="{name:'grid'}">Grid</b-nav-item>
            <b-nav-item :to="{name:'card'}">Card</b-nav-item>
            <b-nav-item :to="{name:'form'}">Form</b-nav-item>
            <b-nav-item :to="{name:'select'}">Select</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
    <b-container>
      <router-view/>
    </b-container>
  </div>
</template>