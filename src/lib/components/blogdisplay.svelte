<script>
    export let image;
    export let description;
    export let location;
</script>

<a href={location}>
<img src={image} alt="Thumbnail">
<p>{description}</p>
</a>
<!--  -->
<style>
    a {
        display: flex;
        flex-flow: row nowrap;
        /* justify-content: center; */
        align-items: center;

        width: 50rem;
        background-color: #F4BF96;
        border-radius: 1.5rem;
        padding: 0.5rem;
        margin: 0.5rem;

    }
</style>