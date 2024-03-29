<script>
    import Cta from "./CTA.svelte";
import Header from "./Header.svelte";
    import SectionWrapper from "./SectionWrapper.svelte";
    import Stars from "./Stars.svelte";

</script>
<SectionWrapper>
    <Header/>
    <div class="flex flex-col gap-10 flex-1 items-center justify-center pb-10 md:pb-14 font-semibold">
        <h2 class="text-5xl sm:text-6xl md:text-7xl lg:text-8xl max-w-[1400px] mx-auto w-full text-center">
            <span class="text-indigo-400">
                Gym
            </span> Training
            <span class="text-slate-600 line-through">Is Hard </span>
            Just Got <span class="text-indigo-500">Easier</span>
        </h2>
        <p class="text-xl sm:text-2xl md:text-3xl text-center max-w-[1000px] mx-auto w-full">Less think and more doing. We're the trainer in your pocket full of <span class="italic">personailzed workouts, exercises explanation, analytics</span> and much much more.</p>
        <Cta />
        <Stars />
    </div>
</SectionWrapper>