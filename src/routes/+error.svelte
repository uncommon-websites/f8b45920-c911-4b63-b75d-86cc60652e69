<script lang="ts">
	import { page } from "$app/state";
</script>

<main class="min-h-screen flex items-center justify-center bg-white px-6">
	<div class="text-center">
		<h1 class="text-6xl font-bold mb-4">Error {page.status}</h1>
		<p class="text-xl text-gray-600 mb-8">{page.error?.message ?? "Something went wrong."}</p>
		<a href="/" class="inline-block bg-black text-white px-8 py-3 rounded-full text-sm font-bold uppercase tracking-wide hover:bg-primary-600 transition-colors">
			Go back home
		</a>
	</div>
</main>
