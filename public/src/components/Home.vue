
<template>
  <div id="intro">
	<h1>Music App</h1>
  </div>
</template>



<script>
export default {
	name: 'intro',
	data () {
		return {
		  msg: 'Welcome to Your Vue.js App'
		}
	},
	mounted() {
	  // When the application loads, we want to call the method that initializes
	  // some data
	  //return 
	  console.log("[home -> vue.ready()]")
	  this.fetchEvents();


	},
	methods: {
		fetchEvents: function(){
			console.log('fetchEvents called');
		}
	}
}
</script>
