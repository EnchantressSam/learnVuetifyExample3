<template>
  <div class="home">
    <h1>Homepage</h1>
    <v-btn class="pink white--text">click me</v-btn>
    <v-btn depressed color="pink">click me</v-btn>
    <v-btn text color="pink">click me</v-btn>

    <v-btn depressed class="pink white--text">
      <v-icon left>mdi-email</v-icon>
      <span>email me</span>
    </v-btn>

    <v-btn depressed small class="pink white--text">
      <v-icon left small>mdi-email</v-icon>
      <span>email me</span>
    </v-btn>

    <v-btn depressed large class="pink white--text">
      <span>email me</span>
      <v-icon right large>mdi-email</v-icon>
     </v-btn>

     <v-btn depressed small dark color="purple">
      <span>email me</span>
      <v-icon right large>mdi-email</v-icon>
     </v-btn>

     <v-btn fab depressed small dark color="purple">
      <v-icon>mdi-heart</v-icon>
     </v-btn>
     <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam vero deserunt dolores odit, qui necessitatibus, odio quos quas provident, exercitationem modi illo ducimus rerum id reiciendis rem at a quia!</p>

     <v-btn class="hidden-md-and-down red">click me</v-btn>
     <v-btn class="hidden-md-and-up blue">click me</v-btn>
     <v-btn dark class="hidden-sm-only">click me</v-btn>

  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'home',
  
}
</script>
