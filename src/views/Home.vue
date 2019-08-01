<template>
  <div class="home">
    <paymentbar/>
    <performance/>
    <absent/>
  </div>
</template>

<script>
import paymentbar from '@/components/paymentbar.vue';
import performance from '@/components/performance.vue';
import absent from '@/components/absent.vue';


export default {
  name: 'home',
  components: {
    paymentbar,
    performance,
    absent 
  }
}
</script>
