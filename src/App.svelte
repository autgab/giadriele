<script>
import Carousel from './lib/Carousel.svelte';
import Valentine from './lib/Valentine.svelte';
  let showPics = false;
</script>

{#if showPics}
 <Carousel />  
{:else } 
<Valentine bind:showPics/>
{/if}
