<template>
    <div>
         
      <div class="py-5 bg-warning">
        <div class="container text-center">
          <h3>Contact Us</h3>
        </div>
      </div>
      <ContactUs/>
  
    </div>
  
</template>

<script>
import ContactUs from '~/components/ContactUs.vue'
export default {
    name:'contact',
    components:{ContactUs},
    head() {
      return {
        title:'Contact Us',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Contact Us'
          },
          {
            hid: 'keywords',
            name: 'keywords',
            content: 'Contact Us'
          }
        ]
      }
    }

}
</script>

