<script lang="ts" setup>
const props = defineProps({
  formFeedback: String,
  url: String,
  isLoading: Boolean,
});
</script>

<template>
  <div
    v-if="formFeedback === 'error'"
    class="text-white w-full block p-3 mt-4 bg-red-500"
  >
    There was an error processing your request.
  </div>

  <div
    v-else-if="formFeedback === 'success' && url"
    class="text-white w-full block p-3 mt-4 bg-green-500"
  >
    You just minted omID, check out the transaction
    <a :href="url" class="text-gray-100 underline" target="_blank">here</a>.
  </div>

  <div
    v-else-if="formFeedback === 'incomplete'"
    class="text-white w-full block p-3 mt-4 bg-red-500"
  >
    Please complete all required fields.
  </div>

  <div
    v-else-if="formFeedback === 'invalid'"
    class="text-white w-full block p-3 mt-4 bg-red-500"
  >
    Please enter a valid wallet address.
  </div>

  <div
    v-else-if="formFeedback === 'consent'"
    class="text-white w-full block p-3 mt-4 bg-red-500"
  >
    Please complete the captcha.
  </div>
</template>

<style>
div {
  @apply rounded;
}
</style>