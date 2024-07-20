<script>
    import { Alert, Button } from 'flowbite-svelte';
    import { InfoCircleSolid } from 'flowbite-svelte-icons';
    import { fly } from 'svelte/transition';
</script>


<Alert color="red" dismissable>
    <InfoCircleSolid slot="icon" class="w-5 h-5" />
อย่าลืมหยิบSlogan หน้างานด้วย! Don't forgot to take slogan at Event!
</Alert>