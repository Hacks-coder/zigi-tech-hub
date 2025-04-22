<script>
	import Fill from "../../UI/Buttons/Fill.svelte";


	import Title from "../../UI/Texts/Title.svelte";
    const client = "./others/client.jpg"

</script>
<section class="text-center mt-30">
    <Title text = "Mobile & Computing" />
    <div style="background-image: url({client});" class="bg-center bg-cover w-full h-100"></div>
    <div class="flex flex-col items-center gap-2">
        <Title text = "Galaxy S5 Ultra" />
        <p>Get up to $1, 000 with multiple offers.</p>
        <Fill text = "Buy now" />
        <a href="/">Learn more!</a>
    </div>
</section>