<script>
  export let showPics;
  const show = () => showPics = true;
</script>
  
<main>
  <div class="max-w-xl bg-red-700 space-y-4 m-3 p-3 rounded-md text-xl">
    <p>Buon San Valentino Giada!</p>
    <button class=" animate-pulse rounded-md bg-red-400 m-1 p-1 px-3" on:click={show}>Tus 💞</button>
  </div>
</main>


<svelte:head>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Protest+Riot&display=swap" rel="stylesheet">
</svelte:head>

<style>
  main {
    font-family: "Protest Riot", sans-serif;
    font-weight: 400;
    font-style: normal;
  }
</style>
