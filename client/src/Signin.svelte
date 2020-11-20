<script>
	let username, password;
</script>

<form>
    <label for="username">Username </label>
    <input id="username" type="text" bind:value={username}>

    <label for="password">Password </label>
    <input id="password" type="text" bind:value={password}>

    <button on:click={signIn} type="button">Sign in</button>
    <button on:click={sigUp} type="button">Sign Up</button>

</form>