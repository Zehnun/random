<script>
    let com;
</script>

<main>
    <div class="bck">
		<label class="header">Post a comment</label>
		<div class="submitCom">
			<label for="submitCom">Comment:</label>
			<textarea id="submitCom" type="text" bind:value={com}></textarea>
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

	textarea { width: 906px; height: 608px; }
	.submitCom{
		margin-top: 20px;
		font-weight: bold;
		font-size: larger;
	}

	.btn{
		background-color: rgb(0, 197, 66);
		color: white;
	}
</style>

