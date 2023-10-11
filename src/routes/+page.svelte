<script>
	import Nested from "../Nested.svelte";

    let userName = 'Tommy'
    const src = "https://img.freepik.com/free-photo/young-bearded-man-with-striped-shirt_273609-5677.jpg"
    const description = "It's a man"
</script>

<h1>Hello new {userName.toUpperCase()} !</h1>

<img {src} alt="{description} with a blue jean">

<Nested/>

<style>
    :root{
        background-color: rgb(33, 33, 33);
    }

    h1{
        color: white;
    }
</style>


<!-- PART 1 - REACTIVITY -->