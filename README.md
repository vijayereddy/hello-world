<html lang="en">
  	<head>
		<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1, maximum-scale=1">
    <title>MRCET VJ APP</title>
		<meta property="og:image" content="http://www.byndr.com/static/img/favicon/ogimg.png" />
    <meta property="og:title" content="Byndr Mobile Learning app - The easy LMS for smartphones" />
    <meta property="og:description" content="Byndr offers customizable, agile, user-friendly LMS for schools, mobile LMS, College mobile app, e learning apps, mobile learning platform in India." />
	<meta property="og:keywords" content="Mobile LMS, College mobile app, Mobile Learning India, online learning platforms in india, Mobile Learning management system, Learning management system" />
    <meta property="og:site_name" content="Byndr" />
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	<link href="https://www.byndr.com" rel="canonical"/>
    <link rel="apple-touch-icon" sizes="57x57" href="/static/img/favicon/apple-touch-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/static/img/favicon/apple-touch-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/static/img/favicon/apple-touch-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/static/img/favicon/apple-touch-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/static/img/favicon/apple-touch-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/static/img/favicon/apple-touch-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/static/img/favicon/apple-touch-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/static/img/favicon/apple-touch-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/static/img/favicon/apple-touch-icon-180x180.png">
    <link rel="icon" type="image/png" href="/static/img/favicon/favicon-32x32.png" sizes="32x32">
    <link rel="icon" type="image/png" href="/static/img/favicon/android-chrome-192x192.png" sizes="192x192">
    <link rel="icon" type="image/png" href="/static/img/favicon/favicon-96x96.png" sizes="96x96">
    <link rel="icon" type="image/png" href="/static/img/favicon/favicon-16x16.png" sizes="16x16">
    
    <script src="https://use.typekit.net/hee1rjy.js"></script>
    <script>try{Typekit.load({ async: true });}catch(e){}</script>
    <link rel="manifest" href="/static/img/favicon/manifest.json">

    <meta name="msapplication-TileColor" content="#b91d47">
    <meta name="msapplication-TileImage" content="/static/img/favicon/mstile-144x144.png">
    <meta name="theme-color" content="#ffffff">
		<link rel="stylesheet" href="/static/css/bootstrap.min.css">
		<link rel="stylesheet" href="/static/css/main.css?v=76">
		
		<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
		<script src="/static/js/jquery.validate.min.js"></script>
		<script src="/static/js/additional-methods.min.js"></script>
		<script src="/static/js/froogaloop.min.js"></script>
		<script src="/static/js/main.js?v58"></script>
		<script>
      (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
      (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
      m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
      })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
      ga('create', 'UA-59718524-2', 'auto');
      ga('send', 'pageview');
    </script>
	</head>
	<body class="nm nm_home fixed-hero">
	    <header>
            <div class="wrap on-dark">
                <a href="/" class="fl">
                    <img class="logo" src="/static/img/byndr_white.png"/>
                </a>
                <div class="burger">
                    <hr><hr><hr>
                </div>
                <div class="links">
                        <a href="https://app.byndr.com/" class="btn mobile-more">sign in </a>
                        <a class="mobile-more page-contact" href="/contact/">contact </a>
                        <a class="mobile-more page-demo" href="/demo/">request a demo </a>
                        <a class="mobile-more page-why" href="/about/">about</a>
                        <a class="mobile-more page-product" href="/product/">product</a>
                </div>
            </div>
            <div class="wrap on-light">
                <a href="/" class="fl">
                    <img class="logo" src="/static/img/byndr_logo.png"/>
                </a>
                <div class="burger">
                    <hr><hr><hr>
                </div>
                <div class="links">
                        <a href="https://app.byndr.com/" class="btn mobile-more">sign in </a>
                        <a class="mobile-more page-contact" href="/contact/">contact </a>
                        <a class="mobile-more page-demo" href="/demo/">request a demo </a>
                        <a class="mobile-more page-why" href="/about/">about</a>
                        <a class="mobile-more page-product" href="/product/">product</a>
                </div>
            </div>
        </header>
        <div class="content">
            <link rel="stylesheet" href="/static/css/guest_home.css?v2">

<script>
var isHomePage = true;
var img=new Image();
if($(window).width() <= 700){
    img.src = "/static/img/home/onphone@mobile.jpg";    
}else{
    img.src = "/static/img/home/onphone.jpg";    
    
}
img.onload = function(){
    sizeHero();
    setTimeout(function(){
        $window.scroll();
        $('header .wrap').hide();
    },0);
    
    setTimeout(function(){
        sizeHero();
        $('body').addClass('hero-ready');
        $('header .wrap').show();
        $window.scroll();
        animateHeroTxt();
    },30);
}

$(document).ready(function(){
    sizeHero();
    
    var rollingOffset = 0;
    var lastScrollLeft = 0;
    var paddingLI = 60;
    var $lastLI = $(".insts>li:last");
    $lastLI.parent().prepend($lastLI);
    var $scroll = $('.scrollhide');
    $scroll.get(0).scrollLeft = $lastLI.width() + paddingLI;
    if(!is_touch_device()){
        $scroll.scroll(function(){
            var $firstLI = $(".insts>li:first");
            var firstWidthAndPad = $firstLI.width();    
            rollingOffsetFirst = this.scrollLeft - lastScrollLeft - $firstLI.width();
            var appendMore = ($('.insts').width() - $scroll.get(0).scrollLeft) <= $scroll.width() ? true : false;
        
            if(appendMore){
                $firstLI.parent().append($firstLI);
                this.scrollLeft = this.scrollLeft - $firstLI.width() - paddingLI;
                lastScrollLeft = this.scrollLeft;
                rollingOffset = 0;
            }else if(rollingOffsetFirst <= (-firstWidthAndPad)){            
                var $lastLI = $(".insts>li:last");
                $lastLI.parent().prepend($lastLI);
                this.scrollLeft = this.scrollLeft + $lastLI.width() + paddingLI;
                rollingOffset = 0;
            }
        });
    }
    
    
    var slInt, lastScrollLft;
    $('#byndr-partners').on( "inView",function(){
        clearInterval(slInt);
        setTimeout(function(){
            slInt = setInterval(function(){
                $scroll.get(0).scrollLeft += 1;
                lastScrollLft = $scroll.get(0).scrollLeft;
            },15); 
        },100)
    });
    
    var stopscroll = is_touch_device() ? "touchmove" : "mousewheel";
    $scroll.on(stopscroll,function(e){
        if($scroll.get(0).scrollLeft !== lastScrollLft){
            clearInterval(slInt);      
        }
    });
});

function animateHeroTxt(){
    var H1_txt = 'Learning MadeMobile.'; 
    var pos = 0;
    var step = 0;
    var typedString = '';
    var heroTxtIn;
    var h1 = $('h1');
    h1.html('&nbsp;')
    heroTxtIn = setInterval(function(){
        step++;
        if(step <= 3 || (step > 6 && step <=9)){
            h1.html('&nbsp;')       
        }else if(step <= 6 || step <= 12){
            h1.html('|')   
        }else{
            typedString += H1_txt.substring(pos,pos+1);
            if(typedString == 'Learning'){
                
                h1.html(typedString)   
            }else if(pos == H1_txt.length - 2){
                 h1.html(typedString + '.<hr/></span>');
                clearInterval(heroTxtIn)
            }else if(pos == 12){
                typedString += '&nbsp;<span>';
                h1.html(typedString)   
            }else{
                h1.html(typedString+'|')   
            }
            pos++;
        }
    },65); 
}
</script>

<div class="video-overlay">
    <div id="video-done" class="stop-playing-intro">done</div>
    <div class="video-outer-wrap"><div class="video-wrap">
    <iframe id="phone-vimeo"  data-src="https://player.vimeo.com/video/128447381?autoplay=1&api=1&player_id=phone-vimeo"
width="500" height="281" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
</div></div>
</div>
<div class="section fixed-section size-hero" id="hero">
    <div class="darkener"></div>
    <div class="contain">
        <div class="left">
            <div class="h1-wrap">
                <h1>
                    Learning<br/> Made <span>Mobile</span>.
                </h1>
            </div>
            <div class="below-h1">
                <p>
                    <b>Mobile First. Lightweight. Multi-Platform.</b>
                    Byndr reaches students, teachers and colleges across the globe
                    with one, easy to use platform.
                    The LMS for everyone.
                </p>
                
                <a href="/demo/" class="btn" title="Download Byndr for Android">
                    Request a Demo
                </a>
                <a class="btn btn-outline play-intro" title="Download Byndr for Android">
                    Watch How it Works
                </a>
            </div>
        </div>
    </div>
    <a class="scroll-down spr pointer"></a>
</div>

<script>

 var img=new Image();
if($(window).width() <= 700){
    img.src = "/static/img/home/onphone@mobile.jpg";    
}else{
    img.src = "/static/img/home/onphone.jpg";    
    
}
img.onload = function(){
    $('body').addClass('hero-ready')
}
</script>
    
    <div class="section white-strip after-hero" id="sec-builtmobile">
        <div class="inner white-strip col-md-tbl">     
            <div class="col-md-4 col-md-tc col">
                <div id="hero-phone" class="mark-in-view">
                <div id="phone-container">
                     <img src="/static/img/nm/phone_cutout.jpg" id="phone-cutout"/>
                 <div id="phone-content-wrap">
                      <img src="/static/img/nm/phone_content.png" id="phone-content"/>
                 </div>
                </div>
                 
                </div>
            </div>
            <div class="col-md-8 col-md-tc middle col">
                <div>
                    <h3>
                      Built for the Mobile Market.
                    </h3>
                    <p class="p_contain">
                      Byndr connects students, teachers and colleges on a simple, fast and mobile-first platform. 
                     We designed Byndr from the ground-up with a focus on ease-of-use,
                     ensuring every student has access to educational resources outside of the classroom.
                    </p>
                    <a target="_blank" href="https://play.google.com/store/apps/details?id=org.byndr.byndr&amp;hl=en" class="gplay" title="Download Byndr for Android">
                        <img src="/static/img/gplay2.png" style="height:57px;">
                    </a>
                    
                    <a class="btn btn-outline" href="/product/" title="Download Byndr for Android">
                        View Product Details
                    </a>
                
                
                </div>
            </div>
        </div>
        <div class="clearfix"></div>
    </div>
        
    <script>$('h1').html('|');sizeHero();</script>
    <div class="section plx-img mark-in-view">
        <div class="inner">
            <div class="img" style="background:url(/static/img/home/gprec1.jpg)center / cover;"></div>
            <div class="img-caption">
                G. Pulla Reddy Engineering College, Kurnool, India - Using Byndr
            </div>
        </div>
        <div class="clearfix"></div>
    </div>
    
    <div class="section white-strip" id="sec-bringtogether">
        <div class="inner white-strip col-md-tbl top">
            <div class="col-md-7 col-md-tc middle col">
                <div>
                    <h3>
                      Bring Students, Teachers<br class="mobile-hide"/> &amp; Administrators Together.
                    </h3>
                    <p class="p_contain">
                        Byndr is designed to meet the learning management needs of colleges.
                        With Byndr, teachers can administer their subjects with ease 
                        from any device. Students stay engaged and connected to educational 
                        resources outside of the classroom.
    
                    </p>
                    <a href="/demo/" class="btn" title="Download Byndr for Android">
                        Request a Demo
                    </a>
                </div>
            </div>
            <div class="col-md-5 col-md-tc col">
                <ul>
                    <li><span class="icon-check"></span> No Servers to Maintain, No Setup Costs</li>
                    <li><span class="icon-check"></span> Intuitive for Teachers and Students</li>
                    <li><span class="icon-check"></span> Easy Reporting for Administrators </li>
                    <li><span class="icon-check"></span> Access on Mobile and Web</li>
                </ul>
            </div>
        </div>
        <div class="clearfix"></div>




    <div id="sec-quotes">
        <div id="byndr-partners" class="mark-in-view">
            <div class="scrollhide">
                <ul class="insts">
                    <li><div  class="inst inst-anurag"></div></li>
                    <li><div  class="inst inst-rajeev"></div></li>
                    <li><div  class="inst inst-bomma"></div></li>
                    <li><div  class="inst inst-cbit"></div></li>
                    <li><div  class="inst inst-snist"></div></li>
                    <li><div  class="inst inst-cvr"></div></li>
                    <li><div  class="inst inst-vardhaman"></div></li>
                    <li><div  class="inst inst-gprec"></div></li>
                    <li><div  class="inst inst-vvit"></div></li>
                    <li><div  class="inst inst-stanley"></div></li>
                    <li><div  class="inst inst-vaagdevi"></div></li>
                    <li><div  class="inst inst-nrcm"></div></li>
                    <li><div  class="inst inst-cmr"></div></li>
                    <li><div  class="inst inst-vidya-jyoti"></div></li>
                    <li><div  class="inst inst-cjits"></div></li>
                    <li><div  class="inst inst-vishwa"></div></li>
                    <li><div  class="inst inst-mrcet"></div></li>
                    <li><div  class="inst inst-sucop"></div></li>
                    <li><div  class="inst inst-pmec"></div></li>
                    <li><div  class="inst inst-backstage"></div></li>
                </ul>
                <div class="clearfix"></div>
            </div>
        </div>
        <div class="inner white-strip quotes-box">   
            <div class="">
                <div>
                <div class="quote-box b1">
                    <div class="quote-open spr"></div>
                    <div class="quote-pic bobbi mobile-hide"></div>
                    <p>
                        Our college has got a number of learning resources, and those
                        resources are now made available to students through Byndr.
                        We are very thankful to Byndr - An innovative learning management
                        system can be developed and can be used in all parts of the world.
                    </p>
                    <p class="quote-author">
                        <span class="quote-pic bobbi mobile-show"></span>
                         <b>Dr. P. Narasimha Reddy</b><br/>
                        Executive Director, Sreenidhi Institute
                        of Science and Technology
                    </p>
                    <div class="clearfix"></div>
                    <div class="quote-closed spr"></div>
                </div>
                <div class="quote-box b2">
                    <div class="quote-open spr"></div>
                    <div class="quote-pic rath mobile-hide"></div>
                    <p>
                        My compliments to team Byndr for designing a simple and sweet LMS. It is versatile, simple and
                        inclusive. All students and faculty have been very positive about Byndr and its role
                        as a learning catalyst.
                    </p>
                    <p class="quote-author">
                        <span class="quote-pic rath mobile-show"></span>
                        <b>Dr. Sabyasachi Rath</b><br/>
                        Dean, Vishwa Vishwani Institute of Systems and Management
                    </p>
                    <div class="clearfix"></div>
                    <div class="quote-closed spr"></div>
                </div>
            </div>
        </div>  
        </div>
    </div>
    <div class="clearfix"></div>
</div>

<div class="section" id="phila">
  <div class="contain">
        <img src="/static/img/home/phila.png" class="pennben"/>
        <p>
            Byndr is backed by Ben Franklin Technology Partners, The University
            of Pennsylvania Graduate School of Education and The Education Design 
            Studio to bring together the latest in technology and education design practices.
        </p>
 </div>
</div>

<div class="section center" id="interested">
    <div class="col-md-6">
        <div class="wrap">
            <h4>
            Interested in seeing what Byndr can do for your College?
            </h4>
            <p class="al">
                Start using Byndr with a Free Trial.  Easy and intuitive, Byndr offers a maintenance-free platform and unlimited support. Request a demo to see what Byndr can do for your college. 
            </p>
            <a class="btn" href="/demo/">
                Request a Demo
            </a>
            <p>
            or want more Information? <span class="mobile-break"></span><a href="/contact/">Contact Us</a>
            </p>
            <br/>
        </div>
    </div>
    <div class="col-md-6">
        <div class="wrap">
            <h4>
            Is your college using Byndr?
            </h4>
            <p class="al">
                Download Byndr for Android and log in using the credentials provided by your college.
            <b class="al">
                Don't have an Android?
            </b>
            <a href="https://app.byndr.com/">Click here to log in to Byndr on your browser.</a>
            </p>
            <br/>
            <a target="_blank" href="https://play.google.com/store/apps/details?id=org.byndr.byndr&hl=en" class="gplay" title="Download Byndr for Android">
                <img src="/static/img/gplay2.png" style="height:57px;"/>
            </a>
        </div>
    </div>
</div>

<script>
$(document).ready(function(){
    var phonePlaying = false;
    $('body').click(function(){
        stopPlayingIntro();
    })

    $('.scroll-down').click(function(){
        $('body,html').animate({scrollTop: ($('#sec-builtmobile').offset().top-$("header .wrap").height()) +"px"}, 350);
    });

    $('.play-intro').click(function(event){
        if(phonePlaying)return;
        phonePlaying = true;
        $('body').addClass('intro-playing video-playing');
        $('#phone-vimeo').show().css('opacity',0).attr('src', $('#phone-vimeo').attr('data-src'));
        setTimeout(function(){
          $('#phone-vimeo').animate({opacity:1}, 300)

        },400);
        event.stopPropagation();
    });
    $('.stop-playing-intro').click(function(){
        stopPlayingIntro();
    });
    function stopPlayingIntro(){
        phonePlaying = false;
        $('body').removeClass('intro-playing video-playing');
        $('#phone-vimeo').hide().attr('src','');
    }

    var iframe = $('#phone-vimeo')[0];
    var player = $f(iframe);

    
    player.addEvent('ready', function() {
        
        player.addEvent('finish', onFinish);
        player.api('play');
    });

    function onFinish(id) {
        stopPlayingIntro();
    }
});

</script>

        </div>
        <div class="clearfix"></div>
	  <footer>
        <div class="col-md-8">
            <ul class="footer">
                <li>
                    <label>
                        <a href="/product/">Product</a>
                    </label>
                </li>
                <li>
                    <label>
                        <a href="/about/">About Us</a>
                    </label>
                </li>
                <li>
                    <label>
                        <a href="/demo/">Request a Demo</a>
                    </label>
                </li>
                <li>
                    <label>
                        <a href="/contact/">Contact</a>
                    </label>
                </li>
                <li>
                    <label>
                        <a href="https://app.byndr.com">Sign In</a>
                    </label>
                </li>
                <li>
                    <ul class="social">
                        <li class="gp"><a target="_blank" href="https://play.google.com/store/apps/details?id=org.byndr.byndr&amp;hl=en">Google Play</a></li>
                        <li class="tw"><a target="_blank" href="https://twitter.com/Byndr_Mobile">Twitter</a></li>
                        <li class="fb"><a target="_blank" href="https://facebook.com/ByndrApp">Facebook</a></li>
                    </ul>  
        	    </li>
        	  </ul><div class="clearfix"></div>
        </div>
        <div class="col-md-4">
     	    &copy; 2017 Byndr, Inc.
	        &middot; <a href="/policies/privacy">Privacy Policy</a>
	        &middot; <a href="/policies/terms">Terms of Use</a>
        </div>
        <div class="clearfix"></div>
	  </footer>
	</body>
</html>
