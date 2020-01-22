<template>
<div>
 
</div>
</template>

<script>
console.log('ok');
import Blogheader from './header'
import BlogFooter from './footer'

export default {
  name: 'home',
   components: { Blogheader, BlogFooter },
  data () {
    return {
      msg: 'home'
    }
  }
}
</script>