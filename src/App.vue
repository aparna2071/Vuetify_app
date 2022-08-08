<template>
  <v-app>
    <v-main>
      <SearchBar/>
      <InvoiceSummary/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SearchBar from './components/SearchBar.vue'
import InvoiceSummary from './components/InvoiceSummary.vue'


export default {
  name: 'App',

  components: {
    HelloWorld,
    SearchBar,
    InvoiceSummary
    
  },

  data: () => ({
    //
  }),
}
</script>
