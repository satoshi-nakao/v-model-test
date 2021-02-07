<template>
  <div>
    <span>入力欄：</span>
    <input type="text" v-model="message">
    <h1>{{ message }}</h1>
    <!-- v-modelを使うことでdataの中にある
    messageとtemplateのmessageをバインディングし、
    textからmessageを変えることができる -->
    </div>
</template>

<script>


export default {
  data(){
    return{
      message: "おはよう"
    }
  }
 
}
</script>


