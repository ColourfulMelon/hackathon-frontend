<script lang="ts">
    import Item from './subscription.svelte'
</script>

<main>
    <div class="header">
        <img src="vite.svg"> //todo: add logo
        <h1>Subscriptions</h1>
    </div>
    <div class="body">
        <Item
                title="Example Title"
                description="Example Description"
                cost="50"
                logo="vite.svg"
        />
        <Item
                title="Example Title"
                description="Example Description"
                cost="50"
                logo="vite.svg"
        />
        <Item
                title="Example Title"
                description="Example Description"
                cost="50"
                logo="vite.svg"
        />

        <Item
                title="Example Title"
                description="Example Description"
                cost="50"
                logo="vite.svg"
        />



    </div>

</main>

<style>
.body {
    display: grid;

    justify-content: flex-start;
    align-items: flex-start;
    gap: 5rem;
    width: 80vw;
    /*height: 20vh;*/

}

.header {
    display: flex;
    justify-content: flex-start;
}
</style>
