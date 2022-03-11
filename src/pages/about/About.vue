<template>
  <div
      style="max-width: 800px; margin: 0 auto"
      class="q-gutter-md"
  >
    <h5>About<a
        target="_blank"
    >
    </a></h5>
    <div class="text-body1">
    </div>
    <h5>Contributors</h5>
    <div class="row q-gutter-md q-ml-none">
      <ContributorCard
          v-for="contributor in contributorList"
          :key="contributor.name"
          :contributor="contributor"
      >
      </ContributorCard>
    </div>
  </div>
</template>

<script setup>
import ContributorCard from './components/ContributorCard.vue'

const contributorList = [

]
</script>
