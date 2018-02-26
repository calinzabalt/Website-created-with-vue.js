<template>
<footer>
    <div class="ft">
        <h3 class="left">Arad Strada Păduri nr.28</h3>
        <p class="center">© 2018 ALL RIGHTS RESERVED</p>
        <h4 class="right"> Număr de telefon: 0757 303 788 </h4>
    </div>   
       
</footer>
</template>

<style scoped>

footer {
  position: relative;
  height: 100%;
  width: 100%;
  background-color:#4caf50;
  left: 0px;
  right: 0px;
  bottom: 0xp;
    
}
   
.ft {
    display: flex;
    flex-direction: row;
    text-align: center;
    padding-top: 45px;
    color: white;
}   

.center{
  text-align: center;
  font-size: 15px;
  color: white;
  padding-bottom: 35px;
}

.left{
  flex-grow: 2; 
  font-size: 22px; 
}
.right{
  flex-grow: 2;  
  font-size: 22px;
            
}



</style>