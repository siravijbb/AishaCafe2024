<script>
    import { Alert, Button } from 'flowbite-svelte';
    import { InfoCircleSolid } from 'flowbite-svelte-icons';
    import { fly } from 'svelte/transition';
</script>


<Alert color="green" dismissable>
    <InfoCircleSolid slot="icon" class="w-5 h-5" />
        สามารถส่งคำอวยพรแล้วได้ <a href="/wishes" class="font-semibold underline hover:no-underline">ที่นี่</a>, You can send a wish at <a href="/wishes" class="font-semibold underline hover:no-underline">Here</a>.

</Alert>