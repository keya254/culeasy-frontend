<template>
  <div class="home cursor-pointer float-right" @click="closeAll()">
    <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path
        d="M14.585 16L10.3424 11.7574C9.95188 11.3668 9.95188 10.7337 10.3424 10.3431C10.7329 9.95262 11.3661 9.95262 11.7566 10.3431L15.9993 14.5858L20.2419 10.3431C20.6324 9.95262 21.2656 9.95262 21.6561 10.3431C22.0466 10.7337 22.0466 11.3668 21.6561 11.7574L17.4135 16L21.6561 20.2426C22.0466 20.6332 22.0466 21.2663 21.6561 21.6569C21.2656 22.0474 20.6324 22.0474 20.2419 21.6569L15.9993 17.4142L11.7566 21.6569C11.3661 22.0474 10.7329 22.0474 10.3424 21.6569C9.95188 21.2663 9.95188 20.6332 10.3424 20.2426L14.585 16Z"
        fill="#F6F6FE"
      />
    </svg>
  </div>
</template>

<script setup lang="ts">
const closeAll = () => {
  const homeElement = document.querySelector('.home') as HTMLElement;
  homeElement.style.display = 'none';
};
</script>

<style scoped></style>
