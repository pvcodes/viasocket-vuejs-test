<script setup>
window.addEventListener('message', (event) => {
  if (event.origin === "https://flow.viasocket.com") {
  const receivedData = event.data;
  }
  });
</script>

<template>
  <div id="main">
    <p>HELLO from viasocket</p>
   <button id="viasocket-embed-open-button" onclick="openViasocket(flowId, serviceData)" >Open Integrations</button>

  </div>
    <!-- <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a> -->
</template>


<style scoped>
#main {
  /* color: #888; */
  height: 100%;
}
</style>
