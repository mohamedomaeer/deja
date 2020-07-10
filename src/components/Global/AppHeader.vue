<template>
    <nav class="navbar navbar-expand navbar-light bg-white static-top osahan-nav sticky-top">
         &nbsp;&nbsp; 
         <router-link to="/" class="navbar-brand mr-1">
            <img class="img-fluid" alt="" src="../../assets/img/logo.png">
         </router-link>
         <router-link to="/latest" class="menu-item">
             <i class="fas fa-redo fa-fw"></i>
             <span>Latest</span> 
        </router-link>
        <router-link to="/" class="menu-item menu-item-home">
             <i class="fas fa-home fa-fw"></i>
             <span>Home</span> 
        </router-link>

         <!-- Navbar Search -->
         <form class="d-none d-md-inline-block form-inline ml-auto mr-0 mr-md-5 my-2 my-md-0 osahan-navbar-search">
            <div class="input-group">
               <input type="text" class="form-control" placeholder="Search for...">
               <div class="input-group-append">
                  <button class="btn btn-light" type="button">
                  <i class="fas fa-search"></i> 
                  </button>
               </div>
            </div>
         </form>
         <!-- Navbar -->
         <ul class="navbar-nav ml-auto ml-md-0 osahan-right-navbar">
            <li class="nav-item dropdown no-arrow mx-1">
               <a class="nav-link dropdown-toggle" href="#" id="alertsDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
               <i class="fas fa-bell fa-fw"></i>
               <span class="badge badge-danger">9+</span>
               </a>
               <div class="dropdown-menu dropdown-menu-right" aria-labelledby="alertsDropdown">
                  <a class="dropdown-item" href="#"><i class="fas fa-fw fa-edit "></i> &nbsp; Action</a>
                  <a class="dropdown-item" href="#"><i class="fas fa-fw fa-headphones-alt "></i> &nbsp; Another action</a>
                  <div class="dropdown-divider"></div>
                  <a class="dropdown-item" href="#"><i class="fas fa-fw fa-star "></i> &nbsp; Something else here</a>
               </div>
            </li>
            <li class="nav-item dropdown no-arrow osahan-right-navbar-user">
               <a class="nav-link dropdown-toggle user-dropdown-link" href="#" id="userDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                <img alt="Avatar" src="../../assets/img/user.png">
               </a>
               <div class="dropdown-menu dropdown-menu-right" aria-labelledby="userDropdown">
                  <a class="dropdown-item" href="#"><i class="fas fa-fw fa-user-circle"></i> &nbsp; My Account</a>
                  <a class="dropdown-item" href="#"><i class="fas fa-fw fa-cog"></i> &nbsp; Settings</a>
                  <div class="dropdown-divider"></div>
                  <a class="dropdown-item" href="#"><i class="fas fa-fw fa-sign-out-alt"></i> &nbsp; Logout</a>
               </div>
            </li>
         </ul>
      </nav>
</template>

<script>
export default {
    name: "AppHeader"
}
</script>