<template>
  <div >

 <nav class="navbar navbar-expand-lg ">
  <a class="navbar-brand" href="#"></a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
    <ul class="navbar-nav">
      <li class="nav-item active">
        <a class="nav-link" href="#">FAQ<span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">MEDIA</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">MITRA LAWYER</a>
      </li>
       <li class="nav-item">
        <a class="nav-link" href="#">KARIR</a>
      </li>
    
      
      
     
    </ul>
  
    <form class="form-inline my-2 my-lg-0">
    <a href="signup.html">JOIN MITRA LAWYER</a>
      <button class="btn_style">Login</button>
      
    </form>
 
  </div>
</nav>
    <HelloWorld msg=""/>
    <h1> Mitra Lawyer</h1>
    <form>
  <input class="search" type="text" placeholder="Pencarian berdasarkan Nama,Kota,Spesialisasi" required>	
  <input class="button" type="button" value="Search">		

    </form>
    <br>

    <h3></h3>
    
   
<div class="container">
  <div class="row">
    <div class="col-md-3">
        <div class="card" >
      <img class="card-img-top" src="./assets/law1.jpg" alt="...">
      <div class="card-body">
        <strong class="card-text">I Komang Try Yoga Kertapati, SH MH</strong>
        <br>
        <br>
        <br>
        <p class="card-text">Suyitno Landung & Rekan</p>
        <p class="card-text">KOTA DEPOK</p>
        <p class="card-text">KOTA JAKARTA SELATAN</p>
      </div>
    </div>
    </div>
    
    <div class="col-md-3">
        <div class="card" >
      <img class="card-img-top" src="./assets/law2.jpg" alt="...">
      <div class="card-body">
        <strong class="card-text">Fawwaz Saeful Salman, SH</strong>
        <br>
        <br>
        <br>
        <br>
        <p class="card-text">TemanHukum</p>
        <p class="card-text">KABUPATEN BEKASI</p>
      </div>
    </div>
    </div>
    
    <div class="col-md-3">
        <div class="card" >
      <img class="card-img-top" src="./assets/law3.jpg" alt="...">
      <div class="card-body">
        <strong class="card-text">Hendra Hermawan, SH</strong>
        <br>
        <br>
        <br>
        <br>
        <p class="card-text">Suyitno Landung & Rekan</p>
        <p class="card-text">KOTA DEPOK</p>
        <p class="card-text">KOTA JAKARTA SELATAN</p>
      </div>
    </div>
    </div>

    <div class="col-md-3">
        <div class="card" >
      <img class="card-img-top" src="./assets/law4.jpg" alt="...">
      <div class="card-body">
        <strong class="card-text">Armilla Madiana,SH</strong>
        <br>
        <br>
        <br>
        <br>
        <p class="card-text">LMC & Partners</p>
        <p class="card-text">KOTA JAKARTA SELATAN</p>
      </div>
    </div>
    </div>


  </div>
</div>
  </div>
  

</template>

<script>

import HelloWorld from './components/HelloWorld.vue'

export default {
  
  components: {
    HelloWorld

   
  }
}
  
</script>

<style>
body{
  background : #fff;
}
h1 {
  text-align: center;

  margin-top: 20px;
  font-family: Avenir;
  font-style: normal;
  font-weight: 500;
  font-size: 53px;


}
h2 {
    font-family: sans-serif; 
  text-align: center;

  font-size: 9px;
  

}
form {
    width: 250px;
    margin:40px auto;
}
.button{
  background-color:blue;
  color:#fafafa;
  border:2px solid blue;

}
.btn_style{
		color: white;
		background-color: blue;
    border:2px solid blue;
    width:70px;
}

div {
  background-color: #fff;

}
nav{

  padding: 0;
  font-size: 12px;
  font-family: HelveticaNeue;
}

a{

  text-decoration:none;
  border-radius:10px;
  color:white;
  
  
}
li{
  display: inline-block;
  margin: 0 10px;
  
}
ul{
  list-style-type:none;
  margin:0;
  
}
button{

  float: right;

}
img{
  width:80px;
  height:200px;

  
}


</style>
