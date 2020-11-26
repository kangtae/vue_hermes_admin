<template>
	<div class="app">
		<!-- <AppHeader></AppHeader>
		<div class="app-contents">
			<router-view></router-view>
		</div>
		<AppFooter></AppFooter>
		<ToastPopup></ToastPopup> -->
		<ProductRegistration></ProductRegistration>
	</div>
</template>

<script>
// import AppHeader from './components/common/AppHeader.vue';
// import AppFooter from './components/common/AppFooter.vue';
// import ToastPopup from './components/common/ToastPopup.vue';
import ProductRegistration from './views/ProductRegistration.vue';
export default {
	components: {
		// AppHeader,
		// ToastPopup,
		// AppFooter,
		ProductRegistration,
	},
};
</script>

<style></style>

<style lang="scss">
@import './assets/libs/arita-dotum/css/arita-dotum.css';
@import './assets/libs/font-awesome/css/font-awesome.min.css';
@import './assets/libs/bootstrap/css/bootstrap-custom.css';
// @import './assets/libs/bootstrap-datetimepicker/css/bootstrap-datetimepicker.min.css';
@import './assets/libs/dropify/css/dropify.min.css';
@import './assets/libs/ez-space-css/css/ez-space.css';
@import './assets/scss/common';
@import './assets/scss/layout';
@import './assets/scss/style';
@import './assets/scss/login';
</style>
