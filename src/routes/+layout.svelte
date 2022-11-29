<script>
import { page } from '$app/stores';
import PageTransition from '../components/PageTransition.svelte';  
import Header from '../components/Header.svelte';
import Footer from '../components/Footer.svelte';


import { afterNavigate, beforeNavigate } from '$app/navigation';


/** @type {import('./$types').LayoutData} */
    export let data;
    $: currentRoute = $page.url.pathname; 
</script>
  
<svelte:head>
  <link rel="stylesheet" href="../css/base.css?ver=1.0.1">
  <link rel="stylesheet" href="../css/main.css?ver=1.0.1">
  <link rel="stylesheet" href="../css/layout.css?ver=1.0.2">
  <link rel="stylesheet" href="../css/var.css?ver=1.0.2">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Shippori+Mincho:wght@400;500&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://use.typekit.net/frp6udl.css">
  <script>
    (function(d) {
      var config = {
        kitId: 'ybz8pts',
        scriptTimeout: 3000,
        async: true
      },
      h=d.documentElement,t=setTimeout(function(){h.className=h.className.replace(/\bwf-loading\b/g,"")+" wf-inactive";},config.scriptTimeout),tk=d.createElement("script"),f=false,s=d.getElementsByTagName("script")[0],a;h.className+=" wf-loading";tk.src='https://use.typekit.net/'+config.kitId+'.js';tk.async=true;tk.onload=tk.onreadystatechange=function(){a=this.readyState;if(f||a&&a!="complete"&&a!="loaded")return;f=true;clearTimeout(t);try{Typekit.load(config)}catch(e){}};s.parentNode.insertBefore(tk,s)
    })(document);
  </script>
</svelte:head>
  

  <!-- 2. Pass the `url` prop to the `PageTransition` component, causing it to re-render when the page changes -->
  <PageTransition pathname={data.pathname}>
    <Header></Header>
      <slot />
    <Footer></Footer>
  </PageTransition>
  

  