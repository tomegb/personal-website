<template>
	<footer class="footer footer-center rounded bg-neutral p-10 text-base-content">
		<div class="grid grid-flow-col gap-4">
			<nuxt-link :to="'/imprint'" class="link link-hover">Imprint</nuxt-link>
			<nuxt-link :to="'/privacypolicy'" class="link link-hover">Privacy Policy</nuxt-link>
			<nuxt-link :to="'/disclaimer'" class="link link-hover">Disclaimer</nuxt-link>
			<nuxt-link :to="'https://status.tomegb.systems'" class="link link-hover">Status</nuxt-link>
		</div>
		<div>
			<p>Copyright © 2022 - All right reserved by tomegb.cloud</p>
		</div>
	</footer>
</template>
