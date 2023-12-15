<script lang="ts">
	import { Button } from '$lib/components/ui/button';
	import { Input } from '$lib/components/ui/input';
	import '../app.postcss';
	import { AppShell, AppBar, Avatar } from '@skeletonlabs/skeleton';
</script>

<!-- App Shell -->
<AppShell>
	<svelte:fragment slot="header">
		<!-- App Bar -->
		<AppBar>
			<svelte:fragment slot="lead">
				<strong class="text-xl uppercase">svelte-ui-template</strong>
			</svelte:fragment>
			<svelte:fragment slot="trail">
				<form class="flex w-full max-w-sm items-center space-x-2">
					<Input type="text" placeholder="search" />
					<Button type="submit">Search</Button>
				</form>
				<a
					class="btn btn-sm variant-ghost-surface"
					href="https://github.com/MBeggiato/svelte-ui-template"
					target="_blank"
					rel="noreferrer"
				>
					<Avatar
						src="https://user-images.githubusercontent.com/25181517/192108374-8da61ba1-99ec-41d7-80b8-fb2f7c0a4948.png"
						width="w-8"
						rounded="rounded-full"
					/>
				</a>
			</svelte:fragment>
		</AppBar>
	</svelte:fragment>
	<!-- Page Route Content -->
	<slot />
</AppShell>
