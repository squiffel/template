<script>
    export let title = "Placeholder"

    function handleClick() {
		alert('no more alerts')
	}
</script>

<button on:click|once={handleClick}>{title}</button>