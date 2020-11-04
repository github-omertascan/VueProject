<template>
    <div id="app"><vue-image-slider :images="imageArray"  :height=700 :width=1079 /> </div>
</template>

<script>
import VueImageSlider from 'vue-image-slider'
export default {
  name: 'app',
  components: {
    VueImageSlider
  },
  data () {
    return {
      imageArray: [
        'https://www.coffeemania.com/epanel/upl/images/shop_top.png',
        'https://www.coffeemania.com/epanel/upl/images/shop_top2.png'
      ]
    }
  }
}

</script>
