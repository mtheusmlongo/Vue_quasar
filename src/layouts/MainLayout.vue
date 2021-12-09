<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="now items-center justify-between q-pt-sm">
      <q-img width="130px" class="q-mx-sm q-my-md" src="../assets/logo.png">
    <div>
      <q-icon
        class= "q-mx-sm- q-pa-sm q-icon-custom"
        nome= "fas fa-search"
        size="25px"
        color="black"

        />
      
      <q-icon
      class="q-mx-sm- q-pa-sm q-icon-custom"
      nome= "fab fa-facebook-mesenger"
      size="25px"
      color="black"
      />
   </div>
   <div>
   <div class="flex flex-center full-width">
     <q-tabs class="text - teal q-mx-sm full-whidth">
       <q-tab nome= "home" icon="fas fa-home">
       <q-tab nome= "users"icon="fas fa-users">
       <q-tab nome= "video" icon="ondement_video">
       <q-tab nome= "store" icon="notifications">
       <q-tab nome= ""   >

    </q-header>

    
      
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>


export default {
  name: 'MainLayout',
  data(){
    return{};
  }.
};
  

  
</script>
