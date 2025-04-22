<script>
	import Fill from "../UI/Buttons/Fill.svelte";
    const hero = "./hero/img1.webp"
</script>
<section style="background-image: url({hero});" class="@container  bg-cover bg-center flex flex-col gap-5 items-center size-full text-cente text-white py-40 px-5 p-20 @xl:gap-7@xl:p-40  @3xl:gap-15 @3xl:p-50">
    <p class="text-3xl font-bold @xl:text-5xl @3xl:text-7xl">The Next Phase of Gaming...</p>
    <p>Get up to $300 Samsung Credit <sup>24</sup>and more when you pre-order.</p>
    <Fill text = "Pre-order now!" />
    <a href="/" class="underline">Shop all monitor deals</a>
</section>