<template>
    <div>

      <div class="py-4 bg-warning">
        <div class="container text-center">
          <h3 class="profile">profile</h3>
        </div>
      </div>
      <profile/>
      
    </div>
</template>

<script>
import profile from '~/components/profile.vue'
export default {
    name:'search',
    comments:{profile},
    head() {
      return {
        title:'profile',
        meta: [
          {
            hid: 'description',
            name: 'description',
          
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


</style>