<script>

let greeting = $state("Hello");


</script>


<header>This is a header</header>
<div>

    <h1>{greeting}</h1>
    <h2 glow> What do you want to write </h2>

    <input type ="text" bind:value={greeting}>






<footer>This is a footer</footer>

</div>
<style>


    header{

     
      width: 100 vh;
      background-color: lightblue;
      font-size: 30px;
      padding: 10px;
      text-align: center;
      color: darkblue;
      font-family: Verdana, Geneva, Tahoma, sans-serif;
      display: flex;
      justify-content: center;
    align-items: center;



    }

    footer{

     
width: 100 vh;
background-color: lightblue;
font-size: 30px;
padding: 10px;
text-align: center;
color: darkblue;
font-family: Verdana, Geneva, Tahoma, sans-serif;
display: flex;
justify-content: center;
    align-items: center;
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;



}

h1,h2{ 
    display: grid;
justify-content: center;
    align-items: center;
    

}


input{
    display: flex;
justify-content: center;
    align-items: center;

}
  

div{
    display: grid;
justify-content: center;
    align-items: center;
    flex-direction: column;

}



</style>

