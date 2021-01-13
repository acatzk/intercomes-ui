<template>
  <div class="flex flex-row h-screen">
    <div class="w-16 bg-gray-200 flex flex-col justify-between items-center p-4">
      <div class="flex flex-col space-y-3">
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
      </div>
      <div class="flex flex-col space-y-3">
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
        <a href="#"><div class="rounded-full bg-gray-400 w-8 h-8"></div></a>
      </div>
    </div>
    <div class="w-64">submenu</div>
    <div class="flex-grow bg-yellow-200">content</div>
  </div>
</template>

<script>
  export default {
    head: {
      title: 'Intercom\s Inbox'
    }
  }
</script>