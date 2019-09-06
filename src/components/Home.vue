<template>

    <body>
        <div class="sidenav">
            <a href="#home"><span>Home</span></a>
            <a href="#resume"><span>Resume</span></a>
            <a href="#portfolio"><span>Portfolio</span></a>
            <a href="#about"><span>About</span></a>
        </div>
        <div style="margin-top: 20%">
            <h1>Kyle Miranda</h1>
            <h2>Front-end Developer</h2>
            <p><a href="https://github.com/kylemiranda">GitHub</a></p>
            <p><a href="https://www.linkedin.com/in/kyle-miranda-24889b11b/">LinkedIn</a></p>
            <p><a href="mailto: miranda14355k@gmail.com">E-Mail</a></p>
        </div>
    </body>
</template>

<style lang="css">

    body {
        font-family: 'Lexend Deca', sans-serif;
        background-color: #E7E5DF;
    }

    h1 {
        font-size: 400%;
        text-align: center;
        color: #393E41;
    }

    h2 {
        font-size: 200%;
        text-align: center;
        color: #393E41;
    }

    p {
        text-align: center;

    }

    .sidenav {
        height: 100%;
        width: 160px;
        position: fixed;
        z-index: 1;
        top: 0;
        left: 0;
        background-color: #111;
        overflow-x: hidden;
        padding-top: 20px;
        transition: width 1s;
    }

    .sidenav a {
        padding: 6px 8px 6px 16px;
        text-decoration: none;
        font-size: 25px;
        color: #818181;
        display: block;
    }

    /* .sidenav:hover{
        width: 160px; 
        opacity: 1;
    } */

    a:link,
    a:visited {
        text-decoration: none;
        color: #438C76;
    }
</style>

<script>
    export default {
        name: 'Home',
        props: {
            name: String
        }
    }
</script>