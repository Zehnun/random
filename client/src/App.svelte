<script>
	import { component_subscribe } from 'svelte/internal';
import Home from './home.svelte';
	import Nav from './navbar.svelte';

	let Comment = [
		{id: 1, author: "cool", body:"text"},
		{id: 2, author: "cool7", body:"tedxt"},
		{id: 3, author: "cool6", body:"tgext"},
		{id: 4, author: "cool5", body:"tegsxt"},
		{id: 5, author: "cool4", body:"tet"}
	];

</script>


<main>
	{#each Comment as com, i}
		{#if i % 2 == 0}
			<div>
				{com.author}
				<div>
					{com.body}
				</div>
			</div>
	{/each}

</main>
<Nav></Nav>
<Home></Home>






<style>

</style>