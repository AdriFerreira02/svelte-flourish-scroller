<script>
	import FlourishScroller from '../components/FlourishScroller.svelte';
	import NewsArticle from './NewsArticle.svelte';
	let steps = [
		'O que mudou no mundo do K-Pop desde a explosão do viral Gangnam Style?',
		'Nos últimos 10 anos, tem se notado uma queda do idioma coreano no K-Pop',
		'Em 2013, as músicas mais populares eram, maioritariamente, cantadas em coreano',
		'No entanto, em 2023 o inglês domina as canções',
		'"Mas os cantores não têm de ser coreanos?"',
		'Porém, sim, alguns dos grupos mais bem sucedidos da atualidade são 100% coreanos',
		
	];
</script>

<FlourishScroller flourish_id="2134682" {steps} />

<NewsArticle />
