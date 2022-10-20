<script>
    import "@brainandbones/skeleton/themes/theme-skeleton.css";
    import "@brainandbones/skeleton/styles/all.css";
	import "../theme.postcss";
    import "../app.postcss";

    import { AppShell, AppBar } from "@brainandbones/skeleton";
</script>

<AppShell>
    <!-- Header -->
    <svelte:fragment slot="header">
	  	<!-- Insert the App Bar: -->
		<AppBar background="bg-transparent" shadow="shadow-none" padding="p-4 md:px-20">
			<svelte:fragment slot="lead">
				<img src="/logo.png" class="h-10 md:h-14" alt="Forward School Logo">
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<a class="btn btn-sm" href="https://dev.to/forwardschool" target="_blank">Tutorials</a>
			</svelte:fragment>
		</AppBar>
		<!-- --- -->
	</svelte:fragment>
    <!-- Page Content Slot -->
    <slot />
</AppShell>
