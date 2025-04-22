
<script>
	import Fill from "../../UI/Buttons/Fill.svelte";
	import Title from "../../UI/Texts/Title.svelte";

    const intro = "./others/tvs.webp"
</script>

<section class="mt-30">
    <div style="background-image: url({intro});" class="w-full h-200 bg-cover bg-center  text-center px-10 text-white flex flex-col justify-center">
        <Title text = "Unlock the future of home tech" />
        <p>A new generation of appliances and home entertainment is here to revolutionise your day with advance AI integration.</p>
    </div>
    <div>
        <p>Preview what's coming....</p>
        <div class="bg-black p-2 pb-20 text-white flex flex-col gap-5 items-center">
            <Title text = "Wash + dry in one mechine" />
            <p>we would watch your clothes very well...</p>
            <Fill text = "Pre-order now" />
        </div>
    </div>
</section>