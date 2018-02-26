<template>
<div class="img">

    
    <div class="main">
        <div><img src="/images/28500889_586651801686728_1007850034_o.jpg"></div>
        <div><img src="/images/28460755_586651918353383_351376479_o.jpg"></div>
        <div><img src="/images/28499885_586652028353372_623998063_o.jpg"></div>
        <div><img src="/images/28408185_586656021686306_1886199169_o.jpg"></div>
        <div><img src="/images/28417592_586656025019639_1488623447_o.jpg"></div>
        <div><img src="/images/28461440_586655241686384_1719418819_o.jpg"></div>
        <div><img src="/images/wood-3158428_640.jpg"></div>
        <div><img src="/images/structure-3028458_640.jpg"></div>
        <div><img src="/images/holzstapel-2792683_1920.jpg"></div>
    </div>    
	
</div>
</template>


<style scoped>
.hed {
    text-align: center;
    padding-top: 20px;
    font-family: times;
    font-size: 25px;
    padding-bottom: 40px;
   }

body {
    margin: 0;
}

.main {
    margin: .5vw;
    font-size: 0;
    display: -ms-flexbox;
    -ms-flexbox-wrap: wrap;
    -ms-flexbox-direction: column;
    -webkit-flex-flow: row wrap;
    flex-flow: row wrap;
    display: -webkit-box;
    display: flex;

}

.main div {
    -webkit-box-flex: auto;
    -ms-flex: auto;
    flex: auto;
    width: 400px;
    margin: .5vw;
}

.main div img {
    width: 100%;
    height: auto;
}

@media screen and (max-width: 400px) {
    .main div {
        margin: 10;
    }

    .main {
        padding: 0;
    }
}

</style>