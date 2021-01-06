<template lang="html">
  <b-navbar id="template-header" class="navbar default-layout col-lg-12 col-12 p-0 fixed-top d-flex flex-row" toggleable="md">
    <div class="text-center navbar-brand-wrapper d-flex align-items-top justify-content-center">

      
      <router-link class="navbar-brand brand-logo" to="/">
       <img src="../../assets/images/Screenshot_1.png" alt="logo" /> 
      </router-link> 
     
   
    </div>
    
    <div class="navbar-menu-wrapper d-flex align-items-center ml-auto ml-lg-0">
            
      <b-navbar-nav class="navbar-nav-right ml-auto">
        <!-- SEARCH -- BUSCAR
        <form class="mr-auto search-form d-none d-md-block" action="#">
          <div class="form-group">
            <input type="search" class="form-control" placeholder="Search Here">
          </div>
        </form>-->
        <div> </div>
        <!--<b-nav-item-dropdown right class="preview-list">
          <template slot="button-content">
            <div class="nav-link count-indicator" >
              <i class="mdi mdi-bell-outline"></i>
              <span class="count">7</span>
            </div>
          </template>
         <!-- <b-dropdown-item class="preview-item py-2 px-0 border-bottom">
            <p class="mb-0 font-weight-medium float-left">You have 7 unread mails </p>
            <span class="badge badge-pill badge-primary float-right">View all</span>
          </b-dropdown-item>
          <b-dropdown-item class="preview-item">
            <div class="preview-thumbnail">
             <!-- <img src="../../assets/images/faces/face10.jpg" alt="image" class="img-sm profile-pic">-->
            <!--</div>
            <div class="preview-item-content flex-grow py-2">
              <p class="preview-subject ellipsis font-weight-medium text-dark">Marian Garner </p>
              <p class="font-weight-light small-text"> The meeting is cancelled </p>
            </div>
          </b-dropdown-item>
          <b-dropdown-item class="preview-item">
            <div class="preview-thumbnail">
             <!--  <img src="../../assets/images/faces/face12.jpg" alt="image" class="img-sm profile-pic">-->
           <!-- </div>
            <div class="preview-item-content flex-grow py-2">
              <p class="preview-subject ellipsis font-weight-medium text-dark">David Grey</p>
              <p class="font-weight-light small-text"> The meeting is cancelled </p>
            </div>

          </b-dropdown-item>
          <b-dropdown-item class="preview-item">
            <div class="preview-thumbnail">
             <!--  <img src="../../assets/images/faces/face1.jpg" alt="image" class="img-sm profile-pic">-->
            <!--</div>
            <div class="preview-item-content flex-grow py-2">
              <p class="preview-subject ellipsis font-weight-medium text-dark">Travis Jenkins</p>
              <p class="font-weight-light small-text"> The meeting is cancelled </p>
            </div>
          </b-dropdown-item>
        </b-nav-item-dropdown>-->
        
        <!--<b-nav-item-dropdown right class="preview-list user-dropdown">
          <!--<template slot="button-content">
            <div class="d-flex align-items-center">
            <img class="img-xs rounded-circle" src="../../assets/images/faces/JM.jpeg" alt="Profile image">
            </div>
          </template>-
          <b-dropdown-item>
           <!-- <div class="dropdown-header text-center w-100">
              <img class="img-md rounded-circle" src="../../assets/images/faces/JM.jpeg" alt="Profile image">
              <p class="mb-1 mt-3 font-weight-semibold">Juan Manuel Gomez Duran</p>
              <p class="font-weight-light text-muted mb-0">juan.m.gomezd@gmail.com</p>
            </div>
          </b-dropdown-item>
            <!--<b-dropdown-item>Cerrar Sesión<i class="dropdown-item-icon ti-power-off"></i></b-dropdown-item>-->
        </b-nav-item-dropdown>
      </b-navbar-nav>
      <!--<button class="navbar-toggler navbar-toggler-right align-self-center" type="button" @click="collapedMobileSidebar()">
        <span class="mdi mdi-menu"></span>
      </button>-->
    </div>
  </b-navbar>
</template>

<script lang="js">
// eslint-disable-next-line
import JQuery from 'jquery'
let $ = JQuery
export default {
  name: 'app-header',
  methods: {
    collapedSidebar: function () {
      $('body').toggleClass('sidebar-icon-only')
    },
    collapedMobileSidebar: function () {
      $('#sidebar').toggleClass('active')
    }
  }
}
</script>

<style scoped lang="scss">
.app-header {
}
</style>
