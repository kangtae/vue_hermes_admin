<template>
	<div class="content">
		<AppHeader></AppHeader>
		<ProductRegistrationForm></ProductRegistrationForm>
	</div>
</template>

<script>
import AppHeader from '../components/common/AppHeader.vue';
import ProductRegistrationForm from '../components/product/ProductRegistrationForm';
export default {
	components: {
		AppHeader,
		ProductRegistrationForm,
	},
};
</script>

<style></style>
