<script>
  import { images } from '../imageData/images';
  let idx = 0;
  $: image = images[idx];
  let forward = () => idx = idx === images.length -1 ? 0 : idx+1;
</script>

<main>
  <div class="max-w-xl space-y-4 bg-red-700 m-3 p-4 rounded-xl">
  <img class="rounded-xl" on:click={forward} src={image?.src} alt={image?.alt}>
  <div class="rounded h-10 bg-red-900 dark:text-white p-2 my-2 text-center">
    {image?.alt}
  </div>
</main>

