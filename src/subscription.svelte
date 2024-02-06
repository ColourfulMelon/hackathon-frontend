<script>
	export let title;
	export let description;
	export let cost;
	export let logo;
</script>

<div class="item">
    <img src={logo} alt="Logo" class="logo">
    <div class="details">
        <h2 class="title">{title}</h2>
        <p class="description">{description}</p>
        <p class="cost">Cost: ${cost}</p>
    </div>
</div>

<style>
    .item {
        display: flex;
        align-items: center;
        margin-bottom: 20px;
        padding: 10px;
        border: 1px solid #ccc;
        border-radius: 5px;
    }

    .logo {
        width: 80px;
        height: 80px;
        margin-right: 20px;
        border-radius: 50%;
    }

    .details {
        flex: 1;
    }

    .title {
        margin: 0 0 5px;
        font-size: 1.2em;
    }

    .description {
        margin: 0 0 10px;
    }

    .cost {
        margin: 0;
        font-weight: bold;
    }
</style>
