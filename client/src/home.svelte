<script>
	let userPost = [
		{ title: 'hello', text: 'test123'}, 
		{ title: 'five', text: "this is not ok"}, 
		{ title: 'test liitle nigger', text: 'awesome'}
    ];
    
</script>

<main>
    {#each userPost as Post}
    <div class = "post">
        <div class = "title">
            {Post.title}
        </div>
        <div class = "text">
            {Post.text}
        </div>
    </div>
{/each}
</main>

<style>
    main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
    .post {
		display: flex;
		background-color: rgb(216, 216, 216);
		margin-left: 30em;
		margin-right: 30em;
		margin-bottom: 20px;
		padding-bottom: 50px;
		padding-left: 20px;
		align-items: flex-start;
		flex-direction: column;
		border-radius: 10px;
	}
	.title{
		display: flex;
		padding-top: 10px;
		font-weight: 900;
		
	}
	.text{
		display: flex;
		padding-top: 10px;
	}

    @media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>