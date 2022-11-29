<script>
    import Arrow from '../components/Arrow.svelte';
    import NewsLetter from '../components/NewsLetter.svelte';
    import Media from '../components/Media.svelte';
</script>

<main>
    <section id="iFirst">
        <div class="wrapper">
            <div class="visuals swiper">
                <div class="visual visual-1"></div>
                <a href="/products" class="button">商品をみる</a>
            </div>
            <div class="info white">
                <h1 class="h1">日々に豊かさを<br>添える焼酎</h1>
            </div>
        </div>
    </section>    

    <section id="iNews">
        <div class="l-section-head" lang="en">News</div>
        <h1 class="l-section-head">イベント情報やお知らせ</h1>
        <div class="wrapper">
            <a href="/" data-sveltekit-prefetch="" class="l-word container">
                <div class="left">
                    <div class="l-line"></div> 
                    <div class="h6 date" lang="en">8th October 2022</div> 
                    <h2 class="h5 sans">東急渋谷フードショーにて、テイスティングセミナーを行いました</h2>
                </div> 
                <div class="right">
                    <Arrow />
                </div>
            </a>
            <a href="/" data-sveltekit-prefetch="" class="l-word container">
                <div class="left">
                    <div class="l-line"></div> 
                    <div class="h6 date" lang="en">8th October 2022</div> 
                    <h2 class="h5 sans">フレンチオークリザーブド（NK麦759）を10/17 (月) 21時から販売開始しました。</h2>
                </div> 
                <div class="right">
                    <Arrow />
                </div>
            </a>
            <a href="/" data-sveltekit-prefetch="" class="l-word container">
                <div class="left">
                    <div class="l-line"></div> 
                    <div class="h6 date" lang="en">8th October 2022</div> 
                    <h2 class="h5 sans">東急渋谷フードショーにて、テイスティングセミナーを行いました</h2>
                </div> 
                <div class="right">
                    <Arrow />
                </div>
            </a>
            <div class="l-line"></div> 
        </div>
    </section>


    <section id="iArrival">
        <div class="l-section-head" lang="en">Limited Series</div>
        <h1 class="l-section-head">限定シリーズ</h1>
        <div class="wrapper">
            <a href="/" class="l-big-card">
                <img src="../image/scx_nk759.webp" alt="">
                <div class="info">
                    <h2 class="h2" lang="en">NK麦759</h2>
                    <p class="h6">French Oak Reservedで熟成を行なった
                        ブランデーを思わせるダークスピリッツに
                        仕上がった一本。</p>
                </div>
                <div class="shop">
                    <div class="container">
                        <h3 class="h4" lang="en">¥13,800</h3>
                        <a href="/" class="h4">購入する</a>
                    </div>
                </div>
            </a>
            <a href="/" class="l-big-card">
                <img src="../image/scx_nk025.jpg" alt="">
                <div class="info">
                    <h2 class="h2" lang="en">NK麦 025</h2>
                    <p class="h6">French Oak Reservedで熟成を行なった
                        ブランデーを思わせるダークスピリッツに
                        仕上がった一本。</p>
                </div>
                <div class="shop">
                    <div class="container">
                        <h3 class="h4" lang="en">¥18,500</h3>
                        <a href="/" class="h4">購入する</a>
                    </div>
                </div>
            </a>
        </div>
    </section>

    <section id="iProduct">
        <div class="l-section-head" lang="en">Daily Series</div>
        <h1 class="l-section-head">デイリーシリーズ</h1>
        <div class="wrapper l-small-container">
            <a href="/" class="l-small-card">
                <div class="container l-overlay">
                    <div class="h5 white cat">米焼酎 40%</div>
                    <img src="../image/scx_nagomi.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">和深 - Nagomi</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥7,300</h5>
                </div>
            </a>
            <a href="/" class="l-small-card">
                <div class="container l-overlay">
                    <div class="h5 white cat">スピリッツ 58%</div>
                    <img src="../image/scx_rinwa.webp" alt="">
                    <div class="limited">限定471本</div>
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">凜和 - Rinwa</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥27,500</h5>
                </div>
            </a>
            <a href="/" class="l-small-card">
                <div class="container l-overlay">
                    <div class="h5 white cat">麦焼酎 43%</div>
                    <img src="../image/scx_kiraboshi.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">煌星 - Kiraboshi</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥9,500</h5>
                </div>
            </a>
            <a href="/" class="l-small-card">
                <div class="container l-overlay">
                    <div class="h5 white cat">麦焼酎 40%</div>
                    <img src="../image/scx_kizuna.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">希継奈 - Kizuna</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥6,800</h5>
                </div>
            </a>
        </div>
        <a href="/products" class="h4">全ての商品をみる</a>
    </section>
    
    <section id="iCraftman" class="white">
        <div class="l-section-head" lang="en">Craftsmanship</div>
        <h1 class="l-section-head">焼酎にかける想い</h1>
        <div>
            <div class="box">
                <h2 class="h3 pc">我々が目指す焼酎の未来</h2>
                <p>数百年の時を経て、異文化が複雑にクロスし、個性と多様性のあるスピリッツに昇華された焼酎。その奥深い伝統に独創的なコンセプトを融合することで、焼酎の再定義とエクスペリエンスの創造に挑み続けます。</p>
            </div>
            <div class="box pc">
                <h2 class="h3">お客様へ届ける価値</h2>
                <p>焼酎とは麹による日本の醗酵技術と1回蒸溜によってもたらされる、世界でも類を見ないフレーバーをもつスピリッツ。 SHOCHU Xの商品は全て、代表の橋本が九州各地の選りすぐりの酒蔵より原酒を厳選又はブレンドしています。<br><br>独創的なコンセプトと洗練されたクリエイティブ、現代風の飲み方を提案し、今までの概念を覆す、唯一無二の焼酎体験を愉しんでいただければと思います。</p>
            </div>
        </div>
        <div class="wrapper">
            <div class="container l-overlay">
                <img src="../image/crft1.webp" alt="">
                <div class="box1 h4">01 ー</div>
                <div class="box2">
                    <h2 class="h2 l-pixel-3">自然との共存<br>大地の育み</h2>
                    <h3 class="h6 l-pixel-2" lang="en">Respect the nature</h3>
                </div>
            </div>
            <div class="container l-overlay">
                <img src="../image/crft2.webp" alt="">
                <div class="box1 h4">02 ー</div>
                <div class="box2">
                    <h2 class="h2 l-pixel-3">麹の蒸溜酒であることの<br>誇りと自信</h2>
                    <h3 class="h6 l-pixel-2" lang="en">Confidence in being a <br>distilled with aspergillus</h3>
                </div>
            </div>
            <div class="container l-overlay">
                <img src="../image/crft3.webp" alt="">
                <div class="box1 h4">03 ー</div>
                <div class="box2">
                    <h2 class="h2 l-pixel-3">焼酎の強みを最大限<br>活かした長期間熟成</h2>
                    <h3 class="h6 l-pixel-2" lang="en">Long-term aging to bring <br>the best out of shochu</h3>
                </div>
            </div>
        </div>
    </section>

    <section id="iCocktail">
        <div class="l-section-head" lang="en">Shochu Cocktail</div>
        <h1 class="l-section-head">焼酎カクテル</h1>
        <div class="wrapper l-grid-3">
            <a href="/" class="container">
                <img src="../image/c1.webp" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
            <a href="/" class="container">
                <img src="../image/c3.webp" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
            <a href="/" class="container">
                <img src="../image/c5.jpg" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
        </div>
        <a href="/products" class="h4">他のカクテルをみる</a>
    </section>


    <section id="iLetter">
        <NewsLetter />
    </section>
    <section id="iMedia">
        <Media />
    </section>

</main>



<style>

#iFirst h1 {letter-spacing: .2em;}
#iFirst .visuals {
    width: 100vw; 
    margin-left: calc(-1 * var(--padding));}
#iFirst .visuals .visual {
    width: 100vw;
    min-height: calc(var(--vh, 1vh) * 100);
    background-size: cover;
    background-position: center;
}
#iFirst .wrapper {position: relative;}
#iFirst .wrapper .info {
    position: absolute;
    top: 50%;
    bottom: auto;
    transform: translateY(-50%);
    z-index: 1;
}


#iNews .wrapper {margin-top: 2.5rem;}
#iNews .wrapper h2 {
    font-size: 1.25rem;
    line-height: 1.75;
}
#iNews .wrapper .l-word .date {opacity: .5;}


#iArrival .wrapper {margin-top: 2rem;}
#iArrival .wrapper img {aspect-ratio: 10/9;}
#iArrival .wrapper .info {
    width: 65%;
    padding-top: 3rem;
}
#iArrival .wrapper .info p {
    opacity: .75;
    line-height: 1.8;
}
#iArrival .wrapper .shop .container {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    padding-right: var(--padding);
}

#iProduct .wrapper {margin-top: 3rem;}
#iProduct .l-small-card {margin-bottom: 6rem;}
#iProduct .l-overlay img {
    width: 100%;
    margin-left: 0;
}





#iCraftman {
    width: 100vw;
    margin-left: calc(-1 * var(--padding));
    padding: 8rem var(--padding) 0;
    background-color: var(--darkColor);
}
#iCraftman p {margin-top: 2rem;}
#iCraftman .wrapper {margin-top: 4rem;}
#iCraftman .l-overlay img {
    aspect-ratio: 5/3;
    filter: brightness(.8) contrast(1);
}
#iCraftman .l-overlay h3 {opacity: .75;}


#iCocktail .wrapper {margin-top: 3rem;}
#iCocktail .container {margin-bottom: 6rem;}
#iCocktail .container img {
    width: calc(100vw - var(--padding));
    width: 100%;
    border-top-left-radius: .5rem;
    border-top-right-radius: .5rem;
    aspect-ratio: 7/5;
}
#iCocktail .container h2 {
    margin-top: 1rem;
    font-size: 2.2rem;
}
#iCocktail .container h3 {opacity: .5;}


@media screen and (min-width: 720px) {

    #iFirst .visuals {margin-left: calc(-1 * var(--pcPadding));}
    #iFirst .wrapper .info {
        top: 50%;
        bottom: auto;
        transform: translateY(-50%);
    }
    #iFirst .info h1 {font-size: 3.5rem;}
    
    #iNews .wrapper {
        width: 50vw;
        margin-left: auto;
        margin-right: 0;
        overflow: hidden;
        margin-top: 0;
    }
    #iNews .wrapper h2 {font-size: 1.5rem;}
    #iNews .l-word .left {width: 92.5%;}

    #iArrival .wrapper {
        width: 60vw;
        margin-top: -4rem;
        margin-left: auto;
        margin-right: 0;
        display: flex;
        justify-content: space-between;
    }
    #iArrival .wrapper a {width: calc(50% - (10rem / 3)/2);}
    #iArrival .wrapper a img {aspect-ratio: 4/3;}
    #iArrival .wrapper a img {
        border-top-left-radius: 1rem;
        border-top-right-radius: 1rem;
    }
    #iArrival .wrapper a .info, #iArrival .wrapper a .shop {padding-left: 3rem;}
    #iArrival .wrapper .shop .container {padding-right: 2.5rem;}
    #iArrival .wrapper .shop .container a {width: fit-content;}
    #iArrival .wrapper .info h2 {font-size: 2.2rem;}
    #iArrival .wrapper .info p {line-height: 1.7;}
    #iArrival .l-big-card img {margin-left: 0;}

    #iProduct .l-small-card {width: calc(25% - 2.5rem);}
    #iProduct .l-small-card img {aspect-ratio: 8/7;}
    #iProduct .limited {right: 1.5rem; bottom: 1rem;}


    #iCraftman {
        margin-left: calc(-1 * var(--pcPadding));
        padding: 12.5rem var(--pcPadding) 0;
    }
    #iCraftman .box {
        margin-top: 10rem;
        display: flex;
        justify-content: space-between;
        align-items: flex-start;
    }
    #iCraftman .box p {width: 65%; margin-top: 1rem;}
    #iCraftman .wrapper {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;

        width: 100vw;
        margin-top: 12rem;
        margin-left: calc(-1 * var(--pcPadding));
        transform: translateY(0);
    }
    #iCraftman .wrapper .container {width: 33.333%;}
    #iCraftman .wrapper .container img {
        width: 100%;
        aspect-ratio: 1;
        margin-left: 0;
    }


    #iCocktail .wrapper {margin-top: 6rem;}
    #iCocktail .l-grid-3 {gap: calc(10rem / 3);}
    #iCocktail .container img {aspect-ratio: 5/4;}

    

}



</style>