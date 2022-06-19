<template>
  <div>
    <div class="d-md-block d-none">
      <header-aboutus-pc/>
      <index-aboutus-pc/>
    </div>
    <div class="d-block d-md-none">
      <header-aboutus-mb/>
      <index-aboutus-mb/>
    </div>
  </div>

</template>

<script>
import HeaderAboutusMb from '~/components/aboutus/mobile/HeaderAboutusMb.vue'
import IndexAboutusMb from '~/components/aboutus/mobile/IndexAboutusMb.vue'
import HeaderAboutusPc from '~/components/aboutus/pc/HeaderAboutusPc.vue'
import IndexAboutusPc from '~/components/aboutus/pc/IndexAboutusPc.vue'
export default {
  components: { HeaderAboutusPc, IndexAboutusPc, HeaderAboutusMb, IndexAboutusMb },
}
</script>
