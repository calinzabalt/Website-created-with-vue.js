<template>
    <header>
        <nav>
            <ul>
                           
                <li><nuxt-link to="/Contact">Contact</nuxt-link></li>
                <li><nuxt-link to="/Galerie">Galerie</nuxt-link></li>
                <li><nuxt-link to="/">Acasă</nuxt-link></li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>

header {
    height: 70px;
    background-color: #4caf50;
}

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    
}

li {
    padding-top: 10px;
    float: right;

}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover:not(.active) {
    background-color: #FFA500;
}


</style>    

