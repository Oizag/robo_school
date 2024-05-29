<template>
  <q-page
    style="max-width: 160vh"
    class="q-mx-auto"
  >
    <AppContent />
    <AppResults />
    <AppTeachers />
    <AppPackage />
  </q-page>
</template>

<script setup lang="ts">
import AppContent from 'src/components/AppContent.vue';
import AppResults from 'src/components/AppResults.vue';
import AppTeachers from 'src/components/AppTeachers.vue';
import AppPackage from 'src/components/AppPackage.vue';
</script>
