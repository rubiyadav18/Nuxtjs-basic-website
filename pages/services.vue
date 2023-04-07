<template>
    <div>
      
      <div class="py-4 bg-warning">
        <div class="container text-center">
          <h3 class="Services_Us"> Services Us</h3>
        </div>
      </div>
  
        <OurServices/>
    </div>
  
</template>

<script>
import OurServices from '~/components/OurServices.vue'
export default {
    name:'services',
    components:{OurServices},
    head() {
      return {
        title:'Services',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Services'
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Services page'
          }
        ]
      }
    }

}
</script>
<style>
.Services_Us{
  text-align: center;
}
</style>
