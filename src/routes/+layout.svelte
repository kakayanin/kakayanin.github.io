<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<main>
	<nav class="sticky top-0 bg-[#FFF8E8] flex justify-around items-center h-[70px] drop-shadow">
		<h1 class="text-[30px] font-bold">
			Enteng Bakery
		</h1>
		<ul class="flex justify-around w-[30%] items-center text-[24px]">
			<li><a href="/">Home</a></li>
			<li><a href="/shop">Features</a></li>
			<li><a href="/visit-us">Visit Us</a></li>
		</ul>
		<button class="text-[24px]">
			Login
		</button>
	</nav>
{@render children()}
</main>
