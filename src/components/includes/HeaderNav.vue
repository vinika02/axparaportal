<template>
    <div>
        <nav class="navbar navbar-expand-lg navbar-dark bg-custom-blue">
            <div class="container-fluid">
                <a class="navbar-brand" href="#">
                    <svg width="112" height="32" viewBox="0 0 112 32" fill="none" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                        <rect width="112" height="32" fill="url(#pattern0)"/>
                        <defs>
                        <pattern id="pattern0" patternContentUnits="objectBoundingBox" width="1" height="1">
                        <use xlink:href="#image0_11269_28298" transform="translate(-0.116071 -0.157656) scale(0.00616071 0.0215625)"/>
                        </pattern>
                        <image id="image0_11269_28298" width="200" height="61" xlink:href="data:image/png;base64,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"/>
                        </defs>
                     </svg>
                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav nav-menu-left">
                    <li class="nav-item">
                      <a class="nav-link active" aria-current="page" href="#">My Dashboard</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">My talent</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">My Orders</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#">My Interviews</a>
                    </li>
                    <li class="nav-item skill-scanner-menu">
                        <a class="nav-link" href="#">Skill Scanner</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Candidate Database</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">My Account</a>
                    </li>
                    
                </ul>
                <ul class="navbar-nav ms-auto nav-menu-right">
                    <li class="nav-item">
                        <a class="nav-link user-email" href="#">axpara@gmail.com</a>
                    </li>
                    <li class="nav-item separator">
                        <a class="nav-link " href="#">
                            <svg width="1" height="24" viewBox="0 0 1 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect opacity="0.5" width="1" height="24" fill="white"/>
                            </svg>
                        </a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link logout" href="#">Logout</a>
                    </li>
                </ul>
                </div>
            </div>
            </nav>
    </div>
</template>
<script>
export default {
    name: 'Header',
    props: {
    msg: String
    }
}
</script>
<style>
     @font-face {
        font-family: "RubikLight";
        src: local("Rubik"),
        url(../../assets/Rubik/Rubik-Light.ttf) format("truetype");
    }
    .bg-custom-blue{
        background-color: rgba(44, 145, 255, 1);
        padding-top:0px !important;
        padding-bottom:0px !important;
    }
    .navbar-nav li a{
        color:white;
        padding-top:18px !important;
        padding-bottom:18px !important;
      
    } 
    .navbar-nav li{
        padding-left: 5px;
        padding-right: 5px;
    } 
    .nav-menu-right li{
        padding-left: 1px;
        padding-right: 1px;
    }
    .container-fluid{
        padding-left: 24px !important;
        padding-right: 24px !important;       
    }
    .nav-menu-left{
        margin-left: 35px !important;
        font-family: RubikLight;
    }
    .logout{
        padding-right: 0px !important;
    }
    .skill-scanner-menu{
        border-bottom:2px solid white;
    }
    .user-email{
        font-weight: 600 !important;
    }
</style>
