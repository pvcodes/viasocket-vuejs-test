<script setup>
window.addEventListener('message', (event) => {
  if (event.origin === "https://flow.viasocket.com") {
  const receivedData = event.data;
  }
  });
</script>

<template>
   <button id="viasocket-embed-open-button" onclick="openViasocket(flowId, serviceData)" >Open Integrations</button>
</template>
