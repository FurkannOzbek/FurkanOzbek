<template>
<div class="navbar-container">
  
    <RouterLink to="/" style="margin-right:3%;margin-left:20%"> Home </RouterLink>
    <RouterLink to="#"> Test </RouterLink>  
     <div class="signin">
        <RouterLink to="#"> Sign In</RouterLink>
        
      </div>
  </div>

</template>

<script>
export default{
  name:'Header'
}</script>

<style>
.navbar-container{
  text-align:center;
  padding-top:15px;
  padding-bottom:30px;
  border-bottom:solid;
  border-color:rgb(53, 52, 52);
  background-color:rgb(0, 0, 0);
  text-decoration:none !important ;
  font-size:150%;
 
  

}
.signin{
  float:right;
  margin-right:20px;
  text-decoration:none !important ;
} 
a:-webkit-any-link{
    text-decoration: none !important;
}





</style>