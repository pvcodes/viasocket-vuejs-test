<script>
window.addEventListener("message", (event) => {
	if (event.origin === "https://flow.viasocket.com") {
		const receivedData = event.data;
	}
});
</script>

<template>
	<div id="integration">
		<button
			id="viasocket-embed-open-button"
			onclick="openViasocket(flowId, serviceData)"
		>
			Open Integrations
		</button>
	</div>
</template>

<style scoped>
#integration {
	height: 100%;
}
</style>
