<template>
      <div id="todo-card">
         <div class="container">
    
<div class="alert alert-info" role="alert">
    <h1>{{ msg2 }}</h1>
</div>
    <br/>
    <p><b>Objective</b></p>
    <p>One can choose to go back toward safety or forward toward growth.</p>
    <br/>
    <p><b>Name</b></p>
    <p>Francis Jose L. Maglalang</p>
    <br/>
    <p><b>Course</b></p>
    <p>BS IT</p>
    <br/>
    <p><b>Specialization</b></p>
    <p>Web Development</p>
    <br/>

</div>
  </div>
  
</template>

<script>
 
  export default {
    name: 'todo-card',
    data () {
      return {
        
        msg2: 'This is the Profile Component'
      }
    }
  }
</script>