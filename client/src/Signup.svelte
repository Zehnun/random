<form>
    <label for="email">Email </label>
    <input id="email" type="text" bind:value={email}>

    <label for="username">Username </label>
    <input id="username" type="text" bind:value={username}>

    <label for="password">Password </label>
    <input id="password" type="text" bind:value={password}>

    <button on:click={sigUp} type="button">Sign Up</button>

</form>