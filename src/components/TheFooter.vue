<script setup lang="ts">
  // const props = defineProps({
  // 	name: {
  // 		type: String,
  // 		default: 'TheFooter',
  // 	},
  // })
</script>
<template>
  <div class="pb-24 pt-12">
    <div class="container mx-auto px-8">
      <div class="flex flex-wrap justify-center space-x-8">
        <a
          href="https://www.facebook.com/vuedesigner/"
          aria-label="facebook"
          external
          target="_blank"
          ><BaseIcon width="24px" name="i-logos-facebook" />
        </a>
        <a
          href="https://twitter.com/vuedesigner/"
          aria-label="twitter"
          external
          target="_blank"
          ><BaseIcon width="24px" name="i-logos-twitter" />
        </a>
        <a
          href="https://forum.pinegrow.com/c/vue-designer"
          aria-label="discourse"
          external
          target="_blank"
          ><BaseIcon width="24px" name="i-logos-discourse-icon" />
        </a>
        <a
          href="https://www.youtube.com/@pgvuedesigner/"
          aria-label="youtube"
          external
          target="_blank"
          ><BaseIcon width="24px" name="i-logos-youtube-icon" />
        </a>
      </div>
    </div>
  </div>
</template>
<style scoped></style>
