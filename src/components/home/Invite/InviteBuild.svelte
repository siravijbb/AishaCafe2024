<script>
    import { Alert, Button } from 'flowbite-svelte';
    import { InfoCircleSolid } from 'flowbite-svelte-icons';
    import { fly } from 'svelte/transition';
</script>


<Alert color="green" dismissable>
    <InfoCircleSolid slot="icon" class="w-5 h-5" />
    สุขสันต์วันเกิดไอช่า! Happy Birthday Aisha!
</Alert>