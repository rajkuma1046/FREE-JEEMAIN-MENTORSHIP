<!DOCTYPE html>
<html lang="en">
<head>

<title> raj ka code</title>

<style type="text/css">

<--body{
font: 15px;
font-family:arial;
color:rgb(799,,0);
}-->

.h2{
width:100%;
text-align: center;
text-decoration:underline;
background-color:yellow;
text-transform:capitalize;
letter-spacing:1px;
word-spacing:10px;
font-weight:0;
text-shadow:2px 2px  blue;
border: 1px  solid  black;
padding: 2px 8px 2px 8px; }

#name,#pin,#address{
width:100%;}

fieldset{
width:100%;



}

#male,#female{
width:20%;
border: 2px solid pink;
}


.name{
background-color: pink;
padding:5px;


}







</style>
</head>
<body>

<pre>

  <h2 align="right" class="h2"> payment form</h2>
<form class="form">
NAME :  <input type="text" class="name" id="name" required placeholder="----name----" width="100%">

<fieldset>male <input type="radio"  name="gender" id="male"> </input> female <input type ="radio" name="gender"  id ="female"> </input></fieldset>

Password : <input type="password" >id="pin"> </input>

Address : 
           <textarea name="address" id="address" row="100"> </textarea>
           
           
           
           
        
Pincode : <input type="number"   >      



Upload Screenshot : <input type="file">
   <hr>
       <h3 align=" center" color="black" border="1px" background-color="yellow" > Payments information</h3>
<p> card type : <select name=" card type" id="card type">
       <option value=" ">---select card type--- </option>
        <option value="rupay card">rupay card </option>
        <option value="master card ">master card </option>
        <option value=" visa card">visa card </option>
        <option value="other prepaid card "> other prepaid card </option> </select></p>
        
<p>card no. : <input type="number" name ="card no." id =" card no." required>
</p>      
<p>Expire Date : <input type="date" name="expire_date"> </p>

<p> CVV  :  <input type="password"  type="number" required>

</p>
<pre>
    <input   type="button" value="pay now">  <input type="reset">     
     
 <input type="checkbox"><p>i am read all instraction . and i agree </p>
</pre>


</form>
</pre>


</body>










</html>
