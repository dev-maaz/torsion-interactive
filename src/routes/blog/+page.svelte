
<script>
    import Blogdisplay from "../../lib/components/blogdisplay.svelte";
</script>

<div class="blograil">
    <Blogdisplay image="favicon.png" description="My First Blog" location="/blog/1"/>
    <Blogdisplay image="favicon.png" description="My Second Blog" location="/blog/2"/>
    <Blogdisplay image="favicon.png" description="My Third Blog" location="/blog/3"/>
    <Blogdisplay image="favicon.png" description="My Fourth Blog" location="/blog/4"/>

</div>


<style>

    .blograil{

        display: flex;
        flex-flow: column wrap;
        /* max-width: 60%; */

    }
</style>