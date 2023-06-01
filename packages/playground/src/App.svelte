<script>
	let browser = !import.meta.env.SSR;
</script>

<p>Hello from the {browser ? 'client' : 'server'}!</p>
