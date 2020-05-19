<template>
  <v-toolbar
    color="white"
  >
 <v-toolbar-items class="head">
    <v-app-bar-nav-icon @click="al"></v-app-bar-nav-icon>
        <v-btn text>
          DashBoard
        </v-btn>

        <v-btn text>
            Users
        </v-btn>

        <v-btn text>
          Settings
        </v-btn>
  </v-toolbar-items>
     <v-spacer></v-spacer>
   <v-toolbar-item>
        <v-btn text>
          Notification
        </v-btn>
  
         <v-btn text @click="Invert">
         Theme
         </v-btn>
  
        <v-btn text>
          Message
        </v-btn>
  
        <v-btn text>
          Account
        </v-btn>

      </v-toolbar-item>
  </v-toolbar>
</template>

<script>
  export default{
    name :'ToolBar',
    methods : {
      al:function() {
        alert('hii');
      },
      Invert:function(){
        <v-toolbar>
        color:black;</v-toolbar>
      }
    }
  }
</script>

