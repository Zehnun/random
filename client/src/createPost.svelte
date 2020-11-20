<script>
    let title, text;
    function submitPost(){
		alert('zakariya sucks')
	}
</script>

<main>
	<div class="bck">
		<label class="header">Create a post </label>
		<div class="submitTitle">
			<label for="submitTitle">Title:</label>
			<input class="Title" id="Title" type="text" bind:value={title}>
		</div>
	
		<div class="submitText">
			<label for="submitText">Text:</label>
			<textarea id="submitText" type="text" bind:value={text}></textarea>
			 <!-- <input id="submitText" type="text" bind:value={text}> -->
		</div>
		<button class="btn" on:click={submitPost} type="button">Submit</button>
	</div>

</main>


<style>
    main{
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.header{
		display: flex;
		align-items: center;
		justify-content: center;
		font-weight: bolder;
		font-size: 50px;
		margin-bottom: 20px;
	}
	.bck{
		padding-top: 50px;
	}
	.Title{
		width: 906px;
	}

	textarea { width: 906px; height: 608px; }

	.submitTitle{
		font-weight: bolder;
		font-size: larger;
	}
	.submitText{
		margin-top: 20px;
		font-weight: bold;
		font-size: larger;
	}

	.btn{
		background-color: rgb(0, 197, 66);
		color: white;
	}
</style>
