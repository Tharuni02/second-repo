<template>
  <div>
          <meta charset="UTF-8">
		  <meta name="viewport" content="width=device-width, initial-scale=1.0">
		  <title>Examsdaily</title> 
		  <meta name="robots" content="noindex,nofollow">
   <b-container>
   <div class="back image-fluid">
   <b-row>
   <b-col cols="3"offset="4">
   <div  class="mt-5">
   <form>
    <input type="text" placeholder="Name" id="Name" Name="Name"/><br><br>
	<input type="email" placeholder="Email Address" id="Email" Name="Email"/><br><br>
	<input type="number" placeholder="Mobile Number" id="Mobile" Name="Mobile"/><br><br>
	<input type="password" placeholder="PassWord" id="Password" Name="Password"/><br><br>
	<input type="text" placeholder="Nation" id="Nation" Name="Nation"/><br><br><br>
    <b-button class="btn" size="lg">Submit</b-button><br><br>
   </form>
   </div>
   </b-col>
   </b-row>
   </div>
   </b-container>
  </div>
</template>
<script>
</script>
<style>

 .btn{
      margin-left: 40px;
 
  }
  
 .back{
  background-image: linear-gradient(rgba(200, 180, 92, 0.5), rgba(200, 162, 67, 0.5)),
                  url("../assets/desert.jpg");
  background-repeat : no-repeat;
  width : 100%;
  height : auto;
  background-size: cover;
  position: relative;

 
  } 

</style>