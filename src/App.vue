<template>
  <h1 class="max-w-[30rem] mx-auto">
    <img src="https://emojicdn.elk.sh/🗄️" alt="logo" class="h-[1.5rem]"> R2 Uploader
  </h1>

  <div class="max-w-[30rem] mx-auto">
    <div>
      <EndPointManage></EndPointManage>
    </div>

    <div>
      <CustomUploader></CustomUploader>
    </div>
    <div class="mt-8">
      <FileList></FileList>
    </div>
  </div>

  <footer class="text-center text-xs py-[2rem] opacity-80">
    <a href="/setup-guide/">Setup Guide</a> | 
  </footer>
</template>

<script setup>
import CustomUploader from './components/CustomUploader.vue'
import FileList from './components/FileList.vue'
import EndPointManage from './components/EndPointManage.vue'
</script>