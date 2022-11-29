<script>
    import { slide } from 'svelte/transition';
    import Saos from "saos";
    import Logo from './Logo.svelte';
    import Menu from './Menu.svelte';

    let clicked = false;
	let isExpanded = false
	function clickHandler() {
		isExpanded = !isExpanded  
    }
	
</script>

<header>
    <div class="menu-sp">
        <a href="/">
            <span lang="en" class="h1 uppercase">ABOUT</span>
            <span class="h6">私たちが目指す焼酎の世界</span>
        </a>

        <a href="/products">
            <span lang="en" class="h1 uppercase">PRODUCTS</span>
            <span class="h6">焼酎の未来を切り開くプロダクト</span>
        </a>

        <a href="/">
            <span lang="en" class="h1 uppercase">JOURNAL</span>
            <span class="h6">焼酎の楽しみ方をご紹介</span>
        </a>
        <div class="container">
            <a href="/"><span lang="en" class="h3 uppercase">NEWS</span></a>
            <a href="/"><span lang="en" class="h3 uppercase">CONTACT</span></a>
            <a href="/"><span lang="en" class="h3 uppercase">MAIL MAGAZINE</span></a>
        </div>
        
        <div class="sns">
            <a href="https://www.facebook.com/shochux/"><svg xmlns="http://www.w3.org/2000/svg" width="8.984" height="17.3" viewBox="0 0 8.984 17.3"><path id="f" d="M362.482,2276.179v-7.891h2.649l.4-3.076h-3.045v-1.963c0-.89.247-1.5,1.524-1.5h1.628V2259a21.75,21.75,0,0,0-2.373-.121,3.705,3.705,0,0,0-3.955,4.065v2.268h-2.656v3.076h2.656v7.891Z" transform="translate(-356.651 -2258.879)" fill="#fff"/></svg></a>
            <a href="https://twitter.com/shochu_x"><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="18.607" height="15.12" viewBox="0 0 18.607 15.12"> <defs> <clipPath id="clip-path"> <rect id="Rectangle_456" data-name="Rectangle 456" width="18.607" height="15.121" transform="translate(0 0)" fill="#fff"/> </clipPath> </defs> <g id="Group_195" data-name="Group 195" transform="translate(0 0)" clip-path="url(#clip-path)"> <path id="Path_129" data-name="Path 129" d="M18.607,1.79a7.62,7.62,0,0,1-2.193.6A3.824,3.824,0,0,0,18.093.279a7.654,7.654,0,0,1-2.425.927,3.818,3.818,0,0,0-6.6,2.611,3.86,3.86,0,0,0,.1.869A10.837,10.837,0,0,1,1.3.7a3.824,3.824,0,0,0,1.182,5.1A3.81,3.81,0,0,1,.748,5.317v.048A3.818,3.818,0,0,0,3.81,9.108,3.819,3.819,0,0,1,2.8,9.242a3.887,3.887,0,0,1-.718-.068,3.822,3.822,0,0,0,3.566,2.651A7.656,7.656,0,0,1,.911,13.46,7.67,7.67,0,0,1,0,13.406a10.807,10.807,0,0,0,5.852,1.715A10.786,10.786,0,0,0,16.712,4.259q0-.248-.011-.494A7.768,7.768,0,0,0,18.607,1.79" transform="translate(0 0)" fill="#fff"/> </g></svg></a>
            <a href="https://www.instagram.com/shochu_x/"><svg xmlns="http://www.w3.org/2000/svg" width="17.3" height="17.3" viewBox="0 0 17.3 17.3"><g id="Group_41" data-name="Group 41" transform="translate(0)"><path id="Path_32" data-name="Path 32" d="M247.851,2276.179H240.4a4.929,4.929,0,0,1-4.924-4.924V2263.8a4.929,4.929,0,0,1,4.924-4.924h7.452a4.93,4.93,0,0,1,4.924,4.924v7.452A4.93,4.93,0,0,1,247.851,2276.179Zm-7.452-15.817a3.445,3.445,0,0,0-3.441,3.441v7.452a3.445,3.445,0,0,0,3.441,3.441h7.452a3.445,3.445,0,0,0,3.441-3.441V2263.8a3.445,3.445,0,0,0-3.441-3.441Z" transform="translate(-235.475 -2258.879)" fill="#fff"/></g><g id="Group_42" data-name="Group 42" transform="translate(4.22 4.22)"><path id="Path_33" data-name="Path 33" d="M257.449,2285.283a4.43,4.43,0,1,1,4.43-4.43A4.435,4.435,0,0,1,257.449,2285.283Zm0-7.376a2.947,2.947,0,1,0,2.947,2.947A2.95,2.95,0,0,0,257.449,2277.907Z" transform="translate(-253.019 -2276.424)" fill="#fff"/></g><g id="Group_43" data-name="Group 43" transform="translate(12.205 2.902)"><path id="Path_34" data-name="Path 34" d="M288.342,2272.009a1.065,1.065,0,1,1-1.065-1.065A1.064,1.064,0,0,1,288.342,2272.009Z" transform="translate(-286.213 -2270.944)" fill="#fff"/></g></svg></a>
            <a href="https://line.me/R/ti/p/%40479esysg"><svg xmlns="http://www.w3.org/2000/svg" width="20.459" height="19.494" viewBox="0 0 20.459 19.494"> <path id="Path_51" data-name="Path 51" d="M31.357,20.081c0-4.577-4.589-8.3-10.229-8.3S10.9,15.5,10.9,20.081c0,4.1,3.639,7.54,8.555,8.191.333.072.787.22.9.5a2.1,2.1,0,0,1,.033.925s-.119.722-.146.876c-.044.258-.205,1.011.886.552a33.008,33.008,0,0,0,8.037-5.94h0A7.38,7.38,0,0,0,31.357,20.081ZM17.123,22.805H15.091a.537.537,0,0,1-.536-.537V18.2a.536.536,0,1,1,1.072,0v3.528h1.5a.537.537,0,0,1,0,1.074Zm2.1-.537a.536.536,0,1,1-1.072,0V18.2a.536.536,0,1,1,1.072,0Zm4.893,0a.536.536,0,0,1-.965.322L21.07,19.754v2.515a.537.537,0,0,1-1.074,0V18.2a.536.536,0,0,1,.367-.509.528.528,0,0,1,.17-.027.539.539,0,0,1,.428.215l2.084,2.837V18.2a.537.537,0,0,1,1.073,0ZM27.407,19.7a.537.537,0,1,1,0,1.073h-1.5v.96h1.5a.537.537,0,1,1,0,1.073H25.375a.537.537,0,0,1-.536-.537V20.237h0V18.2a.537.537,0,0,1,.536-.536h2.032a.536.536,0,1,1,0,1.072h-1.5v.96h1.5Z" transform="translate(-10.898 -11.78)" fill="#fff"/></svg></a>
        </div>
    </div>


    <div class="site-header">
        <div class="banner">
            <div style="text-align: center;">2万円以上の購入で、送料無料</div>
        </div>
        <div class="main-header">
            <div class="home">
                <a href="/">
                    <svg xmlns="http://www.w3.org/2000/svg" width="134.843" height="33.006" viewBox="0 0 134.843 33.006"> <g id="Group_180" data-name="Group 180" transform="translate(2504 78.998)"> <path id="Path_30" data-name="Path 30" d="M126.488,77.349h-5.152v-.02a3.749,3.749,0,0,0,.392-1.68V71.683A3.715,3.715,0,0,0,121.336,70v-.02h4.649l.392,1.791-.08.031c-.534-.554-1.258-1.58-1.7-1.6l-1.7-.07v3.4h.865c.483,0,.906-.675,1.248-1.057h.09v2.275h-.09c-.332-.353-.755-1.017-1.248-1.017H122.9V77.2l1.791-.07c.824-.04,1.589-1.017,2.163-1.8l.081.03Z" transform="translate(-2581.143 -123.491)" fill="#fff"/> <path id="Path_31" data-name="Path 31" d="M144.134,71.68l-.09.031c-.684-1.49-1.389-1.943-2.083-1.943a1.034,1.034,0,0,0-1.1,1.127c0,.956.845,1.349,1.741,1.792.987.483,2.023,1.017,2.023,2.4,0,1.509-1.208,2.143-2.637,2.143a5.994,5.994,0,0,1-2.073-.393l-.2-1.862.081-.03c.785,1.448,1.56,2.083,2.475,2.083a1.287,1.287,0,0,0,1.359-1.378c0-.956-.734-1.439-1.56-1.842-1.046-.513-2.1-1.017-2.1-2.324,0-1.388,1.117-1.922,2.324-1.922a4.9,4.9,0,0,1,1.641.292Z" transform="translate(-2592.829 -123.227)" fill="#fff"/> <path id="Path_32" data-name="Path 32" d="M159.524,77.349h-1.962v-.02a3.226,3.226,0,0,0,.4-1.8V70.153l-1.1.04c-.443.02-1.177,1.167-1.7,1.891l-.081-.03.383-2.073h6.149L162,72.056l-.081.03c-.523-.724-1.257-1.871-1.7-1.891l-1.1-.04v5.374a3.13,3.13,0,0,0,.4,1.8Z" transform="translate(-2602.601 -123.491)" fill="#fff"/> <path id="Path_33" data-name="Path 33" d="M172.4,87.3a.674.674,0,1,1,1.348,0,.674.674,0,1,1-1.348,0" transform="translate(-2613.606 -134.066)" fill="#fff"/> <path id="Path_34" data-name="Path 34" d="M182.606,77.084v-.151c2.787-2.445,3.623-3.814,3.623-5.364,0-1.1-.453-1.8-1.308-1.8s-1.319.775-1.872,1.832l-.1-.041.262-1.67a4.653,4.653,0,0,1,1.731-.322c1.721,0,2.455.845,2.455,1.973,0,1.479-1.247,2.787-3.612,4.538h1.922a2.2,2.2,0,0,0,1.811-.875l.08.03-.563,1.852Z" transform="translate(-2620.097 -123.227)" fill="#fff"/> <path id="Path_35" data-name="Path 35" d="M198.724,73.4c0-2.184,1.318-3.835,3.009-3.835s3.029,1.651,3.029,3.835-1.339,3.833-3.029,3.833-3.009-1.65-3.009-3.833m4.76,0c0-2.084-.433-3.633-1.751-3.633-1.3,0-1.731,1.549-1.731,3.633s.432,3.632,1.731,3.632,1.751-1.55,1.751-3.632" transform="translate(-2630.345 -123.226)" fill="#fff"/> <path id="Path_36" data-name="Path 36" d="M216.2,77.084v-.151c2.787-2.445,3.623-3.814,3.623-5.364,0-1.1-.453-1.8-1.308-1.8s-1.319.775-1.872,1.832l-.1-.041.262-1.67a4.653,4.653,0,0,1,1.731-.322c1.721,0,2.455.845,2.455,1.973,0,1.479-1.247,2.787-3.612,4.538H219.3a2.2,2.2,0,0,0,1.811-.875l.08.03-.563,1.852Z" transform="translate(-2641.453 -123.227)" fill="#fff"/> <path id="Path_37" data-name="Path 37" d="M232.316,73.4c0-2.184,1.318-3.835,3.009-3.835s3.029,1.651,3.029,3.835-1.339,3.833-3.029,3.833-3.009-1.65-3.009-3.833m4.76,0c0-2.084-.433-3.633-1.751-3.633-1.3,0-1.731,1.549-1.731,3.633s.432,3.632,1.731,3.632,1.751-1.55,1.751-3.632" transform="translate(-2651.702 -123.226)" fill="#fff"/> <path id="Path_38" data-name="Path 38" d="M228.077.9c.941,1.557.992,1.582.992,3.717V7.874h-8.083V4.62c0-2.156.051-2.16.992-3.717V.862h-4.737V.9c.918,1.565.992,1.552.992,3.717V12.3c0,2.274-.075,2.152-.992,3.717v.042h4.737v-.042c-.941-1.557-.992-1.431-.992-3.717V8.878h8.083V12.3c0,2.3-.051,2.16-.992,3.717v.042h4.737v-.042c-.918-1.565-.993-1.422-.993-3.717V4.62c0-2.165.075-2.152.993-3.717V.862h-4.737Z" transform="translate(-2642.119 -79.546)" fill="#fff"/> <path id="Path_39" data-name="Path 39" d="M57.985.9c.942,1.557.992,1.582.992,3.717V7.874H50.9V4.62c0-2.156.051-2.16.993-3.717V.862H47.151V.9c.918,1.565.992,1.552.992,3.717V12.3c0,2.274-.075,2.152-.992,3.717v.042h4.737v-.042c-.941-1.557-.993-1.431-.993-3.717V8.878h8.083V12.3c0,2.3-.051,2.16-.992,3.717v.042h4.737v-.042C61.8,14.455,61.73,14.6,61.73,12.3V4.62c0-2.165.075-2.152.992-3.717V.862H57.985Z" transform="translate(-2533.978 -79.546)" fill="#fff"/> <path id="Path_40" data-name="Path 40" d="M109.044.006c-4.8,0-8.871,3.086-8.871,7.932,0,4.284,4.207,7.891,8.871,7.891s8.918-3.326,8.918-7.891S113.707.006,109.044.006m0,14.935c-3.724,0-5.461-3.1-5.461-7s1.737-7.1,5.461-7.1c3.747,0,5.508,3.2,5.508,7.1,0,3.924-1.76,7-5.508,7" transform="translate(-2567.688 -79.001)" fill="#fff"/> <path id="Path_41" data-name="Path 41" d="M338.936,13.176l-4.024-5.732.325-.383,2.355-2.939A9.274,9.274,0,0,1,341.178.916V.862H336.6V.9c.889,1.535.989,1.517-.731,3.7l-1.486,1.881-.087.1L332.213,3.6c-1.155-1.62-1.427-1.7-.4-2.7V.862h-5.827V.928c1.861.99,1.713,1.1,2.905,2.8L332.246,8.5l-.3.377-3.01,3.926c-1.339,1.73-1.44,2.058-3.35,3.206v.054h4.579v-.042c-.845-1.391-1.219-1.419.5-3.7l2.212-2.92,2.745,3.918c1.155,1.62,1.427,1.7.4,2.7v.042h5.827V16c-1.866-.991-1.685-1.1-2.905-2.82" transform="translate(-2710.999 -79.546)" fill="#fff"/> <path id="Path_42" data-name="Path 42" d="M289.806,12.33a1.859,1.859,0,0,0-2.408,1.183,1.988,1.988,0,0,0,1.007,2.287,2.909,2.909,0,0,1-2.2-1.806,8.794,8.794,0,0,1-.374-3.124l0-.006s0-.009,0-.014V4.994c0-2.374.106-2.36,1.735-4.091l0-.042h-4.728V.9c1.652,1.726,1.735,1.721,1.735,4.091v5.877c0,2.492-1.412,4.568-4.446,4.568-2.3,0-4.013-1-4.013-4.382V4.62c0-2.212.062-2.333.895-3.717l.1-.042h-4.98V.9c.942,1.557.992,1.561.992,3.717v6.5c0,3.738,2.949,5.254,6.441,5.254,2.856,0,4.606-1.028,5.506-2.535a4.229,4.229,0,0,0,3.544,2.52,2.687,2.687,0,0,0,1.045-.125,2.125,2.125,0,0,0,.436-.22c.012-.008.025-.012.037-.02a2.278,2.278,0,0,0,.919-1.168,1.986,1.986,0,0,0-1.241-2.5" transform="translate(-2677.013 -79.546)" fill="#fff"/> <path id="Path_43" data-name="Path 43" d="M168.792,14.912c-3.685,0-5.474-2.983-5.474-6.994,0-4.043,1.662-7.1,5.545-7.1,3.022,0,4.1,1.155,6.8,4.305l.291-.042L175.294,1a20,20,0,0,0-6.119-1c-5.4,0-9.291,3.488-9.291,7.911,0,4.444,3.552,7.912,8.9,7.912a15.95,15.95,0,0,0,6.589-1.495l.672-4.212-.267-.035c-2.129,2.736-3.421,4.824-6.99,4.824" transform="translate(-2605.651 -79.001)" fill="#fff"/> <path id="Path_44" data-name="Path 44" d="M7.52,6.533c-2.122-.79-4.3-1.381-4.549-3.19A2.2,2.2,0,0,1,3.883,1.3,3.4,3.4,0,0,1,6.053.788C8.136.921,9.73,2.3,11.828,4.913l.245-.043L11.42.738A19.791,19.791,0,0,0,6.813,0C3.438-.064.547,1.208.547,3.968c0,2.976,2.391,4.077,4.847,5.012,2.026.754,5.113,1.324,5.113,3.441a2.487,2.487,0,0,1-1.28,2.214,3.722,3.722,0,0,1-2.276.4C4.521,14.76,2.777,12.765.22,10.154L0,10.2l.758,4.6a22.139,22.139,0,0,0,5.5,1.018,9.945,9.945,0,0,0,3.26-.317c2.072-.575,3.554-1.813,3.554-4.106,0-2.975-2.85-3.872-5.55-4.869" transform="translate(-2504 -78.997)" fill="#fff"/> </g></svg>
                </a>
            </div>
            <div class="menu"> 
                <ul class="pc"> 
                    <li><a href="/" lang="en">About</a></li>
                    <li><a href="/products" lang="en">Products</a></li>
                    <li><a href="/" lang="en">Journal</a></li>
                    <li><a href="/" lang="en">News</a></li>
                </ul> 
                <div class="sp">
                    <button type="button" class="menu-btn">
                        <svg xmlns="http://www.w3.org/2000/svg" width="22" height="15" > <g id="Group_36" data-name="Group 36" transform="translate(0)"> 
                            <path class="line-1" d="M2.708,18.394a1.224,1.224,0,0,1-.5-1.148c-.016-.9-.032-3.64-.032-7.979,0-4.368.016-7.083.032-7.979A1.224,1.224,0,0,1,2.708.14L2.692,0A10.541,10.541,0,0,1,1.354.084,10.541,10.541,0,0,1,.016,0L0,.14A1.221,1.221,0,0,1,.5,1.288c.016.9.032,3.612.032,7.979,0,4.34-.016,7.083-.032,7.979A1.221,1.221,0,0,1,0,18.394l.016.14a10.54,10.54,0,0,1,1.338-.084,10.54,10.54,0,0,1,1.338.084Z" transform="translate(18.534) rotate(90)" fill="#f0f0f0"/>
                            <path class="line-2" d="M2.708,18.394a1.224,1.224,0,0,1-.5-1.148c-.016-.9-.032-3.64-.032-7.979,0-4.368.016-7.083.032-7.979A1.224,1.224,0,0,1,2.708.14L2.692,0A10.541,10.541,0,0,1,1.354.084,10.541,10.541,0,0,1,.016,0L0,.14A1.221,1.221,0,0,1,.5,1.288c.016.9.032,3.612.032,7.979,0,4.34-.016,7.083-.032,7.979A1.221,1.221,0,0,1,0,18.394l.016.14a10.54,10.54,0,0,1,1.338-.084,10.54,10.54,0,0,1,1.338.084Z" transform="translate(18.534 5.314) rotate(90)" fill="#f0f0f0"/> 
                            <path class="line-3" d="M2.708,18.394a1.224,1.224,0,0,1-.5-1.148c-.016-.9-.032-3.64-.032-7.979,0-4.368.016-7.083.032-7.979A1.224,1.224,0,0,1,2.708.14L2.692,0A10.541,10.541,0,0,1,1.354.084,10.541,10.541,0,0,1,.016,0L0,.14A1.221,1.221,0,0,1,.5,1.288c.016.9.032,3.612.032,7.979,0,4.34-.016,7.083-.032,7.979A1.221,1.221,0,0,1,0,18.394l.016.14a10.54,10.54,0,0,1,1.338-.084,10.54,10.54,0,0,1,1.338.084Z" transform="translate(18.534 10.628) rotate(90)" fill="#f0f0f0"/>      
                            </g>
                        </svg>
                    </button>
                </div>
            </div>
            <div class="shop"> 
                <a href="/">
                    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 18 18"><path id="Path_131" data-name="Path 131" d="M12.26,9.365a5.262,5.262,0,1,0-6.517,0A8.264,8.264,0,0,0,0,17.222V18H1.546v-.778a6.706,6.706,0,0,1,6.7-6.7h.735l.02,0H9l.02,0h.724a6.706,6.706,0,0,1,6.7,6.7V18H18v-.778a8.262,8.262,0,0,0-5.74-7.857M9,8.97A3.708,3.708,0,1,1,9,1.554H9A3.708,3.708,0,0,1,9,8.97" fill="#fff"/></svg>                          
                </a>     
                <a href="/">
                    <svg xmlns="http://www.w3.org/2000/svg" width="17.501" height="18" viewBox="0 0 17.501 18"><path id="Path_130" data-name="Path 130" d="M17.491,12.223,16.71,0H.778L.012,12.209h0a5.329,5.329,0,0,0,4.777,5.773A3.3,3.3,0,0,0,5.14,18h7.221v0A5.29,5.29,0,0,0,17.5,12.582c0-.119,0-.239-.01-.358M12.169,1.942a3.52,3.52,0,0,1-3.417,3.6h0a3.514,3.514,0,0,1-3.417-3.6V1.554h6.835ZM5.29,5.593A4.735,4.735,0,0,0,8.751,7.1a5.037,5.037,0,0,0,4.894-5.158V1.558h1.7l.689,10.761c.008.09.008.179.008.267a3.769,3.769,0,0,1-3.667,3.856H5.142c-.081,0-.165,0-.248-.008a3.8,3.8,0,0,1-3.409-4.117L2.163,1.554H3.855v.391A5.263,5.263,0,0,0,5.29,5.593" transform="translate(0)" fill="#fff"/></svg>                          
                </a> 
            </div>
        </div>
    </div>
</header>
<!--
<header class="top">
    <Saos animation={"header-logo 1.5s cubic-bezier(0.3, 0, 0.7, 1) both"} once={true}>
        <a href="/" class="logo"><Logo /></a>
    </Saos>
    <Saos animation={"header-logo 1.5s cubic-bezier(0.3, 0, 0.7, 1) both"} once={true}>
        <div class="button menu-button h6" 
            class:clicked={clicked} 
            on:click="{() => clicked = !clicked}"
            on:click|preventDefault={clickHandler}
        >
            <span></span>
            <span></span>
        </div>
    </Saos>
</header>
-->

    {#if isExpanded}
    <Menu />
    {/if}



<style>

@keyframes -global-header-logo {
	0% {transform: translateY(-.25rem);opacity: 0;}
	100% {transform: translateX(0);opacity: 1;}
}


.site-header {
    width: 100%;
    display: flex;
    flex-direction: column;
    position: fixed;
    position: absolute;
    z-index: 98;
    padding: 1.5rem 6.5vw 1rem;
}
.site-header .main-header {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 2rem 0 0;
}
.site-header .home svg {
    margin-top: -0.2rem;
    width: 12.0rem;
}


header, .site-header, header path, header .banner * {
    /*transition: all .7s cubic-bezier(.6,0,.4,1);*/
    transition: all 1s cubic-bezier(.3,.1,.1,1);
}

.site-header.scrolled {
    background-color: var(--backgroundColor);
    padding: .75rem 6.5vw .9rem;
    box-shadow: 0 10px 25px 0 rgba(0, 0, 0, 0.05);
}
.site-header.scrolled .main-header {padding-top: .8rem;}
.site-header.scrolled .home svg {
    width: 10rem;
    height: 3rem;
}

#Index .site-header *, #Products .site-header *, .Product .site-header *,
#Cocktails .site-header *, .site-header * {
    color: var(--backgroundColor);
    fill: var(--backgroundColor);
}

#Index .site-header.scrolled *, #Products .site-header.scrolled *, .Product .site-header.scrolled *,
#Cocktails .site-header.scrolled *, .site-header.scrolled * {
    color: var(--textColor);
    fill: var(--textColor);
}

.site-header .shop {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
.site-header .shop a {margin-left: 1.8rem;}

.banner {width: 100%;}
.banner .swiper-slide {
    opacity: 0 !important;
    text-align: center;}
.banner .swiper-slide-active {opacity: 1 !important;}

header .menu-sp {
    width: 100%;
    min-height: 100vh;
    min-height: 100lvh;
    padding: 12rem 6.5vw 0;
    background-color: var(--darkColor);
    position: fixed;
    z-index: -1;
    opacity: 0;
    transition: opacity .4s cubic-bezier(.3,.1,.1,1);
}
html.is-active {overflow: hidden;}
header .menu-sp * {color: var(--backgroundColor);}
header .menu-sp a, header .menu-sp span {display: block;}
header .menu-sp a {margin-bottom: 2.3rem;}

header.is-active .menu-sp {
    display: block;
    opacity: 1;
    z-index: 98;
    transition: opacity .4s cubic-bezier(.3,.1,.1,1);
}

header .menu-sp .sns {display: flex;position: absolute;top: auto;bottom: 4rem;}
header.is-active .menu-sp .sns * {fill: var(--backgroundColor);}
header.is-active .site-header {background-color: var(--darkColor);box-shadow: none;}
header.is-active .site-header * {color: var(--backgroundColor);fill: var(--backgroundColor) !important;}


header .menu-sp a {opacity: 0;}
header.is-active .menu-sp a {opacity: 1;margin-bottom: 3rem;}
header .menu-sp .sns a {margin-right: 2.2rem;}
header.is-active .menu-sp .sns a {margin-right: 2.5rem;}
header .menu-sp .container a {margin-bottom: 1.5rem;}

header.is-active .menu .menu-btn .line-2 {opacity: 0;}
header.is-active .menu .menu-btn .line-1 {transform: translateX(12.8px) rotateZ(45deg);}
header.is-active .menu .menu-btn .line-3 {transform: translateY(2px) rotateZ(-45deg);}




@media screen and (max-width: 480px) {


    .site-header .main-header .home {order: 2; height: 3rem;}
    .site-header .main-header .menu {order: 1;}
    .site-header .main-header .shop {order: 3;}
    .site-header .main-header .menu, header .main-header .shop {width: 10rem;}
}



@media screen and (min-width: 720px) {
    
.site-header {padding: 5rem 9vw 4rem;}
.site-header .shop, header .home {width: 15rem}

.site-header .home svg {
    transform: scale(1.2);
    transform-origin: bottom left;
}
.site-header ul li {
    display: inline;
    margin: 0 2rem;
}
.site-header ul li a {font-size: 1.6rem;}

}
</style>
