<template>
  <div>
    <page-header />
    <nuxt />
    <inquiry />
    <page-footer />
  </div>
</template>

<script>
import PageHeader from '~/components/common/PageHeader.vue'
import Inquiry from '~/components/common/Inquiry.vue'
import PageFooter from '~/components/common/PageFooter.vue'
export default {
  components: {
    PageHeader,
    Inquiry,
    PageFooter
  }
}
</script>