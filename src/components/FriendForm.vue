<template>
    <form >
        <input type="text" placeholder="First Name">
        <input type="text" placeholder="Last Name">
        <input type="text" placeholder="Comments">
        <button class="add">Add</button>
    </form>
</template>

<script>

</script>

<style scoped>
   form{
    text-align: center;
    justify-content: center;
    margin-left: 25%;
    padding: 20px;
    width: 50%;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    border-radius: 10px;
   }
   input{
    display: block;
    width: 95%;
    padding: 10px;
    margin: 5px;
    outline: none;
    border: 1px solid gainsboro;
    
   }
   .add{
     width: 98%;
     padding: 10px;
     border: none;
     color: white;
     font-size: 20px;
     background: rgb(194, 193, 193);
   }
</style>