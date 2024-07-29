<script>
    import { Alert, Button } from 'flowbite-svelte';
    import { InfoCircleSolid } from 'flowbite-svelte-icons';
    import { fly } from 'svelte/transition';
</script>


<Alert color="blue" dismissable>
    <InfoCircleSolid slot="icon" class="w-5 h-5" />
    Happy Birthday Aisha! Aisha in <a class="underline" href="https://x.com/LeBeau_u/status/1817710916596871279">Shinjuku!</a>
</Alert>