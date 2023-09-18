<template>
  <div class="hello">
      <div>
         <h2 class="" style="margin-right:5px">{{message1 }} </h2> 
          <h2 onclick="changeMessage" id="sms">{{ message}}</h2>
      </div>
 

  </div>
</template>

<script>
    function changeMessage() {

        document.getElementById('sms').innerHTML = 'shahin and  '

    }
export default {
        name: "HelloWorld",
 
        data:() => ({

                message1: 'shahin and  ',
                message: 'yasamin does look',
        }),
        methods: {
            changeMessage() {
                    this.message = this.message1
              

    }

        }
                 

    
}
</script>

 
<style scoped>
 div{

     display:flex;
     width:400px;
 
 }
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
