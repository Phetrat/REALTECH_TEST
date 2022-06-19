<template>
  <div>
    <div class="d-md-block d-none">
        <header-aboutus-pc/>
        <join-about-us/>
    </div>
    <div class="d-md-none d-block">
        <header-aboutus-mb/>
        <join-about-us/>
    </div>
  </div>
</template>

<script>
import JoinAboutUs from '~/components/aboutus/JoinAboutUs.vue'
import HeaderAboutusMb from '~/components/aboutus/mobile/HeaderAboutusMb.vue'
import HeaderAboutusPc from '~/components/aboutus/pc/HeaderAboutusPc.vue'
export default {
  components: { JoinAboutUs, HeaderAboutusPc, HeaderAboutusMb },

}
</script>

<style>

</style>