<template>
    <ul class="sidebar navbar-nav">
        <li class="nav-item active">
            <a class="nav-link" href="#">
            <i class="fas fa-fw fa-home"></i>
            <span>Home</span>
            </a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">
            <i class="fas fa-fw fa-users"></i>
            <span>Channels</span>
            </a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">
            <i class="fas fa-fw fa-user-alt"></i>
            <span>Single Channel</span>
            </a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">
            <i class="fas fa-fw fa-video"></i>
            <span>Video Page</span>
            </a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">
            <i class="fas fa-fw fa-cloud-upload-alt"></i>
            <span>Upload Video</span>
            </a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#">
            <i class="fas fa-fw fa-history"></i>
            <span>History Page</span>
            </a>
        </li>
        <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
            <i class="fas fa-fw fa-list-alt"></i>
            <span>Categories</span>
            </a>
            <div class="dropdown-menu">
                <a class="dropdown-item" href="#">Movie</a>
                <a class="dropdown-item" href="#">Music</a>
                <a class="dropdown-item" href="#">Television</a>
            </div>
        </li>
        <li class="nav-item channel-sidebar-list">
            <h6>SUBSCRIPTIONS</h6>
            <ul>
                <li>
                    <a href="#">
                    <img class="img-fluid" alt="" src="img/s1.png"> Your Life 
                    </a>
                </li>
                <li>
                    <a href="#">
                    <img class="img-fluid" alt="" src="img/s2.png"> Unboxing  <span class="badge badge-warning">2</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                    <img class="img-fluid" alt="" src="img/s3.png"> Product / Service  
                    </a>
                </li>
                <li>
                    <a href="#">
                    <img class="img-fluid" alt="" src="img/s4.png">  Gaming 
                    </a>
                </li>
            </ul>
        </li>
        </ul>
</template>

<script>
export default {
    name: "AppHeader"
}
</script>