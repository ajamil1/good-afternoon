<script lang="ts">
    import { onMount } from 'svelte';
    import { page } from '$app/stores';
  
    onMount(() => {
      console.log('Page component mounted');
    });
    </script>

<div class="h-screen bg-slate-950">
    <div class="flex flex-col h-full">
        <h1 class="text-2xl text-center">good-afternoon</h1>
    </div>
</div>
