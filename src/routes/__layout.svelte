<script context="module" lang="ts">
export async function load({ session: { user, token } }) {
	// console.log('zzzzzzzzzzzzzzzzzzzzzzzzzzz', token)
	fetchCart(token)
	return { props: { user } }
}
</script>

<script>
import '../global.css'
import PageTransitions from '$lib/PageTransitions.svelte'
import Nav from '$lib/Nav.svelte'
import MobNav from '$lib/MobNav.svelte'
import MobFooter from '$lib/MobFooter.svelte'
import { getStores, navigating, page } from '$app/stores'
import { fetchCart } from './../../store/cart'
import { me } from './../../store/auth'
import { ToastContainer, FlatToast } from 'svelte-toasts'

export let user
</script>

<PageTransitions refresh="{$page.path}">
	<div class="bg-gray-50 font-sans antialiased">
		<div class="mb-12 lg:mb-20">
			<div class="fixed top-0 z-40 block w-full md:hidden">
				<MobNav user="{user}" />
			</div>

			<div class="fixed top-0 z-40 hidden w-full md:block">
				<Nav user="{user}" />
			</div>
		</div>
		<div class="lg:-mt-2">
			<slot />
		</div>
	</div>

	<div class=" fixed bottom-0 z-40 w-full  md:hidden">
		<MobFooter />
	</div>
</PageTransitions>
<ToastContainer let:data>
	<FlatToast data="{data}" />
</ToastContainer>
