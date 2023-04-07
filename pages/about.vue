<template>
    <div>

      <div class="py-4 bg-warning">
        <div class="container text-center">
          <h3 class="AboutUS"> About Us</h3>
        </div>
      </div>
      <Aboutus/>
      
    </div>
</template>

<script>
import Aboutus from '~/components/Aboutus.vue'
export default {
    name:'about',
    comments:{Aboutus},
    head() {
      return {
        title:'About Us',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'About Us'
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Home page'
          }
        ]
      }
    }
}
</script>

<style>

.AboutUS{
 
   text-align: center;
 
}
</style>