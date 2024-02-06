<script lang="ts">
    import SubscriptionList from './subscriptionList.svelte'

    let myComponent = false;
    let componentTitle = '';
    switch (componentTitle) {
        case '':
            myComponent = false;
            break;
        default:
            myComponent = true;
            break;
    }
</script>

<main>
    <div class="header">
<!--todo: add logo-->
        <img src="/public/vite.svg">
        <h1>Subscriptions</h1>
    </div>
    <div class="body">
        <SubscriptionList />



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
