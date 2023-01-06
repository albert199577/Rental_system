<template>
  <div>Index</div>
  <Link href="/hello">
    Show page
  </Link>
  <p>Message: {{ message }}</p>
</template>

<script setup>
import { Link } from '@inertiajs/inertia-vue3'
defineProps({ message: String })
</script>

<!-- <script>
import MainLayout from "../Layouts/MainLayout.vue";
export default {
  layout: MainLayout
}
</script> -->
