<script>
    import Arrow from '../components/Arrow.svelte';
    import IconNote from '../components/IconNote.svelte';
    import Podcast from '../components/Podcast.svelte';
    import Line from '../components/Line.svelte';
</script>

<main>
    <section id="iFirst">
        <div class="wrapper">
            <div class="visuals swiper">
                <div class="visual visual-1"></div>
                <a href="/collections/products" class="button">商品をみる</a>
            </div>
            <div class="info white">
                <h1 class="h1">日々に豊かさを添える<br>新たな焼酎のかたち。</h1>
            </div>
        </div>
    </section>    

    <section id="iNews">
        <div class="l-section-head" lang="en">News</div>
        <h1 class="l-section-head">イベント情報やお知らせ</h1>
        <div class="wrapper">
            <a href="/words/effor-221619/" data-sveltekit-prefetch="" class="l-word container">
                <div class="left">
                    <div class="l-line"></div> 
                    <div class="h6 date" lang="en">8th October 2022</div> 
                    <h2 class="h5 sans">東急渋谷フードショーにて、テイスティングセミナーを行いました</h2>
                </div> 
                <div class="right">
                    <Arrow />
                </div>
            </a>
            <a href="/words/effor-221619/" data-sveltekit-prefetch="" class="l-word container">
                <div class="left">
                    <div class="l-line"></div> 
                    <div class="h6 date" lang="en">8th October 2022</div> 
                    <h2 class="h5 sans">フレンチオークリザーブド（NK麦759）を10/17 (月) 21時から販売開始しました。</h2>
                </div> 
                <div class="right">
                    <Arrow />
                </div>
            </a>
            <a href="/words/effor-221619/" data-sveltekit-prefetch="" class="l-word container">
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
        <div class="l-section-head" lang="en">New Arrival</div>
        <h1 class="l-section-head">新作コレクション</h1>
        <div class="wrapper">
            <a href="/" class="l-big-card">
                <img src="../image/jds.jpg" alt="">
                <div class="info">
                    <h2 class="h2" lang="en">NK MUGI 759</h2>
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
                <img src="../image/jds.jpg" alt="">
                <div class="info">
                    <h2 class="h2" lang="en">NK MUGI 759</h2>
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
        </div>
    </section>

    <section id="iProduct">
        <div class="l-section-head" lang="en">Shochu Collection</div>
        <h1 class="l-section-head">焼酎コレクション</h1>
        <div class="wrapper l-small-container">
            <a href="/" class="l-small-card">
                <div class="container">
                    <div class="h5 white">米焼酎 40%</div>
                    <img src="../image/rinwa.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">和深 - Nagomi</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥7,300</h5>
                </div>
            </a>
            <a href="/" class="l-small-card">
                <div class="container">
                    <div class="h5 white">米焼酎 40%</div>
                    <img src="../image/rinwa.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">和深 - Nagomi</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥7,300</h5>
                </div>
            </a>
            <a href="/" class="l-small-card">
                <div class="container">
                    <div class="h5 white">米焼酎 40%</div>
                    <img src="../image/rinwa.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">和深 - Nagomi</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥7,300</h5>
                </div>
            </a>
            <a href="/" class="l-small-card">
                <div class="container">
                    <div class="h5 white">米焼酎 40%</div>
                    <img src="../image/rinwa.webp" alt="">
                </div>
                <div class="info">
                    <h3 class="h3" lang="en">和深 - Nagomi</h3>
                    <h4 class="h6 sans">お米の特徴であるコクや甘さを、しっかりとお楽しみいただける14年熟成の米焼酎です。</h4>
                    <h5 class="h4" lang="en">¥7,300</h5>
                </div>
            </a>
        </div>
    </section>
    
    <section id="iCraftman" class="white">
        <div class="l-section-head" lang="en">Craftsmanship</div>
        <h1 class="l-section-head">焼酎にかける想い</h1>
        <p>焼酎とは麹による日本の醗酵技術と1回蒸溜によってもたらされる、世界でも類を見ないフレーバーをもつスピリッツ。 SHOCHU Xの商品は全て、代表の橋本が九州各地の選りすぐりの酒蔵より原酒を厳選又はブレンドしています。<br><br>独創的なコンセプトと洗練されたクリエイティブ、現代風の飲み方を提案し、今までの概念を覆す、唯一無二の焼酎体験を愉しんでいただければと思います。</p>
        <div class="wrapper">
            <div class="container l-overlay">
                <img src="../image/philosophy_scene.webp" alt="">
                <div class="box1 h4">01 ー</div>
                <div class="box2">
                    <h2 class="h1a l-pixel-3">自然との共存<br>大地が育むいただき</h2>
                    <h3 class="h5 l-pixel-2" lang="en">Respect the nature</h3>
                </div>
            </div>
            <div class="container l-overlay">
                <img src="../image/philosophy_scene.webp" alt="">
                <div class="box1 h4">02 ー</div>
                <div class="box2">
                    <h2 class="h1a l-pixel-3">自然との共存<br>大地が育むいただき</h2>
                    <h3 class="h5 l-pixel-2" lang="en">Respect the nature</h3>
                </div>
            </div>
            <div class="container l-overlay">
                <img src="../image/craftsmanship_pc.webp" alt="">
                <div class="box1 h4">03 ー</div>
                <div class="box2">
                    <h2 class="h1a l-pixel-3">自然との共存<br>大地が育むいただき</h2>
                    <h3 class="h5 l-pixel-2" lang="en">Respect the nature</h3>
                </div>
            </div>
        </div>
    </section>

    <section id="iCocktail">
        <div class="l-section-head" lang="en">Shochu Cocktail</div>
        <h1 class="l-section-head">焼酎カクテル</h1>
        <div class="wrapper l-grid-3">
            <a href="/" class="container">
                <img src="../image/cocktail1.webp" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
            <a href="/" class="container">
                <img src="../image/cocktail2.webp" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
            <a href="/" class="container">
                <img src="../image/c2.webp" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
            <a href="/" class="container">
                <img src="../image/c2.webp" alt="">
                <h2 class="h3">1対3の煌星ソーダ</h2>
                <h3 lang="en" class="h6">1:3 Kiraboshi Soda</h3>
            </a>
        </div>
    </section>


    <section id="iLetter">
        <div class="l-overlay">
            <img src="../image/philosophy_scene.webp" alt="">
            <div class="box1">
                <div class="container">
                    <h2 class="h1a" lang="en">News Letter</h2>
                    <h3 class="h5">焼酎の飲み方・楽しみ方、新商品、
                        限定商品、イベント、キャンペーンなどの
                        情報をお届けします。
                    </h3>
                    <form method="post" action="/contact#footer-newsletter" id="footer-newsletter">
                        <input type="email" name="contact[email]" class="h5" aria-label="メールアドレス" placeholder="name@email.com" required="" lang="en">
                        <button type="submit" class="">登録</button>
                    </form>
                </div>
            </div>
        </div>
    </section>


    <section id="iMedia">
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
    </section>

</main>



<style>

#iNews, #iArrival, #iProduct, 
#iCraftman, #iCocktail, #iLetter,
#iMedia {margin-top: 8rem;}

#iFirst h1 {letter-spacing: .2em;}
#iFirst .visuals {
    width: 100vw; 
    margin-left: -6.5vw;}
#iFirst .visuals .visual {
    width: 100vw;
    min-height: calc(var(--vh, 1vh) * 100);
    background-size: cover;
    background-position: center;
}
#iFirst .wrapper {position: relative;}
#iFirst .wrapper .info {
    position: absolute;
    top: auto;
    bottom: 16rem;
    z-index: 1;
}
#iFirst a.button {
    letter-spacing: .2em;
    font-size: 1.5rem;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 1.3rem 3.6rem;
    margin-left: -6.5px;
    color: var(--darkColor);
    border-radius: 50px;
    background: var(--backgroundColor);
    position: absolute;
    z-index: 998;
    top: auto;
    bottom: 8rem;
    left: 0;
    opacity: 1;
}


#iNews .wrapper {margin-top: 4rem;}
#iNews .wrapper h2 {
    font-size: 1.35rem;
    line-height: 1.75;
}


#iArrival .wrapper {margin-top: 2rem;}
#iArrival .wrapper .l-big-card img {aspect-ratio: 1;}
#iArrival .wrapper .l-big-card .info {
    width: 65%;
    padding-top: 3rem;
}
#iArrival .wrapper .l-big-card .info p {
    opacity: .75;
    line-height: 1.8;
}
#iArrival .wrapper .l-big-card .shop .container {
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    padding-right: var(--padding);
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
    filter: brightness(0.7) contrast(1.1);
}
#iCraftman .l-overlay h3 {opacity: .75;}


#iCocktail .wrapper {margin-top: 3rem;}
#iCocktail .container {margin-bottom: 4rem;}
#iCocktail .container:nth-of-type(3),
#iCocktail .container:nth-of-type(4) {display: none;}
#iCocktail .container img {
    width: calc(100vw - var(--padding));
    border-top-left-radius: 1.2rem;
    aspect-ratio: 5/3;
}


#iLetter .l-overlay img {height: 100%;}
#iLetter .box1 {
    padding: 6rem 0;
    margin-left: calc(-1 * var(--padding));
}
#iLetter .container {
    width: 80%;
    margin: 0 auto;
    padding: 8rem 4rem 6rem;
    background-color: rgba(255,255,255,0.6);
    text-align: center;
}
#iLetter .container h2 {margin-bottom: 1.5rem;}
#iLetter .container * {color: var(--textColor);}
#iLetter .container form {
    width: 92.5%;
    display: flex;
    justify-content: space-between;
    margin: 6rem auto 0;
    position: relative;
}
#iLetter .container form::after {
    display: block;
    content: '';
    width: 100%;
    height: 1px;
    background-color: var(--textColor);
    position: absolute;
    top: auto;
    bottom: -.5rem;
    opacity: .5;
}
#iLetter .container form input {width: 80%;}


#iMedia .wrapper {margin-top: 3rem;}
#iMedia .l-word .left {width: 10.5rem;}
#iMedia .l-word .l-line {min-width: calc(100vw - var(--padding));}






#new-arrival {
    padding-top: 12rem;
    text-align: center;
}

#new-arrival .l-cards a.rice .image .tag  {background-color: var(--riceColor);}
#new-arrival .l-cards a.rice .image .tag::before {border-right: 0.5rem solid var(--riceColor);}

#foot-philosophy {padding: 6rem 0 6rem}
#foot-philosophy .l-section-head {
    margin-top: 6rem;
    padding-bottom: 3rem;
}
#foot-philosophy .wrapper p {margin: .5rem 0 2rem;}

#craftsmanship {
    display: grid;
    position: relative;
}

#craftsmanship .l-bgimg, #craftsmanship .wrapper {grid-area: 1/2;}
#craftsmanship .l-bgimg {filter: brightness(1);}
#craftsmanship .wrapper {
    width: 93.5%;
    padding: 10rem 0 8rem;
    position: relative;
}
#craftsmanship .wrapper iframe {width: 100%;}
#craftsmanship .wrapper a {margin: 3rem 0 1rem;}

#index-cocktail {
    padding: 12rem 0 8rem;
    text-align: center;
}

#index-journal .articles {text-align: center;}
#index-journal .article .info {
    width: 90%;
    margin: 2rem auto;
    text-align: center;
}
#index-journal .article .info h3 {margin-bottom: 1rem;}
#index-journal .article {margin-bottom: 6rem;}
#index-journal a.h5 {width: 100%;text-align: center;}







@media screen and (max-width: 480px) {
    #foot-philosophy .l-grid-2 div:nth-of-type(2) {margin: 6rem;}

    #iFirst.wrapper .info {top: 50%;}
    #iFirsta.button {
        font-size: 1.4rem;
        min-width: 14.5rem;
        min-height: 5rem;
        line-height: 2.8rem;
        padding: 1.2rem 3rem 1.1rem;
        top: auto;
        bottom: 6.5rem;
        left: 6.25vw;
        right: auto;
        opacity: .85;
    }
}

#cocktails-index img {
    aspect-ratio: 3/2;
    object-position: center;
}




@media screen and (min-width: 720px) {

#iFirst.visuals {margin-left: -9vw;}
#iFirst.wrapper .info {top: 52.5%;}

#new-arrival {padding: 18rem 0 12rem;}


#craftsmanship {margin-top: 6.5rem;}
#craftsmanship .wrapper {
    width: 37.5%;
    margin: 12.5rem 0 10rem;
}

#craftsmanship .wrapper h1 {margin-bottom: 2rem;}
#craftsmanship .wrapper a {margin: 8rem 0 2rem;}
#craftsmanship .wrapper iframe {margin-bottom: 2rem;}
#craftsmanship .wrapper .h7 {font-size: 1.25rem;}

#foot-philosophy .wrapper div {width: 95%;}
#foot-philosophy .l-section-head {margin-top: 12rem;}

#index-journal {margin-bottom: 7.5rem;}
#index-journal .article * {text-align: left;}
#index-journal .article h3 {font-size: 1.8rem;}
#index-journal .article h4 {font-size: 1.3rem;}
#index-journal .article .info {width: 95%;margin: 2rem 0;}


}






@media screen and (min-width: 720px) {

    #product-top img {
        margin-left: -9vw;
        aspect-ratio: auto;
        height: 100vh;
    }
    .l-shop {
        width: 65%;
        margin-left: auto;
        margin-right: auto;
        text-align: center;
    }
    #product-detail, #product-faq {
        width: 65%;
        margin-left: auto;
        margin-right: auto;
    }
    #product-detail img, #product-faq img {
        width: 100% !important;
        margin-left: 0 !important;
    }

}
</style>