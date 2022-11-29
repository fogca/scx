<div class="NewsLetter">
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
</div>

<style>

.NewsLetter .l-overlay img {height: 100%;}
.NewsLetter .box1 {
    padding: 6rem 0;
    margin-left: calc(-1 * var(--padding));
}
.NewsLetter .container {
    width: 80%;
    margin: 0 auto;
    padding: 8rem 4rem 6rem;
    background-color: rgba(255,255,255,0.6);
    text-align: center;
}
.NewsLetter .container h2 {margin-bottom: 1.5rem;}
.NewsLetter .container * {color: var(--textColor);}
.NewsLetter .container form {
    width: 92.5%;
    display: flex;
    justify-content: space-between;
    margin: 6rem auto 0;
    position: relative;
}
.NewsLetter .container form::after {
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
.NewsLetter .container form input {width: 80%;}


@media screen and (min-width: 720px) {

    .NewsLetter .box1 {
        padding: 12rem 0;
        justify-content: center;
        margin-left: calc(-1 * var(--pcPadding));
    }
    .NewsLetter .container {
        width: 45%;
        padding: 8rem 10% 8rem;
    }
    .NewsLetter .l-overlay img {height: 60rem;}

}

</style>