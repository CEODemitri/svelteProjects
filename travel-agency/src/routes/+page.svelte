<!-- thinking to make a component folder for each container to slim down this page but since first run, let just go -->
<script>
    import Review from "../lib/components/Review.svelte";
    import Inspirations from "../lib/components/Inspirations.svelte";
    import Above from "../lib/components/Above.svelte";
	import Popular from "../lib/components/Popular.svelte";
	import Value from "../lib/components/Value.svelte";
    import Trending from "../lib/components/Trending.svelte"
	import Subscribe from "../lib/components/Subscribe.svelte";
    import Below from "../lib/components/Below.svelte";
</script>

<Above />
<Popular />
<!-- everything past here is pretty good, popular section good refernce to model, for now -->
<Value />
<Trending />
<Review />
<Inspirations />
<Subscribe />
<Below />


<style>
    /* beginning of every project, i forget how much i use flex. remember to add css variable or one class name to share */
    * {
        padding: 0;
        margin: 0;
        min-width: 0;
    }
</style>
