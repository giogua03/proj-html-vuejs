<template>
  <div class="big-cont">
    <PageHeader/>
    <PageMain/>
    <PageFooter/>
  </div>
  
</template>

<script>
import PageHeader from '@/components/PageHeader.vue';
import PageMain from '@/components/PageMain.vue';
import PageFooter from '@/components/PageFooter.vue';
export default {
  name:'App',
  components: {
    PageHeader,
    PageMain,
    PageFooter, 
  },
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
</style>