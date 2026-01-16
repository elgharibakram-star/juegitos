# juegitos

<!DOCTYPE html>
<html lang="es">
<head><meta charset="UTF-8"><script>if(navigator.userAgent.match(/MSIE|Internet Explorer/i)||navigator.userAgent.match(/Trident\/7\..*?rv:11/i)){var href=document.location.href;if(!href.match(/[?&]nowprocket/)){if(href.indexOf("?")==-1){if(href.indexOf("#")==-1){document.location.href=href+"?nowprocket=1"}else{document.location.href=href.replace("#","?nowprocket=1#")}}else{if(href.indexOf("#")==-1){document.location.href=href+"&nowprocket=1"}else{document.location.href=href.replace("#","&nowprocket=1#")}}}}</script><script>(()=>{class RocketLazyLoadScripts{constructor(){this.v="1.2.6",this.triggerEvents=["keydown","mousedown","mousemove","touchmove","touchstart","touchend","wheel"],this.userEventHandler=this.t.bind(this),this.touchStartHandler=this.i.bind(this),this.touchMoveHandler=this.o.bind(this),this.touchEndHandler=this.h.bind(this),this.clickHandler=this.u.bind(this),this.interceptedClicks=[],this.interceptedClickListeners=[],this.l(this),window.addEventListener("pageshow",(t=>{this.persisted=t.persisted,this.everythingLoaded&&this.m()})),this.CSPIssue=sessionStorage.getItem("rocketCSPIssue"),document.addEventListener("securitypolicyviolation",(t=>{this.CSPIssue||"script-src-elem"!==t.violatedDirective||"data"!==t.blockedURI||(this.CSPIssue=!0,sessionStorage.setItem("rocketCSPIssue",!0))})),document.addEventListener("DOMContentLoaded",(()=>{this.k()})),this.delayedScripts={normal:[],async:[],defer:[]},this.trash=[],this.allJQueries=[]}p(t){document.hidden?t.t():(this.triggerEvents.forEach((e=>window.addEventListener(e,t.userEventHandler,{passive:!0}))),window.addEventListener("touchstart",t.touchStartHandler,{passive:!0}),window.addEventListener("mousedown",t.touchStartHandler),document.addEventListener("visibilitychange",t.userEventHandler))}_(){this.triggerEvents.forEach((t=>window.removeEventListener(t,this.userEventHandler,{passive:!0}))),document.removeEventListener("visibilitychange",this.userEventHandler)}i(t){"HTML"!==t.target.tagName&&(window.addEventListener("touchend",this.touchEndHandler),window.addEventListener("mouseup",this.touchEndHandler),window.addEventListener("touchmove",this.touchMoveHandler,{passive:!0}),window.addEventListener("mousemove",this.touchMoveHandler),t.target.addEventListener("click",this.clickHandler),this.L(t.target,!0),this.S(t.target,"onclick","rocket-onclick"),this.C())}o(t){window.removeEventListener("touchend",this.touchEndHandler),window.removeEventListener("mouseup",this.touchEndHandler),window.removeEventListener("touchmove",this.touchMoveHandler,{passive:!0}),window.removeEventListener("mousemove",this.touchMoveHandler),t.target.removeEventListener("click",this.clickHandler),this.L(t.target,!1),this.S(t.target,"rocket-onclick","onclick"),this.M()}h(){window.removeEventListener("touchend",this.touchEndHandler),window.removeEventListener("mouseup",this.touchEndHandler),window.removeEventListener("touchmove",this.touchMoveHandler,{passive:!0}),window.removeEventListener("mousemove",this.touchMoveHandler)}u(t){t.target.removeEventListener("click",this.clickHandler),this.L(t.target,!1),this.S(t.target,"rocket-onclick","onclick"),this.interceptedClicks.push(t),t.preventDefault(),t.stopPropagation(),t.stopImmediatePropagation(),this.M()}O(){window.removeEventListener("touchstart",this.touchStartHandler,{passive:!0}),window.removeEventListener("mousedown",this.touchStartHandler),this.interceptedClicks.forEach((t=>{t.target.dispatchEvent(new MouseEvent("click",{view:t.view,bubbles:!0,cancelable:!0}))}))}l(t){EventTarget.prototype.addEventListenerWPRocketBase=EventTarget.prototype.addEventListener,EventTarget.prototype.addEventListener=function(e,i,o){"click"!==e||t.windowLoaded||i===t.clickHandler||t.interceptedClickListeners.push({target:this,func:i,options:o}),(this||window).addEventListenerWPRocketBase(e,i,o)}}L(t,e){this.interceptedClickListeners.forEach((i=>{i.target===t&&(e?t.removeEventListener("click",i.func,i.options):t.addEventListener("click",i.func,i.options))})),t.parentNode!==document.documentElement&&this.L(t.parentNode,e)}D(){return new Promise((t=>{this.P?this.M=t:t()}))}C(){this.P=!0}M(){this.P=!1}S(t,e,i){t.hasAttribute&&t.hasAttribute(e)&&(event.target.setAttribute(i,event.target.getAttribute(e)),event.target.removeAttribute(e))}t(){this._(this),"loading"===document.readyState?document.addEventListener("DOMContentLoaded",this.R.bind(this)):this.R()}k(){let t=[];document.querySelectorAll("script[type=rocketlazyloadscript][data-rocket-src]").forEach((e=>{let i=e.getAttribute("data-rocket-src");if(i&&!i.startsWith("data:")){0===i.indexOf("//")&&(i=location.protocol+i);try{const o=new URL(i).origin;o!==location.origin&&t.push({src:o,crossOrigin:e.crossOrigin||"module"===e.getAttribute("data-rocket-type")})}catch(t){}}})),t=[...new Map(t.map((t=>[JSON.stringify(t),t]))).values()],this.T(t,"preconnect")}async R(){this.lastBreath=Date.now(),this.j(this),this.F(this),this.I(),this.W(),this.q(),await this.A(this.delayedScripts.normal),await this.A(this.delayedScripts.defer),await this.A(this.delayedScripts.async);try{await this.U(),await this.H(this),await this.J()}catch(t){console.error(t)}window.dispatchEvent(new Event("rocket-allScriptsLoaded")),this.everythingLoaded=!0,this.D().then((()=>{this.O()})),this.N()}W(){document.querySelectorAll("script[type=rocketlazyloadscript]").forEach((t=>{t.hasAttribute("data-rocket-src")?t.hasAttribute("async")&&!1!==t.async?this.delayedScripts.async.push(t):t.hasAttribute("defer")&&!1!==t.defer||"module"===t.getAttribute("data-rocket-type")?this.delayedScripts.defer.push(t):this.delayedScripts.normal.push(t):this.delayedScripts.normal.push(t)}))}async B(t){if(await this.G(),!0!==t.noModule||!("noModule"in HTMLScriptElement.prototype))return new Promise((e=>{let i;function o(){(i||t).setAttribute("data-rocket-status","executed"),e()}try{if(navigator.userAgent.indexOf("Firefox/")>0||""===navigator.vendor||this.CSPIssue)i=document.createElement("script"),[...t.attributes].forEach((t=>{let e=t.nodeName;"type"!==e&&("data-rocket-type"===e&&(e="type"),"data-rocket-src"===e&&(e="src"),i.setAttribute(e,t.nodeValue))})),t.text&&(i.text=t.text),i.hasAttribute("src")?(i.addEventListener("load",o),i.addEventListener("error",(function(){i.setAttribute("data-rocket-status","failed-network"),e()})),setTimeout((()=>{i.isConnected||e()}),1)):(i.text=t.text,o()),t.parentNode.replaceChild(i,t);else{const i=t.getAttribute("data-rocket-type"),s=t.getAttribute("data-rocket-src");i?(t.type=i,t.removeAttribute("data-rocket-type")):t.removeAttribute("type"),t.addEventListener("load",o),t.addEventListener("error",(i=>{this.CSPIssue&&i.target.src.startsWith("data:")?(console.log("WPRocket: data-uri blocked by CSP -> fallback"),t.removeAttribute("src"),this.B(t).then(e)):(t.setAttribute("data-rocket-status","failed-network"),e())})),s?(t.removeAttribute("data-rocket-src"),t.src=s):t.src="data:text/javascript;base64,"+window.btoa(unescape(encodeURIComponent(t.text)))}}catch(i){t.setAttribute("data-rocket-status","failed-transform"),e()}}));t.setAttribute("data-rocket-status","skipped")}async A(t){const e=t.shift();return e&&e.isConnected?(await this.B(e),this.A(t)):Promise.resolve()}q(){this.T([...this.delayedScripts.normal,...this.delayedScripts.defer,...this.delayedScripts.async],"preload")}T(t,e){var i=document.createDocumentFragment();t.forEach((t=>{const o=t.getAttribute&&t.getAttribute("data-rocket-src")||t.src;if(o&&!o.startsWith("data:")){const s=document.createElement("link");s.href=o,s.rel=e,"preconnect"!==e&&(s.as="script"),t.getAttribute&&"module"===t.getAttribute("data-rocket-type")&&(s.crossOrigin=!0),t.crossOrigin&&(s.crossOrigin=t.crossOrigin),t.integrity&&(s.integrity=t.integrity),i.appendChild(s),this.trash.push(s)}})),document.head.appendChild(i)}j(t){let e={};function i(i,o){return e[o].eventsToRewrite.indexOf(i)>=0&&!t.everythingLoaded?"rocket-"+i:i}function o(t,o){!function(t){e[t]||(e[t]={originalFunctions:{add:t.addEventListener,remove:t.removeEventListener},eventsToRewrite:[]},t.addEventListener=function(){arguments[0]=i(arguments[0],t),e[t].originalFunctions.add.apply(t,arguments)},t.removeEventListener=function(){arguments[0]=i(arguments[0],t),e[t].originalFunctions.remove.apply(t,arguments)})}(t),e[t].eventsToRewrite.push(o)}function s(e,i){let o=e[i];e[i]=null,Object.defineProperty(e,i,{get:()=>o||function(){},set(s){t.everythingLoaded?o=s:e["rocket"+i]=o=s}})}o(document,"DOMContentLoaded"),o(window,"DOMContentLoaded"),o(window,"load"),o(window,"pageshow"),o(document,"readystatechange"),s(document,"onreadystatechange"),s(window,"onload"),s(window,"onpageshow");try{Object.defineProperty(document,"readyState",{get:()=>t.rocketReadyState,set(e){t.rocketReadyState=e},configurable:!0}),document.readyState="loading"}catch(t){console.log("WPRocket DJE readyState conflict, bypassing")}}F(t){let e;function i(e){return t.everythingLoaded?e:e.split(" ").map((t=>"load"===t||0===t.indexOf("load.")?"rocket-jquery-load":t)).join(" ")}function o(o){function s(t){const e=o.fn[t];o.fn[t]=o.fn.init.prototype[t]=function(){return this[0]===window&&("string"==typeof arguments[0]||arguments[0]instanceof String?arguments[0]=i(arguments[0]):"object"==typeof arguments[0]&&Object.keys(arguments[0]).forEach((t=>{const e=arguments[0][t];delete arguments[0][t],arguments[0][i(t)]=e}))),e.apply(this,arguments),this}}o&&o.fn&&!t.allJQueries.includes(o)&&(o.fn.ready=o.fn.init.prototype.ready=function(e){return t.domReadyFired?e.bind(document)(o):document.addEventListener("rocket-DOMContentLoaded",(()=>e.bind(document)(o))),o([])},s("on"),s("one"),t.allJQueries.push(o)),e=o}o(window.jQuery),Object.defineProperty(window,"jQuery",{get:()=>e,set(t){o(t)}})}async H(t){const e=document.querySelector("script[data-webpack]");e&&(await async function(){return new Promise((t=>{e.addEventListener("load",t),e.addEventListener("error",t)}))}(),await t.K(),await t.H(t))}async U(){this.domReadyFired=!0;try{document.readyState="interactive"}catch(t){}await this.G(),document.dispatchEvent(new Event("rocket-readystatechange")),await this.G(),document.rocketonreadystatechange&&document.rocketonreadystatechange(),await this.G(),document.dispatchEvent(new Event("rocket-DOMContentLoaded")),await this.G(),window.dispatchEvent(new Event("rocket-DOMContentLoaded"))}async J(){try{document.readyState="complete"}catch(t){}await this.G(),document.dispatchEvent(new Event("rocket-readystatechange")),await this.G(),document.rocketonreadystatechange&&document.rocketonreadystatechange(),await this.G(),window.dispatchEvent(new Event("rocket-load")),await this.G(),window.rocketonload&&window.rocketonload(),await this.G(),this.allJQueries.forEach((t=>t(window).trigger("rocket-jquery-load"))),await this.G();const t=new Event("rocket-pageshow");t.persisted=this.persisted,window.dispatchEvent(t),await this.G(),window.rocketonpageshow&&window.rocketonpageshow({persisted:this.persisted}),this.windowLoaded=!0}m(){document.onreadystatechange&&document.onreadystatechange(),window.onload&&window.onload(),window.onpageshow&&window.onpageshow({persisted:this.persisted})}I(){const t=new Map;document.write=document.writeln=function(e){const i=document.currentScript;i||console.error("WPRocket unable to document.write this: "+e);const o=document.createRange(),s=i.parentElement;let n=t.get(i);void 0===n&&(n=i.nextSibling,t.set(i,n));const c=document.createDocumentFragment();o.setStart(c,0),c.appendChild(o.createContextualFragment(e)),s.insertBefore(c,n)}}async G(){Date.now()-this.lastBreath>45&&(await this.K(),this.lastBreath=Date.now())}async K(){return document.hidden?new Promise((t=>setTimeout(t))):new Promise((t=>requestAnimationFrame(t)))}N(){this.trash.forEach((t=>t.remove()))}static run(){const t=new RocketLazyLoadScripts;t.p(t)}}RocketLazyLoadScripts.run()})();</script>
	
	<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover" />		<meta name='robots' content='index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1' />
	<style>img:is([sizes="auto" i], [sizes^="auto," i]) { contain-intrinsic-size: 3000px 1500px }</style>
	
	<!-- This site is optimized with the Yoast SEO plugin v25.2 - https://yoast.com/wordpress/plugins/seo/ -->
	<title>Juegos Gratis Online - Juega en LudoRex</title><link rel="preload" data-rocket-preload as="style" href="https://fonts.googleapis.com/css?family=Rajdhani%3A400%2C500%2C600%2C700%7CTitillium%20Web%3A400%2C900&#038;display=swap" /><link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Rajdhani%3A400%2C500%2C600%2C700%7CTitillium%20Web%3A400%2C900&#038;display=swap" media="print" onload="this.media='all'" /><noscript><link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Rajdhani%3A400%2C500%2C600%2C700%7CTitillium%20Web%3A400%2C900&#038;display=swap" /></noscript>
	<meta name="description" content="¡Explora miles de juegos gratis de navegador! Juega al instante sin descargas, en cualquier dispositivo." />
	<link rel="canonical" href="https://ludorex.com/" />
	<meta property="og:locale" content="es_ES" />
	<meta property="og:type" content="website" />
	<meta property="og:title" content="Juegos Gratis Online - Juega en LudoRex" />
	<meta property="og:description" content="¡Explora miles de juegos gratis de navegador! Juega al instante sin descargas, en cualquier dispositivo." />
	<meta property="og:url" content="https://ludorex.com/" />
	<meta property="og:site_name" content="Juegos Gratis Online - Ludorex" />
	<meta property="article:modified_time" content="2025-04-09T12:07:21+00:00" />
	<meta property="og:image" content="https://ludorex.com/wp-content/uploads/2024/07/ludorex-logo-icono.png" />
	<meta property="og:image:width" content="512" />
	<meta property="og:image:height" content="512" />
	<meta property="og:image:type" content="image/png" />
	<meta name="twitter:card" content="summary_large_image" />
	<!-- / Yoast SEO plugin. -->


<link rel='dns-prefetch' href='//fonts.googleapis.com' />
<link rel='dns-prefetch' href='//fonts.gstatic.com' />
<link rel='dns-prefetch' href='//analytics.google.com' />
<link href='https://imagedelivery.net' rel='preconnect' />
<link href='https://fonts.gstatic.com' crossorigin rel='preconnect' />
<script type="rocketlazyloadscript" data-rocket-type="text/javascript">
/* <![CDATA[ */
window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.1.0\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.1.0\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/ludorex.com\/wp-includes\/js\/wp-emoji-release.min.js?ver=694c826a732620773805ac4a8aceb5f7"}};
/*! This file is auto-generated */
!function(i,n){var o,s,e;function c(e){try{var t={supportTests:e,timestamp:(new Date).valueOf()};sessionStorage.setItem(o,JSON.stringify(t))}catch(e){}}function p(e,t,n){e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(t,0,0);var t=new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data),r=(e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(n,0,0),new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data));return t.every(function(e,t){return e===r[t]})}function u(e,t,n){switch(t){case"flag":return n(e,"\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f","\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f")?!1:!n(e,"\ud83c\uddfa\ud83c\uddf3","\ud83c\uddfa\u200b\ud83c\uddf3")&&!n(e,"\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f","\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");case"emoji":return!n(e,"\ud83d\udc26\u200d\ud83d\udd25","\ud83d\udc26\u200b\ud83d\udd25")}return!1}function f(e,t,n){var r="undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?new OffscreenCanvas(300,150):i.createElement("canvas"),a=r.getContext("2d",{willReadFrequently:!0}),o=(a.textBaseline="top",a.font="600 32px Arial",{});return e.forEach(function(e){o[e]=t(a,e,n)}),o}function t(e){var t=i.createElement("script");t.src=e,t.defer=!0,i.head.appendChild(t)}"undefined"!=typeof Promise&&(o="wpEmojiSettingsSupports",s=["flag","emoji"],n.supports={everything:!0,everythingExceptFlag:!0},e=new Promise(function(e){i.addEventListener("DOMContentLoaded",e,{once:!0})}),new Promise(function(t){var n=function(){try{var e=JSON.parse(sessionStorage.getItem(o));if("object"==typeof e&&"number"==typeof e.timestamp&&(new Date).valueOf()<e.timestamp+604800&&"object"==typeof e.supportTests)return e.supportTests}catch(e){}return null}();if(!n){if("undefined"!=typeof Worker&&"undefined"!=typeof OffscreenCanvas&&"undefined"!=typeof URL&&URL.createObjectURL&&"undefined"!=typeof Blob)try{var e="postMessage("+f.toString()+"("+[JSON.stringify(s),u.toString(),p.toString()].join(",")+"));",r=new Blob([e],{type:"text/javascript"}),a=new Worker(URL.createObjectURL(r),{name:"wpTestEmojiSupports"});return void(a.onmessage=function(e){c(n=e.data),a.terminate(),t(n)})}catch(e){}c(n=f(s,u,p))}t(n)}).then(function(e){for(var t in e)n.supports[t]=e[t],n.supports.everything=n.supports.everything&&n.supports[t],"flag"!==t&&(n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&n.supports[t]);n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&!n.supports.flag,n.DOMReady=!1,n.readyCallback=function(){n.DOMReady=!0}}).then(function(){return e}).then(function(){var e;n.supports.everything||(n.readyCallback(),(e=n.source||{}).concatemoji?t(e.concatemoji):e.wpemoji&&e.twemoji&&(t(e.twemoji),t(e.wpemoji)))}))}((window,document),window._wpemojiSettings);
/* ]]> */
</script>
<style id='wp-emoji-styles-inline-css' type='text/css'>

	img.wp-smiley, img.emoji {
		display: inline !important;
		border: none !important;
		box-shadow: none !important;
		height: 1em !important;
		width: 1em !important;
		margin: 0 0.07em !important;
		vertical-align: -0.1em !important;
		background: none !important;
		padding: 0 !important;
	}
</style>
<style id='classic-theme-styles-inline-css' type='text/css'>
/*! This file is auto-generated */
.wp-block-button__link{color:#fff;background-color:#32373c;border-radius:9999px;box-shadow:none;text-decoration:none;padding:calc(.667em + 2px) calc(1.333em + 2px);font-size:1.125em}.wp-block-file__button{background:#32373c;color:#fff;text-decoration:none}
</style>
<style id='global-styles-inline-css' type='text/css'>
:root{--wp--preset--aspect-ratio--square: 1;--wp--preset--aspect-ratio--4-3: 4/3;--wp--preset--aspect-ratio--3-4: 3/4;--wp--preset--aspect-ratio--3-2: 3/2;--wp--preset--aspect-ratio--2-3: 2/3;--wp--preset--aspect-ratio--16-9: 16/9;--wp--preset--aspect-ratio--9-16: 9/16;--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:where(.is-layout-flex){gap: 0.5em;}:where(.is-layout-grid){gap: 0.5em;}body .is-layout-flex{display: flex;}.is-layout-flex{flex-wrap: wrap;align-items: center;}.is-layout-flex > :is(*, div){margin: 0;}body .is-layout-grid{display: grid;}.is-layout-grid > :is(*, div){margin: 0;}:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}
:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}
:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}
:root :where(.wp-block-pullquote){font-size: 1.5em;line-height: 1.6;}
</style>
<link data-minify="1" rel='stylesheet' id='menu-image-css' href='https://ludorex.com/wp-content/cache/min/1/wp-content/plugins/menu-image/includes/css/menu-image.css?ver=1748473534' type='text/css' media='all' />
<link data-minify="1" rel='stylesheet' id='dashicons-css' href='https://ludorex.com/wp-content/cache/min/1/wp-includes/css/dashicons.min.css?ver=1748473534' type='text/css' media='all' />
<link data-minify="1" rel='stylesheet' id='trp-language-switcher-style-css' href='https://ludorex.com/wp-content/cache/background-css/ludorex.com/wp-content/cache/min/1/wp-content/plugins/translatepress-multilingual/assets/css/trp-language-switcher.css?ver=1748473534&wpr_t=1768558654' type='text/css' media='all' />
<link rel='stylesheet' id='cmplz-general-css' href='https://ludorex.com/wp-content/plugins/complianz-gdpr/assets/css/cookieblocker.min.css?ver=1748473366' type='text/css' media='all' />
<link data-minify="1" rel='stylesheet' id='vikinger-simplebar-styles-css' href='https://ludorex.com/wp-content/cache/min/1/wp-content/themes/vikinger/css/vendor/simplebar.css?ver=1748473534' type='text/css' media='all' />
<link data-minify="1" rel='stylesheet' id='vikinger-swiper-slider-styles-css' href='https://ludorex.com/wp-content/cache/min/1/wp-content/themes/vikinger/css/vendor/swiper.min.css?ver=1748473534' type='text/css' media='all' />
<link data-minify="1" rel='stylesheet' id='vikinger-styles-css' href='https://ludorex.com/wp-content/cache/background-css/ludorex.com/wp-content/cache/min/1/wp-content/themes/vikinger/style.css?ver=1748473534&wpr_t=1768558654' type='text/css' media='all' />
<style id='vikinger-styles-inline-css' type='text/css'>

    :root {
      --font-primary: Rajdhani, sans-serif;
      --font-secondary: Titillium Web, sans-serif;
    }
  
:root { --color-wplogin-body: #2c1d58;--color-wplogin-header-text: #fff;--color-header-background: #2c1d58;--color-header-logo-background: #f33059;--color-header-text: #fff;--color-header-icon: #4f3e80;--color-header-icon-hover: #fff;--color-header-profile-settings-icon: #fff;--color-header-mobilemenu-trigger-icon: #fff;--color-header-divider: #463283;--color-header-input-background: #221746;--color-header-input-placeholder: #8a7fc4;--color-header-progressbar-line-gradient-start: #f33059;--color-header-progressbar-line-gradient-end: #943dff;--color-header-progressbar-underline: #403076;--color-body: #221746;--color-box-background: #2c1d58;--color-box-background-alt: #281a51;--color-box-over-box-background: #332363;--color-box-over-box-light-background: #332363;--color-box-highlight-background: #332363;--color-box-hover-background: #3b296e;--color-box-shadow: 0 0 40px 0 rgba(0,0,0, .06);--color-overbox-shadow: 3px 5px 20px 0 rgba(0,0,0, .12);--color-overbox-dark-shadow: 0 0 40px 0 rgba(0,0,0, .12);--color-overbox-big-shadow: 3px 5px 40px 0 rgba(0,0,0, .1);--color-text: #fff;--color-text-alt: #9388cc;--color-text-alt-2: #9388cc;--color-icon: #8370bb;--color-icon-highlighted: #f33059;--color-border: #4d378e;--color-divider: #4d378e;--color-progressbar-line-gradient-start: #f33059;--color-progressbar-line-gradient-end: #943dff;--color-progressbar-underline: #403076;--color-avatar-rank-hexagon: #f33059 ;--color-primary: #f33059;--color-primary-hover: #ff426a;--color-primary-light: #ff335e;--color-primary-dark: #ff335e;--color-primary-shadow: 4px 7px 12px 0 rgba(243,48,89, .2);--color-secondary: #943dff;--color-secondary-hover: #a156fe;--color-secondary-dark: #943dff;--color-secondary-shadow: 4px 7px 12px 0 rgba(148,61,255, .2);--color-tertiary: #ff911b;--color-tertiary-hover: #ff9e35;--color-tertiary-shadow: 4px 7px 12px 0 rgba(255,145,27, .2);--color-loading-screen-background: #2c1d58;--color-loading-bar-1: #fd426d;--color-loading-bar-2: #f4447c;--color-loading-bar-3: #e74790;--color-loading-bar-4: #d84aa8;--color-loading-bar-5: #ca4dbd;--color-loading-bar-6: #b951d8;--color-loading-bar-7: #ac54ec;--color-loading-bar-8: #a356fb;--color-overlay: rgba(21,21,31, .96);;--color-notice-overlay-background-primary: rgba(243,48,89, .14);--color-notice-overlay-background-secondary: rgba(148,61,255, .14);--color-notice-overlay-background-tertiary: rgba(255,145,27, .14);--color-avatar-overlay-background: rgba(148,61,255, .9);--footer-navigation-display-mobile: none; }
</style>
<link rel='stylesheet' id='vikingerchild-styles-css' href='https://ludorex.com/wp-content/themes/vikinger-child/style.css?ver=1.0.0' type='text/css' media='all' />

<link rel='stylesheet' id='elementor-frontend-css' href='https://ludorex.com/wp-content/plugins/elementor/assets/css/frontend.min.css?ver=3.29.1' type='text/css' media='all' />
<link rel='stylesheet' id='widget-image-css' href='https://ludorex.com/wp-content/plugins/elementor/assets/css/widget-image.min.css?ver=3.29.1' type='text/css' media='all' />
<link rel='stylesheet' id='widget-search-form-css' href='https://ludorex.com/wp-content/plugins/pro-elements/assets/css/widget-search-form.min.css?ver=3.29.0' type='text/css' media='all' />
<link rel='stylesheet' id='widget-nav-menu-css' href='https://ludorex.com/wp-content/plugins/pro-elements/assets/css/widget-nav-menu.min.css?ver=3.29.0' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-post-27369-css' href='https://ludorex.com/wp-content/uploads/elementor/css/post-27369.css?ver=1748473533' type='text/css' media='all' />
<link data-minify="1" rel='stylesheet' id='font-awesome-5-all-css' href='https://ludorex.com/wp-content/cache/min/1/wp-content/plugins/elementor/assets/lib/font-awesome/css/all.min.css?ver=1748473534' type='text/css' media='all' />
<link rel='stylesheet' id='font-awesome-4-shim-css' href='https://ludorex.com/wp-content/plugins/elementor/assets/lib/font-awesome/css/v4-shims.min.css?ver=3.29.1' type='text/css' media='all' />
<link rel='stylesheet' id='widget-divider-css' href='https://ludorex.com/wp-content/plugins/elementor/assets/css/widget-divider.min.css?ver=3.29.1' type='text/css' media='all' />
<link rel='stylesheet' id='widget-animated-headline-css' href='https://ludorex.com/wp-content/plugins/pro-elements/assets/css/widget-animated-headline.min.css?ver=3.29.0' type='text/css' media='all' />
<link rel='stylesheet' id='widget-posts-css' href='https://ludorex.com/wp-content/plugins/pro-elements/assets/css/widget-posts.min.css?ver=3.29.0' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-post-79-css' href='https://ludorex.com/wp-content/uploads/elementor/css/post-79.css?ver=1748473534' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-post-34220-css' href='https://ludorex.com/wp-content/uploads/elementor/css/post-34220.css?ver=1748473534' type='text/css' media='all' />
<link rel='stylesheet' id='elementor-post-34245-css' href='https://ludorex.com/wp-content/uploads/elementor/css/post-34245.css?ver=1748473534' type='text/css' media='all' />
<link rel='stylesheet' id='eael-general-css' href='https://ludorex.com/wp-content/plugins/essential-addons-for-elementor-lite/assets/front-end/css/view/general.min.css?ver=6.1.9' type='text/css' media='all' />
<style id='rocket-lazyload-inline-css' type='text/css'>
.rll-youtube-player{position:relative;padding-bottom:56.23%;height:0;overflow:hidden;max-width:100%;}.rll-youtube-player:focus-within{outline: 2px solid currentColor;outline-offset: 5px;}.rll-youtube-player iframe{position:absolute;top:0;left:0;width:100%;height:100%;z-index:100;background:0 0}.rll-youtube-player img{bottom:0;display:block;left:0;margin:auto;max-width:100%;width:100%;position:absolute;right:0;top:0;border:none;height:auto;-webkit-transition:.4s all;-moz-transition:.4s all;transition:.4s all}.rll-youtube-player img:hover{-webkit-filter:brightness(75%)}.rll-youtube-player .play{height:100%;width:100%;left:0;top:0;position:absolute;background:var(--wpr-bg-1497b916-5903-4766-b785-2b1a95ca1a84) no-repeat center;background-color: transparent !important;cursor:pointer;border:none;}
</style>
<script type="text/javascript" src="https://ludorex.com/wp-includes/js/jquery/jquery.min.js?ver=3.7.1" id="jquery-core-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" id="jquery-migrate-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/elementor/assets/lib/font-awesome/js/v4-shims.min.js?ver=3.29.1" id="font-awesome-4-shim-js" defer></script>
<link rel="https://api.w.org/" href="https://ludorex.com/wp-json/" /><link rel="alternate" title="JSON" type="application/json" href="https://ludorex.com/wp-json/wp/v2/pages/79" /><link rel="alternate" hreflang="es" href="https://ludorex.com/"/>
<link rel="alternate" hreflang="en" href="https://ludorex.com/en"/>
<link rel="alternate" hreflang="ko" href="https://ludorex.com/ko"/>
<link rel="alternate" hreflang="ru" href="https://ludorex.com/ru"/>
<link rel="alternate" hreflang="hi" href="https://ludorex.com/hi"/>
<link rel="alternate" hreflang="pt" href="https://ludorex.com/pt"/>
<link rel="alternate" hreflang="tr" href="https://ludorex.com/tr"/>
<link rel="alternate" hreflang="vi" href="https://ludorex.com/vi"/>
<link rel="alternate" hreflang="it" href="https://ludorex.com/it"/>
<link rel="alternate" hreflang="fr" href="https://ludorex.com/fr"/>
<link rel="alternate" hreflang="ja" href="https://ludorex.com/ja"/>
			<style>.cmplz-hidden {
					display: none !important;
				}</style><meta name="generator" content="speculation-rules 1.5.0">
<meta property="fb:app_id" content="610736667495739" />
<!-- Schema & Structured Data For WP v1.46 - -->
<script type="application/ld+json" class="saswp-schema-markup-output">
[{"@context":"https:\/\/schema.org\/","@graph":[{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Acci\u00f3n","url":"https:\/\/ludorex.com\/accion"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Arcade","url":"https:\/\/ludorex.com\/arcade"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Juegos de aventuras","url":"https:\/\/ludorex.com\/aventuras"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Cl\u00e1sicos","url":"https:\/\/ludorex.com\/clasicos"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Cartas","url":"https:\/\/ludorex.com\/cartas"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Juegos Casual","url":"https:\/\/ludorex.com\/casual"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Coches","url":"https:\/\/ludorex.com\/carreras\/coches"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Cocina","url":"https:\/\/ludorex.com\/gestion\/cocina"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Juegos Deportes","url":"https:\/\/ludorex.com\/deportes"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Juegos de Disparos","url":"https:\/\/ludorex.com\/disparos"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Estrategia","url":"https:\/\/ludorex.com\/estrategia"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Logica","url":"https:\/\/ludorex.com\/logica"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Juegos de Lucha","url":"https:\/\/ludorex.com\/lucha"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"Plataformas","url":"https:\/\/ludorex.com\/plataformas"},{"@context":"https:\/\/schema.org\/","@type":"SiteNavigationElement","@id":"https:\/\/ludorex.com#Categor\u00edas","name":"RPG","url":"https:\/\/ludorex.com\/rpg-rol"}]},

{"@context":"https:\/\/schema.org\/","@type":"WebSite","@id":"https:\/\/ludorex.com#website","headline":"Juegos Gratis Online - Ludorex","name":"Juegos Gratis Online - Ludorex","description":"\u00a1Explora miles de juegos gratis de navegador! Juega al instante sin descargas, en cualquier dispositivo.","url":"https:\/\/ludorex.com","potentialAction":{"@type":"SearchAction","target":"https:\/\/ludorex.com?s={search_term_string}","query-input":"required name=search_term_string"}},

{"@context":"https:\/\/schema.org\/","@type":"Project","@id":"https:\/\/ludorex.com\/#Project","name":"Ludorex","url":"https:\/\/ludorex.com\/","description":"LudoRex es una plataforma en l\u00ednea que ofrece una amplia variedad de juegos gratuitos para disfrutar directamente desde el navegador, sin necesidad de descargas. Los usuarios pueden explorar categor\u00edas como acci\u00f3n, arcade, aventuras, cl\u00e1sicos, cartas, casual, coches, cocina, deportes, disparos, estrategia, l\u00f3gica, lucha, plataformas y RPG. Cada categor\u00eda contiene m\u00faltiples t\u00edtulos que garantizan horas de entretenimiento para jugadores de todas las edades. Adem\u00e1s, LudoRex se actualiza regularmente para incluir nuevos juegos y mantener la experiencia fresca y emocionante.","logo":{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/07\/ludorex.png","height":"536","width":"194"},"address":{"@type":"PostalAddress","streetAddress":"PLAZA VALDEHONDILLO, 7, 8 A","addressCountry":"ES","addressLocality":"Fuenlabrada","addressRegion":"Madrid","postalCode":"28944","telephone":"660299194","email":""},"duns":"","founder":"","foundingDate":"","hasCredential":"","knowsAbout":"","memberOf":"","parentProject":"","sameAs":["","https:\/\/x.com\/Ruben_Cabra\/","https:\/\/www.linkedin.com\/in\/rubn-cabra-zamora-681856119\/","","https:\/\/mastodon.social\/@xcabrax",""],"review":[],"image":[{"@type":"ImageObject","@id":"https:\/\/ludorex.com\/#primaryimage","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/07\/ludorex-logo-icono.png","width":"512","height":"512","caption":"ludorex logo icono"},{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/06\/night-city-racing-juego-de-carreras-300x300.png","width":0,"height":0,"caption":"night city racing - juego de carreras"},{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/06\/juego-Shell-Shockers-300x300.png","width":0,"height":0,"caption":"juego Shell Shockers"},{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/07\/subway-surfer-300x300.jpg","width":0,"height":0,"caption":"subway surfer"},{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2025\/04\/supermarket-simulator-unblocked.png","width":300,"height":300,"caption":"Hombre con delantal azul sosteniendo una caja llena de frutas y verduras frescas en el pasillo de un supermercado para el juego Supermarket Simulator."},{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/06\/monke-mart-pagina-top-300x300.jpeg","width":0,"height":0,"caption":"monke mart pagina top"},{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2024\/06\/juego-Bloxd-io-300x300.jpg","width":0,"height":0,"caption":"juego Bloxd.io"}]},

{"@context":"https:\/\/schema.org\/","@type":"Person","@id":"https:\/\/ludorex.com#Person","name":"Rub\u00e9n Cabra Zamora","jobTitle":"Consultor SEO","url":"https:\/\/ludorex.com","sameAs":["https:\/\/www.facebook.com\/people\/Juegos-Gratis-Online-Ludorex\/61563979512978\/"],"image":{"@type":"ImageObject","url":"https:\/\/ludorex.com\/wp-content\/uploads\/2022\/11\/ruben-cabra-zamora.jpg","width":"200","height":"200"},"telephone":""}]
</script>


<!-- Schema & Structured Data For WP Custom Markup v1.46 - -->
<script type="application/ld+json" class="saswp-custom-schema-markup-output">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Rubén Cabra Zamora",
  "alternateName": "Ludorex",
  "description": "Creador de contenido y fundador de Ludorex, una plataforma en línea que ofrece una amplia variedad de juegos gratuitos para disfrutar directamente desde el navegador, sin necesidad de descargas. Los usuarios pueden explorar categorías como acción, arcade, aventuras, clásicos, cartas, casual, coches, cocina, deportes, disparos, estrategia, lógica, lucha, plataformas y RPG. Cada categoría contiene múltiples títulos que garantizan horas de entretenimiento para jugadores de todas las edades. Además, LudoRex se actualiza regularmente para incluir nuevos juegos y mantener la experiencia fresca y emocionante.",
  "url": "https://ludorex.com/",
  "image": "https://ludorex.com/wp-content/uploads/2024/07/ludorex-logo-icono.png",
  "jobTitle": "Fundador y Desarrollador",
  "worksFor": {
    "@type": "Organization",
    "name": "Ludorex",
    "url": "https://ludorex.com/"
  },
  "sameAs": [
    "https://www.facebook.com/TU_FACEBOOK",
    "https://www.youtube.com/TU_YOUTUBE",
    "https://twitter.com/TU_TWITTER",
    "https://www.linkedin.com/in/TU_LINKEDIN",
    "https://www.instagram.com/TU_INSTAGRAM"
  ]
}
</script>

			<style>
				.e-con.e-parent:nth-of-type(n+4):not(.e-lazyloaded):not(.e-no-lazyload),
				.e-con.e-parent:nth-of-type(n+4):not(.e-lazyloaded):not(.e-no-lazyload) * {
					background-image: none !important;
				}
				@media screen and (max-height: 1024px) {
					.e-con.e-parent:nth-of-type(n+3):not(.e-lazyloaded):not(.e-no-lazyload),
					.e-con.e-parent:nth-of-type(n+3):not(.e-lazyloaded):not(.e-no-lazyload) * {
						background-image: none !important;
					}
				}
				@media screen and (max-height: 640px) {
					.e-con.e-parent:nth-of-type(n+2):not(.e-lazyloaded):not(.e-no-lazyload),
					.e-con.e-parent:nth-of-type(n+2):not(.e-lazyloaded):not(.e-no-lazyload) * {
						background-image: none !important;
					}
				}
			</style>
			<link rel="icon" href="https://ludorex.com/wp-content/uploads/2024/07/cropped-ludorex-logo-icono-32x32.png" sizes="32x32" />
<link rel="icon" href="https://ludorex.com/wp-content/uploads/2024/07/cropped-ludorex-logo-icono-192x192.png" sizes="192x192" />
<link rel="apple-touch-icon" href="https://ludorex.com/wp-content/uploads/2024/07/cropped-ludorex-logo-icono-180x180.png" />
<meta name="msapplication-TileImage" content="https://ludorex.com/wp-content/uploads/2024/07/cropped-ludorex-logo-icono-270x270.png" />
		<style type="text/css" id="wp-custom-css">
			div.nsl-container[data-align="left"] {
    text-align: left;
    display: none;
}
.header {
    display: -ms-flexbox;
    display: flex;
    -ms-flex-pack: justify;
    justify-content: space-between;
    -ms-flex-align: center;
    align-items: center;
    width: 100%;
    height: 80px;
    background-color: var(--color-header-background);
    position: static;
    top: 0;
    left: 0;
    z-index: 10000;
}
.menu-image-title-before.menu-image-not-hovered img, .menu-image-hovered.menu-image-title-before .menu-image-hover-wrapper, .menu-image-title-after.menu-image-title {
    padding-left: 0px;
}
.header .header-actions .login-button:last-child, .header .header-actions .register-button:last-child {
    margin-right: 28px;
    visibility: hidden;
}
 /* Ajuste de margin en texto h2 y h3 */
.elementor-kit-27369 h3 {
    color: #000000;
    font-family: "nunito", Sans-serif;
    font-weight: 500;
    margin-top: 25px;
    margin-bottom: 25px;
	  font-size: 18px;
}
.elementor-kit-27369 h2 {
    color: #000000;
    font-family: "nunito", Sans-serif;
    font-weight: 500;
    margin-top: 25px;
    margin-bottom: 25px;
    font-size: 22px; /* Tamaño de fuente añadido */
}
/* Ajuste de parrafos */
.gm-play, #hall_of_fame .plays, [class^=post-] p, [class^=post-] p>a, .navtop {
    color: #000;
	  font-weight: 400;
    font-family: "nunito", Sans-serif;
    font-size: 18px;
}
b, strong, optgroup, dt, em {
    font-weight: 650;
}
/* Ajuste de las listas */
ul, ol {
    list-style-type: initial;
}
*, *::before, *::after {
    margin: 0;
    padding: revert;
    border: none;
    outline: none;
    box-sizing: border-box; 
}
/* --- Añade radio a las imagenes */
.elementor img {
    border: none;
    border-radius: 12px;
    box-shadow: none;
    height: auto;
    max-width: 100%;
}		</style>
		<noscript><style id="rocket-lazyload-nojs-css">.rll-youtube-player, [data-lazy-src]{display:none !important;}</style></noscript><style id="wpr-lazyload-bg-container"></style><style id="wpr-lazyload-bg-exclusion"></style>
<noscript>
<style id="wpr-lazyload-bg-nostyle">.trp-language-switcher>div{--wpr-bg-6ff41f54-4cdb-4b4b-ae90-6163f862985c: url('https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/arrow-down-3101.svg');}.stats-box.small.stat-profile-views{--wpr-bg-7eeded16-e58f-4405-8e95-10ecf18b384f: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/01.jpg');}.stats-box.small.stat-posts-created{--wpr-bg-e96fb8e7-e8f5-4afb-990e-3cc0b241aef5: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/02.jpg');}.stats-box.small.stat-reactions-received{--wpr-bg-5026f060-3874-4d1b-88b7-0e2a23315dd4: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/03.jpg');}.stats-box.small.stat-comments-received{--wpr-bg-23a45413-57f2-4bc1-baf5-09d2c0199dc0: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/04.jpg');}.stats-box.stat-profile-views{--wpr-bg-f8913bef-fe0c-4a3d-855d-34493aa1bb25: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/01-big.png');}.stats-box.stat-posts-created{--wpr-bg-278f9293-cca4-468e-bdd0-bbda2b2e937d: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/02-big.png');}.stats-box.stat-reactions-received{--wpr-bg-ea481680-2803-431e-8160-241ce92ca611: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/03-big.png');}.stats-box.stat-comments-received{--wpr-bg-69e77032-4f9a-4a26-9740-c472bea63fd9: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/04-big.png');}.stats-decoration.v2.big.secondary{--wpr-bg-6ca565b9-621a-4d43-a8cf-379d2e1fdb16: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/05-big.png');}.stats-decoration.v2.big.primary{--wpr-bg-73c12be5-1c56-4572-83af-0a22b238f4b6: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/06-big.png');}.profile-stats .profile-stats-cover{--wpr-bg-63108b38-f10b-4625-ac3a-bd94b1db46d6: url('https://ludorex.com/wp-content/themes/vikinger/img/banner/banner-profile-stats.jpg');}.featured-stat-box.reactioner .featured-stat-box-cover{--wpr-bg-70dd6f6b-6b0b-46ee-ac8e-b085d1d01074: url('https://ludorex.com/wp-content/themes/vikinger/img/banner/banner-reaction.jpg');}.featured-stat-box.commenter .featured-stat-box-cover{--wpr-bg-8a52c952-b9a9-4f9a-93f5-d183e07b6eed: url('https://ludorex.com/wp-content/themes/vikinger/img/banner/banner-commenter.jpg');}.achievement-box.secondary{--wpr-bg-2ec0d80e-bcf5-4e06-bc39-81c03ee5c30d: url('https://ludorex.com/wp-content/themes/vikinger/img/achievement/banner/01.jpg');}.achievement-box.primary{--wpr-bg-6a5f757c-f3f6-4e67-b6d9-5fd12808b679: url('https://ludorex.com/wp-content/themes/vikinger/img/achievement/banner/02.jpg');}.level-progress-badge{--wpr-bg-ac7689d2-cdd0-4764-b6f3-ca036a1a3304: url('https://ludorex.com/wp-content/themes/vikinger/img/badge/level-badge.png');}.account-stat-box.account-stat-active-users{--wpr-bg-5f46162e-3267-4510-8548-fe1ebc615cf7: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/07.png');}.account-stat-box.account-stat-visits{--wpr-bg-fa64d429-20b0-49ae-b44a-2e257428455f: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/08.png');}.account-stat-box.account-stat-session-duration{--wpr-bg-f06f37e6-e9ab-475b-b2a5-6f12204a0427: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/09.png');}.account-stat-box.account-stat-returning-visitors{--wpr-bg-c113f948-4ed3-4e3d-9bc2-60c4f0f236f9: url('https://ludorex.com/wp-content/themes/vikinger/img/graph/stat/10.png');}.landing{--wpr-bg-798d756f-91f8-467d-bb23-5117a744cd5a: url('https://ludorex.com/wp-content/themes/img/landing/landing-background.jpg');}.landing .landing-decoration{--wpr-bg-edef48ac-aff4-4b32-9795-a6bff2f8a458: url('https://ludorex.com/wp-content/themes/img/landing/dot-texture.png');}.product-category-box.category-all{--wpr-bg-b983edd3-f222-4334-ab56-a87bfecba6f1: url('https://ludorex.com/wp-content/themes/img/marketplace/category/01.png');}.product-category-box.category-featured{--wpr-bg-377e665f-452f-4578-bc3f-2266de0dd9c0: url('https://ludorex.com/wp-content/themes/img/marketplace/category/02.png');}.product-category-box.category-digital{--wpr-bg-acec67e2-c8d6-4db0-8e56-122eac1b9932: url('https://ludorex.com/wp-content/themes/img/marketplace/category/03.png');}.product-category-box.category-physical{--wpr-bg-7894e7d1-f55d-4d79-a319-81929063b39e: url('https://ludorex.com/wp-content/themes/img/marketplace/category/04.png');}form.pmpro_form select{--wpr-bg-dc540da9-2154-4b7e-aceb-29b2b9350c37: url('https://ludorex.com/wp-content/themes/vikinger/img/form/select-arrow.png');}.page-open-content .wp-block-categories-dropdown select,.page-open-content .wp-block-archives-dropdown select,.post-open-content-body .wp-block-categories-dropdown select,.post-open-content-body .wp-block-archives-dropdown select,.post-comment-text>div .wp-block-categories-dropdown select,.post-comment-text>div .wp-block-archives-dropdown select{--wpr-bg-dc95287e-c039-45d6-a508-978dc382399f: url('https://ludorex.com/wp-content/themes/vikinger/img/form/select-arrow.png');}.widget-box.widget_text select,.widget-box.widget_archive select,.widget-box.widget_categories select{--wpr-bg-eb81a337-3c0c-4781-9cc2-92277763bb69: url('https://ludorex.com/wp-content/themes/vikinger/img/form/select-arrow.png');}.rll-youtube-player .play{--wpr-bg-1497b916-5903-4766-b785-2b1a95ca1a84: url('https://ludorex.com/wp-content/plugins/wp-rocket/assets/img/youtube.png');}</style>
</noscript>
<script type="application/javascript">const rocket_pairs = [{"selector":".trp-language-switcher>div","style":".trp-language-switcher>div{--wpr-bg-6ff41f54-4cdb-4b4b-ae90-6163f862985c: url('https:\/\/ludorex.com\/wp-content\/plugins\/translatepress-multilingual\/assets\/images\/arrow-down-3101.svg');}","hash":"6ff41f54-4cdb-4b4b-ae90-6163f862985c","url":"https:\/\/ludorex.com\/wp-content\/plugins\/translatepress-multilingual\/assets\/images\/arrow-down-3101.svg"},{"selector":".stats-box.small.stat-profile-views","style":".stats-box.small.stat-profile-views{--wpr-bg-7eeded16-e58f-4405-8e95-10ecf18b384f: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/01.jpg');}","hash":"7eeded16-e58f-4405-8e95-10ecf18b384f","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/01.jpg"},{"selector":".stats-box.small.stat-posts-created","style":".stats-box.small.stat-posts-created{--wpr-bg-e96fb8e7-e8f5-4afb-990e-3cc0b241aef5: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/02.jpg');}","hash":"e96fb8e7-e8f5-4afb-990e-3cc0b241aef5","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/02.jpg"},{"selector":".stats-box.small.stat-reactions-received","style":".stats-box.small.stat-reactions-received{--wpr-bg-5026f060-3874-4d1b-88b7-0e2a23315dd4: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/03.jpg');}","hash":"5026f060-3874-4d1b-88b7-0e2a23315dd4","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/03.jpg"},{"selector":".stats-box.small.stat-comments-received","style":".stats-box.small.stat-comments-received{--wpr-bg-23a45413-57f2-4bc1-baf5-09d2c0199dc0: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/04.jpg');}","hash":"23a45413-57f2-4bc1-baf5-09d2c0199dc0","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/04.jpg"},{"selector":".stats-box.stat-profile-views","style":".stats-box.stat-profile-views{--wpr-bg-f8913bef-fe0c-4a3d-855d-34493aa1bb25: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/01-big.png');}","hash":"f8913bef-fe0c-4a3d-855d-34493aa1bb25","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/01-big.png"},{"selector":".stats-box.stat-posts-created","style":".stats-box.stat-posts-created{--wpr-bg-278f9293-cca4-468e-bdd0-bbda2b2e937d: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/02-big.png');}","hash":"278f9293-cca4-468e-bdd0-bbda2b2e937d","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/02-big.png"},{"selector":".stats-box.stat-reactions-received","style":".stats-box.stat-reactions-received{--wpr-bg-ea481680-2803-431e-8160-241ce92ca611: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/03-big.png');}","hash":"ea481680-2803-431e-8160-241ce92ca611","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/03-big.png"},{"selector":".stats-box.stat-comments-received","style":".stats-box.stat-comments-received{--wpr-bg-69e77032-4f9a-4a26-9740-c472bea63fd9: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/04-big.png');}","hash":"69e77032-4f9a-4a26-9740-c472bea63fd9","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/04-big.png"},{"selector":".stats-decoration.v2.big.secondary","style":".stats-decoration.v2.big.secondary{--wpr-bg-6ca565b9-621a-4d43-a8cf-379d2e1fdb16: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/05-big.png');}","hash":"6ca565b9-621a-4d43-a8cf-379d2e1fdb16","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/05-big.png"},{"selector":".stats-decoration.v2.big.primary","style":".stats-decoration.v2.big.primary{--wpr-bg-73c12be5-1c56-4572-83af-0a22b238f4b6: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/06-big.png');}","hash":"73c12be5-1c56-4572-83af-0a22b238f4b6","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/06-big.png"},{"selector":".profile-stats .profile-stats-cover","style":".profile-stats .profile-stats-cover{--wpr-bg-63108b38-f10b-4625-ac3a-bd94b1db46d6: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/banner\/banner-profile-stats.jpg');}","hash":"63108b38-f10b-4625-ac3a-bd94b1db46d6","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/banner\/banner-profile-stats.jpg"},{"selector":".featured-stat-box.reactioner .featured-stat-box-cover","style":".featured-stat-box.reactioner .featured-stat-box-cover{--wpr-bg-70dd6f6b-6b0b-46ee-ac8e-b085d1d01074: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/banner\/banner-reaction.jpg');}","hash":"70dd6f6b-6b0b-46ee-ac8e-b085d1d01074","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/banner\/banner-reaction.jpg"},{"selector":".featured-stat-box.commenter .featured-stat-box-cover","style":".featured-stat-box.commenter .featured-stat-box-cover{--wpr-bg-8a52c952-b9a9-4f9a-93f5-d183e07b6eed: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/banner\/banner-commenter.jpg');}","hash":"8a52c952-b9a9-4f9a-93f5-d183e07b6eed","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/banner\/banner-commenter.jpg"},{"selector":".achievement-box.secondary","style":".achievement-box.secondary{--wpr-bg-2ec0d80e-bcf5-4e06-bc39-81c03ee5c30d: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/achievement\/banner\/01.jpg');}","hash":"2ec0d80e-bcf5-4e06-bc39-81c03ee5c30d","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/achievement\/banner\/01.jpg"},{"selector":".achievement-box.primary","style":".achievement-box.primary{--wpr-bg-6a5f757c-f3f6-4e67-b6d9-5fd12808b679: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/achievement\/banner\/02.jpg');}","hash":"6a5f757c-f3f6-4e67-b6d9-5fd12808b679","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/achievement\/banner\/02.jpg"},{"selector":".level-progress-badge","style":".level-progress-badge{--wpr-bg-ac7689d2-cdd0-4764-b6f3-ca036a1a3304: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/badge\/level-badge.png');}","hash":"ac7689d2-cdd0-4764-b6f3-ca036a1a3304","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/badge\/level-badge.png"},{"selector":".account-stat-box.account-stat-active-users","style":".account-stat-box.account-stat-active-users{--wpr-bg-5f46162e-3267-4510-8548-fe1ebc615cf7: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/07.png');}","hash":"5f46162e-3267-4510-8548-fe1ebc615cf7","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/07.png"},{"selector":".account-stat-box.account-stat-visits","style":".account-stat-box.account-stat-visits{--wpr-bg-fa64d429-20b0-49ae-b44a-2e257428455f: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/08.png');}","hash":"fa64d429-20b0-49ae-b44a-2e257428455f","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/08.png"},{"selector":".account-stat-box.account-stat-session-duration","style":".account-stat-box.account-stat-session-duration{--wpr-bg-f06f37e6-e9ab-475b-b2a5-6f12204a0427: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/09.png');}","hash":"f06f37e6-e9ab-475b-b2a5-6f12204a0427","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/09.png"},{"selector":".account-stat-box.account-stat-returning-visitors","style":".account-stat-box.account-stat-returning-visitors{--wpr-bg-c113f948-4ed3-4e3d-9bc2-60c4f0f236f9: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/10.png');}","hash":"c113f948-4ed3-4e3d-9bc2-60c4f0f236f9","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/graph\/stat\/10.png"},{"selector":".landing","style":".landing{--wpr-bg-798d756f-91f8-467d-bb23-5117a744cd5a: url('https:\/\/ludorex.com\/wp-content\/themes\/img\/landing\/landing-background.jpg');}","hash":"798d756f-91f8-467d-bb23-5117a744cd5a","url":"https:\/\/ludorex.com\/wp-content\/themes\/img\/landing\/landing-background.jpg"},{"selector":".landing .landing-decoration","style":".landing .landing-decoration{--wpr-bg-edef48ac-aff4-4b32-9795-a6bff2f8a458: url('https:\/\/ludorex.com\/wp-content\/themes\/img\/landing\/dot-texture.png');}","hash":"edef48ac-aff4-4b32-9795-a6bff2f8a458","url":"https:\/\/ludorex.com\/wp-content\/themes\/img\/landing\/dot-texture.png"},{"selector":".product-category-box.category-all","style":".product-category-box.category-all{--wpr-bg-b983edd3-f222-4334-ab56-a87bfecba6f1: url('https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/01.png');}","hash":"b983edd3-f222-4334-ab56-a87bfecba6f1","url":"https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/01.png"},{"selector":".product-category-box.category-featured","style":".product-category-box.category-featured{--wpr-bg-377e665f-452f-4578-bc3f-2266de0dd9c0: url('https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/02.png');}","hash":"377e665f-452f-4578-bc3f-2266de0dd9c0","url":"https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/02.png"},{"selector":".product-category-box.category-digital","style":".product-category-box.category-digital{--wpr-bg-acec67e2-c8d6-4db0-8e56-122eac1b9932: url('https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/03.png');}","hash":"acec67e2-c8d6-4db0-8e56-122eac1b9932","url":"https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/03.png"},{"selector":".product-category-box.category-physical","style":".product-category-box.category-physical{--wpr-bg-7894e7d1-f55d-4d79-a319-81929063b39e: url('https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/04.png');}","hash":"7894e7d1-f55d-4d79-a319-81929063b39e","url":"https:\/\/ludorex.com\/wp-content\/themes\/img\/marketplace\/category\/04.png"},{"selector":"form.pmpro_form select","style":"form.pmpro_form select{--wpr-bg-dc540da9-2154-4b7e-aceb-29b2b9350c37: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/form\/select-arrow.png');}","hash":"dc540da9-2154-4b7e-aceb-29b2b9350c37","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/form\/select-arrow.png"},{"selector":".page-open-content .wp-block-categories-dropdown select,.page-open-content .wp-block-archives-dropdown select,.post-open-content-body .wp-block-categories-dropdown select,.post-open-content-body .wp-block-archives-dropdown select,.post-comment-text>div .wp-block-categories-dropdown select,.post-comment-text>div .wp-block-archives-dropdown select","style":".page-open-content .wp-block-categories-dropdown select,.page-open-content .wp-block-archives-dropdown select,.post-open-content-body .wp-block-categories-dropdown select,.post-open-content-body .wp-block-archives-dropdown select,.post-comment-text>div .wp-block-categories-dropdown select,.post-comment-text>div .wp-block-archives-dropdown select{--wpr-bg-dc95287e-c039-45d6-a508-978dc382399f: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/form\/select-arrow.png');}","hash":"dc95287e-c039-45d6-a508-978dc382399f","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/form\/select-arrow.png"},{"selector":".widget-box.widget_text select,.widget-box.widget_archive select,.widget-box.widget_categories select","style":".widget-box.widget_text select,.widget-box.widget_archive select,.widget-box.widget_categories select{--wpr-bg-eb81a337-3c0c-4781-9cc2-92277763bb69: url('https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/form\/select-arrow.png');}","hash":"eb81a337-3c0c-4781-9cc2-92277763bb69","url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/form\/select-arrow.png"},{"selector":".rll-youtube-player .play","style":".rll-youtube-player .play{--wpr-bg-1497b916-5903-4766-b785-2b1a95ca1a84: url('https:\/\/ludorex.com\/wp-content\/plugins\/wp-rocket\/assets\/img\/youtube.png');}","hash":"1497b916-5903-4766-b785-2b1a95ca1a84","url":"https:\/\/ludorex.com\/wp-content\/plugins\/wp-rocket\/assets\/img\/youtube.png"}]; const rocket_excluded_pairs = [];</script><script data-cfasync="false" nonce="9eba7db0-b505-4250-bb9c-b0f84de9f507">try{(function(w,d){!function(j,k,l,m){if(j.zaraz)console.error("zaraz is loaded twice");else{j[l]=j[l]||{};j[l].executed=[];j.zaraz={deferred:[],listeners:[]};j.zaraz._v="5874";j.zaraz._n="9eba7db0-b505-4250-bb9c-b0f84de9f507";j.zaraz.q=[];j.zaraz._f=function(n){return async function(){var o=Array.prototype.slice.call(arguments);j.zaraz.q.push({m:n,a:o})}};for(const p of["track","set","debug"])j.zaraz[p]=j.zaraz._f(p);j.zaraz.init=()=>{var q=k.getElementsByTagName(m)[0],r=k.createElement(m),s=k.getElementsByTagName("title")[0];s&&(j[l].t=k.getElementsByTagName("title")[0].text);j[l].x=Math.random();j[l].w=j.screen.width;j[l].h=j.screen.height;j[l].j=j.innerHeight;j[l].e=j.innerWidth;j[l].l=j.location.href;j[l].r=k.referrer;j[l].k=j.screen.colorDepth;j[l].n=k.characterSet;j[l].o=(new Date).getTimezoneOffset();if(j.dataLayer)for(const t of Object.entries(Object.entries(dataLayer).reduce((u,v)=>({...u[1],...v[1]}),{})))zaraz.set(t[0],t[1],{scope:"page"});j[l].q=[];for(;j.zaraz.q.length;){const w=j.zaraz.q.shift();j[l].q.push(w)}r.defer=!0;for(const x of[localStorage,sessionStorage])Object.keys(x||{}).filter(z=>z.startsWith("_zaraz_")).forEach(y=>{try{j[l]["z_"+y.slice(7)]=JSON.parse(x.getItem(y))}catch{j[l]["z_"+y.slice(7)]=x.getItem(y)}});r.referrerPolicy="origin";r.src="/cdn-cgi/zaraz/s.js?z="+btoa(encodeURIComponent(JSON.stringify(j[l])));q.parentNode.insertBefore(r,q)};["complete","interactive"].includes(k.readyState)?zaraz.init():j.addEventListener("DOMContentLoaded",zaraz.init)}}(w,d,"zarazData","script");window.zaraz._p=async d$=>new Promise(ea=>{if(d$){d$.e&&d$.e.forEach(eb=>{try{const ec=d.querySelector("script[nonce]"),ed=ec?.nonce||ec?.getAttribute("nonce"),ee=d.createElement("script");ed&&(ee.nonce=ed);ee.innerHTML=eb;ee.onload=()=>{d.head.removeChild(ee)};d.head.appendChild(ee)}catch(ef){console.error(`Error executing script: ${eb}\n`,ef)}});Promise.allSettled((d$.f||[]).map(eg=>fetch(eg[0],eg[1])))}ea()});zaraz._p({"e":["(function(w,d){})(window,document)"]});})(window,document)}catch(e){throw fetch("/cdn-cgi/zaraz/t"),e;};</script></head>
<body data-rsssl=1 data-cmplz=1 class="home wp-singular page-template-default page page-id-79 wp-custom-logo wp-theme-vikinger wp-child-theme-vikinger-child translatepress-es_ES vikinger-logged-out elementor-default elementor-template-full-width elementor-kit-27369 elementor-page elementor-page-79">
		<div data-elementor-type="header" data-elementor-id="34220" class="elementor elementor-34220 elementor-location-header" data-elementor-post-type="elementor_library">
					<section class="elementor-section elementor-top-section elementor-element elementor-element-ff4ff21 elementor-section-full_width elementor-section-height-full elementor-section-items-stretch elementor-section-content-space-between elementor-section-height-default" data-id="ff4ff21" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-no">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-248787b8" data-id="248787b8" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<section class="elementor-section elementor-inner-section elementor-element elementor-element-7e1788ce elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="7e1788ce" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-inner-column elementor-element elementor-element-b2462a8" data-id="b2462a8" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-7eb08666 sidebar-toggle elementor-widget__width-auto elementor-absolute elementor-hidden-mobile elementor-view-default elementor-widget elementor-widget-icon" data-id="7eb08666" data-element_type="widget" data-settings="{&quot;_position&quot;:&quot;absolute&quot;}" data-widget_type="icon.default">
				<div class="elementor-widget-container">
							<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg aria-hidden="true" class="e-font-icon-svg e-fas-bars" viewBox="0 0 448 512" xmlns="http://www.w3.org/2000/svg"><path d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"></path></svg>			</div>
		</div>
						</div>
				</div>
				<div class="elementor-element elementor-element-3c534b4 elementor-absolute logo elementor-widget elementor-widget-image" data-id="3c534b4" data-element_type="widget" data-settings="{&quot;_position&quot;:&quot;absolute&quot;}" data-widget_type="image.default">
				<div class="elementor-widget-container">
																<a href="https://ludorex.com">
							<img width="536" height="194" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20536%20194'%3E%3C/svg%3E" class="attachment-large size-large wp-image-35211" alt="ludorex" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/06c8e63a-c82a-4cb1-3b8f-6756b7797100/w=536,h=194" /><noscript><img width="536" height="194" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/06c8e63a-c82a-4cb1-3b8f-6756b7797100/w=536,h=194" class="attachment-large size-large wp-image-35211" alt="ludorex" /></noscript>								</a>
															</div>
				</div>
				<div class="elementor-element elementor-element-3c3cac5e elementor-search-form--skin-minimal elementor-widget elementor-widget-search-form" data-id="3c3cac5e" data-element_type="widget" data-settings="{&quot;skin&quot;:&quot;minimal&quot;}" data-widget_type="search-form.default">
				<div class="elementor-widget-container">
							<search role="search">
			<form class="elementor-search-form" action="https://ludorex.com" method="get">
												<div class="elementor-search-form__container">
					<label class="elementor-screen-only" for="elementor-search-form-3c3cac5e">Search</label>

											<div class="elementor-search-form__icon">
							<div class="e-font-icon-svg-container"><svg aria-hidden="true" class="e-font-icon-svg e-fas-search" viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg"><path d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"></path></svg></div>							<span class="elementor-screen-only">Search</span>
						</div>
					
					<input id="elementor-search-form-3c3cac5e" placeholder="Search..." class="elementor-search-form__input" type="search" name="s" value="">
					
					
									</div>
			</form>
		</search>
						</div>
				</div>
				<div class="elementor-element elementor-element-59d619c elementor-nav-menu--dropdown-tablet elementor-nav-menu__text-align-aside elementor-widget elementor-widget-nav-menu" data-id="59d619c" data-element_type="widget" data-settings="{&quot;layout&quot;:&quot;horizontal&quot;,&quot;submenu_icon&quot;:{&quot;value&quot;:&quot;&lt;svg class=\&quot;e-font-icon-svg e-fas-caret-down\&quot; viewBox=\&quot;0 0 320 512\&quot; xmlns=\&quot;http:\/\/www.w3.org\/2000\/svg\&quot;&gt;&lt;path d=\&quot;M31.3 192h257.3c17.8 0 26.7 21.5 14.1 34.1L174.1 354.8c-7.8 7.8-20.5 7.8-28.3 0L17.2 226.1C4.6 213.5 13.5 192 31.3 192z\&quot;&gt;&lt;\/path&gt;&lt;\/svg&gt;&quot;,&quot;library&quot;:&quot;fa-solid&quot;}}" data-widget_type="nav-menu.default">
				<div class="elementor-widget-container">
								<nav aria-label="Menu" class="elementor-nav-menu--main elementor-nav-menu__container elementor-nav-menu--layout-horizontal e--pointer-text e--animation-grow">
				<ul id="menu-1-59d619c" class="elementor-nav-menu"><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32903"><a href="https://ludorex.com/accion" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría acción" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/55cd801b-ef95-45ba-afd8-d80214343400/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/55cd801b-ef95-45ba-afd8-d80214343400/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría acción" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Acción</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32904"><a href="https://ludorex.com/arcade" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría arcade" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ae464036-2aaf-45b0-339c-ca1c8ead7100/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ae464036-2aaf-45b0-339c-ca1c8ead7100/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría arcade" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Arcade</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32898"><a href="https://ludorex.com/aventuras" title="Aventuras" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría aventuras" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/807c0e05-33e8-4f1e-260e-d75bd4825100/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/807c0e05-33e8-4f1e-260e-d75bd4825100/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría aventuras" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos de aventuras</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32902"><a href="https://ludorex.com/clasicos" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría clasicos" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d55da30a-e3c2-4988-46d5-45ff0fddce00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d55da30a-e3c2-4988-46d5-45ff0fddce00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría clasicos" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Clásicos</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32905"><a href="https://ludorex.com/cartas" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría cartas" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/84d2883a-7ce7-4e22-3c93-558d49e40e00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/84d2883a-7ce7-4e22-3c93-558d49e40e00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría cartas" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Cartas</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32899"><a href="https://ludorex.com/casual" title="Casual" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría casual" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/e0bd08be-97c5-4715-1cf7-3fbd7af63400/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/e0bd08be-97c5-4715-1cf7-3fbd7af63400/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría casual" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos Casual</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32906"><a href="https://ludorex.com/carreras/coches" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría coches" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3042705e-c7be-4355-132b-02fab7324700/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3042705e-c7be-4355-132b-02fab7324700/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría coches" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Coches</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32907"><a href="https://ludorex.com/gestion/cocina" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría cocina" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0739e412-ee19-43a8-6957-947e1ca06c00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0739e412-ee19-43a8-6957-947e1ca06c00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría cocina" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Cocina</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32900"><a href="https://ludorex.com/deportes" title="Deportes" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría deportes" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f6b9b184-57eb-49c4-9287-78fcdc3fee00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f6b9b184-57eb-49c4-9287-78fcdc3fee00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría deportes" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos Deportes</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32901"><a href="https://ludorex.com/disparos" title="Disparos" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría disparos" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2d5feb27-2479-41e2-aece-f91b58fff900/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2d5feb27-2479-41e2-aece-f91b58fff900/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría disparos" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos de Disparos</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32908"><a href="https://ludorex.com/estrategia" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría estrategia" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/45f9a54d-f7be-4276-86cd-d8eb0b0ffb00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/45f9a54d-f7be-4276-86cd-d8eb0b0ffb00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría estrategia" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Estrategia</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32909"><a href="https://ludorex.com/logica" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría logica" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3a8868ec-987b-4f97-cdf3-d20348ab1900/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3a8868ec-987b-4f97-cdf3-d20348ab1900/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría logica" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Logica</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32912"><a href="https://ludorex.com/lucha" title="Lucha" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría lucha" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a4ba035d-0843-40e3-148d-2cb26328a400/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a4ba035d-0843-40e3-148d-2cb26328a400/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría lucha" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos de Lucha</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32910"><a href="https://ludorex.com/plataformas" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría plataformas" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1d5b4740-a20b-453a-a4b6-a4a896f81900/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1d5b4740-a20b-453a-a4b6-a4a896f81900/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría plataformas" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Plataformas</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32911"><a href="https://ludorex.com/rpg-rol" class="menu-image-title-after menu-image-not-hovered elementor-item"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría rpg" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/8ea5a1c2-113c-4617-2f92-57b9201eae00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/8ea5a1c2-113c-4617-2f92-57b9201eae00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría rpg" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">RPG</span></a></li>
</ul>			</nav>
						<nav class="elementor-nav-menu--dropdown elementor-nav-menu__container" aria-hidden="true">
				<ul id="menu-2-59d619c" class="elementor-nav-menu"><li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32903"><a href="https://ludorex.com/accion" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría acción" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/55cd801b-ef95-45ba-afd8-d80214343400/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/55cd801b-ef95-45ba-afd8-d80214343400/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría acción" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Acción</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32904"><a href="https://ludorex.com/arcade" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría arcade" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ae464036-2aaf-45b0-339c-ca1c8ead7100/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ae464036-2aaf-45b0-339c-ca1c8ead7100/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría arcade" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Arcade</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32898"><a href="https://ludorex.com/aventuras" title="Aventuras" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría aventuras" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/807c0e05-33e8-4f1e-260e-d75bd4825100/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/807c0e05-33e8-4f1e-260e-d75bd4825100/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría aventuras" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos de aventuras</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32902"><a href="https://ludorex.com/clasicos" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría clasicos" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d55da30a-e3c2-4988-46d5-45ff0fddce00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d55da30a-e3c2-4988-46d5-45ff0fddce00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría clasicos" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Clásicos</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32905"><a href="https://ludorex.com/cartas" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría cartas" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/84d2883a-7ce7-4e22-3c93-558d49e40e00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/84d2883a-7ce7-4e22-3c93-558d49e40e00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría cartas" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Cartas</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32899"><a href="https://ludorex.com/casual" title="Casual" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría casual" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/e0bd08be-97c5-4715-1cf7-3fbd7af63400/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/e0bd08be-97c5-4715-1cf7-3fbd7af63400/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría casual" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos Casual</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32906"><a href="https://ludorex.com/carreras/coches" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría coches" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3042705e-c7be-4355-132b-02fab7324700/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3042705e-c7be-4355-132b-02fab7324700/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría coches" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Coches</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32907"><a href="https://ludorex.com/gestion/cocina" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría cocina" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0739e412-ee19-43a8-6957-947e1ca06c00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0739e412-ee19-43a8-6957-947e1ca06c00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría cocina" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Cocina</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32900"><a href="https://ludorex.com/deportes" title="Deportes" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría deportes" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f6b9b184-57eb-49c4-9287-78fcdc3fee00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f6b9b184-57eb-49c4-9287-78fcdc3fee00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría deportes" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos Deportes</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32901"><a href="https://ludorex.com/disparos" title="Disparos" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría disparos" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2d5feb27-2479-41e2-aece-f91b58fff900/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2d5feb27-2479-41e2-aece-f91b58fff900/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría disparos" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos de Disparos</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32908"><a href="https://ludorex.com/estrategia" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría estrategia" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/45f9a54d-f7be-4276-86cd-d8eb0b0ffb00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/45f9a54d-f7be-4276-86cd-d8eb0b0ffb00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría estrategia" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Estrategia</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32909"><a href="https://ludorex.com/logica" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría logica" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3a8868ec-987b-4f97-cdf3-d20348ab1900/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/3a8868ec-987b-4f97-cdf3-d20348ab1900/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría logica" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Logica</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32912"><a href="https://ludorex.com/lucha" title="Lucha" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría lucha" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a4ba035d-0843-40e3-148d-2cb26328a400/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a4ba035d-0843-40e3-148d-2cb26328a400/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría lucha" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Juegos de Lucha</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32910"><a href="https://ludorex.com/plataformas" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría plataformas" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1d5b4740-a20b-453a-a4b6-a4a896f81900/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1d5b4740-a20b-453a-a4b6-a4a896f81900/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría plataformas" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">Plataformas</span></a></li>
<li class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-32911"><a href="https://ludorex.com/rpg-rol" class="menu-image-title-after menu-image-not-hovered elementor-item" tabindex="-1"><img width="36" height="36" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2036%2036'%3E%3C/svg%3E" class="menu-image menu-image-title-after" alt="Categoría rpg" decoding="async" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/8ea5a1c2-113c-4617-2f92-57b9201eae00/w=36,h=36,fit=crop" /><noscript><img width="36" height="36" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/8ea5a1c2-113c-4617-2f92-57b9201eae00/w=36,h=36,fit=crop" class="menu-image menu-image-title-after" alt="Categoría rpg" decoding="async" /></noscript><span class="menu-image-title-after menu-image-title">RPG</span></a></li>
</ul>			</nav>
						</div>
				</div>
				<div class="elementor-element elementor-element-67eb2f68 elementor-widget elementor-widget-html" data-id="67eb2f68" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
					<script data-minify="1" src="https://ludorex.com/wp-content/cache/min/1/jquery-3.6.0.min.js?ver=1748473154" defer></script>
<script type="rocketlazyloadscript">window.addEventListener('DOMContentLoaded', function() {

var $ = jQuery,
    clickLock = false

$(document).ready(function(){

$('.sidebar-toggle').on('click', function(){
    
    if( $(window).width() < 768 ){
        $('body').toggleClass('left')
    }else{
        if( $('body').hasClass('open') ){
            $('body').removeClass('open')
            setTimeout(function(){
            $('body').removeClass('opening')        
            },300)  
        }else{
            $('body').addClass('opening')
            setTimeout(function(){
            $('body').addClass('open')        
            },300)    
        }
    }
})

$('.navigation .elementor-icon-list-item').on('click', function(){
    $('.navigation .elementor-icon-list-item').removeClass('active')
    $(this).addClass('active')
    clickLock = true
    setTimeout(function(){
        clickLock = false
    },500)
})

})

$(window).on('load resize', function(){
    if( $(window).width() < 768 ){
        $('body').removeClass('open opening')
        // $('body').addClass('left')
    }else if( $(window).width() < 1025 ){
        $('body').addClass('open opening')
    }else{
        $('body').removeClass('open opening')
    }
})

var hash = true

$(window).on('load', function(){
    $('.elementor-icon-list-item a').each(function(){
        if( $(this).attr('href') == location.protocol+'//'+location.host+location.pathname ){
            hash = false
            $(this).parent().addClass('active')
        }
    })
})

$(window).on('load scroll', function(){
    
    if( !hash || clickLock ) return
    
    var ids = [],
        id
    
    $('.elementor-top-section').each(function(){
        if($(window).scrollTop() + $(window).height() - 350 > $(this).offset().top){
            ids.push($(this).attr('id'))
        }
    })
    
    ids = ids.filter(element => {
      return element !== undefined
    })
    
    id = ids[ids.length - 1]
    
    $('.elementor-icon-list-item').removeClass('active')
    $('[href="#'+id+'"]').parent().addClass('active')
})

$('body').on('click', function(e){
    
if(!$(e.target).closest('.elementor-location-header').length && !$(e.target).hasClass('elementor-location-header') ){
    
    if( $(window).width() < 768 ){
        $('body').removeClass('left')
    }else if( $(window).width() < 1025 ){
        $('body').addClass('open opening')
    }
}
    
})
});</script>				</div>
				</div>
					</div>
		</div>
					</div>
		</section>
					</div>
		</div>
					</div>
		</section>
				<section class="elementor-section elementor-top-section elementor-element elementor-element-5638ec23 elementor-section-boxed elementor-section-height-default elementor-section-height-default" data-id="5638ec23" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-592c621d" data-id="592c621d" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-25f2c6fa sidebar-toggle elementor-widget__width-auto elementor-fixed elementor-hidden-desktop elementor-hidden-tablet elementor-view-default elementor-widget elementor-widget-icon" data-id="25f2c6fa" data-element_type="widget" data-settings="{&quot;_position&quot;:&quot;fixed&quot;}" data-widget_type="icon.default">
				<div class="elementor-widget-container">
							<div class="elementor-icon-wrapper">
			<div class="elementor-icon">
			<svg aria-hidden="true" class="e-font-icon-svg e-fas-bars" viewBox="0 0 448 512" xmlns="http://www.w3.org/2000/svg"><path d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z"></path></svg>			</div>
		</div>
						</div>
				</div>
					</div>
		</div>
					</div>
		</section>
				</div>
				<div data-elementor-type="wp-post" data-elementor-id="79" class="elementor elementor-79" data-elementor-post-type="page">
				<article class="elementor-element elementor-element-2c38cde e-con-full e-flex e-con e-parent" data-id="2c38cde" data-element_type="container">
		<article class="elementor-element elementor-element-eca965e e-con-full e-flex e-con e-child" data-id="eca965e" data-element_type="container">
				<div class="elementor-element elementor-element-f87eb23 elementor-widget-divider--separator-type-pattern elementor-widget-divider--view-line elementor-widget elementor-widget-divider" data-id="f87eb23" data-element_type="widget" data-widget_type="divider.default">
				<div class="elementor-widget-container">
							<div class="elementor-divider" style="--divider-pattern-url: url(&quot;data:image/svg+xml,%3Csvg xmlns=&#039;http://www.w3.org/2000/svg&#039; preserveAspectRatio=&#039;none&#039; overflow=&#039;visible&#039; height=&#039;100%&#039; viewBox=&#039;0 0 24 24&#039; fill=&#039;black&#039; stroke=&#039;none&#039;%3E%3Cpolygon points=&#039;9.4,2 24,2 14.6,21.6 0,21.6&#039;/%3E%3C/svg%3E&quot;);">
			<span class="elementor-divider-separator">
						</span>
		</div>
						</div>
				</div>
				<div class="elementor-element elementor-element-cb6c0f5 elementor-headline--style-highlight elementor-widget elementor-widget-animated-headline" data-id="cb6c0f5" data-element_type="widget" data-settings="{&quot;marker&quot;:&quot;curly&quot;,&quot;highlighted_text&quot;:&quot;GRATIS&quot;,&quot;headline_style&quot;:&quot;highlight&quot;,&quot;highlight_animation_duration&quot;:1200}" data-widget_type="animated-headline.default">
				<div class="elementor-widget-container">
							<h1 class="elementor-headline">
					<span class="elementor-headline-plain-text elementor-headline-text-wrapper">JUEGOS</span>
				<span class="elementor-headline-dynamic-wrapper elementor-headline-text-wrapper">
					<span class="elementor-headline-dynamic-text elementor-headline-text-active">GRATIS</span>
				</span>
				</h1>
						</div>
				</div>
				<div class="elementor-element elementor-element-403f00a elementor-widget-divider--separator-type-pattern elementor-widget-divider--view-line elementor-widget elementor-widget-divider" data-id="403f00a" data-element_type="widget" data-widget_type="divider.default">
				<div class="elementor-widget-container">
							<div class="elementor-divider" style="--divider-pattern-url: url(&quot;data:image/svg+xml,%3Csvg xmlns=&#039;http://www.w3.org/2000/svg&#039; preserveAspectRatio=&#039;none&#039; overflow=&#039;visible&#039; height=&#039;100%&#039; viewBox=&#039;0 0 24 24&#039; fill=&#039;black&#039; stroke=&#039;none&#039;%3E%3Cpolygon points=&#039;9.4,2 24,2 14.6,21.6 0,21.6&#039;/%3E%3C/svg%3E&quot;);">
			<span class="elementor-divider-separator">
						</span>
		</div>
						</div>
				</div>
		<div class="elementor-element elementor-element-8ca8082 e-grid e-con-full e-con e-child" data-id="8ca8082" data-element_type="container">
				<div class="elementor-element elementor-element-bd0aab3 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 e-transform e-transform e-transform e-transform elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="bd0aab3" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-32580 post type-post status-publish format-standard has-post-thumbnail hentry category-casual">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/space-waves" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-32589" alt="Space Waves" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0c552641-ab9d-4f4a-e6ae-e3dd78beef00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0c552641-ab9d-4f4a-e6ae-e3dd78beef00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-32589" alt="Space Waves" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/space-waves" >
				Space Waves			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-33679 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/pacman-30th-anniversary" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-33680" alt="pacman" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/26e07df5-5547-4f5e-7aef-2a64091de000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/26e07df5-5547-4f5e-7aef-2a64091de000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-33680" alt="pacman" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/pacman-30th-anniversary" >
				Pacman 30th Anniversary			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-33720 post type-post status-publish format-standard has-post-thumbnail hentry category-plataformas">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/geometry-dash" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-33722" alt="geometry dash online" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/38914262-dfa6-497a-8f90-bed5ffc97f00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/38914262-dfa6-497a-8f90-bed5ffc97f00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-33722" alt="geometry dash online" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/geometry-dash" >
				Geometry Dash			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-33645 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/buscaminas" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-33656" alt="Tablero del juego Buscaminas con casillas numeradas, bombas y corazones como vidas. Diseño metálico con efectos brillantes y colores vibrantes." data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/88aac9a3-7133-4d80-3d85-4488d37c2a00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/88aac9a3-7133-4d80-3d85-4488d37c2a00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-33656" alt="Tablero del juego Buscaminas con casillas numeradas, bombas y corazones como vidas. Diseño metálico con efectos brillantes y colores vibrantes." /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/buscaminas" >
				Buscaminas			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-fee795e elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 e-transform e-transform e-transform e-transform elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="fee795e" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-33733 post type-post status-publish format-standard has-post-thumbnail hentry category-cartas">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/solitario" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-33885" alt="Solitario" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/72903bb5-b9b7-4241-e3b9-07e32a9e8200/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/72903bb5-b9b7-4241-e3b9-07e32a9e8200/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-33885" alt="Solitario" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/solitario" >
				Solitario			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-32823 post type-post status-publish format-standard has-post-thumbnail hentry category-plataformas-2">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/pixel-speedrun" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-32833" alt="Pixel Speedrun" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b0c50c4c-15aa-40a4-0ccc-fce946eff600/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b0c50c4c-15aa-40a4-0ccc-fce946eff600/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-32833" alt="Pixel Speedrun" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/pixel-speedrun" >
				Pixel Speedrun			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-33999 post type-post status-publish format-standard has-post-thumbnail hentry category-lucha">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/king-of-fighters-wing-1-91" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34000" alt="King Of Fighters Wing 1.91" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/7e95c046-27f2-4264-d4b1-03b49e53d200/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/7e95c046-27f2-4264-d4b1-03b49e53d200/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34000" alt="King Of Fighters Wing 1.91" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/king-of-fighters-wing-1-91" >
				King Of Fighters Wing 1.91			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-32788 post type-post status-publish format-standard has-post-thumbnail hentry category-aventuras tag-minecraft">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/bloxd-io" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-32798" alt="Bloxd.io" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ec6909b3-f79d-4575-2efb-37f313177c00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ec6909b3-f79d-4575-2efb-37f313177c00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-32798" alt="Bloxd.io" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/bloxd-io" >
				Bloxd.io			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-2987938 e-transform e-transform e-transform e-transform e-transform e-transform e-transform e-transform elementor-hidden-tablet elementor-widget elementor-widget-image" data-id="2987938" data-element_type="widget" data-settings="{&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.1,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleX_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleX_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleY_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleY_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="image.default">
				<div class="elementor-widget-container">
												<figure class="wp-caption">
											<a href="https://ludorex.com/juego/night-city-racing">
							<img decoding="async" width="300" height="300" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" class="attachment-medium size-medium wp-image-32725" alt="night city racing - juego de carreras" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/dace218c-545d-4956-1cd2-77b474cc4200/w=300,h=300,fit=crop" /><noscript><img decoding="async" width="300" height="300" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/dace218c-545d-4956-1cd2-77b474cc4200/w=300,h=300,fit=crop" class="attachment-medium size-medium wp-image-32725" alt="night city racing - juego de carreras" /></noscript>								</a>
											<figcaption class="widget-image-caption wp-caption-text">Night City Racing</figcaption>
										</figure>
									</div>
				</div>
				<div class="elementor-element elementor-element-8abd9a1 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="8abd9a1" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-37243 post type-post status-publish format-standard has-post-thumbnail hentry category-carreras category-coches category-conducir category-unblocked-games-76-77-66-67-premium category-juegos-yandex">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/drift-hunters" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-37248" alt="Una imagen de estilo manga de un coche deportivo derrapando en una pista de carreras con las palabras &quot;Drift Hunters&quot; incorporadas en el diseño." data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/04/drift-hunters.png 150w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-48x48.png 48w" data-lazy-sizes="(max-width: 150px) 100vw, 150px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/04/drift-hunters.png" /><noscript><img decoding="async" width="150" height="150" src="https://ludorex.com/wp-content/uploads/2025/04/drift-hunters.png" class="attachment-thumbnail size-thumbnail wp-image-37248" alt="Una imagen de estilo manga de un coche deportivo derrapando en una pista de carreras con las palabras &quot;Drift Hunters&quot; incorporadas en el diseño." srcset="https://ludorex.com/wp-content/uploads/2025/04/drift-hunters.png 150w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/drift-hunters-48x48.png 48w" sizes="(max-width: 150px) 100vw, 150px" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/drift-hunters" >
				Drift Hunters			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36174 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos category-arcade category-lucha category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/golden-axe" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36182" alt="Golden Axe" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/fb45e196-279a-483f-634f-05a85e39db00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/fb45e196-279a-483f-634f-05a85e39db00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36182" alt="Golden Axe" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/golden-axe" >
				Golden Axe			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36123 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-arcade category-simulacion tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/epic-pinball" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36134" alt="Epic Pinball" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/08ff8b85-79d7-4c29-e33c-26a196729f00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/08ff8b85-79d7-4c29-e33c-26a196729f00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36134" alt="Epic Pinball" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/epic-pinball" >
				Epic Pinball			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36010 post type-post status-publish format-standard has-post-thumbnail hentry category-arcade category-puzzles tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/bust-a-move" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36016" alt="Bust-A-Move" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/05462975-513b-46c0-6306-2d5a2217a400/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/05462975-513b-46c0-6306-2d5a2217a400/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36016" alt="Bust-A-Move" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/bust-a-move" >
				Bust A Move			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-2044c70 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="2044c70" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-26272 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/super-pang" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-32474" alt="super pang" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/18c60ff2-cbf2-4833-61f1-aaff7b2a7500/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/18c60ff2-cbf2-4833-61f1-aaff7b2a7500/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-32474" alt="super pang" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/super-pang" >
				Super Pang			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34013 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/pong-atari" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34011" alt="pong" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2a978089-1b30-4fd2-46fa-9a379d476900/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2a978089-1b30-4fd2-46fa-9a379d476900/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34011" alt="pong" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/pong-atari" >
				Pong &#8211; Atari			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-33027 post type-post status-publish format-standard has-post-thumbnail hentry category-puzzles">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/bubble-shooter" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-33086" alt="Bubble Shooter" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/59fb9201-81d4-4b1e-ddad-a56bb7456800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/59fb9201-81d4-4b1e-ddad-a56bb7456800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-33086" alt="Bubble Shooter" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/bubble-shooter" >
				Bubble Shooter			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-5167 post type-post status-publish format-standard has-post-thumbnail hentry category-fireboy-and-watergirl category-aventuras tag-fuego-agua">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/nino-fuego-y-nina-agua-2-templo-de-luz" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-32467" alt="nino fuego y nina agua 2 - templo de luz" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b337d4b7-f8a5-444a-7dab-050d2ea34200/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b337d4b7-f8a5-444a-7dab-050d2ea34200/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-32467" alt="nino fuego y nina agua 2 - templo de luz" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/nino-fuego-y-nina-agua-2-templo-de-luz" >
				Niño fuego y niña agua 2: Templo de Luz			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-17ccc62 e-transform e-transform e-transform e-transform e-transform e-transform e-transform e-transform elementor-hidden-tablet elementor-widget elementor-widget-image" data-id="17ccc62" data-element_type="widget" data-settings="{&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.1,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleX_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleX_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleY_effect_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scaleY_effect_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_rotateZ_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="image.default">
				<div class="elementor-widget-container">
												<figure class="wp-caption">
											<a href="https://ludorex.com/juego/shell-shockers">
							<img decoding="async" width="300" height="300" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" class="attachment-medium size-medium wp-image-32781" alt="juego Shell Shockers" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b756ffc0-55c5-49f2-73a2-6df6b1dae100/w=300,h=300,fit=crop" /><noscript><img decoding="async" width="300" height="300" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b756ffc0-55c5-49f2-73a2-6df6b1dae100/w=300,h=300,fit=crop" class="attachment-medium size-medium wp-image-32781" alt="juego Shell Shockers" /></noscript>								</a>
											<figcaption class="widget-image-caption wp-caption-text">Shell Shockers</figcaption>
										</figure>
									</div>
				</div>
				<div class="elementor-element elementor-element-4a7584b elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="4a7584b" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-34470 post type-post status-publish format-standard has-post-thumbnail hentry category-aventuras category-unblocked-games-76-77-66-67-premium">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/jetpack-joyride" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34488" alt="Jetpack Joyride" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ce1a047f-32e4-45ec-1185-591226d50400/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/ce1a047f-32e4-45ec-1185-591226d50400/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34488" alt="Jetpack Joyride" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/jetpack-joyride" >
				Jetpack Joyride			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34408 post type-post status-publish format-standard has-post-thumbnail hentry category-casual">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/fruit-ninja" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34413" alt="Fruit Ninja" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bb26da6d-807b-40db-1f4d-e23f551aa000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bb26da6d-807b-40db-1f4d-e23f551aa000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34413" alt="Fruit Ninja" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/fruit-ninja" >
				Fruit Ninja			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34053 post type-post status-publish format-standard has-post-thumbnail hentry category-logica">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/tres-en-raya-para-2-jugadores" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34062" alt="Tres en Raya para 2 Jugadores" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/7173dd3c-41de-460b-e501-b007771c0300/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/7173dd3c-41de-460b-e501-b007771c0300/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34062" alt="Tres en Raya para 2 Jugadores" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/tres-en-raya-para-2-jugadores" >
				Tres en Raya para 2 Jugadores			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34031 post type-post status-publish format-standard has-post-thumbnail hentry category-click">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/juego-de-la-sandia" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34043" alt="juego de la sandia" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/50816596-e82b-40e8-5b7e-75ca9288ea00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/50816596-e82b-40e8-5b7e-75ca9288ea00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34043" alt="juego de la sandia" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/juego-de-la-sandia" >
				Juego de la Sandía			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-5b1483c elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="5b1483c" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-34690 post type-post status-publish format-standard has-post-thumbnail hentry category-rompecabezas">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/mahjong-magic-islands" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34703" alt="Mahjong Magic Islands" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/18d13754-7913-4d23-7d1e-42ed5e35e300/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/18d13754-7913-4d23-7d1e-42ed5e35e300/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34703" alt="Mahjong Magic Islands" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/mahjong-magic-islands" >
				Mahjong Magic Islands			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34535 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos category-street-fighter">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/marvel-vs-capcom-clash-of-super-heroes" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34550" alt="Marvel vs Capcom: Clash of Super Heroes" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1b6267b2-9541-4f9a-5cb9-2f556ce97f00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1b6267b2-9541-4f9a-5cb9-2f556ce97f00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34550" alt="Marvel vs Capcom: Clash of Super Heroes" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/marvel-vs-capcom-clash-of-super-heroes" >
				Marvel vs Capcom: Clash of Super Heroes			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34426 post type-post status-publish format-standard has-post-thumbnail hentry category-agilidad-habilidad-reflejos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/juego-del-dinosaurio" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34432" alt="juego del dinosaurio" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/5e0f6e59-210a-40d7-503e-6bbfd858cf00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/5e0f6e59-210a-40d7-503e-6bbfd858cf00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34432" alt="juego del dinosaurio" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/juego-del-dinosaurio" >
				Juego del dinosaurio			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34101 post type-post status-publish format-standard has-post-thumbnail hentry category-estrategia">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/alla-tu-online" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34452" alt="Deal or No Deal" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0a81aeb7-c0cc-408f-d54a-448cf5528200/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0a81aeb7-c0cc-408f-d54a-448cf5528200/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34452" alt="Deal or No Deal" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/alla-tu-online" >
				Alla tu Online			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-e87ae5e elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="e87ae5e" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-5167 post type-post status-publish format-standard has-post-thumbnail hentry category-fireboy-and-watergirl category-aventuras tag-fuego-agua">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/nino-fuego-y-nina-agua-2-templo-de-luz" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-32467" alt="nino fuego y nina agua 2 - templo de luz" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b337d4b7-f8a5-444a-7dab-050d2ea34200/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b337d4b7-f8a5-444a-7dab-050d2ea34200/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-32467" alt="nino fuego y nina agua 2 - templo de luz" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/nino-fuego-y-nina-agua-2-templo-de-luz" >
				Niño fuego y niña agua 2: Templo de Luz			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34506 post type-post status-publish format-standard has-post-thumbnail hentry category-fireboy-and-watergirl category-aventuras">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/fireboy-and-watergirl-1-forest-temple" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34521" alt="Fireboy and Watergirl 1 Forest Temple" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/be1eb619-8af4-4ef8-aae3-25a1f5822c00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/be1eb619-8af4-4ef8-aae3-25a1f5822c00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34521" alt="Fireboy and Watergirl 1 Forest Temple" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/fireboy-and-watergirl-1-forest-temple" >
				Fireboy and Watergirl 1 Forest Temple			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34559 post type-post status-publish format-standard has-post-thumbnail hentry category-fireboy-and-watergirl category-aventuras category-sin-categorizar">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/fireboy-and-watergirl-3-ice-temple" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34569" alt="Fireboy and Watergirl 3 Ice Temple" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/c1e635f7-fccf-428b-480f-58aa96f52600/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/c1e635f7-fccf-428b-480f-58aa96f52600/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34569" alt="Fireboy and Watergirl 3 Ice Temple" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/fireboy-and-watergirl-3-ice-temple" >
				Fireboy and Watergirl 3: Ice Temple			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34584 post type-post status-publish format-standard has-post-thumbnail hentry category-fireboy-and-watergirl category-aventuras">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/fireboy-and-watergirl-4-crystal-temple" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34586" alt="Fireboy and Watergirl 4 Crystal Temple" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/68a07f1a-1611-49d8-5745-38562cbffd00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/68a07f1a-1611-49d8-5745-38562cbffd00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34586" alt="Fireboy and Watergirl 4 Crystal Temple" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/fireboy-and-watergirl-4-crystal-temple" >
				Fireboy and Watergirl 4 Crystal Temple			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-bd85e0e e-transform elementor-hidden-tablet elementor-widget elementor-widget-image" data-id="bd85e0e" data-element_type="widget" data-settings="{&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.1,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="image.default">
				<div class="elementor-widget-container">
												<figure class="wp-caption">
											<a href="https://ludorex.com/juego/subway-surfers">
							<img decoding="async" width="300" height="300" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" class="attachment-medium size-medium wp-image-33702" alt="subway surfer" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/fb6719f4-4d5d-49c3-7ad2-ea1c311f0800/w=300,h=300,fit=crop" /><noscript><img decoding="async" width="300" height="300" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/fb6719f4-4d5d-49c3-7ad2-ea1c311f0800/w=300,h=300,fit=crop" class="attachment-medium size-medium wp-image-33702" alt="subway surfer" /></noscript>								</a>
											<figcaption class="widget-image-caption wp-caption-text">Subway Surfers</figcaption>
										</figure>
									</div>
				</div>
				<div class="elementor-element elementor-element-d8c48ea elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="d8c48ea" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-34876 post type-post status-publish format-standard has-post-thumbnail hentry category-casual category-io category-multijugador category-sin-categorizar tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/hole-io" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34899" alt="Hole.io" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/62c9a3fd-5f11-4e76-5a38-ad805a994600/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/62c9a3fd-5f11-4e76-5a38-ad805a994600/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34899" alt="Hole.io" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/hole-io" >
				Hole.io			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34829 post type-post status-publish format-standard has-post-thumbnail hentry category-click">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/cookie-clicker-cookies" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34853" alt="Cookie Clicker Cookies" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/97212478-d014-416b-fef8-d178aaccc300/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/97212478-d014-416b-fef8-d178aaccc300/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34853" alt="Cookie Clicker Cookies" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/cookie-clicker-cookies" >
				Cookie Clicker Cookies			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34803 post type-post status-publish format-standard has-post-thumbnail hentry category-futbol category-deportes">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/soccer-skills-champions-league" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34814" alt="Soccer Skills Champions League" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1fed5782-6476-4454-0500-c960f9e9e900/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1fed5782-6476-4454-0500-c960f9e9e900/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34814" alt="Soccer Skills Champions League" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/soccer-skills-champions-league" >
				Soccer Skills Champions League			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34774 post type-post status-publish format-standard has-post-thumbnail hentry category-puzzles">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/park-me" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34782" alt="Park Me" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/69707b08-1102-4dfb-e531-fb1663485c00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/69707b08-1102-4dfb-e531-fb1663485c00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34782" alt="Park Me" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/park-me" >
				Park Me			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-5ef1884 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="5ef1884" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35283 post type-post status-publish format-standard has-post-thumbnail hentry category-logica">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/fuzzies" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35304" alt="fuzzies" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bf6f90ff-6fec-478f-a6f1-3d310bef4700/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bf6f90ff-6fec-478f-a6f1-3d310bef4700/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35304" alt="fuzzies" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/fuzzies" >
				Fuzzies			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34969 post type-post status-publish format-standard has-post-thumbnail hentry category-autocar category-conducir">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/coach-bus-simulator" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34972" alt="Coach Bus Simulator" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f9191ec9-fc9b-4705-077f-f2922f3aaf00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f9191ec9-fc9b-4705-077f-f2922f3aaf00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34972" alt="Coach Bus Simulator" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/coach-bus-simulator" >
				Coach Bus Simulator			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34928 post type-post status-publish format-standard has-post-thumbnail hentry category-disparar category-disparos category-lucha category-multijugador">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/1v1-lol" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34930" alt="1v1 LOL" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/8467a81c-6e09-4cb7-61ab-cc338bf99e00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/8467a81c-6e09-4cb7-61ab-cc338bf99e00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34930" alt="1v1 LOL" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/1v1-lol" >
				1v1 LOL			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34909 post type-post status-publish format-standard has-post-thumbnail hentry category-lucha category-rompecabezas">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/crown-guard" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34912" alt="Crown Guard" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/483bc452-3a7c-43f2-92eb-005be0c9ca00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/483bc452-3a7c-43f2-92eb-005be0c9ca00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34912" alt="Crown Guard" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/crown-guard" >
				Crown Guard			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-9e3e46f e-transform elementor-hidden-tablet elementor-widget elementor-widget-image" data-id="9e3e46f" data-element_type="widget" data-settings="{&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.1,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="image.default">
				<div class="elementor-widget-container">
												<figure class="wp-caption">
											<a href="https://ludorex.com/juego/supermarket-simulator">
							<img decoding="async" width="300" height="300" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" class="attachment-medium size-medium wp-image-37239" alt="Hombre con delantal azul sosteniendo una caja llena de frutas y verduras frescas en el pasillo de un supermercado para el juego Supermarket Simulator." data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked.png 300w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-150x150.png 150w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-48x48.png 48w" data-lazy-sizes="(max-width: 300px) 100vw, 300px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked.png" /><noscript><img decoding="async" width="300" height="300" src="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked.png" class="attachment-medium size-medium wp-image-37239" alt="Hombre con delantal azul sosteniendo una caja llena de frutas y verduras frescas en el pasillo de un supermercado para el juego Supermarket Simulator." srcset="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked.png 300w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-150x150.png 150w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-unblocked-48x48.png 48w" sizes="(max-width: 300px) 100vw, 300px" /></noscript>								</a>
											<figcaption class="widget-image-caption wp-caption-text">Supermarket Simulator</figcaption>
										</figure>
									</div>
				</div>
				<div class="elementor-element elementor-element-b83fec5 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="b83fec5" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35317 post type-post status-publish format-standard has-post-thumbnail hentry category-accion">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/momo-horror-story" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35330" alt="momo horror story" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bca5c271-1e98-4185-6684-a3f79c638f00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bca5c271-1e98-4185-6684-a3f79c638f00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35330" alt="momo horror story" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/momo-horror-story" >
				Momo juego de terror			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35168 post type-post status-publish format-standard has-post-thumbnail hentry category-casual category-click">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/geometry-dash-wave" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35191" alt="Geometry Dash Wave" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2d9e0379-d9dd-4ceb-c11e-b399cbd25b00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2d9e0379-d9dd-4ceb-c11e-b399cbd25b00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35191" alt="Geometry Dash Wave" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/geometry-dash-wave" >
				Geometry Dash Wave			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35039 post type-post status-publish format-standard has-post-thumbnail hentry category-puzzles">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/sutom" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35057" alt="Sutom" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d6672248-1898-4012-5585-b5c1b4be5800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d6672248-1898-4012-5585-b5c1b4be5800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35057" alt="Sutom" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/sutom" >
				Sutom			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34988 post type-post status-publish format-standard has-post-thumbnail hentry category-colecciones-de-juegos category-clasicos category-mario">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/super-mario-world" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34993" alt="super mario world" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/69ec8b15-1356-4291-11c1-cea92e886d00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/69ec8b15-1356-4291-11c1-cea92e886d00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34993" alt="super mario world" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/super-mario-world" >
				Super Mario World			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-80e3846 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="80e3846" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35466 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-aventuras category-rpg-rol">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/epic-hero-quest-idle-rpg" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35477" alt="Epic Hero Quest Idle RPG" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/361bb141-30a8-44a3-da8d-82619fedb800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/361bb141-30a8-44a3-da8d-82619fedb800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35477" alt="Epic Hero Quest Idle RPG" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/epic-hero-quest-idle-rpg" >
				Epic Hero Quest: Idle RPG			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35426 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-arcade category-click category-lucha">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/sword-hunter" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35431" alt="Sword Hunter" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/26dcb84a-5079-47f5-511b-716964df5b00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/26dcb84a-5079-47f5-511b-716964df5b00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35431" alt="Sword Hunter" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/sword-hunter" >
				Sword Hunter			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35402 post type-post status-publish format-standard has-post-thumbnail hentry category-cartas category-educacion">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/uno-online-2-4-jugadores" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35413" alt="UNO online (2-4 Jugadores)" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/10a9b9d8-f5e1-43ad-2a10-8b5365fa1700/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/10a9b9d8-f5e1-43ad-2a10-8b5365fa1700/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35413" alt="UNO online (2-4 Jugadores)" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/uno-online-2-4-jugadores" >
				UNO online (2-4 Jugadores)			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35351 post type-post status-publish format-standard has-post-thumbnail hentry category-arcade">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/atari-centipede" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35356" alt="Atari Centipede" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/72d45fca-26d7-4baf-c843-d5e3413c0700/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/72d45fca-26d7-4baf-c843-d5e3413c0700/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35356" alt="Atari Centipede" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/atari-centipede" >
				Atari Centipede			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-8b03ee1 e-transform elementor-hidden-tablet elementor-widget elementor-widget-image" data-id="8b03ee1" data-element_type="widget" data-settings="{&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.1,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="image.default">
				<div class="elementor-widget-container">
												<figure class="wp-caption">
											<a href="https://ludorex.com/juego/monkey-mart">
							<img decoding="async" width="300" height="300" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" class="attachment-medium size-medium wp-image-32316" alt="monke mart pagina top" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1ed895b4-2ed7-47a2-39ca-73fa37e16500/w=300,h=300,fit=crop" /><noscript><img decoding="async" width="300" height="300" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1ed895b4-2ed7-47a2-39ca-73fa37e16500/w=300,h=300,fit=crop" class="attachment-medium size-medium wp-image-32316" alt="monke mart pagina top" /></noscript>								</a>
											<figcaption class="widget-image-caption wp-caption-text">Monkey Mart</figcaption>
										</figure>
									</div>
				</div>
				<div class="elementor-element elementor-element-58a9c0c elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="58a9c0c" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35621 post type-post status-publish format-standard has-post-thumbnail hentry category-colecciones-de-juegos category-aventuras category-mario">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/super-mario-land" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35626" alt="Super Mario Land" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/4e9b3790-e5ce-4518-29e1-2b3c0899a700/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/4e9b3790-e5ce-4518-29e1-2b3c0899a700/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35626" alt="Super Mario Land" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/super-mario-land" >
				Super Mario Land			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35594 post type-post status-publish format-standard has-post-thumbnail hentry category-colecciones-de-juegos category-aventuras category-mario">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/super-mario-rpg" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35608" alt="juego super mario rpg" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/4be2b82c-f5ca-4f32-693c-27e28766b700/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/4be2b82c-f5ca-4f32-693c-27e28766b700/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35608" alt="juego super mario rpg" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/super-mario-rpg" >
				Super Mario RPG			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35378 post type-post status-publish format-standard has-post-thumbnail hentry category-educacion category-para-ninos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/pacman-tablas-de-multiplicar" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35389" alt="PACMAN Tablas de Multiplicar" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/5ceeb2f9-8776-4fc8-93a4-805dcee20c00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/5ceeb2f9-8776-4fc8-93a4-805dcee20c00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35389" alt="PACMAN Tablas de Multiplicar" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/pacman-tablas-de-multiplicar" >
				Pacman Tablas de Multiplicar			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-34072 post type-post status-publish format-standard has-post-thumbnail hentry category-juegos-de-google-classroom category-para-ninos">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/pato-multiplicador" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-34081" alt="Pato Multiplicador" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1640b2a8-b229-4bb6-88b0-ca423a321000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/1640b2a8-b229-4bb6-88b0-ca423a321000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-34081" alt="Pato Multiplicador" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/pato-multiplicador" >
				Pato Multiplicador			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-5116b71 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="5116b71" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35653 post type-post status-publish format-standard has-post-thumbnail hentry category-disparar category-disparos category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/bullet-force" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35663" alt="Bullet Force" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/240a75f5-a169-4189-a32b-b58485554800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/240a75f5-a169-4189-a32b-b58485554800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35663" alt="Bullet Force" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/bullet-force" >
				Bullet Force			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35640 post type-post status-publish format-standard has-post-thumbnail hentry category-puzzles tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/a-dark-room" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35642" alt="A Dark Room" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/83d97ec6-837e-427c-d9da-da50633bb200/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/83d97ec6-837e-427c-d9da-da50633bb200/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35642" alt="A Dark Room" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/a-dark-room" >
				A Dark Room			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35532 post type-post status-publish format-standard has-post-thumbnail hentry category-estrategia">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/my-kingdom-for-the-princess" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35544" alt="My Kingdom for the Princess" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2f546263-5812-4393-f210-3a1bfebde300/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/2f546263-5812-4393-f210-3a1bfebde300/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35544" alt="My Kingdom for the Princess" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/my-kingdom-for-the-princess" >
				My Kingdom for the Princess			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35490 post type-post status-publish format-standard has-post-thumbnail hentry category-casual">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/calculadora-de-amor" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35512" alt="Calculadora de amor" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b2f362ec-fb30-4e90-1336-e963de4a7e00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b2f362ec-fb30-4e90-1336-e963de4a7e00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35512" alt="Calculadora de amor" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/calculadora-de-amor" >
				Calculadora de amor			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-cdd7297 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="cdd7297" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35729 post type-post status-publish format-standard has-post-thumbnail hentry category-casual tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/super-meat-boy" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35741" alt="Super Meat Boy" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a55caf51-eda7-4354-ba7c-543627c01d00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a55caf51-eda7-4354-ba7c-543627c01d00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35741" alt="Super Meat Boy" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/super-meat-boy" >
				Super Meat Boy			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35712 post type-post status-publish format-standard has-post-thumbnail hentry category-estrategia category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/little-war-game" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35717" alt="Little War Game" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/56a21e97-d2e7-4646-d8d6-08eb32c26400/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/56a21e97-d2e7-4646-d8d6-08eb32c26400/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35717" alt="Little War Game" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/little-war-game" >
				Little War Game			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35696 post type-post status-publish format-standard has-post-thumbnail hentry category-io category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/helmet-royale-io" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35701" alt="Helmet Royale" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/255125dd-6186-4a6a-455d-de56d4d4eb00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/255125dd-6186-4a6a-455d-de56d4d4eb00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35701" alt="Helmet Royale" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/helmet-royale-io" >
				Helmet Royale.io			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35677 post type-post status-publish format-standard has-post-thumbnail hentry category-rpg-rol category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/dragon-awaken" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35680" alt="Dragon Awaken" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/e1130a68-9f47-4a21-2110-54ca03d7a100/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/e1130a68-9f47-4a21-2110-54ca03d7a100/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35680" alt="Dragon Awaken" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/dragon-awaken" >
				Dragon Awaken			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-27c6396 e-transform elementor-hidden-tablet elementor-widget elementor-widget-image" data-id="27c6396" data-element_type="widget" data-settings="{&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.1,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="image.default">
				<div class="elementor-widget-container">
												<figure class="wp-caption">
											<a href="https://ludorex.com/juego/bloxd-io">
							<img decoding="async" width="300" height="300" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20300%20300'%3E%3C/svg%3E" class="attachment-medium size-medium wp-image-32802" alt="juego Bloxd.io" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f90292ff-af9d-4ff0-ceb7-ae785c04b200/w=300,h=300,fit=crop" /><noscript><img decoding="async" width="300" height="300" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f90292ff-af9d-4ff0-ceb7-ae785c04b200/w=300,h=300,fit=crop" class="attachment-medium size-medium wp-image-32802" alt="juego Bloxd.io" /></noscript>								</a>
											<figcaption class="widget-image-caption wp-caption-text">Bloxd.io</figcaption>
										</figure>
									</div>
				</div>
				<div class="elementor-element elementor-element-a3ce779 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="a3ce779" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35826 post type-post status-publish format-standard has-post-thumbnail hentry category-colecciones-de-juegos category-plataformas category-sonic tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/sonic-with-a-gun" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35831" alt="Sonic with a Gun" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/09593ca6-8a39-4c16-0dd2-199577802b00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/09593ca6-8a39-4c16-0dd2-199577802b00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35831" alt="Sonic with a Gun" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/sonic-with-a-gun" >
				Sonic with a Gun			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35800 post type-post status-publish format-standard has-post-thumbnail hentry category-arcade category-disparar category-disparos tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/sigil" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35805" alt="Sigil" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bdf30bbb-2074-4b88-3da8-77254c215000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bdf30bbb-2074-4b88-3da8-77254c215000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35805" alt="Sigil" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/sigil" >
				Sigil			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35772 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-lucha tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/science-kombat" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35781" alt="Science Kombat" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b0efba2c-10c8-4aa9-5266-712a7e6e4100/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/b0efba2c-10c8-4aa9-5266-712a7e6e4100/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35781" alt="Science Kombat" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/science-kombat" >
				Science Kombat			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35753 post type-post status-publish format-standard has-post-thumbnail hentry category-accion tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/samurai-shodown" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35761" alt="Samurai Shodown" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/212583a8-2dd3-4180-6ec0-9a95f46e8a00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/212583a8-2dd3-4180-6ec0-9a95f46e8a00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35761" alt="Samurai Shodown" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/samurai-shodown" >
				Samurai Shodown			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-3501b7d elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="3501b7d" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-35941 post type-post status-publish format-standard has-post-thumbnail hentry category-disparar category-disparos tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/warscrap" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="130" height="130" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20130%20130'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35948" alt="Warscrap" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/6ae1db51-96e8-4f2d-7165-19811e115d00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="130" height="130" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/6ae1db51-96e8-4f2d-7165-19811e115d00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35948" alt="Warscrap" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/warscrap" >
				Warscrap			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35918 post type-post status-publish format-standard has-post-thumbnail hentry category-lucha category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/treasure-arena" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35927" alt="Treasure Arena" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/7a21065b-91d1-405f-eb09-85a390608000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/7a21065b-91d1-405f-eb09-85a390608000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35927" alt="Treasure Arena" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/treasure-arena" >
				Treasure Arena			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35893 post type-post status-publish format-standard has-post-thumbnail hentry category-logica category-rompecabezas tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/tiny-heist" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35898" alt="Tiny Heist" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/324b1fae-c8c2-4348-0e8b-f9e6dfa93e00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/324b1fae-c8c2-4348-0e8b-f9e6dfa93e00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35898" alt="Tiny Heist" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/tiny-heist" >
				Tiny Heist			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35856 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/tanki-online" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35867" alt="Tanki Online" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0b9b71b6-399f-4fe6-c569-a0b9923c1000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/0b9b71b6-399f-4fe6-c569-a0b9923c1000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35867" alt="Tanki Online" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/tanki-online" >
				Tanki Online			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-c5e9cd6 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="c5e9cd6" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-36029 post type-post status-publish format-standard has-post-thumbnail hentry category-estrategia tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/command-conquer-red-alert" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36035" alt="Command and Conquer Red Alert" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/9bb1b6bc-9d49-4b05-dd77-2af597141e00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/9bb1b6bc-9d49-4b05-dd77-2af597141e00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36035" alt="Command and Conquer Red Alert" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/command-conquer-red-alert" >
				Command &amp; Conquer: Red Alert			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36010 post type-post status-publish format-standard has-post-thumbnail hentry category-arcade category-puzzles tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/bust-a-move" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36016" alt="Bust-A-Move" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/05462975-513b-46c0-6306-2d5a2217a400/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/05462975-513b-46c0-6306-2d5a2217a400/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36016" alt="Bust-A-Move" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/bust-a-move" >
				Bust A Move			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35989 post type-post status-publish format-standard has-post-thumbnail hentry category-puzzles category-rompecabezas tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/alone-in-the-dark" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35998" alt="Alone in the dark" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/631fed0f-1031-4bef-bd39-1d9951e3ec00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/631fed0f-1031-4bef-bd39-1d9951e3ec00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35998" alt="Alone in the dark" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/alone-in-the-dark" >
				Alone in the dark			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35973 post type-post status-publish format-standard has-post-thumbnail hentry category-accion tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/vampire-survivors" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35975" alt="Vampire Survivors" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/c1e7596a-1ff8-4e84-8b4d-ab9b063a8e00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/c1e7596a-1ff8-4e84-8b4d-ab9b063a8e00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35975" alt="Vampire Survivors" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/vampire-survivors" >
				Vampire Survivors			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-b68e60f elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="b68e60f" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-36108 post type-post status-publish format-standard has-post-thumbnail hentry category-logica category-rompecabezas category-linkedin-games">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/queens" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36113" alt="Queens" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a303fca3-0b81-4e36-645d-fe2b3db14900/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/a303fca3-0b81-4e36-645d-fe2b3db14900/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36113" alt="Queens" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/queens" >
				Queens			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36093 post type-post status-publish format-standard has-post-thumbnail hentry category-estrategia tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/dune-2-the-building-of-a-dinasty" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36098" alt="Dune 2 - The Building of a Dinasty" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/6e20f864-f602-4526-e472-ea28ba543800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/6e20f864-f602-4526-e472-ea28ba543800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36098" alt="Dune 2 - The Building of a Dinasty" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/dune-2-the-building-of-a-dinasty" >
				Dune 2 &#8211; The Building of a Dinasty			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36077 post type-post status-publish format-standard has-post-thumbnail hentry category-lucha tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/double-dragon" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36083" alt="Double Dragon" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/6146cf15-12f3-4c22-ee4c-f0e71eb05800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/6146cf15-12f3-4c22-ee4c-f0e71eb05800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36083" alt="Double Dragon" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/double-dragon" >
				Double Dragon			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36056 post type-post status-publish format-standard has-post-thumbnail hentry category-aventuras category-rpg-rol tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/diablo" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36064" alt="Diablo" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d0c0888e-65a0-475d-341b-c1fdddd9b300/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/d0c0888e-65a0-475d-341b-c1fdddd9b300/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36064" alt="Diablo" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/diablo" >
				Diablo			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-04167e2 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="04167e2" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-36198 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos category-aventuras tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/indiana-jones-and-the-last-crusade" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36206" alt="Indiana Jones and the Last Crusade" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/13755408-89c4-4b5d-d406-ec72b1650600/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/13755408-89c4-4b5d-d406-ec72b1650600/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36206" alt="Indiana Jones and the Last Crusade" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/indiana-jones-and-the-last-crusade" >
				Indiana Jones and the Last Crusade			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36174 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos category-arcade category-lucha category-multijugador tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/golden-axe" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36182" alt="Golden Axe" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/fb45e196-279a-483f-634f-05a85e39db00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/fb45e196-279a-483f-634f-05a85e39db00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36182" alt="Golden Axe" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/golden-axe" >
				Golden Axe			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36148 post type-post status-publish format-standard has-post-thumbnail hentry category-rpg-rol tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/eye-of-the-beholder" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36158" alt="Eye of the Beholder" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/5869b45d-8408-4e1f-7491-31d37456c900/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/5869b45d-8408-4e1f-7491-31d37456c900/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36158" alt="Eye of the Beholder" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/eye-of-the-beholder" >
				Eye of the Beholder			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36123 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-arcade category-simulacion tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/epic-pinball" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36134" alt="Epic Pinball" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/08ff8b85-79d7-4c29-e33c-26a196729f00/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/08ff8b85-79d7-4c29-e33c-26a196729f00/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36134" alt="Epic Pinball" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/epic-pinball" >
				Epic Pinball			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-467df32 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="467df32" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-36624 post type-post status-publish format-standard has-post-thumbnail hentry category-baloncesto category-deportes category-unblocked-games-76-77-66-67-premium category-juegos-yandex">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/tap-tap-shots" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36628" alt="Ilustración futurista de un juego arcade de baloncesto con efectos de neón y un balón iluminado apuntando hacia la canasta. Inspirado en Tap Tap Shots." data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots.avif 150w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-40x40.jpg 40w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-64x64.jpg 64w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-24x24.jpg 24w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-36x36.jpg 36w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-48x48.jpg 48w" data-lazy-sizes="(max-width: 150px) 100vw, 150px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots.avif" /><noscript><img decoding="async" width="150" height="150" src="https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots.avif" class="attachment-thumbnail size-thumbnail wp-image-36628" alt="Ilustración futurista de un juego arcade de baloncesto con efectos de neón y un balón iluminado apuntando hacia la canasta. Inspirado en Tap Tap Shots." srcset="https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots.avif 150w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-40x40.jpg 40w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-64x64.jpg 64w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-24x24.jpg 24w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-36x36.jpg 36w, https://ludorex.com/wp-content/uploads/2025/02/tap-tap-shots-48x48.jpg 48w" sizes="(max-width: 150px) 100vw, 150px" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/tap-tap-shots" >
				Tap Tap Shots			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36453 post type-post status-publish format-standard has-post-thumbnail hentry category-puzzles category-linkedin-games">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/tango" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36460" alt="Juego de mesa digital Tango con diseño colorido y futurista. Tablero 4x4 con fichas azules, naranjas y amarillas, interfaz interactiva con puntuaciones y controles. Aplicación de juego moderna con gráficos vibrantes y temática estratégica." data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f4b277b4-65e7-4b8e-697f-006cf19e5700/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/f4b277b4-65e7-4b8e-697f-006cf19e5700/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36460" alt="Juego de mesa digital Tango con diseño colorido y futurista. Tablero 4x4 con fichas azules, naranjas y amarillas, interfaz interactiva con puntuaciones y controles. Aplicación de juego moderna con gráficos vibrantes y temática estratégica." /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/tango" >
				Tango			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36290 post type-post status-publish format-standard has-post-thumbnail hentry category-logica category-deportes">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/adivinar-futbolistas" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36299" alt="Adivinar Futbolistas" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/701387f8-6baa-4686-f23b-3f5037092800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/701387f8-6baa-4686-f23b-3f5037092800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36299" alt="Adivinar Futbolistas" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/adivinar-futbolistas" >
				Adivinar futbolistas			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36269 post type-post status-publish format-standard has-post-thumbnail hentry category-clasicos category-accion category-plataformas tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/prince-of-persia" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36277" alt="Prince of Persia" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/916b76ee-3708-4cfc-771d-05f04ea08800/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/916b76ee-3708-4cfc-771d-05f04ea08800/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-36277" alt="Prince of Persia" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/prince-of-persia" >
				Prince of Persia			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-a0e26f0 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="a0e26f0" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-37213 post type-post status-publish format-standard has-post-thumbnail hentry category-casual category-gestion category-simulacion category-unblocked-games-76-77-66-67-premium category-juegos-yandex">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/supermarket-simulator" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-37219" alt="Supermarket Simulator: ¡Descubre la Emoción de Gestionar Tu Propio Supermercado 3D! Haz Clic y Empieza a Jugar Gratis" data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator.png 150w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-48x48.png 48w" data-lazy-sizes="(max-width: 150px) 100vw, 150px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator.png" /><noscript><img decoding="async" width="150" height="150" src="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator.png" class="attachment-thumbnail size-thumbnail wp-image-37219" alt="Supermarket Simulator: ¡Descubre la Emoción de Gestionar Tu Propio Supermercado 3D! Haz Clic y Empieza a Jugar Gratis" srcset="https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator.png 150w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/supermarket-simulator-48x48.png 48w" sizes="(max-width: 150px) 100vw, 150px" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/supermarket-simulator" >
				Supermarket Simulator			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-37076 post type-post status-publish format-standard has-post-thumbnail hentry category-accion category-batalla-naval-online category-estrategia">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/world-of-warships" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-37085" alt="Submarinos de guerra navegando en alta mar durante una batalla naval épica al atardecer en World of Warships, con olas violentas y montañas al fondo." data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/04/World-of-warships.png 150w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-48x48.png 48w" data-lazy-sizes="(max-width: 150px) 100vw, 150px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/04/World-of-warships.png" /><noscript><img decoding="async" width="150" height="150" src="https://ludorex.com/wp-content/uploads/2025/04/World-of-warships.png" class="attachment-thumbnail size-thumbnail wp-image-37085" alt="Submarinos de guerra navegando en alta mar durante una batalla naval épica al atardecer en World of Warships, con olas violentas y montañas al fondo." srcset="https://ludorex.com/wp-content/uploads/2025/04/World-of-warships.png 150w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/World-of-warships-48x48.png 48w" sizes="(max-width: 150px) 100vw, 150px" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/world-of-warships" >
				World of Warships &#8211; Juego de barcos de batalla naval			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-36635 post type-post status-publish format-standard has-post-thumbnail hentry category-futbol category-deportes category-unblocked-games-76-77-66-67-premium category-juegos-yandex">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/a-small-world-cup" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-36639" alt="Ilustración digital vibrante de un partido de fútbol en un estadio lleno de espectadores en A Small World Cup, con jugadores caricaturescos realizando acrobacias en el aire mientras intentan anotar un gol. La imagen refleja dinamismo, emoción y un estilo humorístico y simplificado" data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup.avif 150w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-40x40.jpg 40w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-64x64.jpg 64w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-24x24.jpg 24w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-36x36.jpg 36w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-48x48.jpg 48w" data-lazy-sizes="(max-width: 150px) 100vw, 150px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup.avif" /><noscript><img decoding="async" width="150" height="150" src="https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup.avif" class="attachment-thumbnail size-thumbnail wp-image-36639" alt="Ilustración digital vibrante de un partido de fútbol en un estadio lleno de espectadores en A Small World Cup, con jugadores caricaturescos realizando acrobacias en el aire mientras intentan anotar un gol. La imagen refleja dinamismo, emoción y un estilo humorístico y simplificado" srcset="https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup.avif 150w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-40x40.jpg 40w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-64x64.jpg 64w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-24x24.jpg 24w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-36x36.jpg 36w, https://ludorex.com/wp-content/uploads/2025/02/A-Small-World-Cup-48x48.jpg 48w" sizes="(max-width: 150px) 100vw, 150px" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/a-small-world-cup" >
				A Small World Cup			</a>
		</h2>
				</div>
					</div>
		</article>
				<article class="elementor-post elementor-grid-item post-35800 post type-post status-publish format-standard has-post-thumbnail hentry category-arcade category-disparar category-disparos tag-vidaextra">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/sigil" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-35805" alt="Sigil" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bdf30bbb-2074-4b88-3da8-77254c215000/w=150,h=150,fit=crop" /><noscript><img decoding="async" width="150" height="150" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/bdf30bbb-2074-4b88-3da8-77254c215000/w=150,h=150,fit=crop" class="attachment-thumbnail size-thumbnail wp-image-35805" alt="Sigil" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/sigil" >
				Sigil			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				<div class="elementor-element elementor-element-3e851a5 elementor-grid-mobile-2 elementor-posts--align-center elementor-grid-tablet-1 limitado elementor-posts__hover-none e-transform e-transform e-transform elementor-grid-2 elementor-posts--thumbnail-top elementor-widget elementor-widget-posts" data-id="3e851a5" data-element_type="widget" data-settings="{&quot;cards_columns_mobile&quot;:&quot;2&quot;,&quot;cards_row_gap_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:14,&quot;sizes&quot;:[]},&quot;cards_columns_tablet&quot;:&quot;1&quot;,&quot;cards_row_gap&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:15,&quot;sizes&quot;:[]},&quot;cards_masonry&quot;:&quot;yes&quot;,&quot;_transform_scale_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1.05,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:1,&quot;sizes&quot;:[]},&quot;cards_columns&quot;:&quot;2&quot;,&quot;cards_row_gap_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_translateY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_scale_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewX_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover&quot;:{&quot;unit&quot;:&quot;px&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_tablet&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]},&quot;_transform_skewY_effect_hover_mobile&quot;:{&quot;unit&quot;:&quot;deg&quot;,&quot;size&quot;:&quot;&quot;,&quot;sizes&quot;:[]}}" data-widget_type="posts.cards">
				<div class="elementor-widget-container">
							<div class="elementor-posts-container elementor-posts elementor-posts--skin-cards elementor-grid">
				<article class="elementor-post elementor-grid-item post-37524 post type-post status-publish format-standard has-post-thumbnail hentry category-casual category-coches category-unblocked-games-76-77-66-67-premium">
			<div class="elementor-post__card">
				<a class="elementor-post__thumbnail__link" href="https://ludorex.com/juego/drift-boss" tabindex="-1" ><div class="elementor-post__thumbnail"><img decoding="async" width="150" height="150" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20150%20150'%3E%3C/svg%3E" class="attachment-thumbnail size-thumbnail wp-image-37530" alt="Coche verde pixel art derrapando con humo en pista retro de Drift Boss" data-lazy-srcset="https://ludorex.com/wp-content/uploads/2025/04/drift-boss.png 150w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-48x48.png 48w" data-lazy-sizes="(max-width: 150px) 100vw, 150px" data-lazy-src="https://ludorex.com/wp-content/uploads/2025/04/drift-boss.png" /><noscript><img decoding="async" width="150" height="150" src="https://ludorex.com/wp-content/uploads/2025/04/drift-boss.png" class="attachment-thumbnail size-thumbnail wp-image-37530" alt="Coche verde pixel art derrapando con humo en pista retro de Drift Boss" srcset="https://ludorex.com/wp-content/uploads/2025/04/drift-boss.png 150w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-12x12.png 12w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-40x40.png 40w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-64x64.png 64w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-24x24.png 24w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-36x36.png 36w, https://ludorex.com/wp-content/uploads/2025/04/drift-boss-48x48.png 48w" sizes="(max-width: 150px) 100vw, 150px" /></noscript></div></a>
				<div class="elementor-post__text">
				<h2 class="elementor-post__title">
			<a href="https://ludorex.com/juego/drift-boss" >
				Drift Boss			</a>
		</h2>
				</div>
					</div>
		</article>
				</div>
		
						</div>
				</div>
				</div>
				</article>
				</article>
				<main class="elementor-section elementor-top-section elementor-element elementor-element-3800f1f3 elementor-section-full_width elementor-section-height-default elementor-section-height-default" data-id="3800f1f3" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;}">
						<div class="elementor-container elementor-column-gap-default">
					<article class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-56a3a20" data-id="56a3a20" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-d8071b0 elementor-widget elementor-widget-text-editor" data-id="d8071b0" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<h2><span style="color: #ffffff;">Disfruta de Juegos Gratuitos Online</span></h2><p>En la era digital, los juegos web gratuitos se han convertido en una de las formas más entretenidas de relajarse. Los juegos basados en HTML5 ofrecen una experiencia de juego fluida y sin interrupciones, sin necesidad de descargas ni instalaciones complicadas.</p><h2><span style="color: #ffffff;">Ventajas de Jugar Juegos Gratuitos en Línea</span></h2><ul><li><span style="color: #ffffff;"><strong>Acceso Instantáneo</strong>: Juega desde cualquier lugar con conexión a internet.</span></li><li><span style="color: #ffffff;"><strong>Compatibilidad</strong>: Los juegos son compatibles tanto en PC como en dispositivos móviles.</span></li><li><span style="color: #ffffff;"><strong>Diversidad</strong>: Una amplia gama de géneros, desde acción y aventuras hasta rompecabezas y juegos educativos.</span></li><li><span style="color: #ffffff;"><strong>Actualizaciones Frecuentes</strong>: Nuevas funcionalidades y juegos para mantener el interés.</span></li></ul><h2><span style="color: #ffffff;">Optimiza tu Experiencia de Juego</span></h2><ul><li><span style="color: #ffffff;">Utiliza navegadores modernos como Microsoft Edge, Google Chrome o Mozilla Firefox.</span></li><li><span style="color: #ffffff;">Mantén una conexión a internet estable para evitar interrupciones.</span></li><li><span style="color: #ffffff;">Disfruta de la adaptabilidad de los juegos a diferentes dispositivos.</span></li><li><span style="color: #ffffff;">Explora diferentes géneros para encontrar tus juegos favoritos.</span></li></ul>								</div>
				</div>
					</div>
		</article>
					</div>
		</main>
				</div>
				<div data-elementor-type="footer" data-elementor-id="34245" class="elementor elementor-34245 elementor-location-footer" data-elementor-post-type="elementor_library">
					<footer class="elementor-section elementor-top-section elementor-element elementor-element-31bac8c elementor-section-full_width elementor-section-stretched elementor-section-height-default elementor-section-height-default" data-id="31bac8c" data-element_type="section" data-settings="{&quot;background_background&quot;:&quot;classic&quot;,&quot;stretch_section&quot;:&quot;section-stretched&quot;}">
							<div class="elementor-background-overlay"></div>
							<div class="elementor-container elementor-column-gap-no">
					<div class="elementor-column elementor-col-100 elementor-top-column elementor-element elementor-element-77c84f9" data-id="77c84f9" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<footer class="elementor-section elementor-inner-section elementor-element elementor-element-f3f8856 elementor-section-full_width elementor-hidden-mobile elementor-section-height-default elementor-section-height-default" data-id="f3f8856" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<footer class="elementor-column elementor-col-33 elementor-inner-column elementor-element elementor-element-2e87635 elementor-hidden-mobile" data-id="2e87635" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-a67eccf elementor-widget elementor-widget-image" data-id="a67eccf" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
																<a href="https://ludorex.com">
							<img width="536" height="194" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20536%20194'%3E%3C/svg%3E" class="attachment-large size-large wp-image-35211" alt="ludorex" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/06c8e63a-c82a-4cb1-3b8f-6756b7797100/w=536,h=194" /><noscript><img width="536" height="194" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/06c8e63a-c82a-4cb1-3b8f-6756b7797100/w=536,h=194" class="attachment-large size-large wp-image-35211" alt="ludorex" /></noscript>								</a>
															</div>
				</div>
				<div class="elementor-element elementor-element-82bbe01 elementor-widget elementor-widget-text-editor" data-id="82bbe01" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p style="text-align: center;"><span style="color: #ffffff;">Copyright © 2024. All rights reserved. ludorex.com</span></p>								</div>
				</div>
				<div class="elementor-element elementor-element-ac7fe51 elementor-widget elementor-widget-html" data-id="ac7fe51" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
					<script type="rocketlazyloadscript">function toggleFullscreen(elem) {
  elem = elem || document.documentElement;

  if (!document.fullscreenElement && !document.mozFullScreenElement &&
    !document.webkitFullscreenElement && !document.msFullscreenElement) {
    if (elem.requestFullscreen) {
      elem.requestFullscreen();
    } else if (elem.msRequestFullscreen) {
      elem.msRequestFullscreen();
    } else if (elem.mozRequestFullScreen) {
      elem.mozRequestFullScreen();
    } else if (elem.webkitRequestFullscreen) {
      elem.webkitRequestFullscreen(Element.ALLOW_KEYBOARD_INPUT);
    }
  } else {
    if (document.exitFullscreen) {
      document.exitFullscreen();
    } else if (document.msExitFullscreen) {
      document.msExitFullscreen();
    } else if (document.mozCancelFullScreen) {
      document.mozCancelFullScreen();
    } else if (document.webkitExitFullscreen) {
      document.webkitExitFullscreen();
    }
  }
}

document.getElementById('btnFullscreen').addEventListener('click', function() {
  toggleFullscreen();
});</script>				</div>
				</div>
					</div>
		</footer>
				<footer class="elementor-column elementor-col-33 elementor-inner-column elementor-element elementor-element-16d288a elementor-hidden-mobile" data-id="16d288a" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-4e2db42 elementor-widget elementor-widget-html" data-id="4e2db42" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
					<span style="color: #ffffff;"><a style="color: #ffffff;" href="https://ludorex.com/politica-de-privacidad">Política de privacidad</a></span><br><br>
<span style="color: #ffffff;"><a style="color: #ffffff;" href="https://ludorex.com/terminos-y-condiciones-de-uso" target="_blank" rel="noopener">Términos y condiciones de uso</a></span><br><br>
<a href="https://ludorex.com/acerca-de-mi"><span style="color: #ffffff;">Contacto</span></a><br><br>
<span style="color: #ffffff;"><a style="color: #ffffff;" href="https://ludorex.com/sitemap_index.xml">Sitemap</a></span><br><br>
<span style="color: #ffffff;"><a href="" class="cmplz-show-banner" style="color: #ffffff;">Preferencias Cookies</a></span>				</div>
				</div>
					</div>
		</footer>
				<footer class="elementor-column elementor-col-33 elementor-inner-column elementor-element elementor-element-c5080c0 elementor-hidden-mobile" data-id="c5080c0" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-735fd28 elementor-widget elementor-widget-shortcode" data-id="735fd28" data-element_type="widget" data-widget_type="shortcode.default">
				<div class="elementor-widget-container">
							<div class="elementor-shortcode"><div class="trp_language_switcher_shortcode">
<div class="trp-language-switcher trp-language-switcher-container" data-no-translation >
    <div class="trp-ls-shortcode-current-language">
        <a href="#" class="trp-ls-shortcode-disabled-language trp-ls-disabled-language" title="Spanish" onclick="event.preventDefault()">
			<img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="es_ES" title="Spanish" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/es_ES.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/es_ES.png" width="18" height="12" alt="es_ES" title="Spanish"></noscript> Spanish		</a>
    </div>
    <div class="trp-ls-shortcode-language">
                <a href="#" class="trp-ls-shortcode-disabled-language trp-ls-disabled-language"  title="Spanish" onclick="event.preventDefault()">
			<img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="es_ES" title="Spanish" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/es_ES.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/es_ES.png" width="18" height="12" alt="es_ES" title="Spanish"></noscript> Spanish		</a>
                    <a href="https://ludorex.com/en" title="English">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="en_US" title="English" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/en_US.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/en_US.png" width="18" height="12" alt="en_US" title="English"></noscript> English        </a>

            <a href="https://ludorex.com/ko" title="Korean">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="ko_KR" title="Korean" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/ko_KR.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/ko_KR.png" width="18" height="12" alt="ko_KR" title="Korean"></noscript> Korean        </a>

            <a href="https://ludorex.com/ru" title="Russian">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="ru_RU" title="Russian" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/ru_RU.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/ru_RU.png" width="18" height="12" alt="ru_RU" title="Russian"></noscript> Russian        </a>

            <a href="https://ludorex.com/hi" title="Hindi">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="hi_IN" title="Hindi" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/hi_IN.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/hi_IN.png" width="18" height="12" alt="hi_IN" title="Hindi"></noscript> Hindi        </a>

            <a href="https://ludorex.com/pt" title="Portuguese">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="pt_BR" title="Portuguese" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/pt_BR.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/pt_BR.png" width="18" height="12" alt="pt_BR" title="Portuguese"></noscript> Portuguese        </a>

            <a href="https://ludorex.com/tr" title="Turkish">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="tr_TR" title="Turkish" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/tr_TR.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/tr_TR.png" width="18" height="12" alt="tr_TR" title="Turkish"></noscript> Turkish        </a>

            <a href="https://ludorex.com/vi" title="Vietnamese">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="vi" title="Vietnamese" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/vi.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/vi.png" width="18" height="12" alt="vi" title="Vietnamese"></noscript> Vietnamese        </a>

            <a href="https://ludorex.com/it" title="Italian">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="it_IT" title="Italian" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/it_IT.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/it_IT.png" width="18" height="12" alt="it_IT" title="Italian"></noscript> Italian        </a>

            <a href="https://ludorex.com/fr" title="French">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="fr_FR" title="French" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/fr_FR.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/fr_FR.png" width="18" height="12" alt="fr_FR" title="French"></noscript> French        </a>

            <a href="https://ludorex.com/ja" title="Japanese">
            <img class="trp-flag-image" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%2018%2012'%3E%3C/svg%3E" width="18" height="12" alt="ja" title="Japanese" data-lazy-src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/ja.png"><noscript><img class="trp-flag-image" src="https://ludorex.com/wp-content/plugins/translatepress-multilingual/assets/images/flags/ja.png" width="18" height="12" alt="ja" title="Japanese"></noscript> Japanese        </a>

        </div>
    <script type="rocketlazyloadscript" data-rocket-type="application/javascript">
        // need to have the same with set from JS on both divs. Otherwise it can push stuff around in HTML
        var trp_ls_shortcodes = document.querySelectorAll('.trp_language_switcher_shortcode .trp-language-switcher');
        if ( trp_ls_shortcodes.length > 0) {
            // get the last language switcher added
            var trp_el = trp_ls_shortcodes[trp_ls_shortcodes.length - 1];

            var trp_shortcode_language_item = trp_el.querySelector( '.trp-ls-shortcode-language' )
            // set width
            var trp_ls_shortcode_width                                               = trp_shortcode_language_item.offsetWidth + 16;
            trp_shortcode_language_item.style.width                                  = trp_ls_shortcode_width + 'px';
            trp_el.querySelector( '.trp-ls-shortcode-current-language' ).style.width = trp_ls_shortcode_width + 'px';

            // We're putting this on display: none after we have its width.
            trp_shortcode_language_item.style.display = 'none';
        }
    </script>
</div>
</div></div>
						</div>
				</div>
					</div>
		</footer>
					</div>
		</footer>
				<footer class="elementor-section elementor-inner-section elementor-element elementor-element-89639d5 elementor-section-full_width elementor-section-height-default elementor-section-height-default" data-id="89639d5" data-element_type="section">
						<div class="elementor-container elementor-column-gap-default">
					<footer class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-212342b elementor-hidden-desktop elementor-hidden-tablet" data-id="212342b" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-e348ee8 elementor-widget elementor-widget-html" data-id="e348ee8" data-element_type="widget" data-widget_type="html.default">
				<div class="elementor-widget-container">
					<span style="color: #ffffff;"><a style="color: #ffffff;" href="https://ludorex.com/politica-de-privacidad">Política de privacidad</a></span><br><br>
<span style="color: #ffffff;"><a style="color: #ffffff;" href="https://ludorex.com/terminos-y-condiciones-de-uso" target="_blank" rel="noopener">Términos y condiciones de uso</a></span><br><br>
<a href="https://ludorex.com/acerca-de-mi"><span style="color: #ffffff;">Contacto</span></a><br><br>
<span style="color: #ffffff;"><a style="color: #ffffff;" href="https://ludorex.com/sitemap_index.xml">Sitemap</a></span><br><br>
<span style="color: #ffffff;"><a href="" class="cmplz-show-banner" style="color: #ffffff;">Preferencias Cookies</a></span>				</div>
				</div>
					</div>
		</footer>
				<footer class="elementor-column elementor-col-50 elementor-inner-column elementor-element elementor-element-1f54526 elementor-hidden-desktop elementor-hidden-tablet" data-id="1f54526" data-element_type="column">
			<div class="elementor-widget-wrap elementor-element-populated">
						<div class="elementor-element elementor-element-decb5b9 elementor-widget elementor-widget-image" data-id="decb5b9" data-element_type="widget" data-widget_type="image.default">
				<div class="elementor-widget-container">
																<a href="https://ludorex.com">
							<img width="536" height="194" src="data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20536%20194'%3E%3C/svg%3E" class="attachment-large size-large wp-image-35211" alt="ludorex" data-lazy-src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/06c8e63a-c82a-4cb1-3b8f-6756b7797100/w=536,h=194" /><noscript><img width="536" height="194" src="https://imagedelivery.net/Gz9njdoQWfQyE3LMlxhb2w/06c8e63a-c82a-4cb1-3b8f-6756b7797100/w=536,h=194" class="attachment-large size-large wp-image-35211" alt="ludorex" /></noscript>								</a>
															</div>
				</div>
				<div class="elementor-element elementor-element-0dd7059 elementor-widget elementor-widget-text-editor" data-id="0dd7059" data-element_type="widget" data-widget_type="text-editor.default">
				<div class="elementor-widget-container">
									<p style="text-align: center;"><span style="color: #ffffff;">Copyright © 2024. All rights reserved. ludorex.com</span></p>								</div>
				</div>
					</div>
		</footer>
					</div>
		</footer>
					</div>
		</div>
					</div>
		</footer>
				</div>
		
<template id="tp-language" data-tp-language="es_ES"></template><script type="speculationrules">
{"prerender":[{"source":"document","where":{"and":[{"href_matches":"\/*"},{"not":{"href_matches":["\/wp-*.php","\/wp-admin\/*","\/wp-content\/uploads\/*","\/wp-content\/*","\/wp-content\/plugins\/*","\/wp-content\/themes\/vikinger-child\/*","\/wp-content\/themes\/vikinger\/*","\/*\\?(.+)"]}},{"not":{"selector_matches":"a[rel~=\"nofollow\"]"}},{"not":{"selector_matches":".no-prerender, .no-prerender a"}},{"not":{"selector_matches":".no-prefetch, .no-prefetch a"}}]},"eagerness":"moderate"}]}
</script>
    <script type="rocketlazyloadscript">
        function addEvent(event, selector, callback, context) {
            document.addEventListener(event, e => {
                if ( e.target.closest(selector) ) {
                    callback(e);
                }
            });
        }
        addEvent('click', '.cmplz-show-banner', function(){
            document.querySelectorAll('.cmplz-manage-consent').forEach(obj => {
                obj.click();
            });
        });
    </script>
    
<!-- Consent Management powered by Complianz | GDPR/CCPA Cookie Consent https://wordpress.org/plugins/complianz-gdpr -->
<div id="cmplz-cookiebanner-container"><div class="cmplz-cookiebanner cmplz-hidden banner-1 bottom-right-view-preferences optin cmplz-center cmplz-categories-type-view-preferences" aria-modal="true" data-nosnippet="true" role="dialog" aria-live="polite" aria-labelledby="cmplz-header-1-optin" aria-describedby="cmplz-message-1-optin">
	<div class="cmplz-header">
		<div class="cmplz-logo"></div>
		<div class="cmplz-title" id="cmplz-header-1-optin">Gestionar el consentimiento de las cookies</div>
		<div class="cmplz-close" tabindex="0" role="button" aria-label="Cerrar ventana">
			<svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="times" class="svg-inline--fa fa-times fa-w-11" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 352 512"><path fill="currentColor" d="M242.72 256l100.07-100.07c12.28-12.28 12.28-32.19 0-44.48l-22.24-22.24c-12.28-12.28-32.19-12.28-44.48 0L176 189.28 75.93 89.21c-12.28-12.28-32.19-12.28-44.48 0L9.21 111.45c-12.28 12.28-12.28 32.19 0 44.48L109.28 256 9.21 356.07c-12.28 12.28-12.28 32.19 0 44.48l22.24 22.24c12.28 12.28 32.2 12.28 44.48 0L176 322.72l100.07 100.07c12.28 12.28 32.2 12.28 44.48 0l22.24-22.24c12.28-12.28 12.28-32.19 0-44.48L242.72 256z"></path></svg>
		</div>
	</div>

	<div class="cmplz-divider cmplz-divider-header"></div>
	<div class="cmplz-body">
		<div class="cmplz-message" id="cmplz-message-1-optin">Para ofrecer las mejores experiencias, utilizamos tecnologías como las cookies para almacenar y/o acceder a la información del dispositivo. El consentimiento de estas tecnologías nos permitirá procesar datos como el comportamiento de navegación o las identificaciones únicas en este sitio. No consentir o retirar el consentimiento, puede afectar negativamente a ciertas características y funciones.</div>
		<!-- categories start -->
		<div class="cmplz-categories">
			<details class="cmplz-category cmplz-functional" >
				<summary>
						<span class="cmplz-category-header">
							<span class="cmplz-category-title">Funcional</span>
							<span class='cmplz-always-active'>
								<span class="cmplz-banner-checkbox">
									<input type="checkbox"
										   id="cmplz-functional-optin"
										   data-category="cmplz_functional"
										   class="cmplz-consent-checkbox cmplz-functional"
										   size="40"
										   value="1"/>
									<label class="cmplz-label" for="cmplz-functional-optin" tabindex="0"><span class="screen-reader-text">Funcional</span></label>
								</span>
								Siempre activo							</span>
							<span class="cmplz-icon cmplz-open">
								<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"  height="18" ><path d="M224 416c-8.188 0-16.38-3.125-22.62-9.375l-192-192c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0L224 338.8l169.4-169.4c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25l-192 192C240.4 412.9 232.2 416 224 416z"/></svg>
							</span>
						</span>
				</summary>
				<div class="cmplz-description">
					<span class="cmplz-description-functional">El almacenamiento o acceso técnico es estrictamente necesario para el propósito legítimo de permitir el uso de un servicio específico explícitamente solicitado por el abonado o usuario, o con el único propósito de llevar a cabo la transmisión de una comunicación a través de una red de comunicaciones electrónicas.</span>
				</div>
			</details>

			<details class="cmplz-category cmplz-preferences" >
				<summary>
						<span class="cmplz-category-header">
							<span class="cmplz-category-title">Preferencias</span>
							<span class="cmplz-banner-checkbox">
								<input type="checkbox"
									   id="cmplz-preferences-optin"
									   data-category="cmplz_preferences"
									   class="cmplz-consent-checkbox cmplz-preferences"
									   size="40"
									   value="1"/>
								<label class="cmplz-label" for="cmplz-preferences-optin" tabindex="0"><span class="screen-reader-text">Preferencias</span></label>
							</span>
							<span class="cmplz-icon cmplz-open">
								<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"  height="18" ><path d="M224 416c-8.188 0-16.38-3.125-22.62-9.375l-192-192c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0L224 338.8l169.4-169.4c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25l-192 192C240.4 412.9 232.2 416 224 416z"/></svg>
							</span>
						</span>
				</summary>
				<div class="cmplz-description">
					<span class="cmplz-description-preferences">El almacenamiento o acceso técnico es necesario para la finalidad legítima de almacenar preferencias no solicitadas por el abonado o usuario.</span>
				</div>
			</details>

			<details class="cmplz-category cmplz-statistics" >
				<summary>
						<span class="cmplz-category-header">
							<span class="cmplz-category-title">Estadísticas</span>
							<span class="cmplz-banner-checkbox">
								<input type="checkbox"
									   id="cmplz-statistics-optin"
									   data-category="cmplz_statistics"
									   class="cmplz-consent-checkbox cmplz-statistics"
									   size="40"
									   value="1"/>
								<label class="cmplz-label" for="cmplz-statistics-optin" tabindex="0"><span class="screen-reader-text">Estadísticas</span></label>
							</span>
							<span class="cmplz-icon cmplz-open">
								<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"  height="18" ><path d="M224 416c-8.188 0-16.38-3.125-22.62-9.375l-192-192c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0L224 338.8l169.4-169.4c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25l-192 192C240.4 412.9 232.2 416 224 416z"/></svg>
							</span>
						</span>
				</summary>
				<div class="cmplz-description">
					<span class="cmplz-description-statistics">El almacenamiento o acceso técnico que es utilizado exclusivamente con fines estadísticos.</span>
					<span class="cmplz-description-statistics-anonymous">El almacenamiento o acceso técnico que se utiliza exclusivamente con fines estadísticos anónimos. Sin un requerimiento, el cumplimiento voluntario por parte de tu Proveedor de servicios de Internet, o los registros adicionales de un tercero, la información almacenada o recuperada sólo para este propósito no se puede utilizar para identificarte.</span>
				</div>
			</details>
			<details class="cmplz-category cmplz-marketing" >
				<summary>
						<span class="cmplz-category-header">
							<span class="cmplz-category-title">Marketing</span>
							<span class="cmplz-banner-checkbox">
								<input type="checkbox"
									   id="cmplz-marketing-optin"
									   data-category="cmplz_marketing"
									   class="cmplz-consent-checkbox cmplz-marketing"
									   size="40"
									   value="1"/>
								<label class="cmplz-label" for="cmplz-marketing-optin" tabindex="0"><span class="screen-reader-text">Marketing</span></label>
							</span>
							<span class="cmplz-icon cmplz-open">
								<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512"  height="18" ><path d="M224 416c-8.188 0-16.38-3.125-22.62-9.375l-192-192c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0L224 338.8l169.4-169.4c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25l-192 192C240.4 412.9 232.2 416 224 416z"/></svg>
							</span>
						</span>
				</summary>
				<div class="cmplz-description">
					<span class="cmplz-description-marketing">El almacenamiento o acceso técnico es necesario para crear perfiles de usuario para enviar publicidad, o para rastrear al usuario en una web o en varias web con fines de marketing similares.</span>
				</div>
			</details>
		</div><!-- categories end -->
			</div>

	<div class="cmplz-links cmplz-information">
		<a class="cmplz-link cmplz-manage-options cookie-statement" href="#" data-relative_url="#cmplz-manage-consent-container">Administrar opciones</a>
		<a class="cmplz-link cmplz-manage-third-parties cookie-statement" href="#" data-relative_url="#cmplz-cookies-overview">Gestionar los servicios</a>
		<a class="cmplz-link cmplz-manage-vendors tcf cookie-statement" href="#" data-relative_url="#cmplz-tcf-wrapper">Gestionar {vendor_count} proveedores</a>
		<a class="cmplz-link cmplz-external cmplz-read-more-purposes tcf" target="_blank" rel="noopener noreferrer nofollow" href="https://cookiedatabase.org/tcf/purposes/">Leer más sobre estos propósitos</a>
			</div>

	<div class="cmplz-divider cmplz-footer"></div>

	<div class="cmplz-buttons">
		<button class="cmplz-btn cmplz-accept">Aceptar</button>
		<button class="cmplz-btn cmplz-deny">Denegar</button>
		<button class="cmplz-btn cmplz-view-preferences">Ver preferencias</button>
		<button class="cmplz-btn cmplz-save-preferences">Guardar preferencias</button>
		<a class="cmplz-btn cmplz-manage-options tcf cookie-statement" href="#" data-relative_url="#cmplz-manage-consent-container">Ver preferencias</a>
			</div>

	<div class="cmplz-links cmplz-documents">
		<a class="cmplz-link cookie-statement" href="#" data-relative_url="">{title}</a>
		<a class="cmplz-link privacy-statement" href="#" data-relative_url="">{title}</a>
		<a class="cmplz-link impressum" href="#" data-relative_url="">{title}</a>
			</div>

</div>
</div>
					<div id="cmplz-manage-consent" data-nosnippet="true"><button class="cmplz-btn cmplz-hidden cmplz-manage-consent manage-consent-1">Gestionar consentimiento</button>

</div>			<script>
				const lazyloadRunObserver = () => {
					const lazyloadBackgrounds = document.querySelectorAll( `.e-con.e-parent:not(.e-lazyloaded)` );
					const lazyloadBackgroundObserver = new IntersectionObserver( ( entries ) => {
						entries.forEach( ( entry ) => {
							if ( entry.isIntersecting ) {
								let lazyloadBackground = entry.target;
								if( lazyloadBackground ) {
									lazyloadBackground.classList.add( 'e-lazyloaded' );
								}
								lazyloadBackgroundObserver.unobserve( entry.target );
							}
						});
					}, { rootMargin: '200px 0px 200px 0px' } );
					lazyloadBackgrounds.forEach( ( lazyloadBackground ) => {
						lazyloadBackgroundObserver.observe( lazyloadBackground );
					} );
				};
				const events = [
					'DOMContentLoaded',
					'elementor/lazyload/observe',
				];
				events.forEach( ( event ) => {
					document.addEventListener( event, lazyloadRunObserver );
				} );
			</script>
			<script type="rocketlazyloadscript" data-rocket-type="text/javascript" id="rocket-browser-checker-js-after">
/* <![CDATA[ */
"use strict";var _createClass=function(){function defineProperties(target,props){for(var i=0;i<props.length;i++){var descriptor=props[i];descriptor.enumerable=descriptor.enumerable||!1,descriptor.configurable=!0,"value"in descriptor&&(descriptor.writable=!0),Object.defineProperty(target,descriptor.key,descriptor)}}return function(Constructor,protoProps,staticProps){return protoProps&&defineProperties(Constructor.prototype,protoProps),staticProps&&defineProperties(Constructor,staticProps),Constructor}}();function _classCallCheck(instance,Constructor){if(!(instance instanceof Constructor))throw new TypeError("Cannot call a class as a function")}var RocketBrowserCompatibilityChecker=function(){function RocketBrowserCompatibilityChecker(options){_classCallCheck(this,RocketBrowserCompatibilityChecker),this.passiveSupported=!1,this._checkPassiveOption(this),this.options=!!this.passiveSupported&&options}return _createClass(RocketBrowserCompatibilityChecker,[{key:"_checkPassiveOption",value:function(self){try{var options={get passive(){return!(self.passiveSupported=!0)}};window.addEventListener("test",null,options),window.removeEventListener("test",null,options)}catch(err){self.passiveSupported=!1}}},{key:"initRequestIdleCallback",value:function(){!1 in window&&(window.requestIdleCallback=function(cb){var start=Date.now();return setTimeout(function(){cb({didTimeout:!1,timeRemaining:function(){return Math.max(0,50-(Date.now()-start))}})},1)}),!1 in window&&(window.cancelIdleCallback=function(id){return clearTimeout(id)})}},{key:"isDataSaverModeOn",value:function(){return"connection"in navigator&&!0===navigator.connection.saveData}},{key:"supportsLinkPrefetch",value:function(){var elem=document.createElement("link");return elem.relList&&elem.relList.supports&&elem.relList.supports("prefetch")&&window.IntersectionObserver&&"isIntersecting"in IntersectionObserverEntry.prototype}},{key:"isSlowConnection",value:function(){return"connection"in navigator&&"effectiveType"in navigator.connection&&("2g"===navigator.connection.effectiveType||"slow-2g"===navigator.connection.effectiveType)}}]),RocketBrowserCompatibilityChecker}();
/* ]]> */
</script>
<script type="text/javascript" id="rocket-preload-links-js-extra">
/* <![CDATA[ */
var RocketPreloadLinksConfig = {"excludeUris":"\/(.*)sitemap(.*).xml|\/(.*)sitemap.xsl|\/(?:.+\/)?feed(?:\/(?:.+\/?)?)?$|\/(?:.+\/)?embed\/|\/(index.php\/)?(.*)wp-json(\/.*|$)|\/refer\/|\/go\/|\/recommend\/|\/recommends\/","usesTrailingSlash":"1","imageExt":"jpg|jpeg|gif|png|tiff|bmp|webp|avif|pdf|doc|docx|xls|xlsx|php","fileExt":"jpg|jpeg|gif|png|tiff|bmp|webp|avif|pdf|doc|docx|xls|xlsx|php|html|htm","siteUrl":"https:\/\/ludorex.com","onHoverDelay":"100","rateThrottle":"3"};
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" id="rocket-preload-links-js-after">
/* <![CDATA[ */
(function() {
"use strict";var r="function"==typeof Symbol&&"symbol"==typeof Symbol.iterator?function(e){return typeof e}:function(e){return e&&"function"==typeof Symbol&&e.constructor===Symbol&&e!==Symbol.prototype?"symbol":typeof e},e=function(){function i(e,t){for(var n=0;n<t.length;n++){var i=t[n];i.enumerable=i.enumerable||!1,i.configurable=!0,"value"in i&&(i.writable=!0),Object.defineProperty(e,i.key,i)}}return function(e,t,n){return t&&i(e.prototype,t),n&&i(e,n),e}}();function i(e,t){if(!(e instanceof t))throw new TypeError("Cannot call a class as a function")}var t=function(){function n(e,t){i(this,n),this.browser=e,this.config=t,this.options=this.browser.options,this.prefetched=new Set,this.eventTime=null,this.threshold=1111,this.numOnHover=0}return e(n,[{key:"init",value:function(){!this.browser.supportsLinkPrefetch()||this.browser.isDataSaverModeOn()||this.browser.isSlowConnection()||(this.regex={excludeUris:RegExp(this.config.excludeUris,"i"),images:RegExp(".("+this.config.imageExt+")$","i"),fileExt:RegExp(".("+this.config.fileExt+")$","i")},this._initListeners(this))}},{key:"_initListeners",value:function(e){-1<this.config.onHoverDelay&&document.addEventListener("mouseover",e.listener.bind(e),e.listenerOptions),document.addEventListener("mousedown",e.listener.bind(e),e.listenerOptions),document.addEventListener("touchstart",e.listener.bind(e),e.listenerOptions)}},{key:"listener",value:function(e){var t=e.target.closest("a"),n=this._prepareUrl(t);if(null!==n)switch(e.type){case"mousedown":case"touchstart":this._addPrefetchLink(n);break;case"mouseover":this._earlyPrefetch(t,n,"mouseout")}}},{key:"_earlyPrefetch",value:function(t,e,n){var i=this,r=setTimeout(function(){if(r=null,0===i.numOnHover)setTimeout(function(){return i.numOnHover=0},1e3);else if(i.numOnHover>i.config.rateThrottle)return;i.numOnHover++,i._addPrefetchLink(e)},this.config.onHoverDelay);t.addEventListener(n,function e(){t.removeEventListener(n,e,{passive:!0}),null!==r&&(clearTimeout(r),r=null)},{passive:!0})}},{key:"_addPrefetchLink",value:function(i){return this.prefetched.add(i.href),new Promise(function(e,t){var n=document.createElement("link");n.rel="prefetch",n.href=i.href,n.onload=e,n.onerror=t,document.head.appendChild(n)}).catch(function(){})}},{key:"_prepareUrl",value:function(e){if(null===e||"object"!==(void 0===e?"undefined":r(e))||!1 in e||-1===["http:","https:"].indexOf(e.protocol))return null;var t=e.href.substring(0,this.config.siteUrl.length),n=this._getPathname(e.href,t),i={original:e.href,protocol:e.protocol,origin:t,pathname:n,href:t+n};return this._isLinkOk(i)?i:null}},{key:"_getPathname",value:function(e,t){var n=t?e.substring(this.config.siteUrl.length):e;return n.startsWith("/")||(n="/"+n),this._shouldAddTrailingSlash(n)?n+"/":n}},{key:"_shouldAddTrailingSlash",value:function(e){return this.config.usesTrailingSlash&&!e.endsWith("/")&&!this.regex.fileExt.test(e)}},{key:"_isLinkOk",value:function(e){return null!==e&&"object"===(void 0===e?"undefined":r(e))&&(!this.prefetched.has(e.href)&&e.origin===this.config.siteUrl&&-1===e.href.indexOf("?")&&-1===e.href.indexOf("#")&&!this.regex.excludeUris.test(e.href)&&!this.regex.images.test(e.href))}}],[{key:"run",value:function(){"undefined"!=typeof RocketPreloadLinksConfig&&new n(new RocketBrowserCompatibilityChecker({capture:!0,passive:!0}),RocketPreloadLinksConfig).init()}}]),n}();t.run();
}());
/* ]]> */
</script>
<script type="text/javascript" id="rocket_lazyload_css-js-extra">
/* <![CDATA[ */
var rocket_lazyload_css_data = {"threshold":"300"};
/* ]]> */
</script>
<script type="text/javascript" id="rocket_lazyload_css-js-after">
/* <![CDATA[ */
!function o(n,c,a){function u(t,e){if(!c[t]){if(!n[t]){var r="function"==typeof require&&require;if(!e&&r)return r(t,!0);if(s)return s(t,!0);throw(e=new Error("Cannot find module '"+t+"'")).code="MODULE_NOT_FOUND",e}r=c[t]={exports:{}},n[t][0].call(r.exports,function(e){return u(n[t][1][e]||e)},r,r.exports,o,n,c,a)}return c[t].exports}for(var s="function"==typeof require&&require,e=0;e<a.length;e++)u(a[e]);return u}({1:[function(e,t,r){"use strict";{const c="undefined"==typeof rocket_pairs?[]:rocket_pairs,a=(("undefined"==typeof rocket_excluded_pairs?[]:rocket_excluded_pairs).map(t=>{var e=t.selector;document.querySelectorAll(e).forEach(e=>{e.setAttribute("data-rocket-lazy-bg-"+t.hash,"excluded")})}),document.querySelector("#wpr-lazyload-bg-container"));var o=rocket_lazyload_css_data.threshold||300;const u=new IntersectionObserver(e=>{e.forEach(t=>{t.isIntersecting&&c.filter(e=>t.target.matches(e.selector)).map(t=>{var e;t&&((e=document.createElement("style")).textContent=t.style,a.insertAdjacentElement("afterend",e),t.elements.forEach(e=>{u.unobserve(e),e.setAttribute("data-rocket-lazy-bg-"+t.hash,"loaded")}))})})},{rootMargin:o+"px"});function n(){0<(0<arguments.length&&void 0!==arguments[0]?arguments[0]:[]).length&&c.forEach(t=>{try{document.querySelectorAll(t.selector).forEach(e=>{"loaded"!==e.getAttribute("data-rocket-lazy-bg-"+t.hash)&&"excluded"!==e.getAttribute("data-rocket-lazy-bg-"+t.hash)&&(u.observe(e),(t.elements||=[]).push(e))})}catch(e){console.error(e)}})}n(),function(){const r=window.MutationObserver;return function(e,t){if(e&&1===e.nodeType)return(t=new r(t)).observe(e,{attributes:!0,childList:!0,subtree:!0}),t}}()(document.querySelector("body"),n)}},{}]},{},[1]);
//# sourceMappingURL=lazyload-css.min.js.map
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/swiper.min.js?ver=1.0.0" id="vikinger-swiper-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_accordion.min.js?ver=1.0.0" id="vikinger-xmaccordion-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_dropdown.min.js?ver=1.0.0" id="vikinger-xmdropdown-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_hexagon.min.js?ver=1.0.0" id="vikinger-xmhexagon-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_popup.min.js?ver=1.0.0" id="vikinger-xmpopup-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_progressBar.min.js?ver=1.0.0" id="vikinger-xmprogressBar-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_tab.min.js?ver=1.0.0" id="vikinger-xmtab-scripts-js" defer></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/vendor/xm_tooltip.min.js?ver=1.0.0" id="vikinger-xmtooltip-scripts-js" defer></script>
<script type="text/javascript" id="vikinger-main-scripts-js-extra">
/* <![CDATA[ */
var vikinger_translation = {"day":"Day","month":"Month","year":"Year","members_only_content_text":"This content is for members only.","join_now":"Join Now","search_placeholder":"Enter your search here...","members":"Members","no_members_found":"No members found","groups":"Groups","no_groups_found":"No groups found","posts":"Posts","by":"By","friend_requests":"Friend Requests","received":"Received","sent":"Sent","no_friend_requests_received":"No friend requests received","no_friend_requests_sent":"No friend requests sent","view_all_friend_requests":"View all Friend Requests","messages":"Messages","no_messages_received":"No messages received","view_all_messages":"View all Messages","email_settings":"Email Settings","notifications":"Notifications","no_notifications_received":"No notifications received","view_all_notifications":"View all Notifications","no_results_found":"No results found","item_list_no_results_text":"Please try with another filter!","showing_results_text_1":"Showing","showing_results_text_2":"out of","category":"Category","all_categories":"All Categories","type":"Type","all":"All","filter_by":"Filter By","date":"Date","popularity":"Popularity","order_by":"Order By","member_type":"Member Type","group_type":"Group Type","ascending":"Ascending","descending":"Descending","filter_action":"Filter","result":"Result","results":"Results","grid_filter":{"big":"Big Grid","small":"Small Grid","list":"List Grid"},"read_more":"Read More...","comment":"Comment","comments":"Comments","share":"Share","shares":"Shares","more_reactions_text_1":"and","more_reactions_text_2":"more...","newest":"Newest","popular":"Popular","active":"Active","no_photos_found":"No photos found","friends":"Friends","no_friends_found":"No friends found","find_friends":"Find Friends","see_all_friends":"See all Friends","locked":"Locked","unlocked!":"Unlocked!","status_update":"Status Update","post_in":"Post In","my_profile":"My Profile","privacy":"Privacy","public":"Public","private":"Private","activity_form_placeholder_1":"Hi","activity_form_placeholder_2":"Write something here, use @ to mention someone...","activity_form_placeholder_3":"Write something here...","add_photo":"Add Photo","add_video":"Add Video","add_gif":"Add Gif","upload_photo":"Upload Photo","discard":"Discard","save":"Save","post_action":"Post","activity_form_empty_error":"Please enter some text or add a photo or video!","upload_form_photo_empty_error":"Please add a photo to upload!","upload_form_video_empty_error":"Please add a video to upload!","maximum_size_accepted_is":"Maximum size accepted is","size_is_too_big":"size is too big!","file_extension_is_not_allowed":"file extension is not allowed!","all_updates":"All Updates","mentions":"Mentions","favorites":"Favorites","scope":"Scope","show":"Show","everything":"Everything","status":"Status","media":"Media","photos":"Photos","videos":"Videos","friendships":"Friendships","new_groups":"New Groups","add_favorite":"Add Favorite","remove_favorite":"Remove Favorite","pin_to_top":"Pin to Top","unpin_from_top":"Unpin from Top","edit_post":"Edit Post","delete_post":"Delete Post","delete_activity_message_title":"Delete Post","delete_activity_message_text":"Are you sure you want to delete this post?","edit_comment":"Edit Comment","cancel_edit":"Cancel Edit","delete_comment":"Delete Comment","delete_comment_message_title":"Delete Comment","delete_comment_message_text":"Are you sure you want to delete this comment?","edited_by":"* edited by","and":"and","in_the_group":"in the group","shared_content_deleted_title":"Oops! -","shared_content_deleted_text":"the shared content was deleted.","show_more":"Show More","react":"React!","comment_action":"Comment","share_action":"Share","leave_a_comment":"Leave a Comment","your_reply":"Your Reply","post_reply":"Post Reply","reply_action":"Reply","cancel_action":"Cancel","load":"Load","reply":"Reply","replies":"Replies","load_more_comments":"Load More Comments","comment_empty_message":"Please enter a comment","comment_not_approved_message":"Your comment is awaiting moderation and will be visible when approved","search_groups":"Search Groups","alphabetical":"Alphabetical","newest_groups":"Newest Groups","recently_active":"Recently Active","group":"Group","member":"Member","post":"Post","banned":"Banned","accept":"Accept","cancel":"Cancel","continue":"Continue","join_group":"Join Group","leave_group":"Leave Group","send_join_request":"Send Join Request","cancel_join_request":"Cancel Join Request","reject_join_request":"Reject Join Request","accept_join_request":"Accept Join Request","remove_member":"Remove Member","remove_invitation":"Remove Invitation","reject_invitation":"Reject Invitation","accept_invitation":"Accept Invitation","ban_member":"Ban Member","unban_member":"Unban Member","promote_to_admin":"Promote to Admin","promote_to_mod":"Promote to Mod","demote_to_mod":"Demote to Mod","demote_to_member":"Demote to Member","manage_groups":"Manage Groups","search_members":"Search Members","newest_members":"Newest Members","friend":"Friend","no_social_networks_linked":"No social networks linked","no_badges_unlocked":"No badges unlocked","add_friend":"Add Friend","remove_friend":"Remove Friend","accept_friend":"Accept Friend Request","reject_friend":"Reject Friend Request","withdraw_friend":"Cancel Friend Request","send_message":"Send Message","browse":"Browse","photos_no_results_title":"No photos found","photos_no_results_text":"There aren't any uploaded photos!","videos_no_results_title":"No videos found","videos_no_results_text":"There aren't any uploaded videos!","upload_photos":"Upload Photos","upload_video":"Upload Video","select_all":"Select All","unselect_all":"Unselect All","delete":"Delete","save_changes":"Save Changes","saving":"Saving...","profile_info":"Profile Info","change_avatar":"Change Avatar","change_cover":"Change Cover","upload_error":"Upload Error","upload_error_message":"An error has ocurred, please verify avatar\/cover dimensions or try again later","avatar_upload_error":"Avatar Upload Error","cover_upload_error":"Cover Upload Error","select_an_option":"Select an Option","social_networks":"Social Networks","no_social_info_available":"No social info available","stream":"Stream","stream_settings_username_title":"Twitch Streamer - Username","stream_settings_username_placeholder":"Enter Twitch streamer username here...","stream_settings_preview_title":"Twitch Stream - Preview","stream_settings_preview_text":"Below, you can see a preview of how the Twitch stream will look like with the currently entered streamer username","stream_settings_preview_no_results":"No streamer username entered","notifications_received_no_results_title":"No notifications received","notifications_received_no_results_text":"If you receive notifications they will appear here!","mark_as_read":"Mark as Read","delete_selected_message":"Are you sure you want to delete all selected items?","inbox":"Inbox","sentbox":"Sentbox","starred":"Starred","new_message":"New Message","started":"Started","add_friend_placeholder":"Use @ to add a friend...","search_messages":"Search Messages","write_a_message":"Write a Message...","no_messages_found":"No messages found","message_search_no_results":"No messages match your search","star_action":"Star","unstar":"Unstar","delete_item_message":"Are you sure you want to delete this?","you":"You","friend_requests_received":"Friend Requests Received","friend_requests_received_no_results_title":"No friend requests received","friend_requests_received_no_results_text":"If you receive friend requests they will appear here!","friend_requests_sent":"Friend Requests Sent","friend_requests_sent_no_results_title":"No friend requests sent","friend_requests_sent_no_results_text":"If you send friend requests they will appear here!","account":"Account","account_info":"Account Info","no_account_info_available":"No account info available","change_password":"Change Password","enter_your_current_password":"Enter your Current Password","your_new_password":"Your New Password","confirm_new_password":"Confirm New Password","change_password_error_title":"Change Password Error","change_password_error_text":"Couldn't change password. Please try again later","current_password_mismatch_error_title":"Incorrect Password","current_password_mismatch_error_text":"Entered current password doesn't match your password. Please make sure to enter your current password correctly","new_password_mismatch_error_title":"New Password Mismatch","new_password_mismatch_error_text":"New password field and new password confirmation field don't match. Please make sure to enter the same password in both fields","activity":"Activity","email_settings_mentions_description":"A member mentions you in an update","email_settings_replies_description":"A member replies to an update or comment you've posted","email_settings_newmessage_description":"A member sends you a new message","new_friend_request":"New Friend Request","email_settings_newfriendrequest_description":"A member sends you a friendship request","friend_request_accepted":"Friend Request Accepted","email_settings_friendrequestaccepted_description":"A member accepts your friendship request","group_invite":"Group Invite","email_settings_groupinvite_description":"A member invites you to join a group","group_update":"Group Update","email_settings_groupupdate_description":"Group information is updated","group_promotion":"Group Promotion","email_settings_grouppromotion_description":"You are promoted to a group administrator or moderator","private_group_membership_request":"Private Group Membership Request","email_settings_privategroupmembershiprequest_description":"A member requests to join a private group for which you are an admin","group_join_request_status":"Group Join Request Status","email_settings_groupjoinrequeststatus_description":"Your request to join a group has been approved or denied","manage_group":"Manage Group","cant_manage_groups_message":"You can't manage any groups yet!","create_group":"Create Group!","create_new_group":"Create New Group","create_new_group_text":"Share your passion with others!","start_creating":"Start Creating!","creating":"Creating...","group_creator":"Group Creator","group_admin":"Group Admin","group_mod":"Group Mod","group_info":"Group Info","group_name":"Group Name","group_status":"Group Status","group_slug":"Group Slug (what you see on the URL)","group_description":"Group Description","forum":"Forum","forums":"Forums","forum_topics":"Forum Topics","forum_replies":"Forum Replies","group_forum":"Group Forum","group_forum_enable_title":"Should this group have a forum?","group_forum_enable_text":"Enable forum for this group","forum_name":"Forum Name","forum_description":"Forum Description","forum_privacy":"Forum Privacy","avatar_and_cover":"Avatar and Cover","administrators":"Administrators","mods":"Mods","banned_members":"Banned Members","no_mods_found":"No mods found","no_banned_members_found":"No banned members found","delete_group":"Delete Group","delete_group_text":"Deleting a group will remove all its content, this action cannot be undone.","delete_group_confirmation":"Are you sure you want to delete this group?","required_fields_message":"Please fill all required fields","save_error_message":"Error when saving, please try again later","create_group_error":"Group creation failed! Please try again later.","update_group_error":"Group update failed! Please try again later.","discard_all":"Discard All","send_invitations":"Send Invitations","send_invitations_no_results_title":"No groups","send_invitations_no_results_text_1":"You don't belong to any groups. Create or join a group first!","send_invitations_no_results_text_2":"You don't belong to any groups which you can send invitations from","select_the_group":"Select the Group","select_your_friends":"Select your Friends","send_invitations_friends_no_results":"You don't have any friends that can be invited to this group","sending":"Sending...","pending_invitations":"Pending Invitations","pending_invitations_no_results_title":"No invitations sent","pending_invitations_no_results_text":"If you send invitations they will appear here!","received_invitations":"Received Invitations","received_invitations_no_results_title":"No invitations received","received_invitations_no_results_text":"If you receive invitations they will appear here!","invited_by":"Invited By","received_membership_requests":"Received Membership Requests","received_membership_requests_no_results_title":"No membership requests received","received_membership_requests_no_results_text":"If you receive membership requests they will appear here!","sent_membership_requests":"Sent Membership Requests","sent_membership_requests_no_results_title":"No membership requests sent","sent_membership_requests_no_results_text":"If you send membership requests they will appear here!","wants_to_join":"Wants to Join"};
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" id="vikinger-main-scripts-js-before">
/* <![CDATA[ */
const vikinger_constants = {"vikinger_url":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger","home_url":"https:\/\/ludorex.com\/","ajax_url":"https:\/\/ludorex.com\/wp-admin\/admin-ajax.php","wp_rest_nonce":"8c9e63ddfd","vikinger_ajax_nonce":"5472eb560c","rest_root":"https:\/\/ludorex.com\/wp-json\/","plugin_active":{"buddypress":false,"bp-verified-member":false,"bp-better-messages":false,"bbpress":false,"gamipress":false,"gamipress-buddypress-integration":false,"gamipress-bbpress-integration":false,"woocommerce":false,"elementor":true,"paid-memberships-pro":false,"pmpro-buddypress":false,"pmpro-bbpress":false,"advanced-ads":false,"vikinger-buddypress-extension":false,"vkreact":false,"vkreact-buddypress":false,"vkmedia":false,"vikinger-widgets":false,"vikinger-metaboxes":false,"advanced-ads-pro":false},"gamipress_badge_type_exists":false,"colors":{"--color-wplogin-body":"#2c1d58","--color-wplogin-header-text":"#fff","--color-header-background":"#2c1d58","--color-header-logo-background":"#f33059","--color-header-text":"#fff","--color-header-icon":"#4f3e80","--color-header-icon-hover":"#fff","--color-header-profile-settings-icon":"#fff","--color-header-mobilemenu-trigger-icon":"#fff","--color-header-divider":"#463283","--color-header-input-background":"#221746","--color-header-input-placeholder":"#8a7fc4","--color-header-progressbar-line-gradient-start":"#f33059","--color-header-progressbar-line-gradient-end":"#943dff","--color-header-progressbar-underline":"#403076","--color-body":"#221746","--color-box-background":"#2c1d58","--color-box-background-alt":"#281a51","--color-box-over-box-background":"#332363","--color-box-over-box-light-background":"#332363","--color-box-highlight-background":"#332363","--color-box-hover-background":"#3b296e","--color-box-shadow":"0 0 40px 0 rgba(0,0,0, .06)","--color-overbox-shadow":"3px 5px 20px 0 rgba(0,0,0, .12)","--color-overbox-dark-shadow":"0 0 40px 0 rgba(0,0,0, .12)","--color-overbox-big-shadow":"3px 5px 40px 0 rgba(0,0,0, .1)","--color-text":"#fff","--color-text-alt":"#9388cc","--color-text-alt-2":"#9388cc","--color-icon":"#8370bb","--color-icon-highlighted":"#f33059","--color-border":"#4d378e","--color-divider":"#4d378e","--color-progressbar-line-gradient-start":"#f33059","--color-progressbar-line-gradient-end":"#943dff","--color-progressbar-underline":"#403076","--color-avatar-rank-hexagon":"#f33059 ","--color-primary":"#f33059","--color-primary-hover":"#ff426a","--color-primary-light":"#ff335e","--color-primary-dark":"#ff335e","--color-primary-shadow":"4px 7px 12px 0 rgba(243,48,89, .2)","--color-secondary":"#943dff","--color-secondary-hover":"#a156fe","--color-secondary-dark":"#943dff","--color-secondary-shadow":"4px 7px 12px 0 rgba(148,61,255, .2)","--color-tertiary":"#ff911b","--color-tertiary-hover":"#ff9e35","--color-tertiary-shadow":"4px 7px 12px 0 rgba(255,145,27, .2)","--color-loading-screen-background":"#2c1d58","--color-loading-bar-1":"#fd426d","--color-loading-bar-2":"#f4447c","--color-loading-bar-3":"#e74790","--color-loading-bar-4":"#d84aa8","--color-loading-bar-5":"#ca4dbd","--color-loading-bar-6":"#b951d8","--color-loading-bar-7":"#ac54ec","--color-loading-bar-8":"#a356fb","--color-overlay":"#15151f"},"settings":{"users_can_register":false,"posts_per_page":"40","current_user_is_admin":false,"membership_levels_page_link":"","sidemenu_status":"hide","sidemenu_active":false,"search_status":"hide","search_blog_enabled":true,"search_members_enabled":false,"search_groups_enabled":false,"post_types_to_display_in_search":["post"],"post_type_filter_display_is_enabled":false,"post_type_split_display_is_enabled":false,"post_excerpt_display_is_enabled":true,"member_types":[],"group_types":[],"newsfeed_yt_playback_limit":"no","stream_twitch_embeds_parent":"ludorex.com","activity_show_more_status":"disabled","activity_show_more_height":1000,"activity_character_limit":1000,"activity_comment_character_limit":500,"activity_edit_time_limit":5,"activity_line_break_limit":2,"media_photo_upload_enabled":false,"media_photo_upload_maximum_size":100,"media_photo_allowed_extensions":["jpg","jpeg","png","gif"],"media_photo_allowed_extensions_case_sensitive":false,"media_video_upload_enabled":false,"media_video_upload_maximum_size":100,"media_video_allowed_extensions":["mp4","mkv"],"media_video_allowed_extensions_case_sensitive":false,"avatar_type":"hexagon","member_avatar_url_default":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/avatar\/default-avatar.jpg","group_avatar_url_default":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/avatar\/default-avatar.jpg","member_cover_image_url_default":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/cover\/default-cover.png","group_cover_image_url_default":"https:\/\/ludorex.com\/wp-content\/themes\/vikinger\/img\/cover\/default-cover.png","footer_status":"hide"}};
/* ]]> */
</script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/themes/vikinger/js/app.bundle.min.js?ver=4.0.5" id="vikinger-main-scripts-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/elementor/assets/js/webpack.runtime.min.js?ver=3.29.1" id="elementor-webpack-runtime-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/elementor/assets/js/frontend-modules.min.js?ver=3.29.1" id="elementor-frontend-modules-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-includes/js/jquery/ui/core.min.js?ver=1.13.3" id="jquery-ui-core-js" defer></script>
<script type="text/javascript" id="elementor-frontend-js-before">
/* <![CDATA[ */
var elementorFrontendConfig = {"environmentMode":{"edit":false,"wpPreview":false,"isScriptDebug":false},"i18n":{"shareOnFacebook":"Compartir en Facebook","shareOnTwitter":"Compartir en Twitter","pinIt":"Pinear","download":"Descargar","downloadImage":"Descargar imagen","fullscreen":"Pantalla completa","zoom":"Zoom","share":"Compartir","playVideo":"Reproducir v\u00eddeo","previous":"Anterior","next":"Siguiente","close":"Cerrar","a11yCarouselPrevSlideMessage":"Diapositiva anterior","a11yCarouselNextSlideMessage":"Diapositiva siguiente","a11yCarouselFirstSlideMessage":"Esta es la primera diapositiva","a11yCarouselLastSlideMessage":"Esta es la \u00faltima diapositiva","a11yCarouselPaginationBulletMessage":"Ir a la diapositiva"},"is_rtl":false,"breakpoints":{"xs":0,"sm":480,"md":768,"lg":1025,"xl":1440,"xxl":1600},"responsive":{"breakpoints":{"mobile":{"label":"M\u00f3vil vertical","value":767,"default_value":767,"direction":"max","is_enabled":true},"mobile_extra":{"label":"M\u00f3vil horizontal","value":880,"default_value":880,"direction":"max","is_enabled":false},"tablet":{"label":"Tableta vertical","value":1024,"default_value":1024,"direction":"max","is_enabled":true},"tablet_extra":{"label":"Tableta horizontal","value":1200,"default_value":1200,"direction":"max","is_enabled":false},"laptop":{"label":"Port\u00e1til","value":1366,"default_value":1366,"direction":"max","is_enabled":false},"widescreen":{"label":"Pantalla grande","value":2400,"default_value":2400,"direction":"min","is_enabled":false}},"hasCustomBreakpoints":false},"version":"3.29.1","is_static":false,"experimentalFeatures":{"e_font_icon_svg":true,"additional_custom_breakpoints":true,"container":true,"e_local_google_fonts":true,"theme_builder_v2":true,"nested-elements":true,"editor_v2":true,"e_element_cache":true,"home_screen":true,"cloud-library":true,"e_opt_in_v4_page":true},"urls":{"assets":"https:\/\/ludorex.com\/wp-content\/plugins\/elementor\/assets\/","ajaxurl":"https:\/\/ludorex.com\/wp-admin\/admin-ajax.php","uploadUrl":"https:\/\/ludorex.com\/wp-content\/uploads"},"nonces":{"floatingButtonsClickTracking":"9355030cc6"},"swiperClass":"swiper","settings":{"page":[],"editorPreferences":[]},"kit":{"active_breakpoints":["viewport_mobile","viewport_tablet"],"global_image_lightbox":"yes","lightbox_enable_counter":"yes","lightbox_enable_fullscreen":"yes","lightbox_enable_zoom":"yes","lightbox_enable_share":"yes","lightbox_title_src":"title","lightbox_description_src":"description"},"post":{"id":79,"title":"Juegos%20Gratis%20Online%20-%20Juega%20en%20LudoRex","excerpt":"","featuredImage":"https:\/\/imagedelivery.net\/Gz9njdoQWfQyE3LMlxhb2w\/e341a1fd-a2fb-45a1-77cb-b44aae1d3600\/w=512,h=512,fit=crop"}};
/* ]]> */
</script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/elementor/assets/js/frontend.min.js?ver=3.29.1" id="elementor-frontend-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/pro-elements/assets/lib/smartmenus/jquery.smartmenus.min.js?ver=1.2.1" id="smartmenus-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-includes/js/imagesloaded.min.js?ver=5.0.0" id="imagesloaded-js" defer></script>
<script type="text/javascript" id="yasr-window-var-js-extra">
/* <![CDATA[ */
var yasrWindowVar = {"siteUrl":"https:\/\/ludorex.com","adminUrl":"https:\/\/ludorex.com\/wp-admin\/","ajaxurl":"https:\/\/ludorex.com\/wp-admin\/admin-ajax.php","visitorStatsEnabled":"no","ajaxEnabled":"yes","loaderHtml":"<div id=\"yasr-loader\" style=\"display: inline-block\">\u00a0 <img src=\"https:\/\/ludorex.com\/wp-content\/plugins\/yet-another-stars-rating\/includes\/img\/loader.gif\" \r\n                 title=\"yasr-loader\" alt=\"yasr-loader\" height=\"16\" width=\"16\"><\/div>","loaderUrl":"https:\/\/ludorex.com\/wp-content\/plugins\/yet-another-stars-rating\/includes\/img\/loader.gif","isUserLoggedIn":"false","isRtl":"false","starSingleForm":"\"estrella\"","starsPluralForm":"\"estrellas\"","textAfterVr":"\"\u00a0\u00a0Total: %total_count%  Media: %average%\"","textRating":"\"Valoraci\\u00f3n\"","textLoadRanking":"\"Cargando por favor espere\"","textVvStats":"\"de 5 estrellas\"","textOrderBy":"\"Ordenar por\"","textMostRated":"\"Mayor puntuaci\\u00f3n\"","textHighestRated":"\"Mejor puntuaci\\u00f3n\"","textLeftColumnHeader":"\"Enrada\""};
/* ]]> */
</script>
<script type="text/javascript" id="eael-general-js-extra">
/* <![CDATA[ */
var localize = {"ajaxurl":"https:\/\/ludorex.com\/wp-admin\/admin-ajax.php","nonce":"21d10f2c8e","i18n":{"added":"A\u00f1adido","compare":"Comparar","loading":"Cargando..."},"eael_translate_text":{"required_text":"es un campo obligatorio","invalid_text":"No v\u00e1lido","billing_text":"Facturaci\u00f3n","shipping_text":"Env\u00edo","fg_mfp_counter_text":"de"},"page_permalink":"https:\/\/ludorex.com\/","cart_redirectition":"no","cart_page_url":"","el_breakpoints":{"mobile":{"label":"M\u00f3vil vertical","value":767,"default_value":767,"direction":"max","is_enabled":true},"mobile_extra":{"label":"M\u00f3vil horizontal","value":880,"default_value":880,"direction":"max","is_enabled":false},"tablet":{"label":"Tableta vertical","value":1024,"default_value":1024,"direction":"max","is_enabled":true},"tablet_extra":{"label":"Tableta horizontal","value":1200,"default_value":1200,"direction":"max","is_enabled":false},"laptop":{"label":"Port\u00e1til","value":1366,"default_value":1366,"direction":"max","is_enabled":false},"widescreen":{"label":"Pantalla grande","value":2400,"default_value":2400,"direction":"min","is_enabled":false}}};
/* ]]> */
</script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/essential-addons-for-elementor-lite/assets/front-end/js/view/general.min.js?ver=6.1.9" id="eael-general-js" defer></script>
<script type="text/javascript" id="cmplz-cookiebanner-js-extra">
/* <![CDATA[ */
var complianz = {"prefix":"cmplz_","user_banner_id":"1","set_cookies":[],"block_ajax_content":"0","banner_version":"173","version":"7.4.0.1","store_consent":"","do_not_track_enabled":"","consenttype":"optin","region":"eu","geoip":"","dismiss_timeout":"","disable_cookiebanner":"","soft_cookiewall":"","dismiss_on_scroll":"","cookie_expiry":"365","url":"https:\/\/ludorex.com\/wp-json\/complianz\/v1\/","locale":"lang=es&locale=es_ES","set_cookies_on_root":"0","cookie_domain":"","current_policy_id":"35","cookie_path":"\/","categories":{"statistics":"estad\u00edsticas","marketing":"m\u00e1rketing"},"tcf_active":"","placeholdertext":"Haz clic para aceptar cookies de marketing y permitir este contenido","css_file":"https:\/\/ludorex.com\/wp-content\/uploads\/complianz\/css\/banner-{banner_id}-{type}.css?v=173","page_links":{"eu":{"cookie-statement":{"title":"Pol\u00edtica de Cookies","url":"https:\/\/ludorex.com\/politica-de-cookies"},"privacy-statement":{"title":"Pol\u00edtica de privacidad","url":"https:\/\/ludorex.com\/politica-de-privacidad"},"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}},"us":{"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}},"uk":{"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}},"ca":{"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}},"au":{"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}},"za":{"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}},"br":{"impressum":{"title":"Impressum","url":"https:\/\/ludorex.com\/terminos-y-condiciones-de-uso"}}},"tm_categories":"","forceEnableStats":"","preview":"","clean_cookies":"","aria_label":"Haz clic para aceptar cookies de marketing y permitir este contenido"};
/* ]]> */
</script>
<script type="rocketlazyloadscript" defer data-rocket-type="text/javascript" data-rocket-src="https://ludorex.com/wp-content/plugins/complianz-gdpr/cookiebanner/js/complianz.min.js?ver=1748473366" id="cmplz-cookiebanner-js"></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" id="cmplz-cookiebanner-js-after">window.addEventListener('DOMContentLoaded', function() {
/* <![CDATA[ */
    
		if ('undefined' != typeof window.jQuery) {
			jQuery(document).ready(function ($) {
				$(document).on('elementor/popup/show', () => {
					let rev_cats = cmplz_categories.reverse();
					for (let key in rev_cats) {
						if (rev_cats.hasOwnProperty(key)) {
							let category = cmplz_categories[key];
							if (cmplz_has_consent(category)) {
								document.querySelectorAll('[data-category="' + category + '"]').forEach(obj => {
									cmplz_remove_placeholder(obj);
								});
							}
						}
					}

					let services = cmplz_get_services_on_page();
					for (let key in services) {
						if (services.hasOwnProperty(key)) {
							let service = services[key].service;
							let category = services[key].category;
							if (cmplz_has_service_consent(service, category)) {
								document.querySelectorAll('[data-service="' + service + '"]').forEach(obj => {
									cmplz_remove_placeholder(obj);
								});
							}
						}
					}
				});
			});
		}
    
    
		
			document.addEventListener("cmplz_enable_category", function(consentData) {
				var category = consentData.detail.category;
				var services = consentData.detail.services;
				var blockedContentContainers = [];
				let selectorVideo = '.cmplz-elementor-widget-video-playlist[data-category="'+category+'"],.elementor-widget-video[data-category="'+category+'"]';
				let selectorGeneric = '[data-cmplz-elementor-href][data-category="'+category+'"]';
				for (var skey in services) {
					if (services.hasOwnProperty(skey)) {
						let service = skey;
						selectorVideo +=',.cmplz-elementor-widget-video-playlist[data-service="'+service+'"],.elementor-widget-video[data-service="'+service+'"]';
						selectorGeneric +=',[data-cmplz-elementor-href][data-service="'+service+'"]';
					}
				}
				document.querySelectorAll(selectorVideo).forEach(obj => {
					let elementService = obj.getAttribute('data-service');
					if ( cmplz_is_service_denied(elementService) ) {
						return;
					}
					if (obj.classList.contains('cmplz-elementor-activated')) return;
					obj.classList.add('cmplz-elementor-activated');

					if ( obj.hasAttribute('data-cmplz_elementor_widget_type') ){
						let attr = obj.getAttribute('data-cmplz_elementor_widget_type');
						obj.classList.removeAttribute('data-cmplz_elementor_widget_type');
						obj.classList.setAttribute('data-widget_type', attr);
					}
					if (obj.classList.contains('cmplz-elementor-widget-video-playlist')) {
						obj.classList.remove('cmplz-elementor-widget-video-playlist');
						obj.classList.add('elementor-widget-video-playlist');
					}
					obj.setAttribute('data-settings', obj.getAttribute('data-cmplz-elementor-settings'));
					blockedContentContainers.push(obj);
				});

				document.querySelectorAll(selectorGeneric).forEach(obj => {
					let elementService = obj.getAttribute('data-service');
					if ( cmplz_is_service_denied(elementService) ) {
						return;
					}
					if (obj.classList.contains('cmplz-elementor-activated')) return;

					if (obj.classList.contains('cmplz-fb-video')) {
						obj.classList.remove('cmplz-fb-video');
						obj.classList.add('fb-video');
					}

					obj.classList.add('cmplz-elementor-activated');
					obj.setAttribute('data-href', obj.getAttribute('data-cmplz-elementor-href'));
					blockedContentContainers.push(obj.closest('.elementor-widget'));
				});

				/**
				 * Trigger the widgets in Elementor
				 */
				for (var key in blockedContentContainers) {
					if (blockedContentContainers.hasOwnProperty(key) && blockedContentContainers[key] !== undefined) {
						let blockedContentContainer = blockedContentContainers[key];
						if (elementorFrontend.elementsHandler) {
							elementorFrontend.elementsHandler.runReadyTrigger(blockedContentContainer)
						}
						var cssIndex = blockedContentContainer.getAttribute('data-placeholder_class_index');
						blockedContentContainer.classList.remove('cmplz-blocked-content-container');
						blockedContentContainer.classList.remove('cmplz-placeholder-' + cssIndex);
					}
				}

			});
		
		
        
            document.addEventListener("cmplz_enable_category", function () {
                document.querySelectorAll('[data-rocket-lazyload]').forEach(obj => {
                    if (obj.hasAttribute('data-lazy-src')) {
                        obj.setAttribute('src', obj.getAttribute('data-lazy-src'));
                    }
                });
            });
        
		

	let cmplzBlockedContent = document.querySelector('.cmplz-blocked-content-notice');
	if ( cmplzBlockedContent) {
	        cmplzBlockedContent.addEventListener('click', function(event) {
            event.stopPropagation();
        });
	}
    
/* ]]> */
});</script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/pro-elements/assets/js/webpack-pro.runtime.min.js?ver=3.29.0" id="elementor-pro-webpack-runtime-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-includes/js/dist/hooks.min.js?ver=4d63a3d491d11ffd8ac6" id="wp-hooks-js"></script>
<script type="text/javascript" src="https://ludorex.com/wp-includes/js/dist/i18n.min.js?ver=5e580eb46a90c2b997e6" id="wp-i18n-js"></script>
<script type="rocketlazyloadscript" data-rocket-type="text/javascript" id="wp-i18n-js-after">
/* <![CDATA[ */
wp.i18n.setLocaleData( { 'text direction\u0004ltr': [ 'ltr' ] } );
/* ]]> */
</script>
<script type="text/javascript" id="elementor-pro-frontend-js-before">
/* <![CDATA[ */
var ElementorProFrontendConfig = {"ajaxurl":"https:\/\/ludorex.com\/wp-admin\/admin-ajax.php","nonce":"85d224fb5e","urls":{"assets":"https:\/\/ludorex.com\/wp-content\/plugins\/pro-elements\/assets\/","rest":"https:\/\/ludorex.com\/wp-json\/"},"settings":{"lazy_load_background_images":true},"popup":{"hasPopUps":true},"shareButtonsNetworks":{"facebook":{"title":"Facebook","has_counter":true},"twitter":{"title":"Twitter"},"linkedin":{"title":"LinkedIn","has_counter":true},"pinterest":{"title":"Pinterest","has_counter":true},"reddit":{"title":"Reddit","has_counter":true},"vk":{"title":"VK","has_counter":true},"odnoklassniki":{"title":"OK","has_counter":true},"tumblr":{"title":"Tumblr"},"digg":{"title":"Digg"},"skype":{"title":"Skype"},"stumbleupon":{"title":"StumbleUpon","has_counter":true},"mix":{"title":"Mix"},"telegram":{"title":"Telegram"},"pocket":{"title":"Pocket","has_counter":true},"xing":{"title":"XING","has_counter":true},"whatsapp":{"title":"WhatsApp"},"email":{"title":"Email"},"print":{"title":"Print"},"x-twitter":{"title":"X"},"threads":{"title":"Threads"}},"facebook_sdk":{"lang":"es_ES","app_id":"610736667495739"},"lottie":{"defaultAnimationUrl":"https:\/\/ludorex.com\/wp-content\/plugins\/pro-elements\/modules\/lottie\/assets\/animations\/default.json"}};
/* ]]> */
</script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/pro-elements/assets/js/frontend.min.js?ver=3.29.0" id="elementor-pro-frontend-js" defer></script>
<script type="text/javascript" src="https://ludorex.com/wp-content/plugins/pro-elements/assets/js/elements-handlers.min.js?ver=3.29.0" id="pro-elements-handlers-js" defer></script>
<!-- Statistics script Complianz GDPR/CCPA -->
						<script type="text/plain"							data-category="statistics">window['gtag_enable_tcf_support'] = false;
window.dataLayer = window.dataLayer || [];
function gtag(){dataLayer.push(arguments);}
gtag('js', new Date());
gtag('config', '', {
	cookie_flags:'secure;samesite=none',
	'anonymize_ip': true
});
</script><script>window.lazyLoadOptions=[{elements_selector:"img[data-lazy-src],.rocket-lazyload,iframe[data-lazy-src]",data_src:"lazy-src",data_srcset:"lazy-srcset",data_sizes:"lazy-sizes",class_loading:"lazyloading",class_loaded:"lazyloaded",threshold:300,callback_loaded:function(element){if(element.tagName==="IFRAME"&&element.dataset.rocketLazyload=="fitvidscompatible"){if(element.classList.contains("lazyloaded")){if(typeof window.jQuery!="undefined"){if(jQuery.fn.fitVids){jQuery(element).parent().fitVids()}}}}}},{elements_selector:".rocket-lazyload",data_src:"lazy-src",data_srcset:"lazy-srcset",data_sizes:"lazy-sizes",class_loading:"lazyloading",class_loaded:"lazyloaded",threshold:300,}];window.addEventListener('LazyLoad::Initialized',function(e){var lazyLoadInstance=e.detail.instance;if(window.MutationObserver){var observer=new MutationObserver(function(mutations){var image_count=0;var iframe_count=0;var rocketlazy_count=0;mutations.forEach(function(mutation){for(var i=0;i<mutation.addedNodes.length;i++){if(typeof mutation.addedNodes[i].getElementsByTagName!=='function'){continue}
if(typeof mutation.addedNodes[i].getElementsByClassName!=='function'){continue}
images=mutation.addedNodes[i].getElementsByTagName('img');is_image=mutation.addedNodes[i].tagName=="IMG";iframes=mutation.addedNodes[i].getElementsByTagName('iframe');is_iframe=mutation.addedNodes[i].tagName=="IFRAME";rocket_lazy=mutation.addedNodes[i].getElementsByClassName('rocket-lazyload');image_count+=images.length;iframe_count+=iframes.length;rocketlazy_count+=rocket_lazy.length;if(is_image){image_count+=1}
if(is_iframe){iframe_count+=1}}});if(image_count>0||iframe_count>0||rocketlazy_count>0){lazyLoadInstance.update()}});var b=document.getElementsByTagName("body")[0];var config={childList:!0,subtree:!0};observer.observe(b,config)}},!1)</script><script data-no-minify="1" async src="https://ludorex.com/wp-content/plugins/wp-rocket/assets/js/lazyload/17.8.3/lazyload.min.js"></script><script>function lazyLoadThumb(e,alt,l){var t='<img data-lazy-src="https://i.ytimg.com/vi/ID/hqdefault.jpg" alt="" width="480" height="360"><noscript><img src="https://i.ytimg.com/vi/ID/hqdefault.jpg" alt="" width="480" height="360"></noscript>',a='<button class="play" aria-label="play Youtube video"></button>';if(l){t=t.replace('data-lazy-','');t=t.replace('loading="lazy"','');t=t.replace(/<noscript>.*?<\/noscript>/g,'');}t=t.replace('alt=""','alt="'+alt+'"');return t.replace("ID",e)+a}function lazyLoadYoutubeIframe(){var e=document.createElement("iframe"),t="ID?autoplay=1";t+=0===this.parentNode.dataset.query.length?"":"&"+this.parentNode.dataset.query;e.setAttribute("src",t.replace("ID",this.parentNode.dataset.src)),e.setAttribute("frameborder","0"),e.setAttribute("allowfullscreen","1"),e.setAttribute("allow","accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"),this.parentNode.parentNode.replaceChild(e,this.parentNode)}document.addEventListener("DOMContentLoaded",function(){var exclusions=[];var e,t,p,u,l,a=document.getElementsByClassName("rll-youtube-player");for(t=0;t<a.length;t++)(e=document.createElement("div")),(u='https://i.ytimg.com/vi/ID/hqdefault.jpg'),(u=u.replace('ID',a[t].dataset.id)),(l=exclusions.some(exclusion=>u.includes(exclusion))),e.setAttribute("data-id",a[t].dataset.id),e.setAttribute("data-query",a[t].dataset.query),e.setAttribute("data-src",a[t].dataset.src),(e.innerHTML=lazyLoadThumb(a[t].dataset.id,a[t].dataset.alt,l)),a[t].appendChild(e),(p=e.querySelector(".play")),(p.onclick=lazyLoadYoutubeIframe)});</script>
<script>class RocketElementorAnimation{constructor(){this.deviceMode=document.createElement("span"),this.deviceMode.id="elementor-device-mode-wpr",this.deviceMode.setAttribute("class","elementor-screen-only"),document.body.appendChild(this.deviceMode)}_detectAnimations(){let t=getComputedStyle(this.deviceMode,":after").content.replace(/"/g,"");this.animationSettingKeys=this._listAnimationSettingsKeys(t),document.querySelectorAll(".elementor-invisible[data-settings]").forEach(t=>{const e=t.getBoundingClientRect();if(e.bottom>=0&&e.top<=window.innerHeight)try{this._animateElement(t)}catch(t){}})}_animateElement(t){const e=JSON.parse(t.dataset.settings),i=e._animation_delay||e.animation_delay||0,n=e[this.animationSettingKeys.find(t=>e[t])];if("none"===n)return void t.classList.remove("elementor-invisible");t.classList.remove(n),this.currentAnimation&&t.classList.remove(this.currentAnimation),this.currentAnimation=n;let s=setTimeout(()=>{t.classList.remove("elementor-invisible"),t.classList.add("animated",n),this._removeAnimationSettings(t,e)},i);window.addEventListener("rocket-startLoading",function(){clearTimeout(s)})}_listAnimationSettingsKeys(t="mobile"){const e=[""];switch(t){case"mobile":e.unshift("_mobile");case"tablet":e.unshift("_tablet");case"desktop":e.unshift("_desktop")}const i=[];return["animation","_animation"].forEach(t=>{e.forEach(e=>{i.push(t+e)})}),i}_removeAnimationSettings(t,e){this._listAnimationSettingsKeys().forEach(t=>delete e[t]),t.dataset.settings=JSON.stringify(e)}static run(){const t=new RocketElementorAnimation;requestAnimationFrame(t._detectAnimations.bind(t))}}document.addEventListener("DOMContentLoaded",RocketElementorAnimation.run);</script><script defer src="https://static.cloudflareinsights.com/beacon.min.js/vcd15cbe7772f49c399c6a5babf22c1241717689176015" integrity="sha512-ZpsOmlRQV6y907TI0dKBHq9Md29nnaEIPlkf84rnaERnq6zvWvPUqr2ft8M1aS28oN72PdrCzSjY4U6VaAw1EQ==" data-cf-beacon='{"version":"2024.11.0","token":"4519cd74f23d496882d41b0240ae1e41","r":1,"server_timing":{"name":{"cfCacheStatus":true,"cfEdge":true,"cfExtPri":true,"cfL4":true,"cfOrigin":true,"cfSpeedBrain":true},"location_startswith":null}}' crossorigin="anonymous"></script>
</body>
</html>

<!-- This website is like a Rocket, isn't it? Performance optimized by WP Rocket. Learn more: https://wp-rocket.me -->
