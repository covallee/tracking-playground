<script>

const handleClick = () => {
    window.dataLayer.push({
	'event' : 'login',
	'eventName' : 'email' 
});
}

</script>

<button class="event-btn" on:click={handleClick}>Click Me</button>

<style>
    .event-btn{
        padding: 1rem 2rem;
    }
</style>