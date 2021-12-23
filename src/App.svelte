<script>
	import { initializeApp } from 'firebase/app';
	import { getAnalytics } from 'firebase/analytics';
	import { firebaseConfig } from '../firebase.config';

	const app = initializeApp(firebaseConfig);
	const analytics = getAnalytics(app);
</script>

<main>
	<h1>Hello Lazio Winter Cup!</h1>
	<p>
		Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
		how to build Svelte apps.
	</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
