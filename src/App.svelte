<script>
	import { initializeApp } from 'firebase/app';
	import { getAnalytics } from 'firebase/analytics';
	import { firebaseConfig } from '../firebase.config';

	const app = initializeApp(firebaseConfig);
	const analytics = getAnalytics(app);
</script>

<main>
	<h1>Hello Lazio Winter Cup!</h1>
	<marquee><h2>Work in progress!!</h2></marquee>
</main>

<style>
	palette {
		color: #0c2032;
		color: #bac74d;
		color: #5679a4;
		color: #b0d9f1;
		color: #d6ede2;
		color: #ecf1f1;
	}
	main {
		text-align: center;
	}

	h1,
	h2 {
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 100;
		padding: unset;
		margin: unset;
	}

	h2 {
		font-size: 1.5em;
		color: #5679a4;
	}
</style>
