<script>
	import Calendar from '../components/Calendar.svelte';
</script>

<main>
	<Calendar />
</main>

<style lang="scss">
	main {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;

		width: 100%;
		height: 100%;

		gap: 1rem;

		padding: 1rem;

		background: var(--clr-light);
	}
</style>
