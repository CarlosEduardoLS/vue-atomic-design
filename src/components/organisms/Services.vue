<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere molestiae temporibus quaerat magni perferendis tempora nemo, recusandae quia laborum voluptate cumque dolorum vitae tenetur, voluptatem soluta eius consectetur natus."
    />
    <Service
      title="Back End"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere molestiae temporibus quaerat magni perferendis tempora nemo, recusandae quia laborum voluptate cumque dolorum vitae tenetur, voluptatem soluta eius consectetur natus."
    />
    <Service
      title="Manutenção"
      description="Lorem, ipsum dolor sit amet consectetur adipisicing elit. Perspiciatis facere molestiae temporibus quaerat magni perferendis tempora nemo, recusandae quia laborum voluptate cumque dolorum vitae tenetur, voluptatem soluta eius consectetur natus."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  name: 'Services',
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
