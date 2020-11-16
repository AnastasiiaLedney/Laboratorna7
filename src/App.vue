<template>
<div class="groupVue"  text-align: center>
 <h2 class="StudentName">{{group.StudentName}}</h2>
 <p class="Speciality">Спеціальність: {{group.Speciality}}</p>
  <p class="Course">{{group.Course}} курс</p>
  <p class="Variant">{{group.Variant}} варіант</p>

 </div>


</template>

<script>
export default
{
  name:"App",
  data()
  { return{
    group:{
      StudentName:"Ледней Анастасія Михайлівна",
      Speciality:"Прикладна математика",
      Course: 4,
      Variant:2
    }
  }
  }

}
</script>

<style scoped>
.StudentName{
  font-family:"Courier New";
     font-size: 30px;
     color:  #F7F1CB;
  
}
.Speciality{
  font-family: "Courier New";
     font-size: 20px;
     color:  #F7F1CB;
}
.groupVue{
position: absolute;
border-radius: 10px 60px 30px;
width: 400px;
height: 300px;
position: relative;
background: #34568B;
text-align: center;
 margin: auto;

}
.Course{
 font-family: "Courier New";
     font-size: 20px;
     color:  #F7F1CB;
}
.Variant{
  font-family: "Courier New";
     font-size: 20px;
    color: #F7F1CB;
}


 
</style>