<script lang="ts">

    import Subscription from "./subscription.svelte";

</script>

<div class="subscriptionList">
    <Subscription
            title="Example Title"
            description="Example Description"
            cost="50"
            logo="/public/vite.svg"
    />
    <Subscription
            title="Example Title"
            description="Example Description"
            cost="50"
            logo="/public/vite.svg"
    />
    <Subscription
            title="Example Title"
            description="Example Description"
            cost="50"
            logo="/public/vite.svg"
    />

    <Subscription
            title="Example Title"
            description="Example Description"
            cost="50"
            logo="/public/vite.svg"
    />
</div>

<style>
    .subscriptionList {
        display: grid;

        justify-content: flex-start;
        align-items: flex-start;
        gap: 5rem;
        width: 80vw;
        /*height: 20vh;*/

    }
</style>
