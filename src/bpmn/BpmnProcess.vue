<template>
	<div>
		<a-collapse default-active-key="1" :bordered="false" expandIconPosition="right">
			<a-collapse-panel key="1" header="基本设置">
				<p>{{ text }}</p>
			</a-collapse-panel>
			<a-collapse-panel key="2" header="候选配置">
				<p>{{ text }}</p>
			</a-collapse-panel>
			<a-collapse-panel key="3" header="监听器">
				<p>{{ text }}</p>
			</a-collapse-panel>
			<a-collapse-panel key="4" header="附加属性">
				<p>{{ text }}</p>
			</a-collapse-panel>
		</a-collapse>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				text: `A dog is a type of domesticated animal. Known for its loyalty and faithfulness, it can be found as a welcome guest in many households across the world.`,
			};
		},
	};
</script>

<style>
</style>
