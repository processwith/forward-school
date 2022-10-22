<script>
    import "@brainandbones/skeleton/themes/theme-skeleton.css";
    import "@brainandbones/skeleton/styles/all.css";
	import "../theme.postcss";
    import "../app.postcss";

    import { AppShell } from "@brainandbones/skeleton";
</script>

<AppShell>
    <slot />
</AppShell>
