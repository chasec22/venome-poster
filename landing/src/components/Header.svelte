<script>
	import { openModal } from "../store";
	import Logo from "./Logo.svelte";
</script>

<header class="flex flex-col relative z-[998]">
	<div
		class="max-w-[1400px] mx-auto w-full flex items-center justify-between p-4 py-6"
	>
		<a href="#" class="flex gap-2 text-primary-700">
			<Logo />
			<h1 class="font-semibold">Venome</h1>
		</a>
		<nav class="hidden md:flex items-center gap-4 lg:gap-6">
			<a
				href="#project"
				class="duration-200 hover:text-primary-700 cursor-pointer"
				>Project Overview</a
			>
			<a
				href="#who-made-venome"
				class="duration-200 hover:text-primary-700 cursor-pointer"
				>Who made Venome?</a
			>
		</nav>
	</div>
</header>
