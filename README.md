

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd"><html xmlns="http://www.w3.org/1999/xhtml" lang="en-US">
<head profile="http://gmpg.org/xfn/11">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
<title>Edy&#8217;s Vehicle Physics Demo</title>
<meta name="description" content="Controls: WSAD or arrows Throttle, brake, steering. Space Handbrake. Enter Reset vehicle (e.g. if it rolls over). C Change camera. Tab or Page Up / Page Down Select vehicle. E [&hellip;]" />

<link rel="alternate" type="application/rss+xml" href="https://www.edy.es/dev/feed/" title="Edy&#039;s Projects latest posts" />

<link rel="alternate" type="application/rss+xml" href="https://www.edy.es/dev/comments/feed/" title="Edy&#039;s Projects latest comments" />

<link rel="pingback" href="https://www.edy.es/dev/xmlrpc.php" />

<link rel="shortcut icon" href="https://www.edy.es/dev/wp-content/themes/arras/images/favicon.ico" />


<link rel='dns-prefetch' href='//secure.gravatar.com' />
<link rel='dns-prefetch' href='//s.w.org' />
<link rel="alternate" type="application/rss+xml" title="Edy&#039;s Projects &raquo; Edy&#8217;s Vehicle Physics Demo Comments Feed" href="https://www.edy.es/dev/vehicle-physics/demo/feed/" />
		<script type="text/javascript">
			window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/12.0.0-1\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/12.0.0-1\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/www.edy.es\/dev\/wp-includes\/js\/wp-emoji-release.min.js?ver=5.3.10"}};
			!function(e,a,t){var n,r,o,i=a.createElement("canvas"),p=i.getContext&&i.getContext("2d");function s(e,t){var a=String.fromCharCode;p.clearRect(0,0,i.width,i.height),p.fillText(a.apply(this,e),0,0);e=i.toDataURL();return p.clearRect(0,0,i.width,i.height),p.fillText(a.apply(this,t),0,0),e===i.toDataURL()}function c(e){var t=a.createElement("script");t.src=e,t.defer=t.type="text/javascript",a.getElementsByTagName("head")[0].appendChild(t)}for(o=Array("flag","emoji"),t.supports={everything:!0,everythingExceptFlag:!0},r=0;r<o.length;r++)t.supports[o[r]]=function(e){if(!p||!p.fillText)return!1;switch(p.textBaseline="top",p.font="600 32px Arial",e){case"flag":return s([127987,65039,8205,9895,65039],[127987,65039,8203,9895,65039])?!1:!s([55356,56826,55356,56819],[55356,56826,8203,55356,56819])&&!s([55356,57332,56128,56423,56128,56418,56128,56421,56128,56430,56128,56423,56128,56447],[55356,57332,8203,56128,56423,8203,56128,56418,8203,56128,56421,8203,56128,56430,8203,56128,56423,8203,56128,56447]);case"emoji":return!s([55357,56424,55356,57342,8205,55358,56605,8205,55357,56424,55356,57340],[55357,56424,55356,57342,8203,55358,56605,8203,55357,56424,55356,57340])}return!1}(o[r]),t.supports.everything=t.supports.everything&&t.supports[o[r]],"flag"!==o[r]&&(t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&t.supports[o[r]]);t.supports.everythingExceptFlag=t.supports.everythingExceptFlag&&!t.supports.flag,t.DOMReady=!1,t.readyCallback=function(){t.DOMReady=!0},t.supports.everything||(n=function(){t.readyCallback()},a.addEventListener?(a.addEventListener("DOMContentLoaded",n,!1),e.addEventListener("load",n,!1)):(e.attachEvent("onload",n),a.attachEvent("onreadystatechange",function(){"complete"===a.readyState&&t.readyCallback()})),(n=t.source||{}).concatemoji?c(n.concatemoji):n.wpemoji&&n.twemoji&&(c(n.twemoji),c(n.wpemoji)))}(window,document,window._wpemojiSettings);
		</script>
		<style type="text/css">
img.wp-smiley,
img.emoji {
	display: inline !important;
	border: none !important;
	box-shadow: none !important;
	height: 1em !important;
	width: 1em !important;
	margin: 0 .07em !important;
	vertical-align: -0.1em !important;
	background: none !important;
	padding: 0 !important;
}
</style>
	<link rel='stylesheet' id='page-list-style-css'  href='https://www.edy.es/dev/wp-content/plugins/page-list/css/page-list.css?ver=5.2' type='text/css' media='all' />
<link rel='stylesheet' id='social-logos-css'  href='https://www.edy.es/dev/wp-content/plugins/jetpack/_inc/social-logos/social-logos.min.css?ver=1' type='text/css' media='all' />
<link rel='stylesheet' id='jetpack_css-css'  href='https://www.edy.es/dev/wp-content/plugins/jetpack/css/jetpack.css?ver=8.1.2' type='text/css' media='all' />
<link rel='stylesheet' id='thickbox-css'  href='https://www.edy.es/dev/wp-content/plugins/auto-thickbox-plus/thickbox.min.css?ver=1.9' type='text/css' media='all' />
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/jquery/jquery.js?ver=1.12.4-wp'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/jquery/jquery-migrate.min.js?ver=1.4.1'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/themes/arras/js/superfish/hoverIntent.js'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/themes/arras/js/superfish/superfish.js'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/themes/arras/js/jquery.validate.min.js'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var thickboxL10n = {"next":"Next >","prev":"< Prev","image":"Image","of":"of","close":"Close","noiframes":"This feature requires inline frames. You have iframes disabled or your browser does not support them.","loadingAnimation":"https:\/\/www.edy.es\/dev\/wp-content\/plugins\/auto-thickbox-plus\/images\/loadingAnimation.gif","closeImage":"https:\/\/www.edy.es\/dev\/wp-content\/plugins\/auto-thickbox-plus\/images\/tb-close.png"};
/* ]]> */
</script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/plugins/auto-thickbox-plus/thickbox.min.js?ver=1.9'></script>
<link rel='https://api.w.org/' href='https://www.edy.es/dev/wp-json/' />
<link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://www.edy.es/dev/xmlrpc.php?rsd" />
<link rel="wlwmanifest" type="application/wlwmanifest+xml" href="https://www.edy.es/dev/wp-includes/wlwmanifest.xml" /> 
<meta name="generator" content="WordPress 5.3.10" />
<link rel="canonical" href="https://www.edy.es/dev/vehicle-physics/demo/" />
<link rel='shortlink' href='https://wp.me/P1PjRF-mG' />
<link rel="alternate" type="application/json+oembed" href="https://www.edy.es/dev/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.edy.es%2Fdev%2Fvehicle-physics%2Fdemo%2F" />
<link rel="alternate" type="text/xml+oembed" href="https://www.edy.es/dev/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fwww.edy.es%2Fdev%2Fvehicle-physics%2Fdemo%2F&#038;format=xml" />

<link rel='dns-prefetch' href='//v0.wordpress.com'/>
<link rel="stylesheet" href="https://www.edy.es/dev/wp-content/themes/arras/css/styles/default.css" type="text/css" media="screen,projection" /><link rel="stylesheet" href="https://www.edy.es/dev/wp-content/themes/arras/css/layouts/1c-fixed.css" type="text/css" />
<!-- Generated by Arras WP Theme -->
<style type="text/css">
	.posts-default li  { width: 205px; height: 225px; }
	.posts-default img, .posts-default .entry-thumbnails-link { width: 195px; height: 110px; }
	.posts-default .entry-meta { width: 195px; }
	.posts-default .entry-thumbnails { width: 205px; height: 120px; }
			.posts-quick .entry-thumbnails img { width: 115px; height: 115px; }
		.posts-quick .entry-meta { width: 115px; }
			.featured { height: 310px; }
	.featured-article { width: 640px; height: 300px; }
	.featured-article img { width: 640px; height: 300px; }
	#controls { width: 610px; top: 135px; }
	#controls .next { left: 610px; }
	.featured-entry { height: 100px; top: -100px; }
	.featured-slideshow-inner { height: 300px }
		.featured-stories-summary  { margin-left: 51px; }
	.single .post .entry-photo img, .single-post .entry-photo img  { width: 620px; height: 300px; }
	.blog-name a { background: url(https://www.edy.es/dev/wp-content/uploads/2011/11/webplatelogo.png) no-repeat; text-indent: -9000px; width: 247px; height: 150px; display: block; }
	.footer-sidebar  { width: 920px; }
	</style>
	<script type="text/javascript">
	jQuery(document).ready(function($) {

$('.multi-sidebar').tabs();

$('.sf-menu').superfish({autoArrows: true, speed: 'fast', dropShadows: 'true'});

$('#commentform').validate();


});	</script>
	
<!-- Dynamic Widgets by QURL loaded - http://www.dynamic-widgets.com //-->
<style type="text/css">.broken_link, a.broken_link {
	text-decoration: line-through;
}</style>
<!-- Jetpack Open Graph Tags -->
<meta property="og:type" content="article" />
<meta property="og:title" content="Edy&#8217;s Vehicle Physics Demo" />
<meta property="og:url" content="https://www.edy.es/dev/vehicle-physics/demo/" />
<meta property="og:description" content="Controls: WSAD or arrows Throttle, brake, steering. Space Handbrake. Enter Reset vehicle (e.g. if it rolls over). C Change camera. Tab or Page Up / Page Down Select vehicle. E Makes the gray stone …" />
<meta property="article:published_time" content="2015-04-29T15:53:15+00:00" />
<meta property="article:modified_time" content="2021-12-14T18:56:51+00:00" />
<meta property="og:site_name" content="Edy&#039;s Projects" />
<meta property="og:image" content="https://s0.wp.com/i/blank.jpg" />
<meta property="og:locale" content="en_US" />
<meta name="twitter:text:title" content="Edy&#8217;s Vehicle Physics Demo" />
<meta name="twitter:card" content="summary" />

<!-- End Jetpack Open Graph Tags -->
<link rel="stylesheet" href="https://www.edy.es/dev/wp-content/themes/arras/user.css" type="text/css" media="screen,projection" /><!-- Auto ThickBox Plus by attosoft (http://attosoft.info/en/) -->
<script type="text/javascript">
/* <![CDATA[ */
jQuery(function($) {
	var links = $('a[href][href!=""]').filter(function() {
		// No ThickBox
		var nothickbox = ['nothickbox', 'no_thickbox'];
		for (var i = 0; i < nothickbox.length; i++)
			if ($(this).hasClass(nothickbox[i])) return false;
		// Links with target attribute
		if ($(this).is('[target][target!=""]')) return false;

		return true;
	});

	// Images
	var imageRegex = /\.(jpe?g|gif|png|bmp|webp)($|[?&#])/i;
	var images = links.filter(function() {
		return imageRegex.test($(this).attr('href'));
	});
	images.addClass('thickbox');
	// Gallery Images
	images.not('[rel][rel!=""]').attr('rel', 'gallery-1406');

	// Others
	var others = links.filter(function() {
		return !imageRegex.test($(this).attr('href'));
	});
	others.filter('.thickbox').not('[href*="TB_iframe"]').not('[href*="#TB_inline"]').each(function() {
		var href = $(this).attr('href');
		if (href.indexOf('://') != -1 && href.indexOf(location.host) == -1) {
			// Add 'TB_iframe' to external URL
			var hashIndex = href.indexOf('#');
			var before = hashIndex == -1 ? href : href.substring(0, hashIndex);
			var after = hashIndex == -1 ? '' : href.substring(hashIndex);
			$(this).attr('href', before + (before.indexOf('?') == -1 ? '?' : '&') + 'TB_iframe' + after);
		}
	});
	others.filter('[href*="TB_iframe"]').add('[href*="#TB_inline"]').addClass('thickbox');

	// for WordPress 2.7.x (jQuery 1.2.6)
	if (!$.isFunction($().live))
		tb_init('a.thickbox');

	// Set a different gallery-id for each WordPress Gallery
	$('div.gallery').each(function() {
		if (this.id)
			$(this).find('a.thickbox').attr('rel', this.id);
	});
});

// Options for ThickBox Plus
tb_options.effect_open = 'fade';
tb_options.effect_trans = 'fade';
tb_options.click_img = 'none';
/* ]]> */
</script>
			<style type="text/css" id="wp-custom-css">
				/*
Welcome to Custom CSS!

CSS (Cascading Style Sheets) is a kind of code that tells the browser how
to render a web page. You may delete these comments and get started with
your customizations.

By default, your stylesheet will be loaded after the theme stylesheets,
which means that your rules can take precedence and override the theme CSS
rules. Just write here what you want to change, you don't need to copy all
your theme's stylesheet content.
*/
/* EDY: Permitir 4 columnas en galerías */
.gallery .gallery-item {
	width: 200px;
}

/* EDY: Fix para el padding de las listas UL junto a imágenes */
.entry-content ul {
	padding: 0 2em 1em;
	margin: 0;
	position: relative;
	left: 1em;
}

a, a:link, a:visited {
	color: #C00;
	text-decoration: none;
}

a:hover {
	color: #E00;
	text-decoration: underline;
}

/* EDY: Menus de página */
ul.shortcode_menu.pagemenu {
	margin: 0 auto 20px 20px !important;
}

ul.shortcode_menu.pagemenu li {
	margin: 0;
}

ul.shortcode_menu.pagemenu li.current-menu-item a {
	pointer-events: none;
	color: #000;
}			</style>
		</head>

<body class="page-template page-template-pagetpl-onecolumn page-template-pagetpl-onecolumn-php page page-id-1406 page-child parent-pageid-5 layout-2c-r-fixed no-js style-default">
<script type="text/javascript">
//<![CDATA[
(function(){
var c = document.body.className;
c = c.replace(/no-js/, 'js');
document.body.className = c;
})();
//]]>
</script>

<div id="top-menu" class="clearfix">
	</div><!-- #top-menu -->

<div id="header">
	<div id="branding" class="clearfix">
	<div class="logo">
				<span class="blog-name"><a href="https://www.edy.es/dev">Edy&#039;s Projects</a></span>
		<span class="blog-description"></span>
			</div>
	<div id="searchbar"><form method="get" class="searchform clearfix" action="https://www.edy.es/dev/">
 <input type="text" value="Search..." name="s" class="s" onfocus="this.value=''" />
 <input type="submit" class="searchsubmit" value="Search" title="Search Edy&#039;s Projects" />
</form>
</div>
	</div><!-- #branding -->
</div><!-- #header -->

<div id="nav">
	<div id="nav-content" class="clearfix">
	<div class="menu-mainmenu-container"><ul id="menu-mainmenu" class="sf-menu menu clearfix"><li id="menu-item-220" class="menu-item menu-item-type-taxonomy menu-item-object-category menu-item-220"><a href="https://www.edy.es/dev/category/blog/">Blog</a></li>
<li id="menu-item-233" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-233"><a href="https://www.edy.es/dev/docs/">Documents</a></li>
<li id="menu-item-397" class="menu-item menu-item-type-post_type menu-item-object-page current-page-ancestor current-menu-ancestor current-menu-parent current-page-parent current_page_parent current_page_ancestor menu-item-has-children menu-item-397"><a href="https://www.edy.es/dev/vehicle-physics/">Edy&#8217;s Vehicle Physics</a>
<ul class="sub-menu">
	<li id="menu-item-402" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-402"><a href="https://www.edy.es/dev/vehicle-physics/features/">Features</a></li>
	<li id="menu-item-1514" class="menu-item menu-item-type-post_type menu-item-object-page current-menu-item page_item page-item-1406 current_page_item menu-item-1514"><a href="https://www.edy.es/dev/vehicle-physics/demo/" aria-current="page">Demo</a></li>
	<li id="menu-item-1515" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1515"><a href="https://www.edy.es/dev/vehicle-physics/user-guide/">User Guide</a></li>
	<li id="menu-item-1516" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1516"><a href="https://www.edy.es/dev/vehicle-physics/upgrade-notes/">Upgrade notes</a></li>
</ul>
</li>
</ul></div>		<ul class="quick-nav clearfix">
					<li><a id="rss" title="Edy&#039;s Projects RSS Feed" href="https://www.edy.es/dev/feed/">RSS Feed</a></li>
				
						
						
			</ul>
	</div><!-- #nav-content -->
</div><!-- #nav -->

<div id="wrapper">
	
	  
	<div id="main" class="clearfix">
    <div id="container" class="clearfix">

<div id="content" class="section">

		<div id="post-1406" class="clearfix single-post post-1406 page type-page status-publish hentry">
        <h1 class="entry-title"><a href="https://www.edy.es/dev/vehicle-physics/demo/" rel="bookmark">Edy&#8217;s Vehicle Physics Demo</a></h1>        
        <div class="entry-content clearfix">
		<div class="menu-edys-vehicle-physics-container"><ul id="short_menu_61b913ea51c29" class="shortcode_menu pagemenu wpsm-menu enhance_shortcode_menu_inline  "><li id="menu-item-1335" class="menu-item menu-item-type-post_type menu-item-object-page current-page-ancestor current-page-parent menu-item-1335"><a href="https://www.edy.es/dev/vehicle-physics/">Home</a></li>
<li id="menu-item-1338" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1338"><a href="https://www.edy.es/dev/vehicle-physics/features/">Features</a></li>
<li id="menu-item-1412" class="menu-item menu-item-type-post_type menu-item-object-page current-menu-item page_item page-item-1406 current_page_item menu-item-1412"><a href="https://www.edy.es/dev/vehicle-physics/demo/" aria-current="page">Demo</a></li>
<li id="menu-item-1384" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1384"><a href="https://www.edy.es/dev/vehicle-physics/user-guide/">User Guide</a></li>
<li id="menu-item-1336" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1336"><a href="https://www.edy.es/dev/vehicle-physics/upgrade-notes/">Upgrade notes</a></li>
</ul></div><div class="clear"></div>
			<style>
				#short_menu_61b913ea51c29 {  }
				#short_menu_61b913ea51c29 ul.wpsm-arrow-enabled:before {  } 
				#short_menu_61b913ea51c29 ul, #short_menu_61b913ea51c29 ul ul {  }
				#short_menu_61b913ea51c29 a {  }
				#short_menu_61b913ea51c29 a:hover {  }
				#short_menu_61b913ea51c29 ul a {  }
				#short_menu_61b913ea51c29 ul a:hover {  }
				
			</style>
			<script type="text/javascript">
				var show_arrow = "true";var $sm = jQuery.noConflict();
					jQuery(function ($) {
						$("#short_menu_61b913ea51c29").tinyNav();
						$("#short_menu_61b913ea51c29").next().addClass("shortcode-menu-mobile");
						
						shortcode_menu_responsive();
					});
					jQuery(window).resize(function($){
						shortcode_menu_responsive();
					});
					function shortcode_menu_responsive()
					{
						var window_width = $sm(window).width();
						if(window_width <= 650)
						{
							$sm("#short_menu_61b913ea51c29").hide();
							$sm("#short_menu_61b913ea51c29").next().show();
						}
						else
						{
							$sm("#short_menu_61b913ea51c29").show();
							$sm("#short_menu_61b913ea51c29").next().hide();
						}
					}</script>
<p><iframe id="" src="https://edy.es/unity/evp5-demo/index.html" name="" width="920" height="600" frameborder="0" marginheight="0" scrolling="no"></iframe></p>
<p>Controls:</p>
<table>
<tbody>
<tr>
<td>WSAD or arrows</td>
<td>Throttle, brake, steering.</td>
</tr>
<tr>
<td>Space</td>
<td>Handbrake.</td>
</tr>
<tr>
<td>Enter</td>
<td>Reset vehicle (e.g. if it rolls over).</td>
</tr>
<tr>
<td>C</td>
<td>Change camera.</td>
</tr>
<tr>
<td>Tab or Page Up / Page Down</td>
<td>Select vehicle.</td>
</tr>
<tr>
<td>E</td>
<td>Makes the gray stone to &#8220;jump&#8221;. Useful for load tests.</td>
</tr>
<tr>
<td>R</td>
<td>Repair vehicle damage.</td>
</tr>
<tr>
<td>T</td>
<td>Slow motion time mode on/off.</td>
</tr>
<tr>
<td>P</td>
<td>Pause vehicles. Camera and vehicle selection can be used while paused.</td>
</tr>
<tr>
<td>Y</td>
<td>Show/Hide telemetry.</td>
</tr>
<tr>
<td>shift-Y</td>
<td>Change Telemetry mode.</td>
</tr>
<tr>
<td>Esc</td>
<td>Reset scene</td>
</tr>
</tbody>
</table>
<div class="sharedaddy sd-sharing-enabled"><div class="robots-nocontent sd-block sd-social sd-social-official sd-sharing"><h3 class="sd-title">Share:</h3><div class="sd-content"><ul><li class="share-facebook"><div class="fb-share-button" data-href="https://www.edy.es/dev/vehicle-physics/demo/" data-layout="button_count"></div></li><li class="share-twitter"><a href="https://twitter.com/share" class="twitter-share-button" data-url="https://www.edy.es/dev/vehicle-physics/demo/" data-text="Edy&#039;s Vehicle Physics Demo"  >Tweet</a></li><li class="share-reddit"><div class="reddit_button"><iframe src="https://www.reddit.com/static/button/button1.html?newwindow=true&width=120&amp;url=https%3A%2F%2Fwww.edy.es%2Fdev%2Fvehicle-physics%2Fdemo%2F&amp;title=Edy%27s%20Vehicle%20Physics%20Demo" height="22" width="120" scrolling="no" frameborder="0"></iframe></div></li><li class="share-linkedin"><div class="linkedin_button"><script type="in/share" data-url="https://www.edy.es/dev/vehicle-physics/demo/" data-counter="right"></script></div></li><li class="share-print"><a rel="nofollow noopener noreferrer" data-shared="" class="share-print sd-button" href="https://www.edy.es/dev/vehicle-physics/demo/#print" target="_blank" title="Click to print"><span>Print</span></a></li><li class="share-end"></li></ul></div></div></div>  
        		</div>
        
		
            </div>
    
		<a name="comments"></a>
    
	  
	<h4 class="module-title">107 Comments</h4>
		<ol id="commentlist" class="clearfix">
				<li class="comment even thread-even depth-1" id="li-comment-28950">
		<div class="comment-node" id="comment-28950">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/bc39a4c633ce3dbe457b6b10c8c42a5b?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/bc39a4c633ce3dbe457b6b10c8c42a5b?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Yo Mumma</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-09-28T23:38:20+02:00">September 28, 2015 at 11:38 PM</abbr>			</div>
			<div class="comment-content"><p>Hey guys what does the collider part of the damage section mean . It is always 0.00 even when my car is screwed</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-29073">
		<div class="comment-node" id="comment-29073">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-10-09T13:38:28+02:00">October 9, 2015 at 1:38 PM</abbr>			</div>
			<div class="comment-content"><p>That release was compiled with a Unity version that didn&#8217;t support collider deformation. Recent releases show the amount of deformation applied to the vehicle&#8217;s collider as for the damage.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-29831">
		<div class="comment-node" id="comment-29831">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-16T05:05:17+01:00">December 16, 2015 at 5:05 AM</abbr>			</div>
			<div class="comment-content"><p>I used to be able to switch ABS/TC/AWD on and off. Is this still possible? Also, I prefered the F1-F6 cam views. Is this also still possible?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-29837">
		<div class="comment-node" id="comment-29837">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-16T10:56:03+01:00">December 16, 2015 at 10:56 AM</abbr>			</div>
			<div class="comment-content"><p>ABS / TC / AWD settings will be available in a upcoming upgrade. Also the Camera views. I&#8217;m now working on these and more remaining features from the previous version.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-29841">
		<div class="comment-node" id="comment-29841">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-17T00:26:03+01:00">December 17, 2015 at 12:26 AM</abbr>			</div>
			<div class="comment-content"><p>That&#8217;s good to hear Edy. I&#8217;m looking forward to it. (I haven&#8217;t played this in a long time&#8230;) Something else I noticed, if you pause while some sort of particles are being generated, the particles keep being generated while paused, rather than just stopping the particles.</p>
<p>Thanks a lot Edy! This sim is the best one I&#8217;ve played in a long time. Thanks a lot, once again.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-29871">
		<div class="comment-node" id="comment-29871">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-18T23:52:16+01:00">December 18, 2015 at 11:52 PM</abbr>			</div>
			<div class="comment-content"><p>Thank you for your feedback! I hadn&#8217;t noticed that issue, but the Pause function is an experimental feature at this time. It will greatly evolve in upcoming versions 🙂</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-29873">
		<div class="comment-node" id="comment-29873">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-19T01:21:36+01:00">December 19, 2015 at 1:21 AM</abbr>			</div>
			<div class="comment-content"><p>Using my rudimentary programming knowledge, it might be a particle spawner&#8230;(Hey, I&#8217;ve only used lua for Minetest so far&#8230;), which just continues spawning them. But, like I said, I don&#8217;t know anything about Unity&#8230;</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-29874">
		<div class="comment-node" id="comment-29874">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-19T01:26:44+01:00">December 19, 2015 at 1:26 AM</abbr>			</div>
			<div class="comment-content"><p>It&#8217;s not using particle spawners. The particles are generated from code, but looks like the script is not aware of the Pause state 😀</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-29875">
		<div class="comment-node" id="comment-29875">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-19T01:31:02+01:00">December 19, 2015 at 1:31 AM</abbr>			</div>
			<div class="comment-content"><p>Like I said: I don&#8217;t use Unity, so I have no idea how it works&#8230;. 🙂 </p>
<p>I played the old version again (thanks to Google), and, wow, those old cars handle much, much worse than the new ones.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-29940">
		<div class="comment-node" id="comment-29940">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/24f135a7287fe8a5c3e27cd4abb2dcc3?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/24f135a7287fe8a5c3e27cd4abb2dcc3?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Drift</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-25T03:56:37+01:00">December 25, 2015 at 3:56 AM</abbr>			</div>
			<div class="comment-content"><p>Hi Edy,</p>
<p>I read something of the pro vehicle phys from you long time ago. Is this available too? Or is your car system added to unity 5 already?</p>
<p>Didn&#8217;t find anything about.</p>
<p>Thanks</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-29962">
		<div class="comment-node" id="comment-29962">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2015-12-28T12:01:46+01:00">December 28, 2015 at 12:01 PM</abbr>			</div>
			<div class="comment-content"><p>Vehicle Physics Pro is about to enter the Beta stage. Early Access is available with the Profesional license:<br />
<a href="https://vehiclephysics.com" rel="nofollow ugc">https://vehiclephysics.com</a></p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30003">
		<div class="comment-node" id="comment-30003">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-01-07T01:56:39+01:00">January 7, 2016 at 1:56 AM</abbr>			</div>
			<div class="comment-content"><p>I found that the blue ute&#8217;s wing mirror would deform, but the red ute&#8217;s doesn&#8217;t. Is this intentional, or are they just using different hitboxes?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-30014">
		<div class="comment-node" id="comment-30014">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-01-08T02:28:49+01:00">January 8, 2016 at 2:28 AM</abbr>			</div>
			<div class="comment-content"><p>Both trucks have different damage settings to illustrate the features of the damage component.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-30015">
		<div class="comment-node" id="comment-30015">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-01-08T03:03:58+01:00">January 8, 2016 at 3:03 AM</abbr>			</div>
			<div class="comment-content"><p>Ah, ok. Thanks.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-30017">
		<div class="comment-node" id="comment-30017">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/24f135a7287fe8a5c3e27cd4abb2dcc3?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/24f135a7287fe8a5c3e27cd4abb2dcc3?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Drift</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-01-08T04:49:47+01:00">January 8, 2016 at 4:49 AM</abbr>			</div>
			<div class="comment-content"><p>Hi Edy,</p>
<p>An interesting feature would be a Lod mechanism in case of distance.</p>
<p>A) I thought about AI controlled Cars following a Spline. So perhaps it&#8217;s possible to reduce some non relevant aspects to disable in order of distance. </p>
<p>B) A LightWight physics car system that can be used for AI controlled cars.</p>
<p>I think none of the car assets does until now.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-31895">
		<div class="comment-node" id="comment-31895">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/8f02052eab01f342dd172f788bf804a5?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/8f02052eab01f342dd172f788bf804a5?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Kwan</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-06-17T09:35:52+02:00">June 17, 2016 at 9:35 AM</abbr>			</div>
			<div class="comment-content"><p>Hi Edy,<br />
I&#8217;m very interesting in VPP, how can I get Profesional license?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-33675">
		<div class="comment-node" id="comment-33675">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/c96e63cd14061e02ec4ea90945e2c498?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/c96e63cd14061e02ec4ea90945e2c498?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">James</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-11-08T22:17:33+01:00">November 8, 2016 at 10:17 PM</abbr>			</div>
			<div class="comment-content"><p>dear edy i was wondering if you can do a tire damage mode like if you hit the curb it will pop of just regular tire wear</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-33793">
		<div class="comment-node" id="comment-33793">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-11-17T19:44:20+01:00">November 17, 2016 at 7:44 PM</abbr>			</div>
			<div class="comment-content"><p>@Drift That feature is too specific to each final project. That would explain why no other car assets include it. EVP offers complete flexibility for you to implement the optimization in the way you want: you may disable every add-on component except physics (damage, audio, visual effects), or even disable the physics and move the vehicle yourself, then re-enable physics.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-33794">
		<div class="comment-node" id="comment-33794">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-11-17T21:11:20+01:00">November 17, 2016 at 9:11 PM</abbr>			</div>
			<div class="comment-content"><p>@Kwan Please write me to edy @ vehiclephysics.com for more information. Thanks!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-33795">
		<div class="comment-node" id="comment-33795">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-11-17T21:14:06+01:00">November 17, 2016 at 9:14 PM</abbr>			</div>
			<div class="comment-content"><p>@james Vehicle Physics Pro may include such damage model in the future. I plan to develop a new wheel and tire model including the possibility for receiving such damage.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-33880">
		<div class="comment-node" id="comment-33880">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/3b6386dbf00b08b35d9e48a115ce835d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/3b6386dbf00b08b35d9e48a115ce835d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">apathyjr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-11-23T21:15:08+01:00">November 23, 2016 at 9:15 PM</abbr>			</div>
			<div class="comment-content"><p>Hey Edy,<br />
Can you add multiplayer or servers?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-34171">
		<div class="comment-node" id="comment-34171">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/7e3dd0533cf971f539a2a6a7e8e44a33?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/7e3dd0533cf971f539a2a6a7e8e44a33?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">jesse</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2016-12-13T08:40:38+01:00">December 13, 2016 at 8:40 AM</abbr>			</div>
			<div class="comment-content"><p>why are there only 6 cars</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-34689">
		<div class="comment-node" id="comment-34689">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/7a39514824726c990e8243cfff672c96?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/7a39514824726c990e8243cfff672c96?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Slake_it</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-01-19T10:00:02+01:00">January 19, 2017 at 10:00 AM</abbr>			</div>
			<div class="comment-content"><p>The demo doesn&#8217;t start neither on firefox nor edge ?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-34690">
		<div class="comment-node" id="comment-34690">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/7a39514824726c990e8243cfff672c96?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/7a39514824726c990e8243cfff672c96?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">slake_it</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-01-19T10:04:56+01:00">January 19, 2017 at 10:04 AM</abbr>			</div>
			<div class="comment-content"><p>Hi there, it finally worked, however, can you add adjustable parameters so I can see if I can generate the movement type I want before purchasing the asset ?</p>
<p>Thanks.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-34724">
		<div class="comment-node" id="comment-34724">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-01-21T17:49:14+01:00">January 21, 2017 at 5:49 PM</abbr>			</div>
			<div class="comment-content"><p>@apathyjr I plan to build a multi-player example in the future.</p>
<p>@jesse these are just a few examples of different car setups that can be achieved with EVP.</p>
<p>@Slake_it give it a while. There&#8217;s no progress bar yet, and it must download a significant amount of resources.</p>
<p>@slake_it I&#8217;m now very busy working on the demo for Vehicle Physics Pro, so it will take some time before this demo is updated. You may write me to edy @ vehiclephysics.com describing the movement type you want to achieve and I&#8217;ll tell you my opinion on it.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-34733">
		<div class="comment-node" id="comment-34733">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/24f135a7287fe8a5c3e27cd4abb2dcc3?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/24f135a7287fe8a5c3e27cd4abb2dcc3?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Roger C.</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-01-22T03:05:08+01:00">January 22, 2017 at 3:05 AM</abbr>			</div>
			<div class="comment-content"><p>Hi,</p>
<p>is there any example how to make a vehicle following an path? </p>
<p>I brought the Curvy asset from the unity asset store. I know how to use the API from curvy but I have no idea how I can code a car that use your vehicle physics to follow a path. The API contains nearestPoint(obj, path).</p>
<p>Would be also great to have a code demo how to make a car following a clicked point on any collider. </p>
<p>Thank you,</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-34930">
		<div class="comment-node" id="comment-34930">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/a1b278d7ecdb20f48dc5ba117c175864?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/a1b278d7ecdb20f48dc5ba117c175864?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Johnny</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-01-31T20:07:11+01:00">January 31, 2017 at 8:07 PM</abbr>			</div>
			<div class="comment-content"><p>yo, how do i gt off of roofs? i always glich there</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-34931">
		<div class="comment-node" id="comment-34931">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/a1b278d7ecdb20f48dc5ba117c175864?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/a1b278d7ecdb20f48dc5ba117c175864?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Johnny</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-01-31T20:10:14+01:00">January 31, 2017 at 8:10 PM</abbr>			</div>
			<div class="comment-content"><p>yo, what is that truck doing? it drives by itself</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-35077">
		<div class="comment-node" id="comment-35077">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/aecd80d4841df2313b300604bdb32cfc?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/aecd80d4841df2313b300604bdb32cfc?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Matthew Reeves</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-02-08T02:07:07+01:00">February 8, 2017 at 2:07 AM</abbr>			</div>
			<div class="comment-content"><p>This thing is amazing. I just love doing crazy stunts with the cars and crashing them into each other. Edy you are amazing.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-35741">
		<div class="comment-node" id="comment-35741">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0e1fbfcad8aad6a494f4923d61b4f217?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wilkgr</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-03-27T01:49:40+02:00">March 27, 2017 at 1:49 AM</abbr>			</div>
			<div class="comment-content"><p>@david2126 Loads fine here, probably your computer</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-36223">
		<div class="comment-node" id="comment-36223">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0d40452e443461489bf4dda60da38823?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0d40452e443461489bf4dda60da38823?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Jesus</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-05-14T01:57:36+02:00">May 14, 2017 at 1:57 AM</abbr>			</div>
			<div class="comment-content"><p>this game is really good but when i start it up it laggs and it take time to function right please fix this problem</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-37290">
		<div class="comment-node" id="comment-37290">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/056bc4b790823af74ee52a98eb29744e?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/056bc4b790823af74ee52a98eb29744e?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Max</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-07-29T16:04:20+02:00">July 29, 2017 at 4:04 PM</abbr>			</div>
			<div class="comment-content"><p>My god, it&#8217;s better than in GTA IV.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-37470">
		<div class="comment-node" id="comment-37470">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/01b5822eef74e194be96f720395d7fda?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/01b5822eef74e194be96f720395d7fda?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Hank</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-08-13T15:29:45+02:00">August 13, 2017 at 3:29 PM</abbr>			</div>
			<div class="comment-content"><p>Dear Edy,<br />
    Would it be possible for you to include a SUV, hatchback, or sedan in the demo?  This would make it so that I, and others, could really understand the diversity and potential of your product.</p>
<p>Thanks!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-37791">
		<div class="comment-node" id="comment-37791">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/819ca6ba2b7489c2a260852fe92f4b15?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/819ca6ba2b7489c2a260852fe92f4b15?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Ali</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-08-28T12:49:32+02:00">August 28, 2017 at 12:49 PM</abbr>			</div>
			<div class="comment-content"><p>Dear Edy,</p>
<p>I have issue with Hand Brakes. When I apply HandBrake, wheels should freeze at the spot. But it is not happening. When I apply HandBrake, vehicle stops very slow.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-39796">
		<div class="comment-node" id="comment-39796">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/539e6d22e38016381dae399a815b1065?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/539e6d22e38016381dae399a815b1065?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Julian Johnson</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-12-08T17:44:01+01:00">December 8, 2017 at 5:44 PM</abbr>			</div>
			<div class="comment-content"><p>Edy This game is retarded and is only fun when your in school and have nothing to do</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-39797">
		<div class="comment-node" id="comment-39797">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2017-12-08T18:00:44+01:00">December 8, 2017 at 6:00 PM</abbr>			</div>
			<div class="comment-content"><p>It&#8217;s not a game. It&#8217;s a demo of a vehicle physics simulation package for Unity 3D. You may use this package in your own game. Here&#8217;s an actual example: <a href="http://store.steampowered.com/app/748800/Savage_Offroad/" rel="nofollow">http://store.steampowered.com/app/748800/Savage_Offroad/</a></p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-41234">
		<div class="comment-node" id="comment-41234">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/97540abb7772b317fdd725b1076d2e6d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/97540abb7772b317fdd725b1076d2e6d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Andrew</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-01-31T23:42:32+01:00">January 31, 2018 at 11:42 PM</abbr>			</div>
			<div class="comment-content"><p>Like the turbo blowoff sound XD.. engine sounds could be improved.. so basic.. But overall nice physics. I play Live for Speed, the the physics on that game are more smooth. This one is a bit stiffer if you know what i mean. Both are very realistic tho XD. Pls add working dashboard for sports coupe. Good job Edy!!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-45990">
		<div class="comment-node" id="comment-45990">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/8519aafefd7eba1731ee80f220e101da?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/8519aafefd7eba1731ee80f220e101da?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>john</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-05-15T17:00:25+02:00">May 15, 2018 at 5:00 PM</abbr>			</div>
			<div class="comment-content"><p>hey edy you should add a big rig with a detachable car hauler trailer</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-46320">
		<div class="comment-node" id="comment-46320">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/c56585916ea736e63a9fc78c01583570?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/c56585916ea736e63a9fc78c01583570?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Asiel</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-05-19T23:46:44+02:00">May 19, 2018 at 11:46 PM</abbr>			</div>
			<div class="comment-content"><p>you should also make it so the A.I has settings so you can change it so it can race you or so you can make the others A.I&#8217;s or to add more cars.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-52548">
		<div class="comment-node" id="comment-52548">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/831a2436a4f753e1ff84434a52692319?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/831a2436a4f753e1ff84434a52692319?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">arash</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-08-28T21:16:57+02:00">August 28, 2018 at 9:16 PM</abbr>			</div>
			<div class="comment-content"><p>Hi<br />
Is it possible to attach an accelerometer to an object (like amodel of a phone) inside the car and measure the acceleration of the object as the car collides and crashes ?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-53072">
		<div class="comment-node" id="comment-53072">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e0da0d7d2a4b8bd88de9c7afa212942d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e0da0d7d2a4b8bd88de9c7afa212942d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Gábor</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-09-05T15:07:24+02:00">September 5, 2018 at 3:07 PM</abbr>			</div>
			<div class="comment-content"><p>Is Physics Pro available yet?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-53672">
		<div class="comment-node" id="comment-53672">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/866301d5cbb126b01c19cc65dd9d2ed0?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/866301d5cbb126b01c19cc65dd9d2ed0?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Copper</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-09-13T15:32:37+02:00">September 13, 2018 at 3:32 PM</abbr>			</div>
			<div class="comment-content"><p>this game is awesome both it want load?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-55014">
		<div class="comment-node" id="comment-55014">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/f39401de0a7706467f204bd2dab5307b?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/f39401de0a7706467f204bd2dab5307b?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">austin</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-10-02T18:52:02+02:00">October 2, 2018 at 6:52 PM</abbr>			</div>
			<div class="comment-content"><p>trick #1- go fast then hit pause then hit enter about five times then unpause</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-56028">
		<div class="comment-node" id="comment-56028">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/d5fe739c540d496edbc19485533885e6?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/d5fe739c540d496edbc19485533885e6?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">dylan molina</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-08T16:27:20+01:00">November 8, 2018 at 4:27 PM</abbr>			</div>
			<div class="comment-content"><p>could you add a drag racing car with slicks into the demo</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-56056">
		<div class="comment-node" id="comment-56056">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>jj</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-13T16:23:36+01:00">November 13, 2018 at 4:23 PM</abbr>			</div>
			<div class="comment-content"><p>is there a way to turn the audio off ???</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-56074">
		<div class="comment-node" id="comment-56074">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-16T00:28:03+01:00">November 16, 2018 at 12:28 AM</abbr>			</div>
			<div class="comment-content"><p>Yes, you may switch the audio off clicking the &#8220;speaker&#8221; icon in the browser tab.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-56110">
		<div class="comment-node" id="comment-56110">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/5317a6be395f478a68efe757f225b881?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/5317a6be395f478a68efe757f225b881?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">BIG CHEIF</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-28T14:20:34+01:00">November 28, 2018 at 2:20 PM</abbr>			</div>
			<div class="comment-content"><p>Can you add a pro mod mutsang to the game</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-56125">
		<div class="comment-node" id="comment-56125">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>jj</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-30T15:58:28+01:00">November 30, 2018 at 3:58 PM</abbr>			</div>
			<div class="comment-content"><p>will there be any more maps added to demo version and any more cars</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-56126">
		<div class="comment-node" id="comment-56126">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>jj</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-30T15:59:31+01:00">November 30, 2018 at 3:59 PM</abbr>			</div>
			<div class="comment-content"><p>will the full version of the game be free or not???</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-56127">
		<div class="comment-node" id="comment-56127">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/6454705817db0379739ed1174f88e715?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>jj</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-11-30T16:04:43+01:00">November 30, 2018 at 4:04 PM</abbr>			</div>
			<div class="comment-content"><p>@edy thanks i am allways listening to music while playing and the noise gets in the way so thanks</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-56173">
		<div class="comment-node" id="comment-56173">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/93bbf1f6c740bc987a677b0507b2dcf1?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/93bbf1f6c740bc987a677b0507b2dcf1?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Joel</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2018-12-12T04:16:52+01:00">December 12, 2018 at 4:16 AM</abbr>			</div>
			<div class="comment-content"><p>Is the ABS/TC/AWD working? I can&#8217;t see the buttons for it anymore</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-56207">
		<div class="comment-node" id="comment-56207">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/64a23319b41f7c9eadc3280a780eec83?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/64a23319b41f7c9eadc3280a780eec83?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">joe</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-01-18T23:44:17+01:00">January 18, 2019 at 11:44 PM</abbr>			</div>
			<div class="comment-content"><p>Hey Edy, I realized that in the blue car, even when I am not pressing the brake, it still slips out when I turn. Do you know why this is happening? Also, it glitched out and put a line of skid marks that went straight away in the direction that I was facing at the time. They went straight into the sky, and didn&#8217;t have a collider.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-56317">
		<div class="comment-node" id="comment-56317">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/f0ed225d4a59790bec0d51a2bba987f5?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/f0ed225d4a59790bec0d51a2bba987f5?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Oggyguy72</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-01-27T21:18:26+01:00">January 27, 2019 at 9:18 PM</abbr>			</div>
			<div class="comment-content"><p>Noice.</p>
<p>My fave is the gray car, and blue truck.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-60118">
		<div class="comment-node" id="comment-60118">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo avatar-default' height='32' width='32' />			<cite class="fn">jj</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-09-24T20:52:20+02:00">September 24, 2019 at 8:52 PM</abbr>			</div>
			<div class="comment-content"><p>no disrespect but i could buy a call of duty game with 60 dollars so why is the official game 60$ when the graphics are not the best it still has the same cars as the demo or at least that is what i see in the pictures of the game sooooo ya</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-60119">
		<div class="comment-node" id="comment-60119">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-09-24T22:47:25+02:00">September 24, 2019 at 10:47 PM</abbr>			</div>
			<div class="comment-content"><p>EVP is not a game, but a tool that enables developers to make car games in Unity 3D. As such, it&#8217;s pretty cheap actually!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-60121">
		<div class="comment-node" id="comment-60121">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/a9ae11846900909de58aefcaa5a7fe28?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/a9ae11846900909de58aefcaa5a7fe28?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">FrankieFrazer</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-09-25T06:31:15+02:00">September 25, 2019 at 6:31 AM</abbr>			</div>
			<div class="comment-content"><p>Hi, wanted to ask is it mobile friendly?<br />
Couldn&#8217;t find any details of this anywhere, and if yes can I get a demo apk file before I buy this?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-60204">
		<div class="comment-node" id="comment-60204">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/347c47a0ee5a4bd1db5930b2a9cd53c9?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/347c47a0ee5a4bd1db5930b2a9cd53c9?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>johntnaumann</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-10-10T19:15:03+02:00">October 10, 2019 at 7:15 PM</abbr>			</div>
			<div class="comment-content"><p>can you add mph</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-60378">
		<div class="comment-node" id="comment-60378">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/347c47a0ee5a4bd1db5930b2a9cd53c9?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/347c47a0ee5a4bd1db5930b2a9cd53c9?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>johntnaumann</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-11-13T20:04:36+01:00">November 13, 2019 at 8:04 PM</abbr>			</div>
			<div class="comment-content"><p>nevermind with what i last said</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-60484">
		<div class="comment-node" id="comment-60484">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/2fec9051380b7335c32b8dd99cae43d0?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/2fec9051380b7335c32b8dd99cae43d0?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Abdul Rehman Asif</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-12-03T03:38:52+01:00">December 3, 2019 at 3:38 AM</abbr>			</div>
			<div class="comment-content"><p>Hey Edy!<br />
                Thanks for this wonderful tutorial. i have two question first is<br />
                (1) I have the EVP5 and i&#8217;m looking for a setting of Vehicle Controller that u have shown in this Video. I need the same setting. Kindly let me              know in the comment session.<br />
                (2) I just Buy the Exotic Cars from unity store and i just watched your tutorial for making a racing car but it&#8217;s not working on my car.<br />
                      The problem that i&#8217;m facing is &#8220;The Car have the first two front tyres seperately but have the only one gameobject for back tyres so duplicate and figure out from this thing but the car is trying very hard but not moving&#8221; please help me with this sorry for the bad english</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-60485">
		<div class="comment-node" id="comment-60485">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/2fec9051380b7335c32b8dd99cae43d0?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/2fec9051380b7335c32b8dd99cae43d0?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Abdul Rehman Asif</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-12-03T03:39:32+01:00">December 3, 2019 at 3:39 AM</abbr>			</div>
			<div class="comment-content"><p>Edy&#8217;s Vehicle Physics Steering Assist preview (2016) in this video</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-60487">
		<div class="comment-node" id="comment-60487">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/2fec9051380b7335c32b8dd99cae43d0?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/2fec9051380b7335c32b8dd99cae43d0?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Abdul Rehman Asif</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2019-12-03T03:43:14+01:00">December 3, 2019 at 3:43 AM</abbr>			</div>
			<div class="comment-content"><p>and one more question I want to Switch it for my Mobile is there anyother way that i can switch it like RCC(Realistic Car controller).<br />
or if we can use RCC Stuff or something like that!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-60802">
		<div class="comment-node" id="comment-60802">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/8f5d109e1112f83ba8bb30c5a4495d4a?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/8f5d109e1112f83ba8bb30c5a4495d4a?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>jacob</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2020-02-25T16:19:16+01:00">February 25, 2020 at 4:19 PM</abbr>			</div>
			<div class="comment-content"><p>can you pls add stuff to the demo im really poor and i love to play this may you pls add traps more cars more ramps and mods pls</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-60977">
		<div class="comment-node" id="comment-60977">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/c909d8479e2d17ba08bdefa0a1f3156e?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/c909d8479e2d17ba08bdefa0a1f3156e?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">wyatt</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2020-04-15T23:16:51+02:00">April 15, 2020 at 11:16 PM</abbr>			</div>
			<div class="comment-content"><p>can you make this multi player</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-61434">
		<div class="comment-node" id="comment-61434">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/39dac3f736eb3be67ad9eb8c309abed4?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/39dac3f736eb3be67ad9eb8c309abed4?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://dreek16designer.com' rel='external nofollow ugc' class='url'>Dreek16designer</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2020-07-02T21:26:13+02:00">July 2, 2020 at 9:26 PM</abbr>			</div>
			<div class="comment-content"><p>Wait the dust casts shadows! there are wierd cube shadows flying around :\</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-62153">
		<div class="comment-node" id="comment-62153">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">legoman8185</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2020-10-25T00:37:03+02:00">October 25, 2020 at 12:37 AM</abbr>			</div>
			<div class="comment-content"><p>Can you make it possible so that each car can be customized in the demo? please that would be cool. Like changing the suspension, tire size, and stuff like that. thanks.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-62340">
		<div class="comment-node" id="comment-62340">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/cf22888e61c5c7213d20ed81788e2beb?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/cf22888e61c5c7213d20ed81788e2beb?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">robert</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2020-11-17T18:41:36+01:00">November 17, 2020 at 6:41 PM</abbr>			</div>
			<div class="comment-content"><p>i love this game so much that i am now creating scenes with this game</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-63292">
		<div class="comment-node" id="comment-63292">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/3aba49e8f8c02fa638da89c702dbef6e?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/3aba49e8f8c02fa638da89c702dbef6e?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>nathan</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-02-23T15:05:59+01:00">February 23, 2021 at 3:05 PM</abbr>			</div>
			<div class="comment-content"><p>he edy, i was wondering if you could ad a motorcycle or a dirtbike and a semi with a trailer please</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-63428">
		<div class="comment-node" id="comment-63428">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/ba9ae86b88c88c662b1bc2fae05694c4?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/ba9ae86b88c88c662b1bc2fae05694c4?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Doge_lord</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-03-09T19:51:29+01:00">March 9, 2021 at 7:51 PM</abbr>			</div>
			<div class="comment-content"><p>Did you make these pickup models because i see these models in more games</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-63443">
		<div class="comment-node" id="comment-63443">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e59c6545fca4cb94372caf30f30c4b5c?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e59c6545fca4cb94372caf30f30c4b5c?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>camodogaming</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-03-10T18:11:21+01:00">March 10, 2021 at 6:11 PM</abbr>			</div>
			<div class="comment-content"><p>hey Edy, can you make the pro version available on chrome OS, or is that just because of unity. also, can you put the pro version on here. i would love to play it and maybe even share it with me friends.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-63841">
		<div class="comment-node" id="comment-63841">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/811e178d9c3cbfcf5fb0b3125abd8ee2?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/811e178d9c3cbfcf5fb0b3125abd8ee2?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Greg McGregor</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-04-19T16:04:28+02:00">April 19, 2021 at 4:04 PM</abbr>			</div>
			<div class="comment-content"><p>Hey Edy Nice Physics</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-63911">
		<div class="comment-node" id="comment-63911">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/056fa5757895ca4a2ee2a750cde8dc5a?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/056fa5757895ca4a2ee2a750cde8dc5a?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">julian traut</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-04-26T22:20:05+02:00">April 26, 2021 at 10:20 PM</abbr>			</div>
			<div class="comment-content"><p>epic game</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-64016">
		<div class="comment-node" id="comment-64016">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/18b14a6052d2d6dbd46d93cff54d2936?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/18b14a6052d2d6dbd46d93cff54d2936?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Brandon</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-05-10T22:36:11+02:00">May 10, 2021 at 10:36 PM</abbr>			</div>
			<div class="comment-content"><p>Hey Edy, is it possible to add a motorcycle in here? And if possible can you make this demo multiplayer?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-64080">
		<div class="comment-node" id="comment-64080">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-05-17T18:52:55+02:00">May 17, 2021 at 6:52 PM</abbr>			</div>
			<div class="comment-content"><p>@Brandon you could use a motorcycle 3D model on a 3-4 wheel vehicle, then animate the model procedurally.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-64082">
		<div class="comment-node" id="comment-64082">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/110ba0a3269d4956a9a6e082a258ab10?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/110ba0a3269d4956a9a6e082a258ab10?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Zech</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-05-17T19:03:13+02:00">May 17, 2021 at 7:03 PM</abbr>			</div>
			<div class="comment-content"><p>So I Made a legit record prob of 102.1 damage mesh!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-64099">
		<div class="comment-node" id="comment-64099">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/3fd50818c323e1e4a27039ee03814d22?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/3fd50818c323e1e4a27039ee03814d22?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Austin Dickerson</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-05-19T18:17:31+02:00">May 19, 2021 at 6:17 PM</abbr>			</div>
			<div class="comment-content"><p>How do you turn abs and other stuff on?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor odd alt thread-odd thread-alt depth-1" id="li-comment-64165">
		<div class="comment-node" id="comment-64165">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-05-24T11:51:22+02:00">May 24, 2021 at 11:51 AM</abbr>			</div>
			<div class="comment-content"><p>@Austin Driving aids are already enabled and calibrated in these vehicles. They can be modified further in the vehicle controller component.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-64413">
		<div class="comment-node" id="comment-64413">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">legoman8185</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-06-11T17:49:48+02:00">June 11, 2021 at 5:49 PM</abbr>			</div>
			<div class="comment-content"><p>Can you make it possible so that each car can be customized in the demo? please that would be cool. Like changing the suspension, tire size, and engine power, etc. thanks.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-64415">
		<div class="comment-node" id="comment-64415">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">legoman8185</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-06-11T17:52:32+02:00">June 11, 2021 at 5:52 PM</abbr>			</div>
			<div class="comment-content"><p>And if it&#8217;s not too hard can you do a prop spawner system where we can put stuff in the map and use it to make stunts, better crash scenes, or just a better offroad course.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-64416">
		<div class="comment-node" id="comment-64416">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/596f17480ff291736b4561704c19db34?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">legoman8185</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-06-11T19:36:31+02:00">June 11, 2021 at 7:36 PM</abbr>			</div>
			<div class="comment-content"><p>I got a damage mesh of 107.74! That&#8217;s a new record! Try and beat that.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-64520">
		<div class="comment-node" id="comment-64520">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/14b50ea9cf1f5681495d678f31ebc8e3?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/14b50ea9cf1f5681495d678f31ebc8e3?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">clay</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-06-19T03:15:13+02:00">June 19, 2021 at 3:15 AM</abbr>			</div>
			<div class="comment-content"><p>just got a damage mesh of 131.13 NEW RECORD!!!!!!!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment byuser comment-author-admin bypostauthor even thread-even depth-1" id="li-comment-64526">
		<div class="comment-node" id="comment-64526">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/e3fd24a9906721f86812a17a3928a11d?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Edy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-06-19T10:38:07+02:00">June 19, 2021 at 10:38 AM</abbr>			</div>
			<div class="comment-content"><p>Please post pics and/or videos somewhere!! Or send them to <a href="mailto:edy@vehiclephysics.com">edy@vehiclephysics.com</a> 😀</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-64961">
		<div class="comment-node" id="comment-64961">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/346f746bfb1375bb998e7f20c8bc9b8f?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/346f746bfb1375bb998e7f20c8bc9b8f?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Kyle_Busch</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-07-20T18:42:47+02:00">July 20, 2021 at 6:42 PM</abbr>			</div>
			<div class="comment-content"><p>am i allowed to use vehicles to damage other vehicles to get the record. also if you could add the pro version on here i think that would be great. i only have a chrome book and cant open it on the website to save my life. also i think multiplayer would make this 100000 times better. and if you could and a little oval race track and make a car like a nascar or just a race car in general. if you do at least the race track and the car i would be happy, but if you want to you could also and the rest.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-64962">
		<div class="comment-node" id="comment-64962">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/346f746bfb1375bb998e7f20c8bc9b8f?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/346f746bfb1375bb998e7f20c8bc9b8f?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Kyle_Busch</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-07-20T19:01:09+02:00">July 20, 2021 at 7:01 PM</abbr>			</div>
			<div class="comment-content"><p>also i just got 200.00 flat. i have a video to prove it</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-65804">
		<div class="comment-node" id="comment-65804">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/0449f6dfa4c185702240949551fd6a0a?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/0449f6dfa4c185702240949551fd6a0a?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Matthew W</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-09-23T21:22:35+02:00">September 23, 2021 at 9:22 PM</abbr>			</div>
			<div class="comment-content"><p>Could you please add a humvee, and maybe a larger offroad course?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-65837">
		<div class="comment-node" id="comment-65837">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/d4961ceebd57b91d3afce400b4d8a557?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/d4961ceebd57b91d3afce400b4d8a557?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">moses</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-09-25T20:29:17+02:00">September 25, 2021 at 8:29 PM</abbr>			</div>
			<div class="comment-content"><p>it takes a long time but love it</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-65988">
		<div class="comment-node" id="comment-65988">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Byron A</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-10-08T06:26:37+02:00">October 8, 2021 at 6:26 AM</abbr>			</div>
			<div class="comment-content"><p>things that you might want to add.</p>
<p>semi-trucks</p>
<p>a bigger offroading course</p>
<p>a jeep</p>
<p>bigger map</p>
<p>a bigger highway</p>
<p>a tesla</p>
<p>a sports car</p>
<p>litter better damage model</p>
<p>little better suspension</p>
<p>tow truck</p>
<p>MORE AI!!!</p>
<p>still nice job</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-65990">
		<div class="comment-node" id="comment-65990">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Byron A</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-10-08T06:32:48+02:00">October 8, 2021 at 6:32 AM</abbr>			</div>
			<div class="comment-content"><p>Pt.2</p>
<p>traffic lights </p>
<p>easter eggs </p>
<p>day and night</p>
<p>Thank you Edy for reading this</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-66020">
		<div class="comment-node" id="comment-66020">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Byron A</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-10-11T03:50:54+02:00">October 11, 2021 at 3:50 AM</abbr>			</div>
			<div class="comment-content"><p>I found some glitches you can do</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-66065">
		<div class="comment-node" id="comment-66065">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/5844651e10444cbe16370791db5bc905?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Byron A</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-10-13T01:50:58+02:00">October 13, 2021 at 1:50 AM</abbr>			</div>
			<div class="comment-content"><p>I got a damaged mesh of 320 and I&#8217;m really proud of myself it took me 2 hours just to crash into buildings and get the 320 to get more damage you have to scrape the wall of the highway to get more then ever</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-66579">
		<div class="comment-node" id="comment-66579">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/f91ceff144035b825d9edd79543f0e6c?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/f91ceff144035b825d9edd79543f0e6c?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">josh</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-09T21:53:44+01:00">November 9, 2021 at 9:53 PM</abbr>			</div>
			<div class="comment-content"><p>could use an engine ignition physics</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-66841">
		<div class="comment-node" id="comment-66841">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/dac830edc004a9e710777cb16e0cd03f?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/dac830edc004a9e710777cb16e0cd03f?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Pioneer Astro</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-22T16:32:43+01:00">November 22, 2021 at 4:32 PM</abbr>			</div>
			<div class="comment-content"><p>Could You make the Car from the horror movie &#8220;The Car&#8221; 1977? That would make the game fun to play! And add the horn sound effect on there, too!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-66843">
		<div class="comment-node" id="comment-66843">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/dac830edc004a9e710777cb16e0cd03f?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/dac830edc004a9e710777cb16e0cd03f?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Pioneer Astro</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-22T16:38:36+01:00">November 22, 2021 at 4:38 PM</abbr>			</div>
			<div class="comment-content"><p>And also add Police AI so whenever you do something that&#8217;s illegal, they will start to chase you everywhere. And YES! I mean everywhere!</p>
<p>Thank you for reading this note.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-66864">
		<div class="comment-node" id="comment-66864">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/d7d18ca9a88c0e9b481eee2bb84b8e55?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/d7d18ca9a88c0e9b481eee2bb84b8e55?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>cody ingle</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-23T16:03:09+01:00">November 23, 2021 at 4:03 PM</abbr>			</div>
			<div class="comment-content"><p>i used to play this demo but now it just wont load idk why but its really fun can you please help me i miss playing this</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-66946">
		<div class="comment-node" id="comment-66946">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/f3a5ba3dde4c4937ece566291a3ffe31?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/f3a5ba3dde4c4937ece566291a3ffe31?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">car luver</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-28T01:41:43+01:00">November 28, 2021 at 1:41 AM</abbr>			</div>
			<div class="comment-content"><p>It takes a little while, just be patient</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67005">
		<div class="comment-node" id="comment-67005">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/3047285eb021cd998c56bcc741fda360?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/3047285eb021cd998c56bcc741fda360?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">vw man</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-29T20:57:18+01:00">November 29, 2021 at 8:57 PM</abbr>			</div>
			<div class="comment-content"><p>could you add a vw bug</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-67030">
		<div class="comment-node" id="comment-67030">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/3047285eb021cd998c56bcc741fda360?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/3047285eb021cd998c56bcc741fda360?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">vw man</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-11-30T20:53:35+01:00">November 30, 2021 at 8:53 PM</abbr>			</div>
			<div class="comment-content"><p>could you add the general lee?</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67056">
		<div class="comment-node" id="comment-67056">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/d7d18ca9a88c0e9b481eee2bb84b8e55?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/d7d18ca9a88c0e9b481eee2bb84b8e55?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>cody ingle</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-02T19:46:24+01:00">December 2, 2021 at 7:46 PM</abbr>			</div>
			<div class="comment-content"><p>ive waited and waited but it still wont load the first time i use this website on this device it worked but every time i come back it wont load no mater how long i wait i wish it would load 🙁</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-67075">
		<div class="comment-node" id="comment-67075">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/3047285eb021cd998c56bcc741fda360?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/3047285eb021cd998c56bcc741fda360?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">vw man</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-03T20:53:37+01:00">December 3, 2021 at 8:53 PM</abbr>			</div>
			<div class="comment-content"><p>dear edy<br />
could you add the general lee and a vw bug and a vw bus<br />
           -vw man</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67122">
		<div class="comment-node" id="comment-67122">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/38d0130543daa601fb36819e3eab450b?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/38d0130543daa601fb36819e3eab450b?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Zachary</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-06T19:14:17+01:00">December 6, 2021 at 7:14 PM</abbr>			</div>
			<div class="comment-content"><p>hey this is cool!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-67149">
		<div class="comment-node" id="comment-67149">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/5ee6d3ba784f1b4fe6dd1a7081d24b40?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/5ee6d3ba784f1b4fe6dd1a7081d24b40?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Thomas Gill Stone of Laurens SC</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-08T19:34:55+01:00">December 8, 2021 at 7:34 PM</abbr>			</div>
			<div class="comment-content"><p>Plz add low graphics option</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67152">
		<div class="comment-node" id="comment-67152">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/f3a5ba3dde4c4937ece566291a3ffe31?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/f3a5ba3dde4c4937ece566291a3ffe31?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">car luver</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-08T20:17:31+01:00">December 8, 2021 at 8:17 PM</abbr>			</div>
			<div class="comment-content"><p>bruh now its broken 🙁</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-67166">
		<div class="comment-node" id="comment-67166">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/d74cb332c58d7542bd06a7e51d8222ce?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/d74cb332c58d7542bd06a7e51d8222ce?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>cody ingle</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-09T19:45:55+01:00">December 9, 2021 at 7:45 PM</abbr>			</div>
			<div class="comment-content"><p>its not working any more 🙁</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67198">
		<div class="comment-node" id="comment-67198">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/2e7857d7bd460f3e884a890fafafb367?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/2e7857d7bd460f3e884a890fafafb367?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">car man jesse</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-11T15:07:38+01:00">December 11, 2021 at 3:07 PM</abbr>			</div>
			<div class="comment-content"><p>i want you to put in headlights brake lights and reverse lights to if you are reading this eddy thank you</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-67225">
		<div class="comment-node" id="comment-67225">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/8a35ba99475ed38dcb3a27b41728acc7?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/8a35ba99475ed38dcb3a27b41728acc7?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Guy</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-14T07:21:41+01:00">December 14, 2021 at 7:21 AM</abbr>			</div>
			<div class="comment-content"><p>Nice little demo, the drifting of the cars is fairly accurate.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67237">
		<div class="comment-node" id="comment-67237">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/a6156bdb5c048ad30c0658abd8788ba7?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/a6156bdb5c048ad30c0658abd8788ba7?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Darth_Grevious</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-14T16:29:26+01:00">December 14, 2021 at 4:29 PM</abbr>			</div>
			<div class="comment-content"><p>This game is 10/10, I love it!</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment odd alt thread-odd thread-alt depth-1" id="li-comment-67239">
		<div class="comment-node" id="comment-67239">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/a6156bdb5c048ad30c0658abd8788ba7?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/a6156bdb5c048ad30c0658abd8788ba7?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn"><a href='https://www.edy.es/dev/vehicle-physics/demo/' rel='external nofollow ugc' class='url'>Darth_Grevious</a></cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-14T16:32:15+01:00">December 14, 2021 at 4:32 PM</abbr>			</div>
			<div class="comment-content"><p>But Maybe (if you can) could you make more cars and maybe another map, like a stunt map, with ramps or loops, or maybe corkscrews.</p>
</div>
		</div>
</li><!-- #comment-## -->
	<li class="comment even thread-even depth-1" id="li-comment-67245">
		<div class="comment-node" id="comment-67245">
			<div class="comment-controls">
						</div>
			<div class="comment-author vcard">
			<img alt='' src='https://secure.gravatar.com/avatar/fe87a4b14dacd2c12db23f89900933d2?s=32&#038;d=blank&#038;r=g' srcset='https://secure.gravatar.com/avatar/fe87a4b14dacd2c12db23f89900933d2?s=64&#038;d=blank&#038;r=g 2x' class='avatar avatar-32 photo' height='32' width='32' />			<cite class="fn">Danil Gralike</cite>
			</div>
						<div class="comment-meta commentmetadata">
				Posted <abbr class="comment-datetime" title="2021-12-14T22:53:43+01:00">December 14, 2021 at 10:53 PM</abbr>			</div>
			<div class="comment-content"><p>PLEASE ADD MORE VEHICLES LIKE MABEY ELECTRIC CARS SOON</p>
</div>
		</div>
</li><!-- #comment-## -->
		</ol>
		
	<div class="comments-navigation clearfix">
			</div>
	
		


		<div id="respond" class="comment-respond">
		<h3 id="reply-title" class="comment-reply-title">Leave a Reply <small><a rel="nofollow" id="cancel-comment-reply-link" href="/dev/vehicle-physics/demo/#respond" style="display:none;">Cancel reply</a></small></h3><form action="https://www.edy.es/dev/wp-comments-post.php" method="post" id="commentform" class="comment-form"><p class="comment-notes"><span id="email-notes">Your email address will not be published.</span> Required fields are marked <span class="required">*</span></p><p class="comment-form-comment"><label for="comment">Comment</label><textarea id="comment" name="comment" cols="45" rows="8" aria-required="true" class="required"></textarea></p><p class="comment-form-author"><label for="author">Name</label> <span class="required">*</span><input id="author" class="required" name="author" type="text" value="Danil Gralike" size="30" aria-required="true" /></p>
<p class="comment-form-email"><label for="email">Email</label> <span class="required">*</span><input id="email" class="required email" name="email" type="text" value="26gralikeda@afftonschools.net" size="30" aria-required="true" /></p>
<p class="comment-form-url"><label for="url">Website</label><input id="url" class="url" name="url" type="text" value="" size="30" /></p>
<p class="comment-form-cookies-consent"><input id="wp-comment-cookies-consent" name="wp-comment-cookies-consent" type="checkbox" value="yes" checked="checked" /> <label for="wp-comment-cookies-consent">Save my name, email, and website in this browser for the next time I comment.</label></p>
<p class="comment-subscription-form"><input type="checkbox" name="subscribe_blog" id="subscribe_blog" value="subscribe" style="width: auto; -moz-appearance: checkbox; -webkit-appearance: checkbox;" checked="checked" /> <label class="subscribe-label" id="subscribe-blog-label" for="subscribe_blog">Notify me of new posts by email.</label></p><p class="form-submit"><input name="submit" type="submit" id="submit" class="submit" value="Post Comment" /> <input type='hidden' name='comment_post_ID' value='1406' id='comment_post_ID' />
<input type='hidden' name='comment_parent' id='comment_parent' value='0' />
</p><p style="display: none;"><input type="hidden" id="akismet_comment_nonce" name="akismet_comment_nonce" value="048a35bc0e" /></p><style type="text/css">
		﻿#CheckBot {
    padding:0;
    margin:0;
}
#CheckBot #text {

}
#CheckBot #first {
    width:40px;
    height:40px;
}
#CheckBot #second {
    width:40px;
    height:40px;
}
#CheckBot #third {
    width:40px;
    height:40px;
}
#CheckBot .border_n {
    border:1px dashed #444;
}
#CheckBot .border_y {
    border:1px solid #444;
}
#CheckBot #copyright {
    font-size:11px;
    width:140px;
    padding:0;
    margin:0;
}</style>

<script>
		﻿function reselect(select_id) {
    document.getElementById('tqsxfcqgas').value = '0';
    switch(select_id) {
        case 1:
            document.getElementById('smpmjumfen').className = 'border_y';
            document.getElementById('kphfgqylsi').className = 'border_n';
            document.getElementById('qimldqfuin').className = 'border_n';
            document.getElementById('tqsxfcqgas').value = '1';
        break;
        case 2:
            document.getElementById('smpmjumfen').className = 'border_n';
            document.getElementById('kphfgqylsi').className = 'border_y';
            document.getElementById('qimldqfuin').className = 'border_n';
            document.getElementById('tqsxfcqgas').value = '2';
        break;
        case 3:
            document.getElementById('smpmjumfen').className = 'border_n';
            document.getElementById('kphfgqylsi').className = 'border_n';
            document.getElementById('qimldqfuin').className = 'border_y';
            document.getElementById('tqsxfcqgas').value = '3';
        break;
        case 0:
            document.getElementById('smpmjumfen').className = 'border_n';
            document.getElementById('kphfgqylsi').className = 'border_n';
            document.getElementById('qimldqfuin').className = 'border_n';
            document.getElementById('tqsxfcqgas').value = '0';
        break;
        default:
            document.getElementById('tqsxfcqgas').value = '0';
        break;
    }
    return false;
}</script>

<div id="CheckBot">
	<p id="text">﻿Confirm that you are not a bot - select a man with raised hand:</p>
	<img src="https://www.edy.es/dev/wp-content/plugins/checkbot/images/Default/2.jpg" class="border_n" onclick="javascript: reselect(1)" border="0"
		 id="smpmjumfen"/>
	<img src="https://www.edy.es/dev/wp-content/plugins/checkbot/images/Default/1.jpg" class="border_n" onClick="javascript: reselect(2)" border="0"
		 id="kphfgqylsi"/>
	<img src="https://www.edy.es/dev/wp-content/plugins/checkbot/images/Default/3.jpg" class="border_n" onClick="javascript: reselect(3)" border="0"
		 id="qimldqfuin"/>
	</div>

<input type="hidden" value="alubqxdlrz" name="alubqxdlrz"/>
<input type="hidden" value="" name="tqsxfcqgas" id="tqsxfcqgas"/>

<script>var commentField = document.getElementById("url");var submitp = commentField.parentNode;var answerDiv = document.getElementById("CheckBot");submitp.appendChild(answerDiv, commentField);</script><input type="hidden" id="ak_js" name="ak_js" value="238"/><textarea name="ak_hp_textarea" cols="45" rows="8" maxlength="100" style="display: none !important;"></textarea></form>	</div><!-- #respond -->
		
	    

</div><!-- #content -->
</div><!-- #container -->

	</div><!-- #main -->
	
	    
    <div id="footer">
		<div class="footer-sidebar-container clearfix">
							<ul id="footer-sidebar-1" class="footer-sidebar clearfix xoxo">
										<li></li>
									</ul>
					</div>
		
		<div class="footer-message">
		<p class="floatright"><a class="arras" href="http://www.arrastheme.com/"><strong>About Arras WordPress Theme</strong></a></p>
		<p style="text-align: center;">Copyright Angel Garcia &quot;Edy&quot;. All Rights Reserved &nbsp; | &nbsp; <a href="/dev/about/">About</a> &nbsp; | &nbsp; <a href="/dev/site-map/">Site map</a></p>		
		</div><!-- .footer-message -->
    </div>
</div><!-- #wrapper -->
	<div style="display:none">
	<div class="grofile-hash-map-bc39a4c633ce3dbe457b6b10c8c42a5b">
	</div>
	<div class="grofile-hash-map-e3fd24a9906721f86812a17a3928a11d">
	</div>
	<div class="grofile-hash-map-0e1fbfcad8aad6a494f4923d61b4f217">
	</div>
	<div class="grofile-hash-map-24f135a7287fe8a5c3e27cd4abb2dcc3">
	</div>
	<div class="grofile-hash-map-8f02052eab01f342dd172f788bf804a5">
	</div>
	<div class="grofile-hash-map-c96e63cd14061e02ec4ea90945e2c498">
	</div>
	<div class="grofile-hash-map-3b6386dbf00b08b35d9e48a115ce835d">
	</div>
	<div class="grofile-hash-map-7e3dd0533cf971f539a2a6a7e8e44a33">
	</div>
	<div class="grofile-hash-map-7a39514824726c990e8243cfff672c96">
	</div>
	<div class="grofile-hash-map-a1b278d7ecdb20f48dc5ba117c175864">
	</div>
	<div class="grofile-hash-map-379f6bf9539bf861781843ba06d359c4">
	</div>
	<div class="grofile-hash-map-0d40452e443461489bf4dda60da38823">
	</div>
	<div class="grofile-hash-map-056bc4b790823af74ee52a98eb29744e">
	</div>
	<div class="grofile-hash-map-01b5822eef74e194be96f720395d7fda">
	</div>
	<div class="grofile-hash-map-819ca6ba2b7489c2a260852fe92f4b15">
	</div>
	<div class="grofile-hash-map-539e6d22e38016381dae399a815b1065">
	</div>
	<div class="grofile-hash-map-97540abb7772b317fdd725b1076d2e6d">
	</div>
	<div class="grofile-hash-map-8519aafefd7eba1731ee80f220e101da">
	</div>
	<div class="grofile-hash-map-c56585916ea736e63a9fc78c01583570">
	</div>
	<div class="grofile-hash-map-831a2436a4f753e1ff84434a52692319">
	</div>
	<div class="grofile-hash-map-e0da0d7d2a4b8bd88de9c7afa212942d">
	</div>
	<div class="grofile-hash-map-866301d5cbb126b01c19cc65dd9d2ed0">
	</div>
	<div class="grofile-hash-map-f39401de0a7706467f204bd2dab5307b">
	</div>
	<div class="grofile-hash-map-d5fe739c540d496edbc19485533885e6">
	</div>
	<div class="grofile-hash-map-6454705817db0379739ed1174f88e715">
	</div>
	<div class="grofile-hash-map-5317a6be395f478a68efe757f225b881">
	</div>
	<div class="grofile-hash-map-93bbf1f6c740bc987a677b0507b2dcf1">
	</div>
	<div class="grofile-hash-map-64a23319b41f7c9eadc3280a780eec83">
	</div>
	<div class="grofile-hash-map-f0ed225d4a59790bec0d51a2bba987f5">
	</div>
	<div class="grofile-hash-map-a9ae11846900909de58aefcaa5a7fe28">
	</div>
	<div class="grofile-hash-map-347c47a0ee5a4bd1db5930b2a9cd53c9">
	</div>
	<div class="grofile-hash-map-2fec9051380b7335c32b8dd99cae43d0">
	</div>
	<div class="grofile-hash-map-d540b2d66da3d18ea5f1dece95f2497d">
	</div>
	<div class="grofile-hash-map-c909d8479e2d17ba08bdefa0a1f3156e">
	</div>
	<div class="grofile-hash-map-39dac3f736eb3be67ad9eb8c309abed4">
	</div>
	<div class="grofile-hash-map-596f17480ff291736b4561704c19db34">
	</div>
	<div class="grofile-hash-map-cf22888e61c5c7213d20ed81788e2beb">
	</div>
	<div class="grofile-hash-map-3aba49e8f8c02fa638da89c702dbef6e">
	</div>
	<div class="grofile-hash-map-676010a1671f0e5c0946de9d51a26b34">
	</div>
	<div class="grofile-hash-map-e59c6545fca4cb94372caf30f30c4b5c">
	</div>
	<div class="grofile-hash-map-811e178d9c3cbfcf5fb0b3125abd8ee2">
	</div>
	<div class="grofile-hash-map-056fa5757895ca4a2ee2a750cde8dc5a">
	</div>
	<div class="grofile-hash-map-18b14a6052d2d6dbd46d93cff54d2936">
	</div>
	<div class="grofile-hash-map-110ba0a3269d4956a9a6e082a258ab10">
	</div>
	<div class="grofile-hash-map-3fd50818c323e1e4a27039ee03814d22">
	</div>
	<div class="grofile-hash-map-14b50ea9cf1f5681495d678f31ebc8e3">
	</div>
	<div class="grofile-hash-map-346f746bfb1375bb998e7f20c8bc9b8f">
	</div>
	<div class="grofile-hash-map-0449f6dfa4c185702240949551fd6a0a">
	</div>
	<div class="grofile-hash-map-b6f7750418880539e6f93a90d5b992cd">
	</div>
	<div class="grofile-hash-map-5844651e10444cbe16370791db5bc905">
	</div>
	<div class="grofile-hash-map-f91ceff144035b825d9edd79543f0e6c">
	</div>
	<div class="grofile-hash-map-dac830edc004a9e710777cb16e0cd03f">
	</div>
	<div class="grofile-hash-map-d7d18ca9a88c0e9b481eee2bb84b8e55">
	</div>
	<div class="grofile-hash-map-f3a5ba3dde4c4937ece566291a3ffe31">
	</div>
	<div class="grofile-hash-map-3047285eb021cd998c56bcc741fda360">
	</div>
	<div class="grofile-hash-map-019d43525a24df510537bdb24452316b">
	</div>
	<div class="grofile-hash-map-dc7dade4cb1849d198b45f0be19fb97b">
	</div>
	<div class="grofile-hash-map-d74cb332c58d7542bd06a7e51d8222ce">
	</div>
	<div class="grofile-hash-map-2e7857d7bd460f3e884a890fafafb367">
	</div>
	<div class="grofile-hash-map-8a35ba99475ed38dcb3a27b41728acc7">
	</div>
	<div class="grofile-hash-map-a6156bdb5c048ad30c0658abd8788ba7">
	</div>
	<div class="grofile-hash-map-fe87a4b14dacd2c12db23f89900933d2">
	</div>
	</div>
<script type="text/javascript">
jQuery(document).ready(function($) {

	
});
</script>

	<script type="text/javascript">
		window.WPCOM_sharing_counts = {"https:\/\/www.edy.es\/dev\/vehicle-physics\/demo\/":1406};
	</script>
				<div id="fb-root"></div>
			<script>(function(d, s, id) { var js, fjs = d.getElementsByTagName(s)[0]; if (d.getElementById(id)) return; js = d.createElement(s); js.id = id; js.src = 'https://connect.facebook.net/en_US/sdk.js#xfbml=1&appId=249643311490&version=v2.3'; fjs.parentNode.insertBefore(js, fjs); }(document, 'script', 'facebook-jssdk'));</script>
			<script>
			jQuery( document.body ).on( 'post-load', function() {
				if ( 'undefined' !== typeof FB ) {
					FB.XFBML.parse();
				}
			} );
			</script>
						<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+'://platform.twitter.com/widgets.js';fjs.parentNode.insertBefore(js,fjs);}}(document, 'script', 'twitter-wjs');</script>
			<script type="text/javascript">
			jQuery( document ).ready( function() {
				jQuery.getScript( 'https://platform.linkedin.com/in.js?async=true', function success() {
					IN.init();
				});
			});
			jQuery( document.body ).on( 'post-load', function() {
				if ( typeof IN != 'undefined' )
					IN.parse();
			});
			</script><link rel='stylesheet' id='shortcode-menu-style-css'  href='https://www.edy.es/dev/wp-content/plugins/shortcode-menu/shortcode-menu.css?ver=5.3.10' type='text/css' media='all' />
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/jquery/ui/core.min.js?ver=1.11.4'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/jquery/ui/widget.min.js?ver=1.11.4'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/jquery/ui/tabs.min.js?ver=1.11.4'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/comment-reply.min.js?ver=5.3.10'></script>
<script type='text/javascript' src='https://secure.gravatar.com/js/gprofiles.js?ver=2021Decaa'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var WPGroHo = {"my_hash":"fe87a4b14dacd2c12db23f89900933d2"};
/* ]]> */
</script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/plugins/jetpack/modules/wpgroho.js?ver=5.3.10'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-includes/js/wp-embed.min.js?ver=5.3.10'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/plugins/shortcode-menu/js/enhance.menu.js?ver=5.3.10'></script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/plugins/shortcode-menu/js/tinynav.min.js?ver=5.3.10'></script>
<script async="async" type='text/javascript' src='https://www.edy.es/dev/wp-content/plugins/akismet/_inc/form.js?ver=4.1.8'></script>
<script type='text/javascript'>
/* <![CDATA[ */
var sharing_js_options = {"lang":"en","counts":"1","is_stats_active":"1"};
/* ]]> */
</script>
<script type='text/javascript' src='https://www.edy.es/dev/wp-content/plugins/jetpack/_inc/build/sharedaddy/sharing.min.js?ver=8.1.2'></script>
<script type='text/javascript'>
var windowOpen;
			jQuery( document.body ).on( 'click', 'a.share-facebook', function() {
				// If there's another sharing window open, close it.
				if ( 'undefined' !== typeof windowOpen ) {
					windowOpen.close();
				}
				windowOpen = window.open( jQuery( this ).attr( 'href' ), 'wpcomfacebook', 'menubar=1,resizable=1,width=600,height=400' );
				return false;
			});
</script>
<script type='text/javascript' src='https://stats.wp.com/e-202150.js' async='async' defer='defer'></script>
<script type='text/javascript'>
	_stq = window._stq || [];
	_stq.push([ 'view', {v:'ext',j:'1:8.1.2',blog:'27007427',post:'1406',tz:'1',srv:'www.edy.es'} ]);
	_stq.push([ 'clickTrackerInit', '27007427', '1406' ]);
</script>
</body>
</html>
   
