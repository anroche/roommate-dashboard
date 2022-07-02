<div >
	<h1>METEO</h1>
</div>

<script lang="ts">

	if (typeof window !== "undefined") {
		let meteo = fetch("http://api.meteo-concept.com/api/location/city?token=c72cdeb9a0eee5146770ddb5ca0167dcccf9f0173eb24fa0aff6988b0b9bc666&insee=35238").
		then(e => console.log('THEN =>', e))
		console.log('METEO =>', meteo)
	} else {
		console.log('NO WINDOW =>')
	}

</script>
