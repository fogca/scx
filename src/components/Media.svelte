<script>
    import Arrow from '../components/Arrow.svelte';
    import IconNote from '../components/IconNote.svelte';
    import Podcast from '../components/Podcast.svelte';
    import Line from '../components/Line.svelte';
</script>

<div class="Media">
    <div class="l-section-head" lang="en">Media</div>
    <h1 class="l-section-head">焼酎野郎のメディア</h1>
    <div class="wrapper">
        <a href="/" data-sveltekit-prefetch="" class="l-word container">
            <div class="l-line"></div> 
            <div class="left">
                <IconNote />
            </div> 
            <h2 class="h5 sans">焼酎野郎のノート</h2>
            <div class="right">
                <Arrow />
            </div>
        </a>
        <a href="/" data-sveltekit-prefetch="" class="l-word container">
            <div class="l-line"></div> 
            <div class="left">
                <Podcast />
            </div> 
            <h2 class="h5 sans">焼酎野郎ラジオ</h2>
            <div class="right">
                <Arrow />
            </div>
        </a>
        <a href="/" data-sveltekit-prefetch="" class="l-word container">
            <div class="l-line"></div> 
            <div class="left">
                <Line />
            </div> 
            <h2 class="h5 sans">焼酎野郎のライン</h2>
            <div class="right">
                <Arrow />
            </div>
        </a>
        <div class="l-line"></div> 
    </div>
</div>


<style>

.Media .wrapper {margin-top: 3rem;}
.Media .l-word .left {width: 10.5rem;}
.Media .l-word .l-line {min-width: calc(100vw - var(--padding));}


@media screen and (min-width: 720px) {


    .Media .wrapper {
        width: 50vw;
        margin-left: auto;
        margin-right: 0;
        overflow: hidden;
        margin-top: 0;
    }

    .Media .wrapper .l-word .l-line {
        margin-left: -1rem;
        margin-bottom: 3.75rem;
    }

}



</style>