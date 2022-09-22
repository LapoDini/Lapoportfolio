
<html>
<head>
  <title>Lapo Dini</title>
   <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
   <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
    <!--Colour palette from W3 School colour generator-->
    <meta name="viewport" content="width:device-width, initial-scale=1">
    <style>
        .w3-theme-l5 {color:#000 !important; background-color:#fbfaf8 !important}
        .w3-theme-l4 {color:#000 !important; background-color:#f2eee8 !important}
        .w3-theme-l3 {color:#000 !important; background-color:#e5ddd1 !important}
        .w3-theme-l2 {color:#000 !important; background-color:#d8ccba !important}
        .w3-theme-l1 {color:#000 !important; background-color:#ccbba4 !important}
        .w3-theme-d1 {color:#fff !important; background-color:#b39a78 !important}
        .w3-theme-d2 {color:#fff !important; background-color:#a78a62 !important}
        .w3-theme-d3 {color:#fff !important; background-color:#957954 !important}
        .w3-theme-d4 {color:#fff !important; background-color:#7f6848 !important}
        .w3-theme-d5 {color:#fff !important; background-color:#6a573c !important}

        .w3-theme-light {color:#000 !important; background-color:#fbfaf8 !important}
        .w3-theme-dark {color:#fff !important; background-color:#6a573c !important}
        .w3-theme-action {color:#fff !important; background-color:#6a573c !important}

        .w3-theme {color:#000 !important; background-color:#c0ab8e !important}
        .w3-text-theme {color:#c0ab8e !important}
        .w3-border-theme {border-color:#c0ab8e !important}

        .w3-hover-theme:hover {color:#000 !important; background-color:#c0ab8e !important}
        .w3-hover-text-theme:hover {color:#c0ab8e !important}
        .w3-hover-border-theme:hover {border-color:#c0ab8e !important}
    </style>

</head>

<body class="w3-theme-l3 w3-content" style="max-width:inherit;">
    <nav class="w3-sidebar w3-collapse w3-theme-light w3-animate-left" style="z-index: 3; width: 300px; display: none;" id="mySidebar">
      <div class="w3-container w3-center w3-padding-top-24">
        <img src="Images/lapoprofilo.jpg" class="w3-circle w3-hover-border" style="max-width: 60%">
        <a href="#" onclick="w3_close()" class="w3-hide-large w3-right w3-padding" title="Close menu">
          <i class="fa fa-remove"></i>
        </a>
      </div>

      <div class="w3-container w3-padding-16 w3-center">
        <h2>Lapo Dini</h2>
        <h3>PORTFOLIO</h3>
      </div>
      
      <div class="w3-bar-block">
        <a href="#About" onclick="w3_close()" class="w3-bar-item w3-button w3-theme-light w3-padding scroll-active">
          <i class="fa fa-user fa-fw w3-margin-right"></i>
          ABOUT
        </a>
        
        <a href="#Projects" onclick="w3_close()" class="w3-bar-item w3-button w3-theme-light w3-padding">
          <i class="fa fa-calculator fa-fw w3-margin-right"></i>
          PROJECTS
        </a>
        
        <a href="#Contact" onclick="w3_close()" class="w3-bar-item w3-button w3-theme-light w3-padding">
          <i class="fa fa-phone fa-fw w3-margin-right"></i>
          CONTACT
        </a>
      </div>
    </nav>

    <div class="w3-overlay w3-hide-large w3-animate-opacity" onclick="w3_close()" style="cursor: pointer; display: none;" title="close side menu" id="myOverlay"></div>

    <div class="w3-main" style="margin-left: 300px">
      <header id="about">
        <img src="Images/lapoprofilo.jpg" class="w3-circle w3-hide-large w3-right w3-padding" style="max-width: 30%">
        <span class="w3-button w3-hide-large w3-xxlarge w3-hover-text-theme" onclick="w3_open()">
          <i class="fa fa-bars"></i>
        </span>
        <div class="w3-container" id="About">
          <h1>Lapo Dini</h1>
          <div class="w3-section w3-bottombar w3-padding-16"></div>
        </div>
      </header>
      
      
      <div class="w3-container w3-paddin-bottom:32px">
        <h2>About Me</h2>
        <p>As a child with ADHD and dyslexia, I found numbers to be my language of choice, an alternative means of describing the world in my head, as well as the world out there.</p> 
        <p>Studying Mathematics at university was a natural choice, which gave me the opportunity to explore statistics, geometry, analysis, algebra, and physics first at an undergraduate level and then during my Master&#39s Degree. 
        <p>After graduation, for two years I shared my passion with secondary school students and worked as a teacher of Maths and Physics in public Italian schools. In the meantime, I continued studying and discovered the world of Data Science and Machine Learning: combining my love for numbers with my enthusiasm for technology seemed like an ideal path for me. 
        Since then, I&#39ve been working hard every day to acquire new skills in this field: Python programming, Matlab/Octave programming, data analysis and modelling with Conda environment tools (such as Pandas, NumPy, Scikit-Learn, Matplotlib and Jupyter Notebook), as well as creating models from scratch using Matlab/Octave.</p>
        My extensive knowledge of Mathematics made me an excellent problem solver, also thanks to my lateral thinking and creativity. I have always been a fast learner and an incredibly curious individual: my many and diverse interests were an invaluable experience to develop soft skills such as teamwork, leadership and ability to work under pressure. For example, practicing and teaching martial arts such as karate, iaido and kobudo gave me discipline, focus and team building skills.</p>
        
        <div class="w3-panel w3-leftbar w3-theme-l1">
          <p class="w3-large">''Don&#39t take every challenge as a problem, take every problem as a challenge.''</p>
        </div>

        <div class="w3-container">
          <div class="w3-row-padding">
            <div class="w3-third w3-card-4 w3-padding">
              <img src="Images/lapo-foto-1.jpg" style="max-width:100%">
            </div>
          </div>
        </div>
        <div class="w3-section w3-bottombar w3-padding-16"></div>
      </div>

      <div class="w3-container w3-paddin-bottom">
        <h2 id="Projects">Projects</h1>
        <div class="w3-row-padding w3-padding-top-24">
          <div class="w3-third w3-card-4 w3-padding">
            <a href="https://github.com/LapoDini/LapoDini.github.io/tree/main/dog-breed-classification" target="_blank" class="w3-hover-grayscale">
              <img src="Images/dog4.jpg" style="max-width: 100%;">
        
              <div class="w3-container w3-center">
                <p>Dog Breed Classification</p>
              </div>
            </a>
          </div>

          <div class="w3-third w3-card-4 w3-padding">
            <a href="https://github.com/LapoDini/LapoDini.github.io/blob/main/Titanic_Kaggle/titanic-competition-kaggle.ipynb" target="_blank" class="w3-hover-grayscale">
              <img src="Images/Titanic.png" style="max-width: 100%;">
           
              <div class="w3-container w3-center">
                <p>Titanic: Machine Learning from a disaster</p>
              </div>
            </a>
          </div>

          <div class="w3-third w3-card-4 w3-padding">
            <a href="https://github.com/LapoDini/LapoDini.github.io/tree/main/bulldozer-price-prediction" target="_blank" class="w3-hover-grayscale">
              <img src="Images/bulldozer1.jpg" style="max-width: 100%;">

              <div class="w3-container w3-center">
                <p>Bulldozer prices prediction</p>
              </div>
            </a>
          </div>

        </div>
      </div>

      <div class="w3-container w3-padding-large">
        <h3 id="Contact">
          Contact Me
        </h3>
        <div class="w3-row-padding w3-center w3-padding-24"> 
          <a href="mailto:lapodini.ie@gmail.com">
            <div class="w3-third w3-theme-dark w3-hover-opacity">
            <i class="fa fa-envelope w3-xxlarge w3-text-theme-ligh w3-padding"></i>
            <p>lapodini.ie@gmail.com</p>
            </div>
          </a>

          <div class="w3-third w3-teal">
            <i class="fa fa-map-marker w3-xxlarge w3-padding"></i>
            <p>Dublin, IE</p>
          </div>

          <div class="w3-third w3-theme-dark">
            <i class="fa fa-phone w3-xxlarge w3-padding"></i>
            <p>+353 896109035</p>
          </div>
        </div>
      </div>
    </div>
    
    
    <script>
      function w3_open() {
        document.getElementById("mySidebar").style.display = "block";

        document.getElementById("myOverlay").style.display = "block";
      }
      
      function w3_close() {
        document.getElementById("mySidebar").style.display = "none";

        document.getElementById("myOverlay").style.display = "none";
      }
      </script> 

    
<style>a[href^="https://ttf.trmobc.com/"],[data-css-class="dfp-inarticle"],a[href^="https://reinstandpointdumbest.com/"],a[href^="https://msecure117.com/"],a[href^="https://streamate.com/landing/click/"],a[href^="https://www.healthrangerstore.com/"] > img,[data-ad-manager-id],a[href^="https://oackoubs.com/"],a[data-url^="http://paid.outbrain.com/network/redir?"],a[href^="https://go.xxxjmp.com"],[data-template-type="nativead"],a[href^="https://prf.hn/click/"][href*="/adref:"] > img,a[href^="https://www.bang.com/?aff="],a[href^="https://wittered-mainging.com/"],a[href^="https://static.fleshlight.com/images/banners/"],div[data-dfp-id],[href^="http://join.rodneymoore.com/"],a[href^="https://vo2.qrlsx.com/"],a[href^="https://ads.betfair.com/redirect.aspx?"],a[href^="https://www.sheetmusicplus.com/?aff_id="],div[id^="yandex_ad"],[href^="https://turtlebids.irauctions.com/"] img,a[href^="http://go.xtbaffiliates.com/"],div[data-alias="300x250 Ad 2"],[href^="http://clicks.totemcash.com/"],a[href^="https://go.ebrokerserve.com/"],a[href^="https://www.get-express-vpn.com/offer/"],a[href^="http://pityhostngco2.xyz/"],a[href^="https://avtub.click/assets/link.php"],[href^="http://globsads.com/"],a[href^="https://webroutetrk.com/"],[href^="https://affect3dnetwork.com/track/"],div[id^="ad-server-"],a[href^="https://playuhd.host/"],a[data-redirect^="https://paid.outbrain.com/network/redir?"],iframe[src^="http://ad.yieldmanager.com/"],[href^="https://detachedbates.com/"],a[href^="https://a.montangop.top/"],a[href^="https://aj1070.online/"],a[href^="https://go.xxxiijmp.com"],a[href^="https://dooloust.net/"],[href^="http://go.cm-trk2.com/"],a[href^="https://www.googleadservices.com/pagead/aclk?"],a[href^="https://track.bruceads.com/"],a[href^="https://landing.brazzersnetwork.com/"],display-ad-component,a[href^="https://natour.naughtyamerica.com/track/"],a[href^="http://tour.mrskin.com/"],a[href^="https://go.247traffic.com/"],div[class^="AdCard_"],amp-ad-custom,a[href^="//pubads.g.doubleclick.net/"],a[href^="https://www.iyalc.com/"],div[id^="bunyad-widget-ads-"],a[href^="https://clixtrac.com/"],div[data-test-id="AdDisplayWrapper"],div[id^="dfp-slot-"],a[href^="https://www.infowarsstore.com/"] > img,[href="https://masstortfinancing.com"] img,a[href^="https://a2.adform.net/"],a[href^="https://1free33style.com/"],[href^="https://kingered-banctours.com/"],div[id^="adrotate_widgets-"],a[href^="https://adjoincomprise.com/"],div.fadeInDown[id$="____equal"][class$="____equal"],div[id^="ad-inserter-"],div[jsdata*="CarouselPLA-"][data-id^="CarouselPLA-"],a[href^="https://gghf.mobi/"],a[href^="https://click.hoolig.app/"],div[data-alias="300x250 Ad 1"],a[href^="https://agacelebir.com/"],a[href^="https://tracking.trackcasino.co/"],[href^="https://join3.bannedsextapes.com"],a[href^="http://go.247traffic.com/"],a[href^="//syndication.dynsrvtbg.com/"],[href^="https://www.restoro.com/"],[data-advadstrackid],a[href^="https://trk.moviesflix4k.xyz/"],a[href^="http://pubads.g.doubleclick.net/"],a[href^="https://queersodadults.com/"],a[href^="https://gohere.pl/"],a[href^="https://albionsoftwares.com/"],a[href^="https://k2s.cc/pr/"],div[id^="ad-div-"],a[href^="https://get.surfshark.net/aff_c?"][href*="&aff_id="] > img,a[href^="https://t.hrtye.com/"],a[href^="https://www.goldenfrog.com/vyprvpn?offer_id="][href*="&aff_id="],[href^="http://www.pingperfect.com/aff.php"],div[data-content="Advertisement"],a[href^="http://affiliate.glbtracker.com/"],a[href^="https://chaturbate.com/in/?track="],[class^="amp-ad-"],a[href^="https://incisivetrk.cvtr.io/click?"],a[href^="https://aweptjmp.com/"],a[href^="https://cpartner.bdswiss.com/"],a[href^="https://www.brazzersnetwork.com/landing/"],a[href^="http://betahit.click/"],a[href^="http://bc.vc/?r="],a[href^="https://click.a-ads.com/"],a[href^="https://deliver.tf2www.com/"],div[class^="adsbutt_wrapper_"],a[href^="//voyeurhit.com/cs/"],aside[id^="advads_ad_widget-"],div[data-ad-wrapper],[data-desktop-ad-id],a[href^="https://www.privateinternetaccess.com/"] > img,a[href^="https://black77854.com/"],a[href^="https://ads.leovegas.com/redirect.aspx?"],a[href^="https://tour.mrskin.com/"],div[data-mediatype="advertising"],div[data-spotim-slot],div[class^="AdItem-"],a[href^="https://iqbroker.com/"][href*="?aff="],a[href^="http://adf.ly/?id="],a[href^="https://offers.refchamp.com/"],a[href^="https://www.chngtrack.com/"],[data-mobile-ad-id],a[href^="https://www.sugarinstant.com/?partner_id="],a[href^="https://clicks.pipaffiliates.com/"],[href^="https://www.targetingpartner.com/"],div[id^="ad_script_"],div[id^="zergnet-widget"],[data-ad-cls],[href^="https://freecourseweb.com/"] > .sitefriend,a[href^="https://bs.serving-sys.com"],a[href^="http://deloplen.com/"],a[href^="https://ad.kubiccomps.icu/"],[class^="s2nPlayer"],[href^="https://go.affiliatexe.com/"],div[data-subscript="Advertising"],article.ad,a[href^="https://uncensored.game/"],div[class^="ad_position_"],a[href^="https://go.tmrjmp.com"],a[href*="https://www.sweetdeals.com/"] img,a[href^="https://pcm.bannerator.com/"],a[data-redirect^="http://paid.outbrain.com/network/redir?"],a[href^="https://awentw.com/"],a[href^="https://t.mobtya.com/"],a[href^="//thaudray.com/"],aside[id^="adrotate_widgets-"],[data-d-ad-id],a[href^="http://www.mrskin.com/tour"],a[href^="//coarsewary.com/"],a[href^="http://googleads.g.doubleclick.net/pcs/click"],a[href^="https://landing1.brazzersnetwork.com"],[id^="div-gpt-ad"],a[href*=".zlinkm.com/"],[href^="https://trackfin.asia/"],div[id^="lazyad-"],a[href^="https://torrentsafeguard.com/?aid="],a[href^="https://track.interactivegf.com/"],a[href^="https://mediaserver.gvcaffiliates.com/renderBanner.do?"],a[href^="https://chaturbate.jjgirls.com/?track="],div[id^="div-ads-"],a[href^="https://googleads.g.doubleclick.net/pcs/click"],[href^="https://rapidgator.net/article/premium/ref/"],[href^="https://traffserve.com/"],div[class^="adpubs-"],a[href*="//lkstrck2.com/"],a[href^="https://ausoafab.net/"],a[href^="https://www.mrskin.com/account/"],a[href^="https://bngpt.com/"],a[href^="https://deliver.ptgncdn.com/"],[data-name="adaptiveConstructorAd"],a[href^="https://serve.awmdelivery.com/"],ad-desktop-sidebar,a[href^="https://track.afcpatrk.com/"],a[href^="https://track.ultravpn.com/"],div[id^="adngin-"],a[href^="https://watchmygirlfriend.tv/"],a[href^="https://traffdaq.com/"],[href^="https://mylead.global/stl/"] > img,[href^="https://zone.gotrackier.com/"],a[href^="https://www.highperformancegate.com/"],a[href^="https://www.camsoda.com/enter.php?id="],div[id*="MarketGid"],a[href^="https://tracking.avapartner.com/"],a[href^="http://allaptair.club/"],a[href^="http://intent.bingads.com/"],a[href^="https://moneynow.one/"],[href^="http://join.shemalesfromhell.com/"],[href^="https://optimizedelite.com/"] > img,a[href^="https://ptapjmp.com/"],[href^="https://track.fiverr.com/visit/"] > img,app-large-ad,a[href^="//agacelebir.com/"],a[href^="https://www.awin1.com/cread.php?awinaffid="],a[href^="https://bestcond1tions.com/"],a[href^="https://scurewall.co/"],a[href^="https://partners.fxoro.com/click.php?"],div[class^="index_adAfterContent_"],a[href^="https://ads.ad4game.com/"],a[href^="https://t.adating.link/"],[href^="https://istlnkcl.com/"],[href^="https://go.xlrdr.com"],[href="https://www.masstortfinancing.com/"] > img,a[href^="https://itubego.com/video-downloader/?affid="],a[href^="https://camfapr.com/landing/click/"],[href^="https://join.girlsoutwest.com/"],div[id^="ezoic-pub-ad-"],div[class^="kiwi-ad-wrapper"],a[href^="http://wct.link/"],a[href^="https://join.sexworld3d.com/track/"],a[href^="https://aaucwbe.com/"],div[data-adunit-path],a[onmousedown^="this.href='http://paid.outbrain.com/network/redir?"][target="_blank"],a[href^="https://www.passeura.com/"],a[href^="https://fertilitycommand.com/"],a[href^="https://go.cmtaffiliates.com/"],a[href^="https://go.zybrdr.com"],div[class^="pane-adsense-managed-"],a[href^="https://fast-redirecting.com/"],ADS-RIGHT,a[href^="//benoopto.com/"],div[id^="adfox_"],a[href^="https://www.mrskin.com/tour"],a[href^="https://clickadilla.com/"],a[href^="https://land.brazzersnetwork.com/landing/"],a[href^="http://www.adultempire.com/unlimited/promo?"][href*="&partner_id="],[href^="http://join.hardcoreshemalevideo.com/"],iframe[src^="https://tpc.googlesyndication.com/"],div[aria-label="Ads"],a[href^="https://prf.hn/click/"][href*="/camref:"] > img,a[href^="https://www.rabbits.webcam/?id="],a[href^="http://ads2.williamhill.com/redirect.aspx?"],a[data-url^="http://paid.outbrain.com/network/redir?"] + .author,[href^="https://mystore.com/"] > img,a[href^="https://go.markets.com/visit/?bta="],a[href^="https://landing.brazzersplus.com/"],a[onmousedown^="this.href='https://paid.outbrain.com/network/redir?"][target="_blank"],a[href^="https://iac.ampxdirect.com/"],a[href^="http://d2.zedo.com/"],[id^="chp_ads_block"],div[id^="taboola-stream-"],div[id^="ad-cid-"],div[data-test-id="AdBannerWrapper"],a[href^="http://https://www.get-express-vpn.com/offer/"],div[class^="BlockAdvert-"],a[href*=".trust.zone"],[href^="https://cpa.10kfreesilver.com/"],[data-ad-width],div[class^="StickyHeroAdWrapper-"],a[href^="https://www.bebi.com"],[href^="https://goldcometals.com/clk.trk"],div[id^="advads_"],div[id^="ads300_100-widget-"],a[href^="https://www.kingsoffetish.com/tour?partner_id="],[href^="https://shrugartisticelder.com"],div[id^="vuukle-ad-"],a[href^="https://meet-to-fuck.com/"],a[href^="http://static.fleshlight.com/images/banners/"],a[href^="https://bluedelivery.pro/"],[href^="https://clk.right-wing-health.com/"],[href^="https://www.avantlink.com/click.php"] img,[href^="https://www.herbanomic.com/"] > img,a[href^="https://earandmarketing.com/"],a[href^="https://join.virtualtaboo.com/track/"],a[href^="http://www.advcashpro.com/aff/"],[href^="https://cipledecline.buzz/"],a[href^="http://rs-stripe.wsj.com/stripe/redirect"],a[href^="https://lobimax.com/"],[href^="https://stvkr.com/"],a[href^="https://go.gldrdr.com/"],a[href^="https://go.admjmp.com/"],div[data-id-advertdfpconf],[href^="http://residenceseeingstanding.com/"],a[href^="https://go.xlviirdr.com"],a[href^="https://www.financeads.net/tc.php?"],a[href^="https://engine.phn.doublepimp.com/"],[href^="https://www.mypatriotsupply.com/"] > img,a[href^="http://traffic.tc-clicks.com/"],a[href^="https://bongacams10.com/track?"],a[href^="https://pb-track.com/"],a[href^="https://wantopticalfreelance.com/"],app-ad,a[href^="https://tragency-clesburg.icu/"],a[href^="https://go.strpjmp.com/"],a[href^="https://galaxyroms.net/?scr="],a[href^="http://partners.etoro.com/"],a[href^="https://m.do.co/c/"] > img,a[href^="https://www.purevpn.com/"][href*="&utm_source=aff-"],div[id*="ScriptRoot"],[href^="https://www.mystore.com/"] > img,div[class^="sp-adslot-"],a[href^="http://enter.anabolic.com/track/"],[href^="https://mypillow.com/"] > img,a[href^="https://trf.bannerator.com/"],a[href^="http://www.onclickmega.com/jump/next.php?"],a[href^="https://click.linksynergy.com/fs-bin/"],a[href^="https://meet-sex-here.com/"],a[href^="http://click.payserve.com/"],div[class^="Ad__adContainer"],[href^="http://misslinkvocation.com/"],a[href^="https://axdsz.pro/"],[href^="http://www.mypillow.com/"] > img,a[href^="https://go.xtbaffiliates.com/"],a[href^="http://cam4com.go2cloud.org/aff_c?"],a[href^="http://www.adultdvdempire.com/?partner_id="][href*="&utm_"],div[id^="dfp-ad-"],div[class^="ad_border_"],hl-adsense,[name^="google_ads_iframe"],div[class^="adunit_"],a[href^="https://twinrdsyn.com/"],a[href^="https://5hjdbfjfd5.monster/"],[href^="http://join.shemale.xxx/"],a[href^="https://ad.atdmt.com/"],a[href^="https://mediaserver.entainpartners.com/renderBanner.do?"],a[href^="http://adultgames.xxx/"],iframe[id^="google_ads_frame"],a[href^="https://track.effiliation.com/servlet/effi.click?"] > img,iframe[src^="http://www.adpeepshosted.com/"],a[href^="http://bodelen.com/"],[id^="ad-wrap-"],a[href^="https://ak.hetaruwg.com/"],a[href*=".engine.adglare.net/"],[href^="https://www.hostg.xyz/aff_c"] > img,[href^="http://join.ts-dominopresley.com/"],a[href^="https://creacdn.top-convert.com/"],a[href^="https://ad.zanox.com/ppc/"] > img,[href^="https://click2cvs.com/"],div[data-role="sidebarAd"],a[href^="https://topoffers.com/"][href*="/?pid="],a[href^="https://go.nordvpn.net/aff"] > img,a[href^="https://ads-for-free.com/click.php?"],a[href^="https://www.oneclickroot.com/?tap_a="] > img,a[href^="https://azpresearch.club/"],[data-m-ad-id],a[href^="https://someperceptionparade.com/"],a[href^="https://geniusdexchange.com/"],a[href^="https://adswick.com/"],div[id^="ad-gpt-"],a[href^="https://tm-offers.gamingadult.com/"],a[href^="https://go.alxbgo.com/"],[href^="https://ilovemyfreedoms.com/landing-"],a[href^="http://adserver.adreactor.com/"],div[data-adname],a[href^="https://aff-ads.stickywilds.com/"],[href^="https://totlnkcl.com/"],[href^="https://glersakr.com/"],a[href^="http://www.gfrevenge.com/landing/"],a[href^="https://adclick.g.doubleclick.net/"],div[id^="ad_bigbox_"],a[href^="https://intenseaffiliates.com/redirect/"],a[href^="//go.xlviiirdr.com"],a[href^="https://track.healthtrader.com/"],a[href^="https://tracking.comfortclick.eu/"],[data-revive-zoneid],a[href^="https://adserver.adreactor.com/"],div[data-ad-placeholder],[href^="https://shiftnetwork.infusionsoft.com/go/"] > img,a[href^="https://waisheph.com/"],[href^="http://homemoviestube.com/"],div[class^="adUnit_"],div[data-native-ad],div[class^="AdhesionAd_"],[href^="https://secure.bmtmicro.com/servlets/"],a[href^="https://www.clicktraceclick.com/"],a[href^="https://ads.cdn.live/"],a[href^="http://www.onwebcam.com/random?t_link="],a[href^="https://awecrptjmp.com/"],a[href^="https://join.dreamsexworld.com/"],a[href^="https://go.cmrdr.com/"],a[href^="https://s.zlink2.com/"],a[href^="https://as.sexad.net/"],a[href^="http://trk.mdrtrck.com/"],AMP-AD,a[href^="https://www.vfreecams.com/in/?track="],a[href^="https://www.sweetdeals.com"],div[class^="adbanner_"],a[href^="https://go.trackitalltheway.com/"],a[data-oburl^="https://paid.outbrain.com/network/redir?"],a[target="_blank"][onmousedown="this.href^='http://paid.outbrain.com/network/redir?"],a[href^="https://ismlks.com/"],[data-dynamic-ads],a[href^="https://mk-cdn.net/"],a[href^="https://myusenet.xyz/"],div[class^="s-dfp-"],[href^="http://mypillow.com/"] > img,a[href^="https://billing.purevpn.com/aff.php"] > img,a[href^="https://spygasm.com/track?"],a[href^="https://iactrivago.ampxdirect.com/"],div[data-mpu1],guj-ad,a[href^="https://syndication.dynsrvtbg.com/"],a[data-redirect^="this.href='http://paid.outbrain.com/network/redir?"],a[href*=".zlink9.com/"],a[href^="https://tc.tradetracker.net/"] > img,a[href^="https://a.bestcontentweb.top/"],zeus-ad,a[onmousedown^="this.href='https://paid.outbrain.com/network/redir?"][target="_blank"] + .ob_source,div[class^="index_displayAd_"],a[href^="https://syndication.exoclick.com/"],[href^="https://infinitytrk.com/"],a[href^="https://nutrientassumptionclaims.com/"],ark-top-ad,[href^="https://routewebtk.com/"],a[href^="https://americafirstpolls.com/"],div[id^="ad-position-"],a[href^="https://affcpatrk.com/"],[data-freestar-ad],a[href^="https://t.grtyi.com/"],div[id^="gpt_ad_"],[onclick^="location.href='http://www.reimageplus.com"],[data-role="tile-ads-module"],DFP-AD,a[href^="https://vlnk.me/"],div[class^="block-openx-"],a[href^="https://a-ads.com/"],[data-ad-module],[href^="https://antiagingbed.com/discount/"] > img,a[href^="https://www.jackery.com?aff="] > img,a[href^="https://cam4com.go2cloud.org/"],div[id^="rc-widget-"],a[href^="https://track.themadtrcker.com/"],div[id^="banner-ad-"],a[href^="https://t.hrtyj.com/"],[class^="div-gpt-ad"],a[href*=".flndmyiove.net/"],a[href^="https://reachtrgt.com/"],a[href^="https://adultfriendfinder.com/go/page/landing"],a[href^="https://lead1.pl/"],[href^="http://www.fleshlightgirls.com/"],a[href^="https://ovb.im/"],a[href^="https://look.utndln.com/"],a[href^="http://www.coiwqe.site/"],a[href^="https://chaturbate.com/in/?tour="],div[id^="div-gpt-"],a[href^="https://www.bet365.com/"][href*="affiliate="],bottomadblock,a[href^="https://explore.findanswersnow.net/"],a[href^="http://go.fpmarkets.com/"],a[href^="https://porngames.adult/?SID="],a[href^="https://www.adultempire.com/"][href*="?partner_id="],div[class^="ads-partner-"],a[href^="https://www.nutaku.net/signup/landing/"],a[href^="https://traffic.bannerator.com/"],a[href^="https://banners.livepartners.com/"],[id^="ad_sky"],a[href^="https://medleyads.com/"],a[href^="https://fakelay.com/"],a[href^="http://hotcandyland.com/partner/"],[href^="https://wct.link/"],a[data-oburl^="http://paid.outbrain.com/network/redir?"],a[href^="https://misspkl.com/"],a[href^="https://go.hpyrdr.com/"],[href^="https://mypatriotsupply.com/"] > img,[href^="https://affiliate.fastcomet.com/"] > img,a[href^="https://go.goaserv.com/"],a[href^="https://affiliate.rusvpn.com/click.php?"],a[href^="https://a.bestcontentfood.top/"],a[href^="https://financeads.net/tc.php?"],[href^="https://www.mypillow.com/"] > img,a[href^="https://trusted-click-host.com/"],a[href^="https://adnetwrk.com/"],a[onmousedown^="this.href='http://paid.outbrain.com/network/redir?"][target="_blank"] + .ob_source,a[href*="http://MyPillow.com"] > img,div[id^="ads250_250-widget-"],a[href^="https://fleshlight.sjv.io/"],a[href^="https://tracking.gitads.io/"],[href^="https://zstacklife.com/"] img,a[href^="https://cagothie.net/"],amp-embed[type="taboola"],AD-TRIPLE-BOX,[href^="https://www.brighteonstore.com/products/"] img,div[id^="adspot-"],a[href^="https://awptjmp.com/"],a[href^="https://fastestvpn.com/lifetime-special-deal?a_aid="],[href^="https://www.reimageplus.com/"],a[href^="https://go.etoro.com/"] > img,a[href^="https://cpmspace.com/"],a[href^="http://www.FriendlyDuck.com/"],AFS-AD,a[href^="https://a.bestcontentoperation.top/"],a[href^="https://my-movie.club/"],a[href^="https://maymooth-stopic.com/"],div[class^="ResponsiveAd-"],a[href^="https://frameworkdeserve.com/"],div[data-contentexchange-widget],a[href="//rufflycouncil.com/"],a[href^="http://affiliates.thrixxx.com/"],div[id^="js-dfp-"],a[href^="https://track.wg-aff.com"],a[href^="https://burpee.xyz/"],LEADERBOARD-AD,a[href^="https://cams.imagetwist.com/in/?track="],div[class^="BannerAd_"],[href^="https://join.playboyplus.com/track/"],a[href^="https://www.arthrozene.com/"][href*="?tid="],a[href^="https://mob1ledev1ces.com/"],amp-fx-flying-carpet,a[href^="https://taghaugh.com/"],a[href^="https://porntubemate.com/"],[href^="http://join.michelle-austin.com/"],a[href^="https://track.afftck.com/"],div[class^="native-ad-"],a[href^="https://paid.outbrain.com/network/redir?"],a[href^="https://go.julrdr.com/"],a[href^="https://dialling-abutory.com/"],[href^="https://r.kraken.com/"],div[id^="ad_position_"],[class^="chp_ads_block"],a[href^="https://syndication.optimizesrv.com/"],a[href^="https://t.aslnk.link/"],[href^="https://go.astutelinks.com/"],a[href^="https://www.nudeidols.com/cams/"],AD-SLOT,div[data-adunit],a[href^="https://delivery.porn.com/"],[href^="https://goldforyourfuture.com/clk.trk"] img,a[href^="https://adsrv4k.com/"],[id^="ad_slider"],[href^="http://join.shemalepornstar.com/"],a[href^="https://www.mypornstarcams.com/landing/click/"],iframe[src^="https://pagead2.googlesyndication.com/"],a[href^="https://claring-loccelkin.com/"],a[href^="https://go.goasrv.com/"],a[href^="https://pl.premium4kflix.website/"],div[data-ad-underplayer],div[data-google-query-id],a[data-widget-outbrain-redirect^="http://paid.outbrain.com/network/redir?"],a[href^="https://leg.xyz/?track="],[href^="https://go.4rabettraff.com/"],a[href^="https://refpazkjixes.top/"],a[href^="https://ndt5.net/"],a[href^="https://track.totalav.com/"],[href^="https://v.investologic.co.uk/"],[onclick*="content.ad/"],div[class^="largeRectangleAd_"],a[href^="https://go.xlivrdr.com"],a[href^="http://tc.tradetracker.net/"] > img,topadblock,a[href^="https://thaudray.com/"],a[href^="https://promo-bc.com/"],[href="https://ourgoldguy.com/contact/"] img,[href^="https://awbbjmp.com/"],a[href^="https://uncensored3d.com/"],div[id^="advads-"],div[class^="index_adBeforeContent_"],a[data-obtrack^="http://paid.outbrain.com/network/redir?"],div[data-ad-targeting],[href^="http://trafficare.net/"],a[href^="https://dianches-inchor.com/"],a[href^="https://go.currency.com/"],img[src^="https://images.purevpnaffiliates.com"],a[href^="https://a.adtng.com/"],div[data-insertion],a[href^="http://secure.vivid.com/track/"],[id^="google_ads_iframe"],a[href^="https://torguard.net/aff.php"] > img,a[href^="http://paid.outbrain.com/network/redir?"],display-ads,div[id^="google_dfp_"],app-advertisement,a[href^="https://see.kmisln.com/"],a[href^="https://mmwebhandler.aff-online.com/"],a[href^="https://join.virtuallust3d.com/"],a[href^="https://prf.hn/click/"][href*="/creativeref:"] > img,a[href^="https://transfer.xe.com/signup/track/redirect?"],a[href^="https://ads.planetwin365affiliate.com/redirect.aspx?"],div[data-adzone],div[id^="gtm-ad-"],[href^="https://engine.gettopple.com/"],a[href^="https://trappist-1d.com/"],a[href^="//chrif8kdstie.com/"],div[id^="sticky_ad_"],a[href^="https://www.oboom.com/ref/"],a[href^="https://tupitea.co/"],div[data-native_ad],a[href^="https://track.clickmoi.xyz/"],[href^="http://join.trannies-fuck.com/"],a[href^="https://www.adskeeper.com"],a[href^="https://meet-sexhere.com/"],div[class^="Display_displayAd"],a[href^="https://as.conjectwatson.com/"],a[href^="https://ad.doubleclick.net/"],[data-ez-name],a[href^="https://juicyads.in/"],span[id^="ezoic-pub-ad-placeholder-"],a[href^="https://www.sheetmusicplus.com/"][href*="?aff_id="],a[href^="https://bongacams2.com/track?"],a[href^="//lambingsyddir.com/"],a-ad { display: none !important }</style></body>
</html>
