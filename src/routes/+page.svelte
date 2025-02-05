<script>

let greeting = $state("Hello");


</script>

<!--A header is created. It is at the top of the website-->
<header>THIS IS A HEADER</header>

<!--This div includes one h1, h2 , input and footer, which all create the structrure of the page-->

<div> 
   
    <h1>{greeting}</h1>
    <h2> What do you want to write? </h2>

    <!-- What we write on the input type, will be showed in the h1 area-->
    <input type ="text" bind:value={greeting}>






<footer>This is a footer</footer>

</div>
<style>

 
    /* Easy styled header with a lightblue color */
    header,footer{

     
      width: 100 vh;
      background-color: lightblue;
      font-size: 30px;
      padding: 10px;
      text-align: center;
      color: rgb(0, 21, 139);
      font-family: Verdana, Geneva, Tahoma, sans-serif;
      display: flex;
      justify-content: center;
    align-items: center;



    }

    /* The same goes with footer */
    footer{
    position: fixed;
    left: 0;
    bottom: 0;
    width: 100%;
}

/* Both h1 and h2 are styled at the same block of code */
h1,h2{ 
    display: grid;
justify-content: center;
    align-items: center;
    font-family: Verdana, Geneva, Tahoma, sans-serif;

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

