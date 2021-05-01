# Nothingmuchhere-tester

<!DOCTYPE html>


    <html itemscope itemtype="https://schema.org/QAPage" class="html__responsive  html__fixed-top-bar">

    <head>

        <title>trigonometry - Proving Trig Identities (Complex Numbers) - Mathematics Stack Exchange</title>
        <link rel="shortcut icon" href="https://cdn.sstatic.net/Sites/math/Img/favicon.ico?v=92addaa54d18">
        <link rel="apple-touch-icon" href="https://cdn.sstatic.net/Sites/math/Img/apple-touch-icon.png?v=0ae50baa40ed">
        <link rel="image_src" href="https://cdn.sstatic.net/Sites/math/Img/apple-touch-icon.png?v=0ae50baa40ed"> 
        <link rel="search" type="application/opensearchdescription+xml" title="Mathematics Stack Exchange" href="/opensearch.xml">
        <link rel="canonical" href="https://math.stackexchange.com/questions/1627410/proving-trig-identities-complex-numbers" />
        <meta name="viewport" content="width=device-width, height=device-height, initial-scale=1.0, minimum-scale=1.0">
        <meta property="og:type" content= "website" />
        <meta property="og:url" content="https://math.stackexchange.com/questions/1627410/proving-trig-identities-complex-numbers"/>
        <meta property="og:site_name" content="Mathematics Stack Exchange" />
        <meta property="og:image" itemprop="image primaryImageOfPage" content="https://cdn.sstatic.net/Sites/math/Img/apple-touch-icon@2.png?v=4ec1df2e49b1" />
        <meta name="twitter:card" content="summary"/>
        <meta name="twitter:domain" content="math.stackexchange.com"/>
        <meta name="twitter:site" content="@StackMath" />
        <meta name="twitter:creator" content="@StackMath" />
        <meta name="twitter:title" property="og:title" itemprop="name" content="Proving Trig Identities (Complex Numbers)" />
        <meta name="twitter:description" property="og:description" itemprop="description" content="Question: Prove that if $z = \cos (\theta) &#x2B; i\sin(\theta)$, then&#xA;    &#xA;    $$ z^n &#x2B;  {1\over z^n} = 2\cos(n\theta) $$&#xA;    &#xA;    Hence prove that $\cos^6(\theta)$ $=$ $\frac 1{32}$$(\cos(6\theta)$ &#x2B; ..." />

        <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
        <script src="https://cdn.sstatic.net/Js/stub.en.js?v=d0f0ef54ac95"></script>
    
        <link rel="stylesheet" type="text/css" href="https://cdn.sstatic.net/Shared/stacks.css?v=f5e0a087a500">
        <link rel="stylesheet" type="text/css" href="https://cdn.sstatic.net/Sites/math/primary.css?v=aae49c27d1cc">

    
            <link rel="alternate" type="application/atom+xml" title="Feed for question &#x27;Proving Trig Identities (Complex Numbers)&#x27;" href="/feeds/question/1627410">
<script src="https://cdn.sstatic.net/Js/citation.en.js?v=70fcb838995e"></script>            <meta name="twitter:app:country" content="US" />
            <meta name="twitter:app:name:iphone" content="Stack Exchange iOS" />
            <meta name="twitter:app:id:iphone" content="871299723" />
            <meta name="twitter:app:url:iphone" content="se-zaphod://math.stackexchange.com/questions/1627410/proving-trig-identities-complex-numbers" />
            <meta name="twitter:app:name:ipad" content="Stack Exchange iOS" />
            <meta name="twitter:app:id:ipad" content="871299723" />
            <meta name="twitter:app:url:ipad" content="se-zaphod://math.stackexchange.com/questions/1627410/proving-trig-identities-complex-numbers" />
            <meta name="twitter:app:name:googleplay" content="Stack Exchange Android">
            <meta name="twitter:app:url:googleplay" content="https://math.stackexchange.com/questions/1627410/proving-trig-identities-complex-numbers">
            <meta name="twitter:app:id:googleplay" content="com.stackexchange.marvin">
        <script>
            StackExchange.ready(function () {

                StackExchange.using("postValidation", function () {
                    StackExchange.postValidation.initOnBlurAndSubmit($('#post-form'), 2, 'answer');
                });


                StackExchange.question.init({showCitation:true,showAnswerHelp:true,totalCommentCount:1,shownCommentCount:1,enableTables:true,questionId:1627410});

                styleCode();

                    StackExchange.realtime.subscribeToQuestion('69', '1627410');
                    StackExchange.using("gps", function () { StackExchange.gps.trackOutboundClicks('#content', '.js-post-body'); });



            });
        </script>

        
        
        
        <link rel="stylesheet" type="text/css" href="https://cdn.sstatic.net/Shared/Channels/channels.css?v=2a09da57c2c9">
        
        
        <script src="https://cdn.sstatic.net/Js/third-party/citation-helper.js?v=2591ce444a3f"></script>


            <script type="text/x-mathjax-config">
                MathJax.Hub.Config({"HTML-CSS": { preferredFont: "TeX", availableFonts: ["STIX","TeX"], linebreaks: { automatic:true }, EqnChunk: (MathJax.Hub.Browser.isMobile ? 10 : 50) },
                    tex2jax: { inlineMath: [ ["$", "$"], ["\\\\(","\\\\)"] ], displayMath: [ ["$$","$$"], ["\\[", "\\]"] ], processEscapes: true, ignoreClass: "tex2jax_ignore|dno" },
                    TeX: {
                        extensions: ["begingroup.js"],
                        noUndefined: { attributes: { mathcolor: "red", mathbackground: "#FFEEEE", mathsize: "90%" } }, 
                        Macros: { href: "{}" } 
                    },
                    messageStyle: "none",
                    styles: { ".MathJax_Display, .MathJax_Preview, .MathJax_Preview > *": { "background": "inherit" } },
                    SEEditor: "mathjaxEditing"
            });
            </script>
            <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-AMS_HTML-full"></script>
    <script>
        StackExchange.ready(function () {
            StackExchange.realtime.init('wss://qa.sockets.stackexchange.com');
                StackExchange.realtime.subscribeToReputationNotifications('69');
        StackExchange.realtime.subscribeToTopBarNotifications('69');
        });
    </script>
    <script>
        StackExchange.init({"locale":"en","serverTime":1619871454,"routeName":"Questions/Show","stackAuthUrl":"https://stackauth.com","networkMetaHostname":"meta.stackexchange.com","site":{"name":"Mathematics Stack Exchange","description":"Q&A for people studying math at any level and professionals in related fields","isNoticesTabEnabled":true,"enableNewTagCreationWarning":true,"insertSpaceAfterNameTabCompletion":false,"id":69,"cookieDomain":".stackexchange.com","childUrl":"https://math.meta.stackexchange.com","styleCodeWithHighlightjs":true,"negativeVoteScoreFloor":null,"enableSocialMediaInSharePopup":true,"protocol":"https"},"user":{"fkey":"fbfa9cf76921d03272650b061592cf4031b8318d5c4cced7fe5f66eae2d1d6ac","tid":"6b37c85c-10c1-1bc6-1601-0b2d4bbe2cb9","rep":0,"isAnonymous":true,"isAnonymousNetworkWide":true},"realtime":{"newest":true,"active":true,"tagged":true,"staleDisconnectIntervalInHours":0},"events":{"postType":{"question":1},"postEditionSection":{"title":1,"body":2,"tags":3}},"story":{"minCompleteBodyLength":75,"likedTagsMaxLength":300,"dislikedTagsMaxLength":300},"jobPreferences":{"maxNumDeveloperRoles":2,"maxNumIndustries":4},"svgIconPath":"https://cdn.sstatic.net/Img/stacks-icons","svgIconHash":"7eb510ec72e5"}, {"userProfile":{},"userMessaging":{},"tags":{},"subscriptions":{"defaultBasicMaxTrueUpSeats":250,"defaultFreemiumMaxTrueUpSeats":50,"defaultMaxTrueUpSeats":1000},"snippets":{"renderDomain":"stacksnippets.net"},"slack":{"sidebarAdDismissCookie":"slack-sidebar-ad","sidebarAdDismissCookieExpirationDays":60.0},"site":{"allowImageUploads":true,"enableImgurHttps":true,"enableUserHovercards":true,"forceHttpsImages":true},"questions":{"enableQuestionTitleLengthLiveWarning":true,"maxTitleSize":150,"questionTitleLengthStartLiveWarningChars":50},"intercom":{"appId":"inf0secd","hostBaseUrl":"https://stacksnippets.net"},"paths":{},"monitoring":{"clientTimingsAbsoluteTimeout":30000,"clientTimingsDebounceTimeout":1000},"mentions":{"maxNumUsersInDropdown":50},"markdown":{"enableTables":true},"legal":{"oneTrustConfigId":"cb0f3c87-b769-4e66-bbaa-377f9194216d"},"flags":{"allowRetractingCommentFlags":true,"allowRetractingFlags":true},"elections":{"opaVoteResultsBaseUrl":"https://www.opavote.com/results/"},"comments":{},"accounts":{"currentPasswordRequiredForChangingStackIdPassword":true}});
        StackExchange.using.setCacheBreakers({"js/adops.en.js":"22a9bd59b1e9","js/ask.en.js":"91b4450eec6e","js/begin-edit-event.en.js":"7f52eac9bfd0","js/copy-transpiled.en.js":"f8f92960ae26","js/cm.en.js":"10589c3c82f3","js/events.en.js":"ef56fb37096f","js/explore-qlist.en.js":"a6f836ff8aa6","js/full-anon.en.js":"f0fdc6fa5791","js/full.en.js":"7c3a033d0ea5","js/help.en.js":"71d5b6988a97","js/highlightjs-loader.en.js":"372f52c14ae0","js/inline-tag-editing.en.js":"88510a5b8778","js/keyboard-shortcuts.en.js":"065d00c0709b","js/markdown-it-loader.en.js":"4155292d8c79","js/modElections.en.js":"7dcab67be352","js/mobile.en.js":"8384eaca532c","js/moderator.en.js":"dcbccd170b11","js/postCollections-transpiled.en.js":"4b965196e9d3","js/post-validation.en.js":"5976981207cb","js/prettify-full.en.js":"53ae48d63956","js/question-editor.en.js":"","js/review.en.js":"20f4126c5dfb","js/review-v2-transpiled.en.js":"83979b00fc27","js/revisions.en.js":"2ae1657f6037","js/stacks-editor.en.js":"87a8edc40dec","js/tageditor.en.js":"8b3e172b89a9","js/tageditornew.en.js":"bdb0cce7f692","js/tagsuggestions.en.js":"9b2c5d9791d2","js/unlimited-transpiled.en.js":"bed658a24477","js/wmd.en.js":"d8cb1a90858b","js/mathjax-editing.en.js":"af6e54884fb6"});
        StackExchange.using("gps", function() {
             StackExchange.gps.init(true);
        });
    </script>
    <noscript id="noscript-css"><style>body,.top-bar{margin-top:1.9em}</style></noscript>
    </head>
    <body class="question-page unified-theme">
    <div id="notify-container"></div>
    <div id="custom-header"></div>
        
<header class="top-bar js-top-bar top-bar__network">
    <div class="wmx12 mx-auto grid ai-center h100" role="menubar">
        <div class="-main grid--cell">
                <a href="#" class="left-sidebar-toggle p0 ai-center jc-center js-left-sidebar-toggle" role="menuitem" aria-haspopup="true" aria-controls="left-sidebar" aria-expanded="false"><span class="ps-relative"></span></a>
                <div class="topbar-dialog leftnav-dialog js-leftnav-dialog dno">
                    <div class="left-sidebar js-unpinned-left-sidebar" data-can-be="left-sidebar" data-is-here-when="sm"></div>
                </div>
                <a href="#" class="-logo js-gps-track js-network-logo network-logo"
                   data-gps-track="stack_exchange_popup.show" role="menuitem" aria-haspopup="true" aria-controls="topbar-network-logo-dialog" aria-expanded="false">
                    <svg aria-hidden="true" class="native mtn1 svg-icon iconLogoSEAlternativeSm" width="107" height="15" viewBox="0 0 107 15"><path d="M48.41 11.93l-1.96-3.2-1.04 1.16v2.04h-1.42V2.18h1.42v6.01L48.14 5h1.72l-2.44 2.7 2.74 4.22h-1.75zm-7.06.08c-1.59 0-3.14-.96-3.14-3.56s1.55-3.54 3.14-3.54c.97 0 1.65.27 2.31.97l-.97.93c-.44-.48-.79-.66-1.34-.66s-1 .22-1.3.62c-.31.38-.42.87-.42 1.68 0 .81.1 1.32.41 1.7.3.4.76.62 1.3.62.56 0 .9-.18 1.35-.66l.97.92c-.66.7-1.34.98-2.31.98zm-5.66-3.15h-1.65c-.83 0-1.26.37-1.26 1s.4.99 1.3.99c.53 0 .93-.04 1.3-.4.22-.2.31-.53.31-1.03v-.56zm.03 3.07v-.63c-.51.5-1 .71-1.87.71-.87 0-1.46-.2-1.89-.63a2.1 2.1 0 01-.55-1.49c0-1.16.82-2 2.42-2h1.86v-.5c0-.87-.44-1.3-1.54-1.3-.77 0-1.15.18-1.54.68l-.92-.86c.66-.77 1.35-1 2.52-1 1.93 0 2.9.8 2.9 2.38v4.64h-1.39zm-5.9 0c-1.32 0-1.93-.93-1.93-1.93V6.18h-.8V5.1h.8V3h1.41v2.1h1.36v1.07H29.3v3.75c0 .5.25.81.78.81h.58v1.2h-.85zm-6.33.08c-1.48 0-2.55-.34-3.49-1.28l1-.98c.72.72 1.51.94 2.52.94 1.3 0 2.04-.55 2.04-1.5 0-.42-.13-.78-.39-1.01-.25-.23-.5-.33-1.08-.41l-1.16-.17a3.4 3.4 0 01-1.88-.78 2.41 2.41 0 01-.72-1.86c0-1.7 1.25-2.86 3.3-2.86 1.3 0 2.22.33 3.07 1.1l-.96.94a2.92 2.92 0 00-2.15-.75c-1.16 0-1.8.65-1.8 1.52 0 .35.1.67.37.9.25.22.65.38 1.11.45l1.13.17c.91.13 1.42.35 1.84.72.54.47.8 1.17.8 2 0 1.8-1.48 2.86-3.55 2.86z" fill="#FEFEFE"/><path d="M104.16 7.09c-.2-.42-.6-.74-1.2-.74s-.99.32-1.18.74c-.1.25-.15.44-.16.75h2.7a2 2 0 00-.16-.75zm-2.54 1.96c0 .9.56 1.57 1.55 1.57.78 0 1.16-.21 1.61-.66l1.08 1.04a3.4 3.4 0 01-2.7 1.11c-1.68 0-3.29-.76-3.29-3.62 0-2.3 1.26-3.6 3.1-3.6 1.97 0 3.1 1.44 3.1 3.37v.79h-4.45zm-5.48-2.57C95.1 6.48 95 7.37 95 8.3c0 .94.1 1.85 1.15 1.85 1.05 0 1.18-.91 1.18-1.85 0-.93-.13-1.82-1.18-1.82zm-.17 8.22c-1.1 0-1.84-.21-2.58-.92l1.1-1.11c.4.38.8.54 1.4.54 1.06 0 1.43-.74 1.43-1.46v-.72c-.47.51-1 .7-1.7.7-.69 0-1.29-.23-1.68-.62-.67-.66-.73-1.57-.73-2.8 0-1.24.06-2.13.73-2.8.4-.39 1-.62 1.7-.62.75 0 1.24.2 1.73.75v-.67h1.72v6.8c0 1.7-1.21 2.93-3.12 2.93zm-5.76-2.67V7.76c0-.96-.61-1.28-1.17-1.28-.56 0-1.18.32-1.18 1.28v4.27h-1.78V4.97h1.73v.65a2.44 2.44 0 011.78-.73c.7 0 1.28.23 1.67.62.58.57.73 1.24.73 2v4.52H90.2zm-7.1-2.98h-1.4c-.64 0-1 .3-1 .8 0 .49.33.81 1.02.81.5 0 .8-.04 1.12-.34.2-.17.26-.46.26-.89v-.38zm.04 2.98v-.6c-.48.47-.93.67-1.74.67-.8 0-1.4-.2-1.82-.62-.38-.4-.58-.97-.58-1.59 0-1.12.77-2.05 2.42-2.05h1.68V7.5c0-.77-.38-1.11-1.32-1.11-.68 0-1 .16-1.37.58l-1.13-1.1c.7-.75 1.38-.97 2.57-.97 1.99 0 3.02.84 3.02 2.5v4.64h-1.73zm-6.93 0v-4.3c0-.94-.6-1.25-1.15-1.25-.56 0-1.15.32-1.15 1.24v4.31h-1.77V2.38h1.77v3.24a2.35 2.35 0 011.7-.73c1.56 0 2.38 1.08 2.38 2.57v4.57h-1.78zm-6.96.08c-1.42 0-3.18-.76-3.18-3.62 0-2.85 1.76-3.6 3.18-3.6.98 0 1.72.3 2.34.95l-1.2 1.2c-.36-.4-.68-.56-1.14-.56-.42 0-.75.14-1.01.46-.27.33-.4.8-.4 1.55s.13 1.24.4 1.58c.26.3.59.46 1 .46.47 0 .79-.16 1.15-.56l1.2 1.18c-.62.65-1.36.96-2.34.96zm-5.53-.08l-1.3-2.11-1.3 2.11H59l2.45-3.6-2.35-3.46h2.12L62.42 7l1.21-2.02h2.13L63.4 8.43l2.46 3.6h-2.13zm-11.75 0V2.06h6.6V3.8h-4.65v2.33h3.96v1.74h-3.96v2.42h4.65v1.74h-6.6z" fill="#2F96E8"/><path d="M0 3c0-1.1.9-2 2-2h8a2 2 0 012 2H0z" fill="#8FD8F7"/><path d="M12 10H0c0 1.1.9 2 2 2h5v3l3-3a2 2 0 002-2z" fill="#155397"/><path fill="#46A2D9" d="M0 4h12v2H0z"/><path fill="#2D6DB5" d="M0 7h12v2H0z"/></svg>
                </a>
                <div class="topbar-dialog network-logo-dialog js-network-logo-dialog dno" id="topbar-network-logo-dialog" role="dialog" aria-labelledby="topbar-network-logo-dialog-title" aria-describedby="topbar-network-logo-dialog-body">
                    <div class="dialog-content">
                        <h4 class="bold" id="topbar-network-logo-dialog-title">Stack Exchange Network</h4>
                        <p id="topbar-network-logo-dialog-body">
                            Stack Exchange network consists of 176 Q&amp;A communities including <a href="https://stackoverflow.com">Stack Overflow</a>, the largest, most trusted online community for developers to learn, share their knowledge, and build their careers.
                        </p>
                        <a class="s-btn s-btn__filled" href="https://stackexchange.com"
                        data-gps-track="stack_exchange_popup.click">Visit Stack Exchange</a>
                        <button class="icon-close js-close-button s-btn s-btn__unset" aria-label="Close"><svg aria-hidden="true" class="svg-icon iconClear" width="18" height="18" viewBox="0 0 18 18"><path d="M15 4.41L13.59 3 9 7.59 4.41 3 3 4.41 7.59 9 3 13.59 4.41 15 9 10.41 13.59 15 15 13.59 10.41 9 15 4.41z"/></svg></button>
                    </div>
                </div>



        </div>


            <form id="search" role="search" action=/search class="grid--cell fl-grow1 searchbar px12 js-searchbar " autocomplete="off">
                    <div class="ps-relative">
                        <input name="q"
                               type="text"
                               placeholder="Search on Mathematics&#x2026;"
                               value=""
                               autocomplete="off"
                               maxlength="240"
                               class="s-input s-input__search js-search-field "
                               aria-label="Search"
                               aria-controls="top-search" 
                               data-controller="s-popover"
                               data-action="focus->s-popover#show"
                               data-s-popover-placement="bottom-start"/>
                        <svg aria-hidden="true" class="s-input-icon s-input-icon__search svg-icon iconSearch" width="18" height="18" viewBox="0 0 18 18"><path d="M18 16.5l-5.14-5.18h-.35a7 7 0 10-1.19 1.19v.35L16.5 18l1.5-1.5zM12 7A5 5 0 112 7a5 5 0 0110 0z"/></svg>
                        <div class="s-popover p0 wmx100 wmn4 sm:wmn-initial js-top-search-popover" id="top-search" role="menu">
    <div class="s-popover--arrow"></div>
    <div class="js-spinner p24 grid ai-center jc-center d-none">
        <div class="s-spinner s-spinner__sm fc-orange-400">
            <div class="v-visible-sr">Loading&#x2026;</div>
        </div>
    </div>

    <span class="v-visible-sr js-screen-reader-info"></span>
    <div class="js-ac-results overflow-y-auto hmx3 d-none"></div>

    <div class="js-search-hints" aria-describedby="Tips for searching"></div>
</div>
                    </div>
            </form>
        
        

<ol class="overflow-x-auto ml-auto -secondary grid ai-center list-reset h100 user-logged-out" role="presentation">
        <li class="-item searchbar-trigger"><a href="#" class="-link js-searchbar-trigger" role="button" aria-label="Search" aria-haspopup="true" aria-controls="search" title="Click to show search"><svg aria-hidden="true" class="svg-icon iconSearch" width="18" height="18" viewBox="0 0 18 18"><path d="M18 16.5l-5.14-5.18h-.35a7 7 0 10-1.19 1.19v.35L16.5 18l1.5-1.5zM12 7A5 5 0 112 7a5 5 0 0110 0z"/></svg></a></li>
        <li class="-item inbox-button-item">
            <a href="#" class="-link js-inbox-button"
               aria-label="Inbox" title="Recent inbox messages" role="menuitem" aria-haspopup="true" aria-expanded="false" data-unread-count="0">
                <svg aria-hidden="true" class="svg-icon iconInbox" width="20" height="18" viewBox="0 0 20 18"><path d="M4.63 1h10.56a2 2 0 011.94 1.35L20 10.79V15a2 2 0 01-2 2H2a2 2 0 01-2-2v-4.21l2.78-8.44c.25-.8 1-1.36 1.85-1.35zm8.28 12l2-2h2.95l-2.44-7.32a1 1 0 00-.95-.68H5.35a1 1 0 00-.95.68L1.96 11h2.95l2 2h6z"/></svg>
                <span class="indicator-badge js-unread-count _important d-none">0</span>
            </a>
        </li>
        <li class="-item achievements-button-item">
            <a href="#" class="-link js-achievements-button" data-unread-class="_highlighted-positive"
               aria-label="Achievements" title="Recent achievements: reputation, badges, and privileges earned" role="menuitem" aria-haspopup="true" aria-expanded="false" data-unread-count="0" data-lit-up="false">
                <svg aria-hidden="true" class="svg-icon iconAchievements" width="18" height="18" viewBox="0 0 18 18"><path d="M15 2V1H3v1H0v4c0 1.6 1.4 3 3 3v1c.4 1.5 3 2.6 5 3v2H5s-1 1.5-1 2h10c0-.4-1-2-1-2h-3v-2c2-.4 4.6-1.5 5-3V9c1.6-.2 3-1.4 3-3V2h-3zM3 7c-.5 0-1-.5-1-1V4h1v3zm8.4 2.5L9 8 6.6 9.4l1-2.7L5 5h3l1-2.7L10 5h2.8l-2.3 1.8 1 2.7h-.1zM16 6c0 .5-.5 1-1 1V4h1v2z"/></svg>
                <span class="indicator-badge js-unread-count _positive d-none">+0</span>
            </a>
        </li>
        <li class="-item help-button-item">
            <a href="#" class="-link js-help-button" title="Help Center and other resources" role="menuitem" aria-haspopup="true" aria-controls="topbar-help-dialog"
               data-ga="[&quot;top navigation&quot;,&quot;help menu click&quot;,null,null,null]"><svg aria-hidden="true" class="svg-icon iconHelp" width="18" height="18" viewBox="0 0 18 18"><path d="M9 1C4.64 1 1 4.64 1 9c0 4.36 3.64 8 8 8 4.36 0 8-3.64 8-8 0-4.36-3.64-8-8-8zm.81 12.13c-.02.71-.55 1.15-1.24 1.13-.66-.02-1.17-.49-1.15-1.2.02-.72.56-1.18 1.22-1.16.7.03 1.2.51 1.17 1.23zM11.77 8c-.59.66-1.78 1.09-2.05 1.97a4 4 0 00-.09.75c0 .05-.03.16-.18.16H7.88c-.16 0-.18-.1-.18-.15.06-1.35.66-2.2 1.83-2.88.39-.29.7-.75.7-1.24.01-1.24-1.64-1.82-2.35-.72-.21.33-.18.73-.18 1.1H5.75c0-1.97 1.03-3.26 3.03-3.26 1.75 0 3.47.87 3.47 2.83 0 .57-.2 1.05-.48 1.44z"/></svg></a>
        </li>
        <div class="topbar-dialog help-dialog js-help-dialog dno" id="topbar-help-dialog" role="menu">
            <div class="modal-content">
                <ul>
                        <li>
                            <a href="/tour" class="js-gps-track" data-gps-track="help_popup.click({ item_type:1 })"
                               data-ga="[&quot;top navigation&quot;,&quot;tour submenu click&quot;,null,null,null]">
                                Tour
                                <span class="item-summary">
                                    Start here for a quick overview of the site
                                </span>
                            </a>
                        </li>
                    <li>
                        <a href="/help" class="js-gps-track"
                           data-gps-track="help_popup.click({ item_type:4 })"
                           data-ga="[&quot;top navigation&quot;,&quot;help center&quot;,null,null,null]">
                            Help Center
                            <span class="item-summary">
                                Detailed answers to any questions you might have
                            </span>
                        </a>
                    </li>
                                <li>
                                    <a href="https://math.meta.stackexchange.com" class="js-gps-track" data-gps-track="help_popup.click({ item_type:2 })"
                                       data-ga="[&quot;top navigation&quot;,&quot;meta submenu click&quot;,null,null,null]">
                                        Meta
                                        <span class="item-summary">
                                            Discuss the workings and policies of this site
                                        </span>
                                    </a>
                                </li>
                            <li>
                                <a href="https://stackoverflow.com/company" class="js-gps-track" data-gps-track="help_popup.click({ item_type:6 })"
                                   data-ga="[&quot;top navigation&quot;,&quot;about us submenu click&quot;,null,null,null]">
                                    About Us
                                    <span class="item-summary">
                                        Learn more about Stack Overflow the company
                                    </span>
                                </a>
                            </li>
                            <li>
                                <a href="https://stackoverflowbusiness.com/?ref=topbar_help" class="js-gps-track" data-gps-track="help_popup.click({ item_type:7 })"
                                   data-ga="[&quot;top navigation&quot;,&quot;business submenu click&quot;,null,null,null]">
                                    Business
                                    <span class="item-summary">
                                        Learn more about hiring developers or posting ads with us
                                    </span>
                                </a>
                            </li>
                </ul>
            </div>
        </div>
        <li class="-item site-switcher-item">
            <a href="https://stackexchange.com" class="-link js-site-switcher-button js-gps-track" data-gps-track="site_switcher.show"
               aria-label="Site switcher"
               title="A list of all 176 Stack Exchange sites"
               role="menuitem" aria-haspopup="true" aria-expanded="false"
               data-ga="[&quot;top navigation&quot;,&quot;stack exchange click&quot;,null,null,null]">
                <svg aria-hidden="true" class="svg-icon iconStackExchange" width="18" height="18" viewBox="0 0 18 18"><path d="M15 1H3a2 2 0 00-2 2v2h16V3a2 2 0 00-2-2zM1 13c0 1.1.9 2 2 2h8v3l3-3h1a2 2 0 002-2v-2H1v2zm16-7H1v4h16V6z"/></svg>
            </a>
        </li>

            <li class="-ctas">
                            <a href="https://math.stackexchange.com/users/login?ssrc=head&returnurl=https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers" class="login-link s-btn s-btn__filled py8 js-gps-track" rel="nofollow"
                               data-gps-track="login.click" data-ga="[&quot;top navigation&quot;,&quot;login button click&quot;,null,null,null]">Log in</a>
                            <a href="https://math.stackexchange.com/users/signup?ssrc=head&returnurl=https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers" class="login-link s-btn s-btn__primary py8" rel="nofollow" data-ga="[&quot;sign up&quot;,&quot;Sign Up Navigation&quot;,&quot;Header&quot;,null,null]">Sign up</a>

            </li>

    <li class="js-topbar-dialog-corral" role="presentation">
            

    <div class="topbar-dialog siteSwitcher-dialog dno" role="menu">
        <div class="header">
            <h3>
                <a href="https://math.stackexchange.com">current community</a>
            </h3>
        </div>
        <div class="modal-content bg-powder-050">
            <ul class="current-site">
                    <li class="grid">
                            <div class="fl1">
                <a href="https://math.stackexchange.com"
       class="current-site-link site-link js-gps-track grid gs8 gsx"
       data-id="69"
       data-gps-track="site_switcher.click({ item_type:3 })">
        <div class="favicon favicon-math site-icon grid--cell" title="Mathematics"></div>
        <span class="grid--cell fl1">
            Mathematics
        </span>
    </a>

    </div>
    <div class="related-links">
            <a href="https://math.stackexchange.com/help" class="js-gps-track" data-gps-track="site_switcher.click({ item_type:14 })">help</a>
            <a href="https://chat.stackexchange.com?tab=site&amp;host=math.stackexchange.com" class="js-gps-track" data-gps-track="site_switcher.click({ item_type:6 })">chat</a>
    </div>

                    </li>
                    <li class="related-site grid">
                            <div class="L-shaped-icon-container">
        <span class="L-shaped-icon"></span>
    </div>

                            <a href="https://math.meta.stackexchange.com"
       class=" site-link js-gps-track grid gs8 gsx"
       data-id="70"
       data-gps-track="site.switch({ target_site:70, item_type:3 }),site_switcher.click({ item_type:4 })">
        <div class="favicon favicon-mathmeta site-icon grid--cell" title="Mathematics Meta"></div>
        <span class="grid--cell fl1">
            Mathematics Meta
        </span>
    </a>

                    </li>
            </ul>
        </div>

        <div class="header" id="your-communities-header">
            <h3>
your communities            </h3>

        </div>
        <div class="modal-content" id="your-communities-section">

                <div class="call-to-login">
<a href="https://math.stackexchange.com/users/signup?ssrc=site_switcher&amp;returnurl=https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers" class="login-link js-gps-track" data-gps-track="site_switcher.click({ item_type:10 })">Sign up</a> or <a href="https://math.stackexchange.com/users/login?ssrc=site_switcher&amp;returnurl=https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers" class="login-link js-gps-track" data-gps-track="site_switcher.click({ item_type:11 })">log in</a> to customize your list.                </div>
        </div>

        <div class="header">
            <h3><a href="https://stackexchange.com/sites">more stack exchange communities</a>
            </h3>
            <a href="https://stackoverflow.blog" class="fr">company blog</a>
        </div>
        <div class="modal-content">
                <div class="child-content"></div>
        </div>        
    </div>

    </li>
</ol>

    </div>
</header>

    <script>
        StackExchange.ready(function () { StackExchange.topbar.init(); });
StackExchange.scrollPadding.setPaddingTop(50, 10);    </script>



            

        
    
<div class="py24 bg-black-750 fc-black-200 sm:pt24 sm:pb24 ps-relative js-dismissable-hero">
    <div class="px12 grid ai-center jc-center mx-auto wmx12 sm:fd-column">
        <div class="grid--cell wmx3 fs-body2 mr64 md:mr32 sm:mr0 sm:ta-center sm:mr0 sm:ta-center">
            <p>Mathematics Stack Exchange is a question and answer site for people studying math at any level and professionals in related fields. It only takes a minute to sign up.</p>

            <a href="/users/signup?ssrc=hero&amp;returnurl=https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers" class="s-btn s-btn__primary">Sign up to join this community</a>
        </div>
        <div class="grid fd-column ai-center wmn3 sm:wmn-initial sm:mt32 hero-background">
            <div class="grid ai-center mb24 sm:mb16">
                <div class="grid--cell mr16">
                    <img width="31" src="https://cdn.sstatic.net/Img/hero/anonymousHeroQuestions.svg?v=748bfb046b78">
                </div>
                <div class="grid--cell">
                    Anybody can ask a question
                </div>
            </div>
            <div class="grid ai-center mb24 sm:mb16">
                <div class="grid--cell mr16">
                    <img width="35" src="https://cdn.sstatic.net/Img/hero/anonymousHeroAnswers.svg?v=d5348b00eddc">
                </div>
                <div class="grid--cell">
                    Anybody can answer
                </div>
            </div>
            <div class="grid ai-center">
                <div class="grid--cell mr16">
                    <img width="24" src="https://cdn.sstatic.net/Img/hero/anonymousHeroUpvote.svg?v=af2bb70d5d1b">
                </div>
                <div class="grid--cell wmx2">
                    The best answers are voted up and rise to the top
                </div>
            </div>
        </div>
            <div class="grid--cell as-start md:ps-absolute t8 r8">
                <button class="s-btn s-btn__muted p8 js-dismiss">
                    <svg aria-hidden="true" class="svg-icon iconClear" width="18" height="18" viewBox="0 0 18 18"><path d="M15 4.41L13.59 3 9 7.59 4.41 3 3 4.41 7.59 9 3 13.59 4.41 15 9 10.41 13.59 15 15 13.59 10.41 9 15 4.41z"/></svg>
                </button>
            </div>
    </div>
</div>

<script>
    StackExchange.ready(function () {
        StackExchange.Hero.init("nso", "a");

        var location = 0;
        if ($("body").hasClass("questions-page")) {
            location = 1;
        } else if ($("body").hasClass("question-page")) {
            location = 1;
        } else if ($("body").hasClass("faq-page")) {
            location = 5;
        } else if ($("body").hasClass("home-page")) {
            location = 3;
        }

        $('.js-cta-button').click(function () {
            StackExchange.using("gps", function () {
                StackExchange.gps.track("hero.action", { hero_action_type: 'cta', location: location }, true);
            });
        });

        // TODO: we should review the class names and whatnot in use here. Older heroes use id selectors, the newer
        // sticky question hero on SO has a .js-dismiss class instead, but it's apparently not used anywhere... 
        // It's not great. Ideally we'd have a set of classes in the partials above that would correspond to 
        // the behaviours we want here in a more clear way. 

        // sticky question-page hero at the bottom of the page on SO
        $('.js-dismiss').on('click', function () {
            StackExchange.using("gps", function () {
                StackExchange.gps.track("hero.action", { hero_action_type: "close", location: location }, true);
            });
            StackExchange.Hero.dismiss();
            $(".js-dismissable-hero").fadeOut("fast");
        });
    });
</script>


        <header class="site-header">
            <div class="site-header--container">
                <a class="site-header--link d-flex ai-center fs-headline1 fw-bold" href="https://math.stackexchange.com">
                        <img class="h-auto wmx100" src="https://cdn.sstatic.net/Sites/math/Img/logo.svg?v=2ad3f9715b74" alt="Mathematics">
                </a>

            </div>
        </header>

    <div class="container">
            


<div id="left-sidebar" data-is-here-when="md lg" class="left-sidebar js-pinned-left-sidebar ps-relative">
    <div class="left-sidebar--sticky-container js-sticky-leftnav">
        <nav role="navigation">
            <ol class="nav-links">
        <li class="">
            <a
               href="/"
               class="pl8 js-gps-track nav-links--link"
               
               data-gps-track="top_nav.click({is_current:false, location:2, destination:8})" 
               aria-controls="" data-controller="" data-s-popover-placement="right">
                    <div class="grid ai-center">
                        <div class="grid--cell truncate">
                            Home
                        </div>
                    </div>
            </a>
        </li>
                <li>
                    <ol class="nav-links">
                            <li class="fs-fine tt-uppercase ml8 mt16 mb4 fc-light">Public</li>

        <li class=" youarehere">
            <a id="nav-questions"
               href="/questions"
               class="pl8 js-gps-track nav-links--link -link__with-icon"
               
               data-gps-track="top_nav.click({is_current:true, location:2, destination:1})" 
               aria-controls="" data-controller="" data-s-popover-placement="right">
<svg aria-hidden="true" class="svg-icon iconGlobe" width="18" height="18" viewBox="0 0 18 18"><path d="M9 1C4.64 1 1 4.64 1 9c0 4.36 3.64 8 8 8 4.36 0 8-3.64 8-8 0-4.36-3.64-8-8-8zM8 15.32a6.46 6.46 0 01-4.3-2.74 6.46 6.46 0 01-.93-5.01L7 11.68v.8c0 .88.12 1.32 1 1.32v1.52zm5.72-2c-.2-.66-1-1.32-1.72-1.32h-1v-2c0-.44-.56-1-1-1H6V7h1c.44 0 1-.56 1-1V5h2c.88 0 1.4-.72 1.4-1.6v-.33a6.45 6.45 0 013.83 4.51 6.45 6.45 0 01-1.51 5.73v.01z"/></svg>                    <span class="-link--channel-name">Questions</span>
            </a>
        </li>

        <li class="">
            <a id="nav-tags"
               href="/tags"
               class=" js-gps-track nav-links--link"
               
               data-gps-track="top_nav.click({is_current:false, location:2, destination:2})" 
               aria-controls="" data-controller="" data-s-popover-placement="right">
                    <div class="grid ai-center">
                        <div class="grid--cell truncate">
                            Tags
                        </div>
                    </div>
            </a>
        </li>
        <li class="">
            <a id="nav-users"
               href="/users"
               class=" js-gps-track nav-links--link"
               
               data-gps-track="top_nav.click({is_current:false, location:2, destination:3})" 
               aria-controls="" data-controller="" data-s-popover-placement="right">
                    <div class="grid ai-center">
                        <div class="grid--cell truncate">
                            Users
                        </div>
                    </div>
            </a>
        </li>
        <li class="">
            <a id="nav-unanswered"
               href="/unanswered"
               class=" js-gps-track nav-links--link"
               
               data-gps-track="top_nav.click({is_current:false, location:2, destination:5})" 
               aria-controls="" data-controller="" data-s-popover-placement="right">
                    <div class="grid ai-center">
                        <div class="grid--cell truncate">
                            Unanswered
                        </div>
                    </div>
            </a>
        </li>
                    </ol>
                </li>
                    <li>
                        <ol class="nav-links">
                                    

<div class="js-freemium-cta ps-relative">

    <div class="fs-fine tt-uppercase ml8 mt16 mb8 fc-light">Teams</div>

    <div class="bt bl bb bc-black-075 p12 pb6 fc-black-600 blr-sm overflow-hidden">
        <strong class="fc-black-750 mb6">Stack Overflow for Teams</strong>
        – Collaborate and share knowledge with a private group.
        
        <img class="wmx100 mx-auto my8 h-auto d-block" width="139" height="114" src="https://cdn.sstatic.net/Img/teams/teams-illo-free-sidebar-promo.svg?v=47faa659a05e" alt="">

        <a href="https://stackoverflow.com/teams/create/free?utm_source=so-owned&amp;utm_medium=side-bar&amp;utm_campaign=campaign-38&amp;utm_content=cta" 
           class="w100 s-btn s-btn__primary s-btn__xs js-gps-track"
           data-gps-track="teams.create.left-sidenav.click({ Action: 6 })"
           data-ga="[&quot;teams left navigation - anonymous&quot;,&quot;left nav free cta&quot;,&quot;stackoverflow.com/teams/create/free&quot;,null,null]">Create a free Team</a>
        <a href="https://stackoverflow.com/teams" 
           class="w100 s-btn s-btn__muted s-btn__xs js-gps-track"
           data-gps-track="teams.create.left-sidenav.click({ Action: 5 })"
           data-ga="[&quot;teams left navigation - anonymous&quot;,&quot;left nav free cta&quot;,&quot;stackoverflow.com/teams&quot;,null,null]">What is Teams?</a>
    </div>
</div>

                                <li class="grid ai-center jc-space-between ml8 mt24 mb4 js-create-team-cta d-none">
                                    <div class="grid--cell tt-uppercase fs-fine fc-light">Teams</div>
                                    <div class="grid--cell fs-fine fc-light mr4">
                                        <a href="javascript:void(0)" class="s-link s-link__inherit js-gps-track"
                                            role="button"
                                            aria-controls="popover-teams-create-cta"
                                            data-controller="s-popover"
                                            data-action="s-popover#toggle"
                                            data-s-popover-placement="bottom-start"
                                            data-s-popover-toggle-class="is-selected"
                                            data-gps-track="teams.create.left-sidenav.click({ Action: ShowInfo })"
                                            data-ga="[&quot;teams left navigation - anonymous&quot;,&quot;left nav show teams info&quot;,null,null,null]">
                                            What&#x2019;s this?
                                        </a>

                                    </div>
                                </li>
                                <li class="ps-relative js-create-team-cta d-none">
                                    <a href="https://stackoverflow.com/teams/create/free?utm_source=so-owned&amp;utm_medium=side-bar&amp;utm_campaign=campaign-38&amp;utm_content=cta"
                                       class="pl8 js-gps-track nav-links--link"
                                       title="Stack Overflow for Teams is a private, secure spot for your organization's questions and answers."
                                       data-gps-track="teams.create.left-sidenav.click({ Action: FreemiumTeamsCreateClick })"
                                       data-ga="[&quot;teams left navigation - anonymous&quot;,&quot;left nav team click&quot;,&quot;stackoverflow.com/teams/create/free&quot;,null,null]">
                                        <div class="grid ai-center">
                                            <div class="grid--cell s-avatar va-middle bg-orange-400">
                                                <div class="s-avatar--letter mtn1">
                                                    <svg aria-hidden="true" class="svg-icon iconBriefcaseSm" width="14" height="14" viewBox="0 0 14 14"><path d="M4 3a1 1 0 011-1h4a1 1 0 011 1v1h.5c.83 0 1.5.67 1.5 1.5v5c0 .83-.67 1.5-1.5 1.5h-7A1.5 1.5 0 012 10.5v-5C2 4.67 2.67 4 3.5 4H4V3zm5 1V3H5v1h4z"/></svg>
                                                </div>
                                                <svg aria-hidden="true" class="native s-avatar--badge svg-icon iconShieldXSm" width="9" height="10" viewBox="0 0 9 10"><path d="M0 1.84L4.5 0 9 1.84v3.17C9 7.53 6.3 10 4.5 10 2.7 10 0 7.53 0 5.01V1.84z" fill="var(--white)"/><path d="M1 2.5L4.5 1 8 2.5v2.51C8 7.34 5.34 9 4.5 9 3.65 9 1 7.34 1 5.01V2.5zm2.98 3.02L3.2 7h2.6l-.78-1.48a.4.4 0 01.15-.38c.34-.24.73-.7.73-1.14 0-.71-.5-1.23-1.41-1.23-.92 0-1.39.52-1.39 1.23 0 .44.4.9.73 1.14.12.08.18.23.15.38z" fill="var(--black-500)"/></svg>
                                            </div>
                                            <div class="grid--cell pl6">
                                                Create free Team
                                            </div>
                                        </div>
                                    </a>
                                </li>
                        </ol>
                    </li>
            </ol>
        </nav>
    </div>



        <div class="s-popover"
             id="popover-teams-create-cta"
             role="menu"
             aria-hidden="true">
            <div class="s-popover--arrow"></div>

            <div class="ps-relative overflow-hidden">
                <p class="mb2"><strong>Teams</strong></p>
                <p class="mb12 fs-caption fc-black-400">Q&amp;A for work</p>
                <p class="mb12 fs-caption fc-medium">Connect and share knowledge within a single location that is structured and easy to search.</p>
                <a href="https://stackoverflow.com/teams"
                   class="js-gps-track s-btn s-btn__primary s-btn__xs"
                   data-gps-track="teams.create.left-sidenav.click({ Action: CtaClick })"
                   data-ga="[&quot;teams left navigation - anonymous&quot;,&quot;left nav cta&quot;,&quot;stackoverflow.com/teams&quot;,null,null]">
                    Learn more
                </a>
            </div>

            <div class="ps-absolute t8 r8">
                <svg aria-hidden="true" class="fc-orange-500 svg-spot spotPeople" width="48" height="48" viewBox="0 0 48 48"><path d="M13.5 28a4.5 4.5 0 100-9 4.5 4.5 0 000 9zM7 30a1 1 0 011-1h11a1 1 0 011 1v5h11v-5a1 1 0 011-1h12a1 1 0 011 1v10a2 2 0 01-2 2H33v5a1 1 0 01-1 1H20a1 1 0 01-1-1v-5H8a1 1 0 01-1-1V30zm25-6.5a4.5 4.5 0 109 0 4.5 4.5 0 00-9 0zM24.5 34a4.5 4.5 0 100-9 4.5 4.5 0 000 9z" opacity=".2"/><path d="M16.4 26.08A6 6 0 107.53 26C5.64 26.06 4 27.52 4 29.45V40a1 1 0 001 1h9a1 1 0 100-2h-4v-7a1 1 0 10-2 0v7H6v-9.55c0-.73.67-1.45 1.64-1.45H16a1 1 0 00.4-1.92zM12 18a4 4 0 110 8 4 4 0 010-8zm16.47 14a6 6 0 10-8.94 0A3.6 3.6 0 0016 35.5V46a1 1 0 001 1h14a1 1 0 001-1V35.5c0-1.94-1.64-3.42-3.53-3.5zM20 28a4 4 0 118 0 4 4 0 01-8 0zm-.3 6h8.6c1 0 1.7.75 1.7 1.5V45h-2v-7a1 1 0 10-2 0v7h-4v-7a1 1 0 10-2 0v7h-2v-9.5c0-.75.7-1.5 1.7-1.5zM42 22c0 1.54-.58 2.94-1.53 4A3.5 3.5 0 0144 29.45V40a1 1 0 01-1 1h-9a1 1 0 110-2h4v-7a1 1 0 112 0v7h2v-9.55A1.5 1.5 0 0040.48 28H32a1 1 0 01-.4-1.92A6 6 0 1142 22zm-2 0a4 4 0 10-8 0 4 4 0 008 0z"/><path d="M17 10a1 1 0 011-1h12a1 1 0 110 2H18a1 1 0 01-1-1zm1-5a1 1 0 100 2h12a1 1 0 100-2H18zm-4-4a1 1 0 00-1 1v12a1 1 0 001 1h5.09l4.2 4.2a1 1 0 001.46-.04l3.7-4.16H34a1 1 0 001-1V2a1 1 0 00-1-1H14zm1 12V3h18v10h-5a1 1 0 00-.75.34l-3.3 3.7-3.74-3.75a1 1 0 00-.71-.29H15z" opacity=".35"/></svg>
            </div>
        </div>

</div>



        <div id="content" class="">

            
<div itemprop="mainEntity" itemscope itemtype="https://schema.org/Question">
    <link itemprop="image" href="https://cdn.sstatic.net/Sites/math/Img/apple-touch-icon.png?v=0ae50baa40ed">

    <div class="inner-content clearfix">

        

            <div id="question-header" class="grid sm:fd-column">
                        <h1 itemprop="name" class="fs-headline1 ow-break-word mb8 grid--cell fl1"><a href="/questions/1627410/proving-trig-identities-complex-numbers" class="question-hyperlink">Proving Trig Identities (Complex Numbers)</a></h1>
                <div class="ml12 aside-cta grid--cell print:d-none sm:ml0 sm:mb12 sm:order-first sm:as-end">
                        <a href="/questions/ask" class="ws-nowrap s-btn s-btn__primary">
        Ask Question
    </a>

                </div>
            </div>
            <div class="grid fw-wrap pb8 mb16 bb bc-black-075">
                    <div class="grid--cell ws-nowrap mr16 mb8" title="2016-01-26 07:23:08Z">
                        <span class="fc-light mr2">Asked</span>
                        <time itemprop="dateCreated" datetime="2016-01-26T07:23:08">5 years, 3 months ago</time>
                    </div>
                    <div class="grid--cell ws-nowrap mr16 mb8">
                        <span class="fc-light mr2">Active</span>
                        <a href="?lastactivity" class="s-link s-link__inherit" title="2016-01-26 11:04:37Z">5 years, 3 months ago</a>
                    </div>
                    <div class="grid--cell ws-nowrap mb8" title="Viewed 3,402 times">
                        <span class="fc-light mr2">Viewed</span>
                        3k times
                    </div>
            </div>
            <div id="mainbar" role="main" aria-label="question and answers">

                
<div class="question" data-questionid="1627410" data-ownerid="298824" data-score="2"  id="question">
    <style>
    </style>
<div class="js-zone-container zone-container-main">
    <div id="dfp-tlb" class="everyonelovesstackoverflow everyoneloves__top-leaderboard everyoneloves__leaderboard"></div>
    <div class="js-report-ad-button-container " style="width: 728px"></div>
</div>

    <div class="post-layout">
        <div class="votecell post-layout--left">
            <div class="js-voting-container grid jc-center fd-column ai-stretch gs4 fc-black-200" data-post-id="1627410">
        <button class="js-vote-up-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This question shows research effort; it is useful and clear" aria-pressed="false" aria-label="Up vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowUpLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 26h32L18 10 2 26z"/></svg></button>
        <div class="js-vote-count grid--cell fc-black-500 fs-title grid fd-column ai-center" itemprop="upvoteCount" data-value="2">2</div>
        <button class="js-vote-down-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This question does not show any research effort; it is unclear or not useful" aria-pressed="false" aria-label="Down vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowDownLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 10h32L18 26 2 10z"/></svg></button>

        <button class="js-bookmark-btn s-btn s-btn__unset c-pointer py4 js-gps-track" 
                data-controller="s-tooltip" data-s-tooltip-placement="right" title="Bookmark this question."
                aria-pressed="false" aria-label="Bookmark" data-selected-classes="fc-yellow-600"
                data-gps-track="post.click({ item: 1, priv: 0, post_type: 1 })">
            <svg aria-hidden="true" class="svg-icon iconBookmark" width="18" height="18" viewBox="0 0 18 18"><path d="M6 1a2 2 0 00-2 2v14l5-4 5 4V3a2 2 0 00-2-2H6zm3.9 3.83h2.9l-2.35 1.7.9 2.77L9 7.59l-2.35 1.7.9-2.76-2.35-1.7h2.9L9 2.06l.9 2.77z"/></svg>
            <div class="js-bookmark-count mt4 d-none" data-value=""></div>
        </button>
    

    
        <a class="js-post-issue grid--cell s-btn s-btn__unset c-pointer py6 mx-auto" href="/posts/1627410/timeline" data-shortcut="T" data-ks-title="timeline" data-controller="s-tooltip" data-s-tooltip-placement="right" title="Show activity on this post." aria-label="Timeline"><svg aria-hidden="true" class="mln2 mr0 svg-icon iconHistory" width="19" height="18" viewBox="0 0 19 18"><path d="M3 9a8 8 0 113.73 6.77L8.2 14.3A6 6 0 105 9l3.01-.01-4 4-4-4h3L3 9zm7-4h1.01L11 9.36l3.22 2.1-.6.93L10 10V5z"/></svg></a>

</div>
        </div>

        

<div class="postcell post-layout--right">
    <span class="d-none">$\begingroup$</span>
    <div class="s-prose js-post-body" itemprop="text">
                
<blockquote>
  <blockquote>
    <p>Question: Prove that if $z = \cos (\theta) + i\sin(\theta)$, then</p>
    
    <p>$$ z^n +  {1\over z^n} = 2\cos(n\theta) $$</p>
    
    <p>Hence prove that $\cos^6(\theta)$ $=$ $\frac 1{32}$$(\cos(6\theta)$ + $6\cos(4\theta)$ + $15\cos(2\theta)$ + $10$)</p>
  </blockquote>
</blockquote>

<p>I learnt to prove the first part in another post <a href="https://math.stackexchange.com/questions/1596764/proving-zn-frac1zn-2-cosn-theta-for-z-cos-theta-i-sin-t">linked here</a>.</p>

<p>The second part is where I am confused because there is a 'hence'</p>

<p>so I thought of taking 2 approaches:</p>

<p>either $$ z^6 + \frac 1{z^6} $$</p>

<p>or $$ z^6 $$ and equating real parts.</p>

<p>I will start with my first approach </p>

<p>$$ z^6 + \frac 1{z^6} $$</p>

<p>$$ (\cos(x)+i\sin(x))^6 + \frac 1{(\cos(x)+i\sin(x))^6} $$</p>

<p>$$ (\cos(x)+i\sin(x))^6 + {(\cos(x)+i\sin(x))^{-6}} $$</p>

<p>$$ \cos(6x) + i\sin(6x) + \cos(-6x)+ i \sin(-6x) $$</p>

<p>$$ 2\cos(6x) $$ </p>

<p>Which is no where near what I am suppose to prove..</p>

<p>So with my second approach (expanding and equation real parts)</p>

<p>$$ z^6 $$ </p>

<p>$$ (\cos(x) + i \sin(x))^6 $$</p>

<p>Using pascals </p>

<p>$$ \cos^6(x) + i*6\cos^5(x)\sin(x) + i^2*15\cos^4(x)\sin^2(x) + i^3*20\cos^3(x)\sin(x) + i^4*15\cos^2(x)\sin^4(x) + i^5*6\cos(x)\sin^5(x) + i^6 * \sin^6(x) $$</p>

<p>Simplifying</p>

<p>$$ \cos^6(x) - 15\cos^4(x)\sin^2(x)+ 15\cos^2(x)\sin^4(x) - \sin^6(x) +i(6\cos^5(x)\sin(x)-20\cos^3(x)\sin(x) + 6cos(x)\sin^5(x)$$</p>

<p>Now considering only real </p>

<p>$$ \cos^6(x) - 15\cos^4(x)\sin^2(x)+ 15\cos^2(x)\sin^4(x) - \sin^6(x) $$</p>

<p>At this point I'm confused , am I on the right approach?</p>
    </div>

        <div class="mt24 mb12">
            <div class="post-taglist grid gs4 gsy fd-column">
                <div class="grid ps-relative">
                    <a href="/questions/tagged/trigonometry" class="post-tag" title="show questions tagged &#39;trigonometry&#39;" rel="tag">trigonometry</a> <a href="/questions/tagged/complex-numbers" class="post-tag" title="show questions tagged &#39;complex-numbers&#39;" rel="tag">complex-numbers</a> 
                </div>
            </div>
        </div>

    <div class="mb0 ">
        <div class="mt16 grid gs8 gsy fw-wrap jc-end ai-start pt4 mb16">
            <div class="grid--cell mr16 fl1 w96">
                

<div class="js-post-menu pt2" data-post-id="1627410">
    <div class="grid d-flex gs8 s-anchors s-anchors__muted fw-wrap">

        <div class="grid--cell">
            <a href="/q/1627410"
               rel="nofollow"
               itemprop="url"
               class="js-share-link js-gps-track"
               title="Short permalink to this question"
               data-gps-track="post.click({ item: 2, priv: 0, post_type: 1 })"
               data-controller="se-share-sheet"
               data-se-share-sheet-title="Share a link to this question"
               data-se-share-sheet-subtitle=""
               data-se-share-sheet-post-type="question"
               data-se-share-sheet-social="facebook twitter "
               data-se-share-sheet-location="1"
               data-se-share-sheet-license-url="https%3a%2f%2fcreativecommons.org%2flicenses%2fby-sa%2f3.0%2f"
               data-se-share-sheet-license-name="CC BY-SA 3.0"
               data-s-popover-placement="bottom-start">Share</a>
        </div>

        <div class="grid--cell">
            <button type="button" class="js-cite-link s-btn s-btn__link">Cite</button>
        </div>


        <div class="grid--cell">
            <button type="button"
                    id="btnFollowPost-1627410" class="s-btn s-btn__link js-follow-post js-follow-question js-gps-track"
                    data-gps-track="post.click({ item: 14, priv: 0, post_type: 1 })"
                    data-controller="s-tooltip " data-s-tooltip-placement="bottom"
                    data-s-popover-placement="bottom" aria-controls=""
                    title="Follow this question to receive notifications">
                Follow
            </button>
        </div>




    </div>
    <div class="js-menu-popup-container"></div>
</div>

            </div>

                <div class="post-signature grid--cell">
<div class="user-info user-hover">
    <div class="user-action-time">
        <a href="/posts/1627410/revisions" title="show all edits to this post"
                         class="js-gps-track"
                         data-gps-track="post.click({ item: 4, priv: 0, post_type: 1 })">edited <span title="2017-04-13 12:20:18Z" class="relativetime">Apr 13 '17 at 12:20</span></a>
    </div>
    <div class="user-gravatar32">
        <a href="/users/-1/community"><div class="gravatar-wrapper-32"><img src="https://www.gravatar.com/avatar/a007be5a61f6aa8f3e85ae2fc18dd66e?s=32&amp;d=identicon&amp;r=PG" alt="" width="32" height="32" class="bar-sm"></div></a>
    </div>
    <div class="user-details">
        <a href="/users/-1/community">Community</a><span class="mod-flair " title="moderator">&#9830;</span>
        <div class="-flair">
            <span class="reputation-score" title="reputation score " dir="ltr">1</span>
        </div>
    </div>
</div>
                </div>
            <div class="post-signature owner grid--cell">
                <div class="user-info user-hover">
    <div class="user-action-time">
        asked <span title="2016-01-26 07:23:08Z" class="relativetime">Jan 26 '16 at 7:23</span>
    </div>
    <div class="user-gravatar32">
        <a href="/users/298824/bigfocalchord"><div class="gravatar-wrapper-32"><img src="https://i.stack.imgur.com/Umvuo.png?s=32&amp;g=1" alt="" width="32" height="32" class="bar-sm"></div></a>
    </div>
    <div class="user-details" itemprop="author" itemscope itemtype="http://schema.org/Person">
        <a href="/users/298824/bigfocalchord">bigfocalchord</a><span class="d-none" itemprop="name">bigfocalchord</span>
        <div class="-flair">
            <span class="reputation-score" title="reputation score " dir="ltr">5,325</span><span title="5 gold badges" aria-hidden="true"><span class="badge1"></span><span class="badgecount">5</span></span><span class="v-visible-sr">5 gold badges</span><span title="27 silver badges" aria-hidden="true"><span class="badge2"></span><span class="badgecount">27</span></span><span class="v-visible-sr">27 silver badges</span><span title="56 bronze badges" aria-hidden="true"><span class="badge3"></span><span class="badgecount">56</span></span><span class="v-visible-sr">56 bronze badges</span>
        </div>
    </div>
</div>


            </div>
        </div>
    </div>
    <span class="d-none">$\endgroup$</span>
</div>




            <span class="d-none" itemprop="commentCount">1</span> 
    <div class="post-layout--right js-post-comments-component">
        <div id="comments-1627410" class="comments js-comments-container bt bc-black-075 mt12 " data-post-id="1627410" data-min-length="15">
            <ul class="comments-list js-comments-list"
                    data-remaining-comments-count="0"
                    data-canpost="false"
                    data-cansee="true"
                    data-comments-unavailable="false"
                    data-addlink-disabled="true">

                        <li id="comment-3318401" class="comment js-comment " data-comment-id="3318401" data-comment-owner-id="206444" data-comment-score="0">
        <div class="js-comment-actions comment-actions">
            <div class="comment-score js-comment-edit-hide">
            </div>
        </div>
        <div class="comment-text  js-comment-text-and-form">
            <div class="comment-body js-comment-edit-hide">
                <span class="d-none">$\begingroup$</span>
                <span class="comment-copy">$\cos(\cdot), \sin(\cdot)$ please. My eyes are burning.</span>
                <span class="d-none">$\endgroup$</span>
&ndash;&nbsp;<a href="/users/206444/lonidard"
                       title="3,771 reputation"
                       class="comment-user">Lonidard</a>
                <span class="comment-date" dir="ltr"><span title="2016-01-26 07:28:13Z, License: CC BY-SA 3.0" class="relativetime-clean">Jan 26 '16 at 7:28</span></span>
            </div>
        </div>
    </li>

            </ul>
	    </div>

        <div id="comments-link-1627410" data-rep=50 data-anon=true>
                    <a class="js-add-link comments-link disabled-link" title="Use comments to ask for more information or suggest improvements. Avoid answering questions in comments."  href="#" role="button">Add a comment</a>
                <span class="js-link-separator dno">&nbsp;|&nbsp;</span>
            <a class="js-show-link comments-link dno" title="Expand to show all comments on this post" href=# onclick="" role="button"></a>
        </div>         
    </div>
    </div>
</div>



                <div id="answers">

                    <a name="tab-top"></a>
                    <div id="answers-header">
                        <div class="answers-subheader grid ai-center mb8">
                            <div class="grid--cell fl1">
                                <h2 class="mb0" data-answercount="4">
                                        4 Answers
                                    <span style="display:none;" itemprop="answerCount">4</span>
                                </h2>
                            </div>
                            <div class="grid--cell">
                                <div class=" grid s-btn-group js-filter-btn">
        <a class="grid--cell s-btn s-btn__muted s-btn__outlined" href="/questions/1627410/proving-trig-identities-complex-numbers?answertab=active#tab-top" data-nav-xhref="" title="Answers with the latest activity first" data-value="active" data-shortcut="A">
            Active</a>
        <a class="grid--cell s-btn s-btn__muted s-btn__outlined" href="/questions/1627410/proving-trig-identities-complex-numbers?answertab=oldest#tab-top" data-nav-xhref="" title="Answers in the order they were provided" data-value="oldest" data-shortcut="O">
            Oldest</a>
        <a class="youarehere is-selected grid--cell s-btn s-btn__muted s-btn__outlined" href="/questions/1627410/proving-trig-identities-complex-numbers?answertab=votes#tab-top" data-nav-xhref="" title="Answers with the highest score first" data-value="votes" data-shortcut="V">
            Votes</a>
</div>

                            </div>
                        </div>
                    </div>


                                          
<a name="1627421"></a>
<div id="answer-1627421" class="answer accepted-answer" data-answerid="1627421" data-ownerid="33337" data-score="5" itemprop="acceptedAnswer" itemscope itemtype="https://schema.org/Answer">
    <div class="post-layout">
        <div class="votecell post-layout--left">
            <div class="js-voting-container grid jc-center fd-column ai-stretch gs4 fc-black-200" data-post-id="1627421">
        <button class="js-vote-up-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is useful" aria-pressed="false" aria-label="Up vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowUpLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 26h32L18 10 2 26z"/></svg></button>
        <div class="js-vote-count grid--cell fc-black-500 fs-title grid fd-column ai-center" itemprop="upvoteCount" data-value="5">5</div>
        <button class="js-vote-down-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is not useful" aria-pressed="false" aria-label="Down vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowDownLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 10h32L18 26 2 10z"/></svg></button>

    
            <div class="js-accepted-answer-indicator grid--cell fc-green-500 py6 mtn8" data-s-tooltip-placement="right" title="Loading when this answer was accepted&#x2026;" tabindex="0" role="note" aria-label="Accepted">
                <div class="ta-center">
                    <svg aria-hidden="true" class="svg-icon iconCheckmarkLg" width="36" height="36" viewBox="0 0 36 36"><path d="M6 14l8 8L30 6v8L14 30l-8-8v-8z"/></svg>
                </div>
            </div>

    
        <a class="js-post-issue grid--cell s-btn s-btn__unset c-pointer py6 mx-auto" href="/posts/1627421/timeline" data-shortcut="T" data-ks-title="timeline" data-controller="s-tooltip" data-s-tooltip-placement="right" title="Show activity on this post." aria-label="Timeline"><svg aria-hidden="true" class="mln2 mr0 svg-icon iconHistory" width="19" height="18" viewBox="0 0 19 18"><path d="M3 9a8 8 0 113.73 6.77L8.2 14.3A6 6 0 105 9l3.01-.01-4 4-4-4h3L3 9zm7-4h1.01L11 9.36l3.22 2.1-.6.93L10 10V5z"/></svg></a>

</div>
        </div>

        

<div class="answercell post-layout--right">
    <span class="d-none">$\begingroup$</span>
    <div class="s-prose js-post-body" itemprop="text">
<p>$n=1\implies2\cos x=z+\dfrac1z$</p>

<p>$$\cos^6x=\left(\dfrac{z+\dfrac1z}2\right)^6$$</p>

<p>$$64\cos^6x=\left(z+\dfrac1z\right)^6=z^6+\dfrac1{z^6}+\binom61\left(z^4+\dfrac1{z^4}\right)+\binom62\left(z^2+\dfrac1{z^2}\right)+\binom63$$</p>

<p>Can you take it from here?</p>
    </div>
    <div class="mt24">
        <div class="grid fw-wrap ai-start jc-end gs8 gsy">
            <time itemprop="dateCreated" datetime="2016-01-26T07:37:17"></time>
            <div class="grid--cell mr16" style="flex: 1 1 100px;">
                

<div class="js-post-menu pt2" data-post-id="1627421">
    <div class="grid d-flex gs8 s-anchors s-anchors__muted fw-wrap">

        <div class="grid--cell">
            <a href="/a/1627421"
               rel="nofollow"
               itemprop="url"
               class="js-share-link js-gps-track"
               title="Short permalink to this answer"
               data-gps-track="post.click({ item: 2, priv: 0, post_type: 2 })"
               data-controller="se-share-sheet"
               data-se-share-sheet-title="Share a link to this answer"
               data-se-share-sheet-subtitle=""
               data-se-share-sheet-post-type="answer"
               data-se-share-sheet-social="facebook twitter "
               data-se-share-sheet-location="2"
               data-se-share-sheet-license-url="https%3a%2f%2fcreativecommons.org%2flicenses%2fby-sa%2f3.0%2f"
               data-se-share-sheet-license-name="CC BY-SA 3.0"
               data-s-popover-placement="bottom-start">Share</a>
        </div>

        <div class="grid--cell">
            <button type="button" class="js-cite-link s-btn s-btn__link">Cite</button>
        </div>


        <div class="grid--cell">
            <button type="button"
                    id="btnFollowPost-1627421" class="s-btn s-btn__link js-follow-post js-follow-answer js-gps-track"
                    data-gps-track="post.click({ item: 14, priv: 0, post_type: 2 })"
                    data-controller="s-tooltip " data-s-tooltip-placement="bottom"
                    data-s-popover-placement="bottom" aria-controls=""
                    title="Follow this answer to receive notifications">
                Follow
            </button>
        </div>




    </div>
    <div class="js-menu-popup-container"></div>
</div>

            </div>


            <div class="post-signature grid--cell fl0">
                <div class="user-info user-hover">
    <div class="user-action-time">
        answered <span title="2016-01-26 07:37:17Z" class="relativetime">Jan 26 '16 at 7:37</span>
    </div>
    <div class="user-gravatar32">
        <a href="/users/33337/lab-bhattacharjee"><div class="gravatar-wrapper-32"><img src="https://www.gravatar.com/avatar/f7b714927f899c4a5d50033bfbc7c0e5?s=32&amp;d=identicon&amp;r=PG" alt="" width="32" height="32" class="bar-sm"></div></a>
    </div>
    <div class="user-details" itemprop="author" itemscope itemtype="http://schema.org/Person">
        <a href="/users/33337/lab-bhattacharjee">lab bhattacharjee</a><span class="d-none" itemprop="name">lab bhattacharjee</span>
        <div class="-flair">
            <span class="reputation-score" title="reputation score 264,724" dir="ltr">265k</span><span title="17 gold badges" aria-hidden="true"><span class="badge1"></span><span class="badgecount">17</span></span><span class="v-visible-sr">17 gold badges</span><span title="189 silver badges" aria-hidden="true"><span class="badge2"></span><span class="badgecount">189</span></span><span class="v-visible-sr">189 silver badges</span><span title="302 bronze badges" aria-hidden="true"><span class="badge3"></span><span class="badgecount">302</span></span><span class="v-visible-sr">302 bronze badges</span>
        </div>
    </div>
</div>


            </div>
        </div>
    </div>
    <span class="d-none">$\endgroup$</span>
</div>




            <span class="d-none" itemprop="commentCount">3</span> 
    <div class="post-layout--right js-post-comments-component">
        <div id="comments-1627421" class="comments js-comments-container bt bc-black-075 mt12 " data-post-id="1627421" data-min-length="15">
            <ul class="comments-list js-comments-list"
                    data-remaining-comments-count="0"
                    data-canpost="false"
                    data-cansee="true"
                    data-comments-unavailable="false"
                    data-addlink-disabled="true">

                        <li id="comment-3318423" class="comment js-comment " data-comment-id="3318423" data-comment-owner-id="298824" data-comment-score="0">
        <div class="js-comment-actions comment-actions">
            <div class="comment-score js-comment-edit-hide">
            </div>
        </div>
        <div class="comment-text  js-comment-text-and-form">
            <div class="comment-body js-comment-edit-hide">
                <span class="d-none">$\begingroup$</span>
                <span class="comment-copy">why did you divide the whole expression by 2?</span>
                <span class="d-none">$\endgroup$</span>
&ndash;&nbsp;<a href="/users/298824/bigfocalchord"
                       title="5,325 reputation"
                       class="comment-user owner">bigfocalchord</a>
                <span class="comment-date" dir="ltr"><span title="2016-01-26 07:40:16Z, License: CC BY-SA 3.0" class="relativetime-clean">Jan 26 '16 at 7:40</span></span>
            </div>
        </div>
    </li>
    <li id="comment-3318434" class="comment js-comment " data-comment-id="3318434" data-comment-owner-id="232145" data-comment-score="0">
        <div class="js-comment-actions comment-actions">
            <div class="comment-score js-comment-edit-hide">
            </div>
        </div>
        <div class="comment-text  js-comment-text-and-form">
            <div class="comment-body js-comment-edit-hide">
                <span class="d-none">$\begingroup$</span>
                <span class="comment-copy">@dydxx because we get $2 \cos nx$ everytime. expannd yourself and see.$$e^{in\theta}+e^{-in\theta} = 2 \cos n \theta$$</span>
                <span class="d-none">$\endgroup$</span>
&ndash;&nbsp;<a href="/users/232145/max-payne"
                       title="3,207 reputation"
                       class="comment-user">Max Payne</a>
                <span class="comment-date" dir="ltr"><span title="2016-01-26 07:45:13Z, License: CC BY-SA 3.0" class="relativetime-clean">Jan 26 '16 at 7:45</span></span>
                        <span title="this comment was edited 4 times">
                            <svg aria-hidden="true" class="va-text-bottom o50 svg-icon iconPencilSm" width="14" height="14" viewBox="0 0 14 14"><path d="M11.1 1.71l1.13 1.12c.2.2.2.51 0 .71L11.1 4.7 9.21 2.86l1.17-1.15c.2-.2.51-.2.71 0zM2 10.12l6.37-6.43 1.88 1.88L3.88 12H2v-1.88z"/></svg>
                        </span>
            </div>
        </div>
    </li>
    <li id="comment-3318512" class="comment js-comment " data-comment-id="3318512" data-comment-owner-id="298824" data-comment-score="0">
        <div class="js-comment-actions comment-actions">
            <div class="comment-score js-comment-edit-hide">
            </div>
        </div>
        <div class="comment-text  js-comment-text-and-form">
            <div class="comment-body js-comment-edit-hide">
                <span class="d-none">$\begingroup$</span>
                <span class="comment-copy">Ah I see now , thanks!</span>
                <span class="d-none">$\endgroup$</span>
&ndash;&nbsp;<a href="/users/298824/bigfocalchord"
                       title="5,325 reputation"
                       class="comment-user owner">bigfocalchord</a>
                <span class="comment-date" dir="ltr"><span title="2016-01-26 08:19:58Z, License: CC BY-SA 3.0" class="relativetime-clean">Jan 26 '16 at 8:19</span></span>
            </div>
        </div>
    </li>

            </ul>
	    </div>

        <div id="comments-link-1627421" data-rep=50 data-anon=true>
                    <a class="js-add-link comments-link disabled-link" title="Use comments to ask for more information or suggest improvements. Avoid comments like &#x201C;&#x2B;1&#x201D; or &#x201C;thanks&#x201D;."  href="#" role="button">Add a comment</a>
                <span class="js-link-separator dno">&nbsp;|&nbsp;</span>
            <a class="js-show-link comments-link dno" title="Expand to show all comments on this post" href=# onclick="" role="button"></a>
        </div>         
    </div>
    </div>
</div>
<div class="js-zone-container zone-container-main">
    <div id="dfp-mlb" class="everyonelovesstackoverflow everyoneloves__mid-leaderboard everyoneloves__leaderboard"></div>
    <div class="js-report-ad-button-container " style="width: 728px"></div>
</div>
                                          
<a name="1627444"></a>
<div id="answer-1627444" class="answer" data-answerid="1627444" data-ownerid="280637" data-score="4" itemprop="suggestedAnswer" itemscope itemtype="https://schema.org/Answer">
    <div class="post-layout">
        <div class="votecell post-layout--left">
            <div class="js-voting-container grid jc-center fd-column ai-stretch gs4 fc-black-200" data-post-id="1627444">
        <button class="js-vote-up-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is useful" aria-pressed="false" aria-label="Up vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowUpLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 26h32L18 10 2 26z"/></svg></button>
        <div class="js-vote-count grid--cell fc-black-500 fs-title grid fd-column ai-center" itemprop="upvoteCount" data-value="4">4</div>
        <button class="js-vote-down-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is not useful" aria-pressed="false" aria-label="Down vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowDownLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 10h32L18 26 2 10z"/></svg></button>

    
            <div class="js-accepted-answer-indicator grid--cell fc-green-500 py6 mtn8 d-none" data-s-tooltip-placement="right" title="Loading when this answer was accepted&#x2026;" tabindex="0" role="note" aria-label="Accepted">
                <div class="ta-center">
                    <svg aria-hidden="true" class="svg-icon iconCheckmarkLg" width="36" height="36" viewBox="0 0 36 36"><path d="M6 14l8 8L30 6v8L14 30l-8-8v-8z"/></svg>
                </div>
            </div>

    
        <a class="js-post-issue grid--cell s-btn s-btn__unset c-pointer py6 mx-auto" href="/posts/1627444/timeline" data-shortcut="T" data-ks-title="timeline" data-controller="s-tooltip" data-s-tooltip-placement="right" title="Show activity on this post." aria-label="Timeline"><svg aria-hidden="true" class="mln2 mr0 svg-icon iconHistory" width="19" height="18" viewBox="0 0 19 18"><path d="M3 9a8 8 0 113.73 6.77L8.2 14.3A6 6 0 105 9l3.01-.01-4 4-4-4h3L3 9zm7-4h1.01L11 9.36l3.22 2.1-.6.93L10 10V5z"/></svg></a>

</div>
        </div>

        

<div class="answercell post-layout--right">
    <span class="d-none">$\begingroup$</span>
    <div class="s-prose js-post-body" itemprop="text">
<p>By De Moivre's formula if $z = \cos (\theta) + i\sin(\theta)$ then $z^n = \cos (n\theta) + i\sin(n\theta)$.</p>

<p>So $$z^n = \cos (n\theta) + i\sin(n\theta)$$ </p>

<p>and </p>

<p>$$z^{-n} = \cos (-n\theta) + i\sin(-n\theta)=\cos (n\theta) - i\sin(n\theta)$$</p>

<p>So $$z^n+z^{-n}=2\cos (n\theta)$$</p>

<p>Thus when $n=1$ , </p>

<p>$$z+z^{-1}=2\cos (\theta) \Rightarrow \left(z+\frac{1}{z} \right)^6=2^6 \cdot \cos^6(\theta) $$ </p>

<p>$$2^6 \cdot \cos^6(\theta)=\left(z+\frac{1}{z} \right)^6 $$ </p>

<p>$$2^6 \cdot \cos^6(\theta)=z^6+6z^4+15z^2+20+15+\frac{1}{z^2} +6\frac{1}{z^4} +\frac{1}{z^6}  $$ </p>

<p>$$2^6 \cdot \cos^6(\theta)=\left(z^6+\frac{1}{z^6}\right)+6\left(z^4+\frac{1}{z^4}\right)+15\left(z^2+\frac{1}{z^2}\right)+20 $$</p>

<p>$$64 \cdot \cos^6(\theta)=\left(2\cos 6\theta \right)+6\left(2\cos 4\theta\right)+15\left(2\cos 2\theta\right)+20 $$</p>

<p>Therefore </p>

<p>$$  \cos^6(\theta)=\frac{1}{32}\{\left(\cos 6\theta \right)+6\left(\cos 4\theta\right)+15\left(\cos 2\theta\right)+10 \}$$</p>
    </div>
    <div class="mt24">
        <div class="grid fw-wrap ai-start jc-end gs8 gsy">
            <time itemprop="dateCreated" datetime="2016-01-26T08:13:08"></time>
            <div class="grid--cell mr16" style="flex: 1 1 100px;">
                

<div class="js-post-menu pt2" data-post-id="1627444">
    <div class="grid d-flex gs8 s-anchors s-anchors__muted fw-wrap">

        <div class="grid--cell">
            <a href="/a/1627444"
               rel="nofollow"
               itemprop="url"
               class="js-share-link js-gps-track"
               title="Short permalink to this answer"
               data-gps-track="post.click({ item: 2, priv: 0, post_type: 2 })"
               data-controller="se-share-sheet"
               data-se-share-sheet-title="Share a link to this answer"
               data-se-share-sheet-subtitle=""
               data-se-share-sheet-post-type="answer"
               data-se-share-sheet-social="facebook twitter "
               data-se-share-sheet-location="2"
               data-se-share-sheet-license-url="https%3a%2f%2fcreativecommons.org%2flicenses%2fby-sa%2f3.0%2f"
               data-se-share-sheet-license-name="CC BY-SA 3.0"
               data-s-popover-placement="bottom-start">Share</a>
        </div>

        <div class="grid--cell">
            <button type="button" class="js-cite-link s-btn s-btn__link">Cite</button>
        </div>


        <div class="grid--cell">
            <button type="button"
                    id="btnFollowPost-1627444" class="s-btn s-btn__link js-follow-post js-follow-answer js-gps-track"
                    data-gps-track="post.click({ item: 14, priv: 0, post_type: 2 })"
                    data-controller="s-tooltip " data-s-tooltip-placement="bottom"
                    data-s-popover-placement="bottom" aria-controls=""
                    title="Follow this answer to receive notifications">
                Follow
            </button>
        </div>




    </div>
    <div class="js-menu-popup-container"></div>
</div>

            </div>


            <div class="post-signature grid--cell fl0">
                <div class="user-info ">
    <div class="user-action-time">
        answered <span title="2016-01-26 08:13:08Z" class="relativetime">Jan 26 '16 at 8:13</span>
    </div>
    <div class="user-gravatar32">
        <a href="/users/280637/angelo-mark"><div class="gravatar-wrapper-32"><img src="https://i.stack.imgur.com/wTQtA.jpg?s=32&amp;g=1" alt="" width="32" height="32" class="bar-sm"></div></a>
    </div>
    <div class="user-details" itemprop="author" itemscope itemtype="http://schema.org/Person">
        <a href="/users/280637/angelo-mark">Angelo Mark</a><span class="d-none" itemprop="name">Angelo Mark</span>
        <div class="-flair">
            <span class="reputation-score" title="reputation score " dir="ltr">5,668</span><span title="4 gold badges" aria-hidden="true"><span class="badge1"></span><span class="badgecount">4</span></span><span class="v-visible-sr">4 gold badges</span><span title="23 silver badges" aria-hidden="true"><span class="badge2"></span><span class="badgecount">23</span></span><span class="v-visible-sr">23 silver badges</span><span title="47 bronze badges" aria-hidden="true"><span class="badge3"></span><span class="badgecount">47</span></span><span class="v-visible-sr">47 bronze badges</span>
        </div>
    </div>
</div>


            </div>
        </div>
    </div>
    <span class="d-none">$\endgroup$</span>
</div>




            <span class="d-none" itemprop="commentCount"></span> 
    <div class="post-layout--right js-post-comments-component">
        <div id="comments-1627444" class="comments js-comments-container bt bc-black-075 mt12  dno" data-post-id="1627444" data-min-length="15">
            <ul class="comments-list js-comments-list"
                    data-remaining-comments-count="0"
                    data-canpost="false"
                    data-cansee="true"
                    data-comments-unavailable="false"
                    data-addlink-disabled="true">

            </ul>
	    </div>

        <div id="comments-link-1627444" data-rep=50 data-anon=true>
                    <a class="js-add-link comments-link disabled-link" title="Use comments to ask for more information or suggest improvements. Avoid comments like &#x201C;&#x2B;1&#x201D; or &#x201C;thanks&#x201D;."  href="#" role="button">Add a comment</a>
                <span class="js-link-separator dno">&nbsp;|&nbsp;</span>
            <a class="js-show-link comments-link dno" title="Expand to show all comments on this post" href=# onclick="" role="button"></a>
        </div>         
    </div>
    </div>
</div>
                                          
<a name="1627548"></a>
<div id="answer-1627548" class="answer" data-answerid="1627548" data-ownerid="202857" data-score="2" itemprop="suggestedAnswer" itemscope itemtype="https://schema.org/Answer">
    <div class="post-layout">
        <div class="votecell post-layout--left">
            <div class="js-voting-container grid jc-center fd-column ai-stretch gs4 fc-black-200" data-post-id="1627548">
        <button class="js-vote-up-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is useful" aria-pressed="false" aria-label="Up vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowUpLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 26h32L18 10 2 26z"/></svg></button>
        <div class="js-vote-count grid--cell fc-black-500 fs-title grid fd-column ai-center" itemprop="upvoteCount" data-value="2">2</div>
        <button class="js-vote-down-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is not useful" aria-pressed="false" aria-label="Down vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowDownLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 10h32L18 26 2 10z"/></svg></button>

    
            <div class="js-accepted-answer-indicator grid--cell fc-green-500 py6 mtn8 d-none" data-s-tooltip-placement="right" title="Loading when this answer was accepted&#x2026;" tabindex="0" role="note" aria-label="Accepted">
                <div class="ta-center">
                    <svg aria-hidden="true" class="svg-icon iconCheckmarkLg" width="36" height="36" viewBox="0 0 36 36"><path d="M6 14l8 8L30 6v8L14 30l-8-8v-8z"/></svg>
                </div>
            </div>

    
        <a class="js-post-issue grid--cell s-btn s-btn__unset c-pointer py6 mx-auto" href="/posts/1627548/timeline" data-shortcut="T" data-ks-title="timeline" data-controller="s-tooltip" data-s-tooltip-placement="right" title="Show activity on this post." aria-label="Timeline"><svg aria-hidden="true" class="mln2 mr0 svg-icon iconHistory" width="19" height="18" viewBox="0 0 19 18"><path d="M3 9a8 8 0 113.73 6.77L8.2 14.3A6 6 0 105 9l3.01-.01-4 4-4-4h3L3 9zm7-4h1.01L11 9.36l3.22 2.1-.6.93L10 10V5z"/></svg></a>

</div>
        </div>

        

<div class="answercell post-layout--right">
    <span class="d-none">$\begingroup$</span>
    <div class="s-prose js-post-body" itemprop="text">
<p>This is simply because for such a $z$, $\;\frac1{z^n}=\bar z^n=\overline{z^n}$, and
$$z^n+\overline{z^n}=2\operatorname{Re}(z^n)=2\cos n\theta\qquad\quad\text{by De Moivre's formula.}$$</p>
    </div>
    <div class="mt24">
        <div class="grid fw-wrap ai-start jc-end gs8 gsy">
            <time itemprop="dateCreated" datetime="2016-01-26T10:51:54"></time>
            <div class="grid--cell mr16" style="flex: 1 1 100px;">
                

<div class="js-post-menu pt2" data-post-id="1627548">
    <div class="grid d-flex gs8 s-anchors s-anchors__muted fw-wrap">

        <div class="grid--cell">
            <a href="/a/1627548"
               rel="nofollow"
               itemprop="url"
               class="js-share-link js-gps-track"
               title="Short permalink to this answer"
               data-gps-track="post.click({ item: 2, priv: 0, post_type: 2 })"
               data-controller="se-share-sheet"
               data-se-share-sheet-title="Share a link to this answer"
               data-se-share-sheet-subtitle=""
               data-se-share-sheet-post-type="answer"
               data-se-share-sheet-social="facebook twitter "
               data-se-share-sheet-location="2"
               data-se-share-sheet-license-url="https%3a%2f%2fcreativecommons.org%2flicenses%2fby-sa%2f3.0%2f"
               data-se-share-sheet-license-name="CC BY-SA 3.0"
               data-s-popover-placement="bottom-start">Share</a>
        </div>

        <div class="grid--cell">
            <button type="button" class="js-cite-link s-btn s-btn__link">Cite</button>
        </div>


        <div class="grid--cell">
            <button type="button"
                    id="btnFollowPost-1627548" class="s-btn s-btn__link js-follow-post js-follow-answer js-gps-track"
                    data-gps-track="post.click({ item: 14, priv: 0, post_type: 2 })"
                    data-controller="s-tooltip " data-s-tooltip-placement="bottom"
                    data-s-popover-placement="bottom" aria-controls=""
                    title="Follow this answer to receive notifications">
                Follow
            </button>
        </div>




    </div>
    <div class="js-menu-popup-container"></div>
</div>

            </div>


            <div class="post-signature grid--cell fl0">
                <div class="user-info ">
    <div class="user-action-time">
        answered <span title="2016-01-26 10:51:54Z" class="relativetime">Jan 26 '16 at 10:51</span>
    </div>
    <div class="user-gravatar32">
        <a href="/users/202857/bernard"><div class="gravatar-wrapper-32"><img src="https://www.gravatar.com/avatar/d0bf9f12edb2f10a7e5518404b7ce863?s=32&amp;d=identicon&amp;r=PG&amp;f=1" alt="" width="32" height="32" class="bar-sm"></div></a>
    </div>
    <div class="user-details" itemprop="author" itemscope itemtype="http://schema.org/Person">
        <a href="/users/202857/bernard">Bernard</a><span class="d-none" itemprop="name">Bernard</span>
        <div class="-flair">
            <span class="reputation-score" title="reputation score 164,922" dir="ltr">165k</span><span title="9 gold badges" aria-hidden="true"><span class="badge1"></span><span class="badgecount">9</span></span><span class="v-visible-sr">9 gold badges</span><span title="58 silver badges" aria-hidden="true"><span class="badge2"></span><span class="badgecount">58</span></span><span class="v-visible-sr">58 silver badges</span><span title="152 bronze badges" aria-hidden="true"><span class="badge3"></span><span class="badgecount">152</span></span><span class="v-visible-sr">152 bronze badges</span>
        </div>
    </div>
</div>


            </div>
        </div>
    </div>
    <span class="d-none">$\endgroup$</span>
</div>




            <span class="d-none" itemprop="commentCount"></span> 
    <div class="post-layout--right js-post-comments-component">
        <div id="comments-1627548" class="comments js-comments-container bt bc-black-075 mt12  dno" data-post-id="1627548" data-min-length="15">
            <ul class="comments-list js-comments-list"
                    data-remaining-comments-count="0"
                    data-canpost="false"
                    data-cansee="true"
                    data-comments-unavailable="false"
                    data-addlink-disabled="true">

            </ul>
	    </div>

        <div id="comments-link-1627548" data-rep=50 data-anon=true>
                    <a class="js-add-link comments-link disabled-link" title="Use comments to ask for more information or suggest improvements. Avoid comments like &#x201C;&#x2B;1&#x201D; or &#x201C;thanks&#x201D;."  href="#" role="button">Add a comment</a>
                <span class="js-link-separator dno">&nbsp;|&nbsp;</span>
            <a class="js-show-link comments-link dno" title="Expand to show all comments on this post" href=# onclick="" role="button"></a>
        </div>         
    </div>
    </div>
</div>
<div class="js-zone-container zone-container-main">
    <div id="dfp-smlb" class="everyonelovesstackoverflow everyoneloves__mid-second-leaderboard everyoneloves__leaderboard"></div>
    <div class="js-report-ad-button-container " style="width: 728px"></div>
</div>
                                          
<a name="1627557"></a>
<div id="answer-1627557" class="answer" data-answerid="1627557" data-ownerid="62967" data-score="1" itemprop="suggestedAnswer" itemscope itemtype="https://schema.org/Answer">
    <div class="post-layout">
        <div class="votecell post-layout--left">
            <div class="js-voting-container grid jc-center fd-column ai-stretch gs4 fc-black-200" data-post-id="1627557">
        <button class="js-vote-up-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is useful" aria-pressed="false" aria-label="Up vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowUpLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 26h32L18 10 2 26z"/></svg></button>
        <div class="js-vote-count grid--cell fc-black-500 fs-title grid fd-column ai-center" itemprop="upvoteCount" data-value="1">1</div>
        <button class="js-vote-down-btn grid--cell s-btn s-btn__unset c-pointer" data-controller="s-tooltip" data-s-tooltip-placement="right" title="This answer is not useful" aria-pressed="false" aria-label="Down vote" data-selected-classes="fc-theme-primary"><svg aria-hidden="true" class="m0 svg-icon iconArrowDownLg" width="36" height="36" viewBox="0 0 36 36"><path d="M2 10h32L18 26 2 10z"/></svg></button>

    
            <div class="js-accepted-answer-indicator grid--cell fc-green-500 py6 mtn8 d-none" data-s-tooltip-placement="right" title="Loading when this answer was accepted&#x2026;" tabindex="0" role="note" aria-label="Accepted">
                <div class="ta-center">
                    <svg aria-hidden="true" class="svg-icon iconCheckmarkLg" width="36" height="36" viewBox="0 0 36 36"><path d="M6 14l8 8L30 6v8L14 30l-8-8v-8z"/></svg>
                </div>
            </div>

    
        <a class="js-post-issue grid--cell s-btn s-btn__unset c-pointer py6 mx-auto" href="/posts/1627557/timeline" data-shortcut="T" data-ks-title="timeline" data-controller="s-tooltip" data-s-tooltip-placement="right" title="Show activity on this post." aria-label="Timeline"><svg aria-hidden="true" class="mln2 mr0 svg-icon iconHistory" width="19" height="18" viewBox="0 0 19 18"><path d="M3 9a8 8 0 113.73 6.77L8.2 14.3A6 6 0 105 9l3.01-.01-4 4-4-4h3L3 9zm7-4h1.01L11 9.36l3.22 2.1-.6.93L10 10V5z"/></svg></a>

</div>
        </div>

        

<div class="answercell post-layout--right">
    <span class="d-none">$\begingroup$</span>
    <div class="s-prose js-post-body" itemprop="text">
<p>I don't think that the hint is really that useful. It would be better to do
$$
\cos\theta=\frac{e^{i\theta}+e^{-i\theta}}{2}
$$
that gives you
\begin{align}
64\cos^6\theta
&amp;=(e^{i\theta}+e^{-i\theta})^6 \\[3px]
&amp;=e^{6i\theta}+6e^{4i\theta}+15e^{2i\theta}
  +20+15e^{-2i\theta}+6e^{-4i\theta}+e^{-6i\theta} \\[3px]
&amp;=(e^{6i\theta}+e^{-6i\theta})+
  6(e^{4i\theta}+e^{-4i\theta})+
  15(e^{2i\theta}+e^{-2i\theta})+
  20 \\[3px]
&amp;=2\cos6\theta+12\cos4\theta+30\cos2\theta+20
\end{align}
This is no more than De Moivre’s formula in disguise, but much easier to manage.</p>
    </div>
    <div class="mt24">
        <div class="grid fw-wrap ai-start jc-end gs8 gsy">
            <time itemprop="dateCreated" datetime="2016-01-26T11:04:37"></time>
            <div class="grid--cell mr16" style="flex: 1 1 100px;">
                

<div class="js-post-menu pt2" data-post-id="1627557">
    <div class="grid d-flex gs8 s-anchors s-anchors__muted fw-wrap">

        <div class="grid--cell">
            <a href="/a/1627557"
               rel="nofollow"
               itemprop="url"
               class="js-share-link js-gps-track"
               title="Short permalink to this answer"
               data-gps-track="post.click({ item: 2, priv: 0, post_type: 2 })"
               data-controller="se-share-sheet"
               data-se-share-sheet-title="Share a link to this answer"
               data-se-share-sheet-subtitle=""
               data-se-share-sheet-post-type="answer"
               data-se-share-sheet-social="facebook twitter "
               data-se-share-sheet-location="2"
               data-se-share-sheet-license-url="https%3a%2f%2fcreativecommons.org%2flicenses%2fby-sa%2f3.0%2f"
               data-se-share-sheet-license-name="CC BY-SA 3.0"
               data-s-popover-placement="bottom-start">Share</a>
        </div>

        <div class="grid--cell">
            <button type="button" class="js-cite-link s-btn s-btn__link">Cite</button>
        </div>


        <div class="grid--cell">
            <button type="button"
                    id="btnFollowPost-1627557" class="s-btn s-btn__link js-follow-post js-follow-answer js-gps-track"
                    data-gps-track="post.click({ item: 14, priv: 0, post_type: 2 })"
                    data-controller="s-tooltip " data-s-tooltip-placement="bottom"
                    data-s-popover-placement="bottom" aria-controls=""
                    title="Follow this answer to receive notifications">
                Follow
            </button>
        </div>




    </div>
    <div class="js-menu-popup-container"></div>
</div>

            </div>


            <div class="post-signature grid--cell fl0">
                <div class="user-info user-hover">
    <div class="user-action-time">
        answered <span title="2016-01-26 11:04:37Z" class="relativetime">Jan 26 '16 at 11:04</span>
    </div>
    <div class="user-gravatar32">
        <a href="/users/62967/egreg"><div class="gravatar-wrapper-32"><img src="https://i.stack.imgur.com/wJWMb.png?s=32&amp;g=1" alt="" width="32" height="32" class="bar-sm"></div></a>
    </div>
    <div class="user-details" itemprop="author" itemscope itemtype="http://schema.org/Person">
        <a href="/users/62967/egreg">egreg</a><span class="d-none" itemprop="name">egreg</span>
        <div class="-flair">
            <span class="reputation-score" title="reputation score 216,581" dir="ltr">217k</span><span title="17 gold badges" aria-hidden="true"><span class="badge1"></span><span class="badgecount">17</span></span><span class="v-visible-sr">17 gold badges</span><span title="117 silver badges" aria-hidden="true"><span class="badge2"></span><span class="badgecount">117</span></span><span class="v-visible-sr">117 silver badges</span><span title="280 bronze badges" aria-hidden="true"><span class="badge3"></span><span class="badgecount">280</span></span><span class="v-visible-sr">280 bronze badges</span>
        </div>
    </div>
</div>


            </div>
        </div>
    </div>
    <span class="d-none">$\endgroup$</span>
</div>




            <span class="d-none" itemprop="commentCount"></span> 
    <div class="post-layout--right js-post-comments-component">
        <div id="comments-1627557" class="comments js-comments-container bt bc-black-075 mt12  dno" data-post-id="1627557" data-min-length="15">
            <ul class="comments-list js-comments-list"
                    data-remaining-comments-count="0"
                    data-canpost="false"
                    data-cansee="true"
                    data-comments-unavailable="false"
                    data-addlink-disabled="true">

            </ul>
	    </div>

        <div id="comments-link-1627557" data-rep=50 data-anon=true>
                    <a class="js-add-link comments-link disabled-link" title="Use comments to ask for more information or suggest improvements. Avoid comments like &#x201C;&#x2B;1&#x201D; or &#x201C;thanks&#x201D;."  href="#" role="button">Add a comment</a>
                <span class="js-link-separator dno">&nbsp;|&nbsp;</span>
            <a class="js-show-link comments-link dno" title="Expand to show all comments on this post" href=# onclick="" role="button"></a>
        </div>         
    </div>
    </div>
</div>

                        <a name='new-answer'></a>
                            <form id="post-form" action="/questions/1627410/answer/submit" method="post" class="js-add-answer-component post-form">
                                <input type="hidden" id="post-id" value="1627410" />
                                <input type="hidden" id="qualityBanWarningShown" name="qualityBanWarningShown" value="false" />
                                <input type="hidden" name="referrer" value="https://www.google.com/" />
                                <h2 class="space">
                                    Your Answer
                                </h2>
                                    



<script>
    StackExchange.ready(function() {
        var channelOptions = {
            tags: "".split(" "),
            id: "69"
        };
        initTagRenderer("".split(" "), "".split(" "), channelOptions);

        StackExchange.using("externalEditor", function() {
            // Have to fire editor after snippets, if snippets enabled
            if (StackExchange.settings.snippets.snippetsEnabled) {
                StackExchange.using("snippets", function() {
                    createEditor();
                });
            }
            else {
                createEditor();
            }
        });

        function createEditor() {
            StackExchange.prepareEditor({
                useStacksEditor: false,
                heartbeatType: 'answer',
                autoActivateHeartbeat: false,
                convertImagesToLinks: true,
                noModals: true,
                showLowRepImageUploadWarning: true,
                reputationToPostImages: 10,
                bindNavPrevention: true,
                postfix: "",
                imageUploader: {
                    brandingHtml: "Powered by \u003ca href=\"https://imgur.com/\"\u003e\u003csvg class=\"svg-icon\" width=\"50\" height=\"18\" viewBox=\"0 0 50 18\" fill=\"none\" xmlns=\"http://www.w3.org/2000/svg\"\u003e\u003cpath d=\"M46.1709 9.17788C46.1709 8.26454 46.2665 7.94324 47.1084 7.58816C47.4091 7.46349 47.7169 7.36433 48.0099 7.26993C48.9099 6.97997 49.672 6.73443 49.672 5.93063C49.672 5.22043 48.9832 4.61182 48.1414 4.61182C47.4335 4.61182 46.7256 4.91628 46.0943 5.50789C45.7307 4.9328 45.2525 4.66231 44.6595 4.66231C43.6264 4.66231 43.1481 5.28821 43.1481 6.59048V11.9512C43.1481 13.2535 43.6264 13.8962 44.6595 13.8962C45.6924 13.8962 46.1709 13.2535 46.1709 11.9512V9.17788Z\"/\u003e\u003cpath d=\"M32.492 10.1419C32.492 12.6954 34.1182 14.0484 37.0451 14.0484C39.9723 14.0484 41.5985 12.6954 41.5985 10.1419V6.59049C41.5985 5.28821 41.1394 4.66232 40.1061 4.66232C39.0732 4.66232 38.5948 5.28821 38.5948 6.59049V9.60062C38.5948 10.8521 38.2696 11.5455 37.0451 11.5455C35.8209 11.5455 35.4954 10.8521 35.4954 9.60062V6.59049C35.4954 5.28821 35.0173 4.66232 34.0034 4.66232C32.9703 4.66232 32.492 5.28821 32.492 6.59049V10.1419Z\" /\u003e\u003cpath fill-rule=\"evenodd\" clip-rule=\"evenodd\" d=\"M25.6622 17.6335C27.8049 17.6335 29.3739 16.9402 30.2537 15.6379C30.8468 14.7755 30.9615 13.5579 30.9615 11.9512V6.59049C30.9615 5.28821 30.4833 4.66231 29.4502 4.66231C28.9913 4.66231 28.4555 4.94978 28.1109 5.50789C27.499 4.86533 26.7335 4.56087 25.7005 4.56087C23.1369 4.56087 21.0134 6.57349 21.0134 9.27932C21.0134 11.9852 23.003 13.913 25.3754 13.913C26.5612 13.913 27.4607 13.4902 28.1109 12.6616C28.1109 12.7229 28.1161 12.7799 28.121 12.8346C28.1256 12.8854 28.1301 12.9342 28.1301 12.983C28.1301 14.4373 27.2502 15.2321 25.777 15.2321C24.8349 15.2321 24.1352 14.9821 23.5661 14.7787C23.176 14.6393 22.8472 14.5218 22.5437 14.5218C21.7977 14.5218 21.2429 15.0123 21.2429 15.6887C21.2429 16.7375 22.9072 17.6335 25.6622 17.6335ZM24.1317 9.27932C24.1317 7.94324 24.9928 7.09766 26.1024 7.09766C27.2119 7.09766 28.0918 7.94324 28.0918 9.27932C28.0918 10.6321 27.2311 11.5116 26.1024 11.5116C24.9737 11.5116 24.1317 10.6491 24.1317 9.27932Z\"/\u003e\u003cpath d=\"M16.8045 11.9512C16.8045 13.2535 17.2637 13.8962 18.2965 13.8962C19.3298 13.8962 19.8079 13.2535 19.8079 11.9512V8.12928C19.8079 5.82936 18.4879 4.62866 16.4027 4.62866C15.1594 4.62866 14.279 4.98375 13.3609 5.88013C12.653 5.05154 11.6581 4.62866 10.3573 4.62866C9.34336 4.62866 8.57809 4.89931 7.9466 5.5079C7.58314 4.9328 7.10506 4.66232 6.51203 4.66232C5.47873 4.66232 5.00066 5.28821 5.00066 6.59049V11.9512C5.00066 13.2535 5.47873 13.8962 6.51203 13.8962C7.54479 13.8962 8.0232 13.2535 8.0232 11.9512V8.90741C8.0232 7.58817 8.44431 6.91179 9.53458 6.91179C10.5104 6.91179 10.893 7.58817 10.893 8.94108V11.9512C10.893 13.2535 11.3711 13.8962 12.4044 13.8962C13.4375 13.8962 13.9157 13.2535 13.9157 11.9512V8.90741C13.9157 7.58817 14.3365 6.91179 15.4269 6.91179C16.4027 6.91179 16.8045 7.58817 16.8045 8.94108V11.9512Z\"/\u003e\u003cpath d=\"M3.31675 6.59049C3.31675 5.28821 2.83866 4.66232 1.82471 4.66232C0.791758 4.66232 0.313354 5.28821 0.313354 6.59049V11.9512C0.313354 13.2535 0.791758 13.8962 1.82471 13.8962C2.85798 13.8962 3.31675 13.2535 3.31675 11.9512V6.59049Z\" /\u003e\u003cpath d=\"M1.87209 0.400291C0.843612 0.400291 0 1.1159 0 1.98861C0 2.87869 0.822846 3.57676 1.87209 3.57676C2.90056 3.57676 3.7234 2.87869 3.7234 1.98861C3.7234 1.1159 2.90056 0.400291 1.87209 0.400291Z\" fill=\"#1BB76E\"/\u003e\u003c/svg\u003e\u003c/a\u003e",
                    contentPolicyHtml: "User contributions licensed under \u003ca href=\"https://stackoverflow.com/help/licensing\"\u003ecc by-sa\u003c/a\u003e \u003ca href=\"https://stackoverflow.com/legal/content-policy\"\u003e(content policy)\u003c/a\u003e",
                    allowUrls: true
                },
noCode: true,                onDemand: true,
                discardSelector: ".discard-answer"
                ,immediatelyShowMarkdownHelp:true,enableTables:true
            });
                    }
    });
</script>
<div id="post-editor" class="post-editor js-post-editor">


        <div class="ps-relative">
            <div class="wmd-container mb8">
                <div id="wmd-button-bar" class="wmd-button-bar btr-sm"></div>
                <div class="js-stacks-validation">
                    <div class="ps-relative">
                        <textarea id="wmd-input"
                                  name="post-text"
                                  class="wmd-input s-input bar0 js-post-body-field"
                                  data-post-type-id="2"
                                  cols="92" rows="15"
                                  tabindex="101"
                                  data-min-length=""></textarea>
                    </div>
                    <div class="s-input-message mt4 d-none js-stacks-validation-message"></div>
                </div>
            </div>
        </div>

    <aside class="grid ai-start jc-space-between js-answer-help s-notice s-notice__warning pb0 pr4 pt4 mb8 d-none" role="status" aria-hidden="true">
    <div class="grid--cell pt8">
        <p>Thanks for contributing an answer to Mathematics Stack Exchange!</p><ul><li>Please be sure to <em>answer the question</em>. Provide details and share your research!</li></ul><p>But <em>avoid</em> …</p><ul><li>Asking for help, clarification, or responding to other answers.</li><li>Making statements based on opinion; back them up with references or personal experience.</li></ul><p>Use MathJax to format equations. <a href="http://meta.math.stackexchange.com/questions/5020/tex-latex-mathjax-basic-tutorial-and-quick-reference">MathJax reference</a>.</p><p>To learn more, see our <a href="/help/how-to-answer">tips on writing great answers</a>.</p>
    </div>
    <button class="grid--cell js-answer-help-close-btn s-btn s-btn__muted fc-dark">
        <svg aria-hidden="true" class="svg-icon iconClear" width="18" height="18" viewBox="0 0 18 18"><path d="M15 4.41L13.59 3 9 7.59 4.41 3 3 4.41 7.59 9 3 13.59 4.41 15 9 10.41 13.59 15 15 13.59 10.41 9 15 4.41z"/></svg>
    </button>
</aside>



    <div>
        <div id="draft-saved" class="fc-success h24" style="display:none;">Draft saved</div>
        <div id="draft-discarded" class="fc-error h24" style="display:none;">Draft discarded</div>
    </div>


            <div id="wmd-preview" class="s-prose mb16 wmd-preview js-wmd-preview"></div>
            <div></div>

        <div class="edit-block">
            <input id="fkey" name="fkey" type="hidden" value="fbfa9cf76921d03272650b061592cf4031b8318d5c4cced7fe5f66eae2d1d6ac">
            <input id="author" name="author" type="text">
        </div>

</div>


                                <div class="ps-relative">
                                                <div class="form-item dno new-post-login p0 my16">
                <div class="grid gs16 md:fd-column new-login-form">
                    <div class="grid fd-column w50 md:w-auto gsy gs8 jc-space-between new-login-left">
                        <h3 class="grid--cell fs-title">Sign up or <a id="login-link" href="/users/login?ssrc=question_page&returnurl=https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers%23new-answer">log in</a></h3>
                        <script>
                            StackExchange.ready(function () {
                                StackExchange.helpers.onClickDraftSave('#login-link');
                            });
                        </script>
                        <div class="grid--cell s-btn s-btn__muted s-btn__outlined s-btn__icon google-login" data-ga="[&quot;sign up&quot;,&quot;Sign Up Started - Google&quot;,&quot;New Post&quot;,null,null]">
                            <svg aria-hidden="true" class="native svg-icon iconGoogle" width="18" height="18" viewBox="0 0 18 18"><path d="M16.51 8H8.98v3h4.3c-.18 1-.74 1.48-1.6 2.04v2.01h2.6a7.8 7.8 0 002.38-5.88c0-.57-.05-.66-.15-1.18z" fill="#4285F4"/><path d="M8.98 17c2.16 0 3.97-.72 5.3-1.94l-2.6-2a4.8 4.8 0 01-7.18-2.54H1.83v2.07A8 8 0 008.98 17z" fill="#34A853"/><path d="M4.5 10.52a4.8 4.8 0 010-3.04V5.41H1.83a8 8 0 000 7.18l2.67-2.07z" fill="#FBBC05"/><path d="M8.98 4.18c1.17 0 2.23.4 3.06 1.2l2.3-2.3A8 8 0 001.83 5.4L4.5 7.49a4.77 4.77 0 014.48-3.3z" fill="#EA4335"/></svg> Sign up using Google
                        </div>
                        <div class="grid--cell s-btn s-btn__muted s-btn__icon facebook-login" data-ga="[&quot;sign up&quot;,&quot;Sign Up Started - Facebook&quot;,&quot;New Post&quot;,null,null]">
                            <svg aria-hidden="true" class="svg-icon iconFacebook" width="18" height="18" viewBox="0 0 18 18"><path d="M3 1a2 2 0 00-2 2v12c0 1.1.9 2 2 2h12a2 2 0 002-2V3a2 2 0 00-2-2H3zm6.55 16v-6.2H7.46V8.4h2.09V6.61c0-2.07 1.26-3.2 3.1-3.2.88 0 1.64.07 1.87.1v2.16h-1.29c-1 0-1.19.48-1.19 1.18V8.4h2.39l-.31 2.42h-2.08V17h-2.5z" fill="#4167B2"/></svg> Sign up using Facebook
                        </div>
                        <div class="grid--cell s-btn s-btn__muted s-btn__outlined s-btn__icon stackexchange-login" data-ga="[&quot;sign up&quot;,&quot;Sign Up Navigation&quot;,&quot;New Post&quot;,null,null]">
                            <svg aria-hidden="true" class="native svg-icon iconLogoGlyphXSm" width="18" height="18" viewBox="0 0 18 18"><path d="M14 16v-5h2v7H2v-7h2v5h10z" fill="#BCBBBB"/><path d="M12.09.72l-1.21.9 4.5 6.07 1.22-.9L12.09.71zM5 15h8v-2H5v2zm9.15-5.87L8.35 4.3l.96-1.16 5.8 4.83-.96 1.16zm-7.7-1.47l6.85 3.19.63-1.37-6.85-3.2-.63 1.38zm6.53 5L5.4 11.39l.38-1.67 7.42 1.48-.22 1.46z" fill="#F48024"/></svg> Sign up using Email and Password
                        </div>
                    </div>
                    <input type="hidden" name="use-facebook" class="use-facebook" value="false" />
                    <input type="hidden" name="use-google" class="use-google" value="false" />
                    <button type="button" class="d-none js-submit-openid">Submit</button>
                    <div class="grid gsy gs8 fd-column w50 md:w-auto new-login-right form-item p0">
                                <h3 class="grid--cell fs-title">Post as a guest</h3>
            <div class="grid--cell">
                <div class="grid gs4 gsy fd-column">
                    <label class="s-label" for="display-name">Name</label>
                    <div class="grid ps-relative">
                        <input class="s-input" id="display-name" name="display-name" maxlength="30" type="text" value="" tabindex="105" placeholder="" />
                    </div>
                </div>
            </div>
            <div class="grid--cell">
                <div class="grid gs4 gsy fd-column">
                    <div class="grid--cell">
                        <div class="grid gs2 gsy fd-column">
                            <label class="grid--cell s-label" for="m-address">Email</label>
                            <p class="grid--cell s-description">Required, but never shown</p>
                        </div>
                    </div>
                    <div class="grid ps-relative">
                        <input class="s-input js-post-email-field" id="m-address" name="m-address" type="text" value="" size="40" tabindex="106" placeholder="" />
                    </div>
                </div>
            </div>

                    </div>
                </div>
            </div>
            <script>
                StackExchange.ready(
                    function () {
                        StackExchange.openid.initPostLogin('.new-post-login', 'https%3a%2f%2fmath.stackexchange.com%2fquestions%2f1627410%2fproving-trig-identities-complex-numbers%23new-answer', 'question_page');
                    }
                );
            </script>
            <noscript>
                        <h3 class="grid--cell fs-title">Post as a guest</h3>
            <div class="grid--cell">
                <div class="grid gs4 gsy fd-column">
                    <label class="s-label" for="display-name">Name</label>
                    <div class="grid ps-relative">
                        <input class="s-input" id="display-name" name="display-name" maxlength="30" type="text" value="" tabindex="105" placeholder="" />
                    </div>
                </div>
            </div>
            <div class="grid--cell">
                <div class="grid gs4 gsy fd-column">
                    <div class="grid--cell">
                        <div class="grid gs2 gsy fd-column">
                            <label class="grid--cell s-label" for="m-address">Email</label>
                            <p class="grid--cell s-description">Required, but never shown</p>
                        </div>
                    </div>
                    <div class="grid ps-relative">
                        <input class="s-input js-post-email-field" id="m-address" name="m-address" type="text" value="" size="40" tabindex="106" placeholder="" />
                    </div>
                </div>
            </div>

            </noscript>

                                </div>

                                    <div class="form-submit cbt grid gsx gs4">
                                        <button id="submit-button" class="grid--cell s-btn s-btn__primary s-btn__icon" type="submit" tabindex="120" autocomplete="off">
Post Your Answer                                        </button>
                                        <button class="grid--cell s-btn s-btn__danger discard-answer dno">
                                            Discard
                                        </button>
                                            <p class="privacy-policy-agreement">
                                                By clicking “Post Your Answer”, you agree to our <a href='https://stackoverflow.com/legal/terms-of-service/public' name='tos' target='_blank' class='-link'>terms of service</a>, <a href='https://stackoverflow.com/legal/privacy-policy' name='privacy' target='_blank' class='-link'>privacy policy</a> and <a href='https://stackoverflow.com/legal/cookie-policy' name='cookie' target='_blank' class='-link'>cookie policy</a><input type="hidden" name="legalLinksShown" value="1" />
                                            </p>
                                    </div>
                                    <div class="js-general-error general-error cbt d-none"></div>
                            </form>



                            <h2 class="bottom-notice" data-loc="1">
Not the answer you&#x27;re looking for? Browse other questions tagged <a href="/questions/tagged/trigonometry" class="post-tag" title="show questions tagged &#39;trigonometry&#39;" rel="tag">trigonometry</a> <a href="/questions/tagged/complex-numbers" class="post-tag" title="show questions tagged &#39;complex-numbers&#39;" rel="tag">complex-numbers</a>  or <a href="/questions/ask">ask your own question</a>.                            </h2>
                </div>
            </div>
            <div id="sidebar" class="show-votes" role="complementary" aria-label="sidebar">
                    

                
<div class="s-sidebarwidget s-sidebarwidget__yellow s-anchors s-anchors__grayscale mb16" data-tracker="cb=1">
    <ul class="d-block p0 m0">
                    <div class="s-sidebarwidget--header s-sidebarwidget__small-bold-text fc-light d:fc-black-900 bb bbw1">
                        The Overflow Blog
                    </div>
        <li class="s-sidebarwidget--item grid px16">
            <div class="grid--cell1 fl-shrink0">
<svg aria-hidden="true" class="va-text-top svg-icon iconPencilSm" width="14" height="14" viewBox="0 0 14 14"><path d="M11.1 1.71l1.13 1.12c.2.2.2.51 0 .71L11.1 4.7 9.21 2.86l1.17-1.15c.2-.2.51-.2.71 0zM2 10.12l6.37-6.43 1.88 1.88L3.88 12H2v-1.88z"/></svg>            </div>
            <div class="grid--cell wmn0 ow-break-word">
                <a href="https://stackoverflow.blog/2021/04/29/vote-for-stack-overflow-in-this-years-webby-awards/" class="js-gps-track" data-ga="[&quot;community bulletin board&quot;,&quot;The Overflow Blog&quot;,&quot;https://stackoverflow.blog/2021/04/29/vote-for-stack-overflow-in-this-years-webby-awards/&quot;,null,null]" data-gps-track="communitybulletin.click({ priority: 1, position: 0 })">Vote for Stack Overflow in this year’s Webby Awards!</a>
            </div>
        </li>
                    <div class="s-sidebarwidget--header s-sidebarwidget__small-bold-text fc-light d:fc-black-900 bb bbw1">
                        Featured on Meta
                    </div>
        <li class="s-sidebarwidget--item grid px16">
            <div class="grid--cell1 fl-shrink0">
<div class="favicon favicon-stackexchangemeta" title="Meta Stack Exchange"></div>            </div>
            <div class="grid--cell wmn0 ow-break-word">
                <a href="https://meta.stackexchange.com/questions/363485/new-onboarding-for-review-queues" class="js-gps-track" data-ga="[&quot;community bulletin board&quot;,&quot;Featured on Meta&quot;,&quot;https://meta.stackexchange.com/questions/363485/new-onboarding-for-review-queues&quot;,null,null]" data-gps-track="communitybulletin.click({ priority: 3, position: 1 })">New onboarding for review queues</a>
            </div>
        </li>
        <li class="s-sidebarwidget--item grid px16">
            <div class="grid--cell1 fl-shrink0">
<div class="favicon favicon-mathmeta" title="Mathematics Meta Stack Exchange"></div>            </div>
            <div class="grid--cell wmn0 ow-break-word">
                <a href="https://math.meta.stackexchange.com/questions/33508/enforcement-of-quality-standards" class="js-gps-track" data-ga="[&quot;community bulletin board&quot;,&quot;Featured on Meta&quot;,&quot;https://math.meta.stackexchange.com/questions/33508/enforcement-of-quality-standards&quot;,null,null]" data-gps-track="communitybulletin.click({ priority: 6, position: 2 })">Enforcement of Quality Standards</a>
            </div>
        </li>
    </ul>
</div>


<div class="js-zone-container zone-container-sidebar">
    <div id="dfp-tsb" class="everyonelovesstackoverflow everyoneloves__top-sidebar"></div>
    <div class="js-report-ad-button-container " style="width: 300px"></div>
</div>
            <div id="dfp-tsb"></div>
            <script>setTimeout(function(){try{typeof clc!=='undefined'&&typeof clc.loadDisplayAds==='function'&&clc.loadDisplayAds(['dfp-tsb']);}catch(e){console.error(e);}},0);</script>
                    <div class="module sidebar-linked">
	<h4 id="h-linked">Linked</h4>
	<div class="linked" data-tracker="lq=1">
            <div class="spacer js-gps-track" data-gps-track="linkedquestion.click({ source_post_id: 1627410, target_question_id: 1596764, position: 0 })">
				<a href="/q/1596764" title="Vote score (upvotes - downvotes)">
					<div class="answer-votes answered-accepted default">8</div>
				</a>
				<a href="/questions/1596764/proving-zn-frac1zn-2-cosn-theta-for-z-cos-theta-i-sin?noredirect=1" class="question-hyperlink">Proving $ z^n + \frac{1}{z^n} = 2\cos(n\theta) $ for $z = \cos (\theta) + i\sin(\theta)$</a>
			</div>
	</div>
</div>


                    <div class="module sidebar-related">
                        <h4 id="h-related">Related</h4>
                        <div class="related js-gps-related-questions" data-tracker="rq=1">
                                <div class="spacer">
                                    <a href="/q/118725" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">3</div>
                                    </a>
                                    <a href="/questions/118725/proving-the-cosine-subtraction-identity-using-complex-numbers" class="question-hyperlink">Proving the cosine subtraction identity using complex numbers</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/817109" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes default">1</div>
                                    </a>
                                    <a href="/questions/817109/summation-of-cos-2n-1-theta" class="question-hyperlink">Summation of cos (2n-1) theta</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/1056747" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">1</div>
                                    </a>
                                    <a href="/questions/1056747/understanding-expanding-trig-identities" class="question-hyperlink">Understanding expanding trig identities</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/1495052" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">1</div>
                                    </a>
                                    <a href="/questions/1495052/formula-for-tana-b-by-complex-numbers" class="question-hyperlink">Formula for $\tan(a + b)$ by complex numbers?</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/1627154" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">0</div>
                                    </a>
                                    <a href="/questions/1627154/proving-equations-complex-conjugates" class="question-hyperlink">Proving Equations (Complex Conjugates)</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/1627361" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">4</div>
                                    </a>
                                    <a href="/questions/1627361/proving-trig-identity-using-de-moivres-theorem" class="question-hyperlink">Proving trig identity using De Moivre&#39;s Theorem</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/2655039" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">4</div>
                                    </a>
                                    <a href="/questions/2655039/using-demoivres-theorem-to-prove-some-identities-regarding-trigonometric-functi" class="question-hyperlink">Using DeMoivre&#39;s Theorem to prove some identities regarding trigonometric functions</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/2812346" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes default">3</div>
                                    </a>
                                    <a href="/questions/2812346/trigonometric-functions-limit-to-complex-infinity" class="question-hyperlink">Trigonometric functions limit to complex infinity</a>
                                </div>
                                <div class="spacer">
                                    <a href="/q/3236172" title="Vote score (upvotes - downvotes)">
                                        <div class="answer-votes answered-accepted default">1</div>
                                    </a>
                                    <a href="/questions/3236172/using-complex-numbers-to-find-cos-5-theta" class="question-hyperlink">Using complex numbers to find $\cos 5\theta$</a>
                                </div>
                        </div>
                    </div>

                <div id="hot-network-questions" class="module tex2jax_ignore">
    <h4>
        <a href="https://stackexchange.com/questions?tab=hot"
           class="js-gps-track s-link s-link__inherit" 
           data-gps-track="posts_hot_network.click({ item_type:1, location:11 })">
            Hot Network Questions
        </a>
    </h4>
    <ul>
            <li >
                <div class="favicon favicon-diy" title="Home Improvement Stack Exchange"></div><a href="https://diy.stackexchange.com/questions/223244/my-apartment-door-unlocked-by-itself-can-anyone-offer-an-explanation-please" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:73 }); posts_hot_network.click({ item_type:2, location:11 })">
                    My apartment door unlocked by itself. Can anyone offer an explanation please?
                </a>

            </li>
            <li >
                <div class="favicon favicon-economics" title="Economics Stack Exchange"></div><a href="https://economics.stackexchange.com/questions/43671/second-order-stochastic-dominance" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:591 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Second order stochastic dominance
                </a>

            </li>
            <li >
                <div class="favicon favicon-stackoverflow" title="Stack Overflow"></div><a href="https://stackoverflow.com/questions/67340908/whats-the-difference-between-a-coroutine-and-a-function-with-static-variables" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:1 }); posts_hot_network.click({ item_type:2, location:11 })">
                    What&#x27;s the difference between a coroutine and a function with static variables?
                </a>

            </li>
            <li >
                <div class="favicon favicon-rpg" title="Role-playing Games Stack Exchange"></div><a href="https://rpg.stackexchange.com/questions/184517/can-a-player-create-a-magic-artifact" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:122 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Can a player create a magic artifact?
                </a>

            </li>
            <li >
                <div class="favicon favicon-academia" title="Academia Stack Exchange"></div><a href="https://academia.stackexchange.com/questions/166998/getting-married-abroad-on-august-21st-job-begins-on-august-23rd-what-do-i-do" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:415 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Getting married abroad on August 21st, job begins on August 23rd. What do I do?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-worldbuilding" title="Worldbuilding Stack Exchange"></div><a href="https://worldbuilding.stackexchange.com/questions/201644/how-would-a-sci-fi-matter-replicator-create-a-pressurised-aerosol-can" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:579 }); posts_hot_network.click({ item_type:2, location:11 })">
                    How would a sci-fi matter replicator create a pressurised aerosol can?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-academia" title="Academia Stack Exchange"></div><a href="https://academia.stackexchange.com/questions/166931/advice-on-publishing-original-theorems-with-easy-proofs" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:415 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Advice on publishing original theorems with easy proofs
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-aviation" title="Aviation Stack Exchange"></div><a href="https://aviation.stackexchange.com/questions/86851/how-is-flight-planning-performed-with-short-turnaround-times" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:528 }); posts_hot_network.click({ item_type:2, location:11 })">
                    How is flight planning performed with short turnaround times?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-japanese" title="Japanese Language Stack Exchange"></div><a href="https://japanese.stackexchange.com/questions/86411/why-are-%e5%85%b3-and-%e5%a4%8d-half-width-in-japanese" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:257 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Why are &#x5173; and &#x590D; half-width in Japanese?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-worldbuilding" title="Worldbuilding Stack Exchange"></div><a href="https://worldbuilding.stackexchange.com/questions/201829/what-would-happen-if-a-refrigerated-bag-of-human-blood-was-warmed-up-in-a-normal" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:579 }); posts_hot_network.click({ item_type:2, location:11 })">
                    What would happen if a refrigerated bag of human blood was warmed up in a normal kitchen microwave?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-english" title="English Language &amp; Usage Stack Exchange"></div><a href="https://english.stackexchange.com/questions/566186/what-is-the-direct-object-of-i-imagined-in-the-context-as-i-imagined-would-be" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:97 }); posts_hot_network.click({ item_type:2, location:11 })">
                    What is the direct object of &quot;I imagined&quot; in the context &quot;as I imagined would be the case&quot;? (i.e. I imagined what?)
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-electronics" title="Electrical Engineering Stack Exchange"></div><a href="https://electronics.stackexchange.com/questions/562916/constant-current-source-drop" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:135 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Constant current source drop
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-security" title="Information Security Stack Exchange"></div><a href="https://security.stackexchange.com/questions/248853/how-is-it-possible-for-boss-to-know-i-am-finding-a-job" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:162 }); posts_hot_network.click({ item_type:2, location:11 })">
                    How is it possible for boss to know I am finding a job?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-electronics" title="Electrical Engineering Stack Exchange"></div><a href="https://electronics.stackexchange.com/questions/562922/charge-pump-has-an-unexpected-voltage-drop-with-a-1k-load" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:135 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Charge pump has an unexpected voltage drop with a 1K load
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-latin" title="Latin Language Stack Exchange"></div><a href="https://latin.stackexchange.com/questions/15924/why-subjunctive-mood-in-this-sentence-from-a-vatican-document" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:644 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Why subjunctive mood in this sentence from a Vatican document?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-christianity" title="Christianity Stack Exchange"></div><a href="https://christianity.stackexchange.com/questions/83011/are-there-theological-explanations-for-why-god-allowed-ambiguity-to-exist-in-scr" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:304 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Are there theological explanations for why God allowed ambiguity to exist in Scripture?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-scifi" title="Science Fiction &amp; Fantasy Stack Exchange"></div><a href="https://scifi.stackexchange.com/questions/246443/need-source-for-the-inverse-of-clarkes-third-law" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:186 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Need source for the inverse of &quot;Clarke&#x27;s Third Law&quot;
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-diy" title="Home Improvement Stack Exchange"></div><a href="https://diy.stackexchange.com/questions/223334/junction-box-partially-behind-drywall-and-partially-exposed" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:73 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Junction box partially behind drywall and partially exposed
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-pets" title="Pets Stack Exchange"></div><a href="https://pets.stackexchange.com/questions/31275/is-it-safe-for-a-cat-to-be-with-a-covid-patient" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:518 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Is it safe for a cat to be with a Covid patient?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-physics" title="Physics Stack Exchange"></div><a href="https://physics.stackexchange.com/questions/632892/does-robert-walds-definition-of-a-manifold-make-it-a-topological-space" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:151 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Does Robert Wald&#x27;s definition of a manifold make it a topological space?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-stats" title="Cross Validated"></div><a href="https://stats.stackexchange.com/questions/522187/what-are-the-use-cases-for-propensity-score-matching" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:65 }); posts_hot_network.click({ item_type:2, location:11 })">
                    What are the use cases for Propensity Score Matching?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-travel" title="Travel Stack Exchange"></div><a href="https://travel.stackexchange.com/questions/163519/are-steam-train-rides-safe" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:273 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Are steam train rides safe?
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-academia" title="Academia Stack Exchange"></div><a href="https://academia.stackexchange.com/questions/166966/how-to-give-feedback-to-students-after-bad-grades" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:415 }); posts_hot_network.click({ item_type:2, location:11 })">
                    How to give feedback to students after bad grades
                </a>

            </li>
            <li class="dno js-hidden">
                <div class="favicon favicon-worldbuilding" title="Worldbuilding Stack Exchange"></div><a href="https://worldbuilding.stackexchange.com/questions/201806/can-one-nation-purposefully-inconspicuously-cause-global-warming" class="js-gps-track question-hyperlink mb0" data-gps-track="site.switch({ item_type:11, target_site:579 }); posts_hot_network.click({ item_type:2, location:11 })">
                    Can one nation purposefully, inconspicuously, cause global warming?
                </a>

            </li>
    </ul>

        <a href="#" 
           class="show-more js-show-more js-gps-track" 
           data-gps-track="posts_hot_network.click({ item_type:3, location:11 })">
            more hot questions
        </a>
</div>

                            <div id="feed-link" class="js-feed-link">
        <a href="/feeds/question/1627410" title="Feed of this question and its answers">
            <svg aria-hidden="true" class="fc-orange-400 svg-icon iconRss" width="18" height="18" viewBox="0 0 18 18"><path d="M1 3c0-1.1.9-2 2-2h12c1.09 0 2 .91 2 2v12c0 1.09-.91 2-2 2H3c-1.09 0-2-.91-2-2V3zm14.5 12C15.5 8.1 9.9 2.5 3 2.5V5a10 10 0 0110 10h2.5zm-5 0A7.5 7.5 0 003 7.5V10a5 5 0 015 5h2.5zm-5 0A2.5 2.5 0 003 12.5V15h2.5z"/></svg>
            Question feed
        </a>
    </div>
    <aside class="s-modal js-feed-link-modal" tabindex="-1" role="dialog" aria-labelledby="feed-modal-title" aria-describedby="feed-modal-description" aria-hidden="true">
        <div class="s-modal--dialog js-modal-dialog wmx4" role="document"  data-controller="se-draggable">
            <h1 class="s-modal--header fw-bold js-first-tabbable" id="feed-modal-title" data-target="se-draggable.handle" tabindex="0">
                Subscribe to RSS
            </h1>
            <div class="grid gs4 gsy fd-column">
                <div class="grid--cell">
                    <label class="d-block s-label c-default" for="feed-url">
                        Question feed
                        <p class="s-description mt2" id="feed-modal-description">To subscribe to this RSS feed, copy and paste this URL into your RSS reader.</p>
                    </label>
                </div>
                <div class="grid ps-relative">
                    <input class="s-input" type="text" name="feed-url" id="feed-url" readonly="readonly" value="https://math.stackexchange.com/feeds/question/1627410" />
                    <svg aria-hidden="true" class="s-input-icon fc-orange-400 svg-icon iconRss" width="18" height="18" viewBox="0 0 18 18"><path d="M1 3c0-1.1.9-2 2-2h12c1.09 0 2 .91 2 2v12c0 1.09-.91 2-2 2H3c-1.09 0-2-.91-2-2V3zm14.5 12C15.5 8.1 9.9 2.5 3 2.5V5a10 10 0 0110 10h2.5zm-5 0A7.5 7.5 0 003 7.5V10a5 5 0 015 5h2.5zm-5 0A2.5 2.5 0 003 12.5V15h2.5z"/></svg>
                </div>
            </div>
            <a class="s-modal--close s-btn s-btn__muted js-modal-close js-last-tabbable" href="#" aria-label="Close">
                <svg aria-hidden="true" class="svg-icon iconClearSm" width="14" height="14" viewBox="0 0 14 14"><path d="M12 3.41L10.59 2 7 5.59 3.41 2 2 3.41 5.59 7 2 10.59 3.41 12 7 8.41 10.59 12 12 10.59 8.41 7 12 3.41z"/></svg>
            </a>
        </div>
    </aside>

            </div>
    </div>
<script>StackExchange.ready(function(){$.get('/posts/1627410/ivc/0719');});</script>
<noscript><div><img src="/posts/1627410/ivc/0719" class="dno" alt="" width="0" height="0"></div></noscript></div>


        </div>
    </div>

        
<script>;try{(function(a){function b(a){return'string'==typeof a?document.getElementById(a):a}function c(a){return a=b(a),!!a&&'none'===getComputedStyle(a).display}function d(a){return!c(a)}function e(a){return!!a}function f(a){return /^\s*$/.test(b(a).innerHTML)}function g(a){var b=a.style;b.height=b.maxHeight=b.minHeight='auto',b.display='none'}function h(a){var b=a.style;b.height=b.maxHeight=b.minHeight='auto',b.display='none',[].forEach.call(a.children,h)}function i(a){var b=a.style;b.height=b.maxHeight=b.minHeight='auto',b.removeProperty('display')}function j(a,b){var c;return function(){return a&&(c=a.call(b||this,arguments),a=null),c}}function k(a){var b=document.createElement('script');b.src=a,document.body.appendChild(b)}function l(a){return m([],a)}function m(a,b){return a.push=function(a){return b(),delete this.push,this.push(a)},a}function n(){try{return!new Function('return async()=>{};')}catch(a){return!0}}function o(){return'undefined'!=typeof googletag&&!!googletag.apiReady}function p(){o()||(googletag={cmd:l(B)})}function q(){var a=document.createElement('div');a.className='adsbox',a.id='clc-abd',a.style.position='absolute',a.style.pointerEvents='none',a.innerHTML='&nbsp;',document.body.appendChild(a)}function r(){return Object.keys(F.ids).filter(function(a){return'clc-cpa'!=a})}function s(a){var b=a.split('_')[0],c=F.ids[b],d=F.slots[c];'function'==typeof d&&(d=d(b));return{path:'/'+C+'/'+E+'/'+c+'/'+D,sizes:d,zone:c}}function t(a){try{Array.isArray(clc.dfp.slotsRenderedEvents)||(clc.dfp.slotsRenderedEvents=[]),clc.dfp.slotsRenderedEvents.push(a);var b=a.slot.getSlotElementId(),c=[];b||c.push('id=0');var d=document.getElementById(b);if(!b||d?d.hasAttribute('data-clc-stalled')&&c.push('st=1'):c.push('el=0'),0!==c.length)return void G(c.join('&'));var e=s(b),f=e.zone;if(clc.collapse&&clc.collapse[f]&&a.isEmpty)return h(d),void d.setAttribute('data-clc-ready','true');if(-1!==y.dh.indexOf(a.lineItemId))h(d);else if(a.lineItemId){d.setAttribute('data-clc-prefilled','true');var j=d.parentElement;if(j.classList.contains('js-zone-container')){g(j);var k=j.querySelectorAll('.js-report-ad-button-container'),l=k[0];switch(l.style.height='24px',b){case'dfp-tlb':case'dfp-tag':{j.classList.add('mb8');break}case'dfp-mlb':case'dfp-smlb':case'dfp-bmlb':{j.classList.add('my8');break}case'dfp-isb':{j.classList.add('mt24');break}case'dfp-m-aq':{j.classList.add('my12'),j.classList.add('mx-auto');break}default:}i(j),i(d)}else i(d);if('dfp-msb'==b){var m=document.getElementById('hireme');h(m)}}d.setAttribute('data-clc-ready','true')}catch(a){var n=document.querySelector('#dfp-tsb, #dfp-isb, #clc-tsb');n&&n.setAttribute('data-clc-ready','true'),G('e=1')}}function u(a,b){'dfp-isb'===a&&b.setTargeting('Sidebar',['Inline']),'dfp-tsb'===a&&b.setTargeting('Sidebar',['Right']);var c=s(a),d=c.path,e=c.sizes,f=c.zone,g=googletag.defineSlot(d,e,a);g.addService(b),!1;var h=a.split('_');if('clc-cpa'==h[0]&&h[1]){var i=h[1];g.setTargeting('talent-company-id',i)}}function v(b){var c=a.dfp&&a.dfp.targeting||{};'SystemDefault'===c.ProductVariant&&(window.matchMedia&&window.matchMedia('(prefers-color-scheme: dark)').matches?c.ProductVariant='Dark':c.ProductVariant='Light'),Object.keys(c).forEach(function(a){b.setTargeting(a,c[a])})}function w(a){var g=a.map(b).filter(e);return{eligible:g.filter(f).filter(d),ineligible:g.filter(c)}}function x(b){void 0===b&&(b=r());var c=['dfp-mlb','dfp-smlb'];if(!o())return p(),void googletag.cmd.push(function(){return x(b)});var d=w(b),e=d.eligible,f=d.ineligible;if(e.forEach(function(a){g(a)}),f.forEach(h),0!==e.length){y.abd&&q();var i=googletag.pubads().getSlots(),j=i.filter(function(a){return 0<=b.indexOf(a.getSlotElementId())});googletag.destroySlots(j);var k=googletag.pubads();y.sf&&(k.setForceSafeFrame(!0),k.setSafeFrameConfig({allowOverlayExpansion:!0,allowPushExpansion:!0,sandbox:!0})),'undefined'!=typeof y.targeting_consent&&(k.setRequestNonPersonalizedAds(y.targeting_consent?0:1),!y.targeting_consent&&k.setPrivacySettings({limitedAds:!0})),y.ll||k.enableSingleRequest(),a.sreEvent||(k.addEventListener('slotRenderEnded',t),a.sreEvent=!0),v(k);var l=e.filter(function(a){return!y.ll||0>c.indexOf(a.id)}),m=e.filter(function(a){return!!y.ll&&0<=c.indexOf(a.id)});l.forEach(function(a){u(a.id,k),a.setAttribute('data-dfp-zone','true')}),googletag.enableServices(),l.forEach(function(a){googletag.display(a.id)}),y.ll&&(k.enableLazyLoad({fetchMarginPercent:0,renderMarginPercent:0}),m.forEach(function(a){u(a.id,k),a.setAttribute('data-clc-prefilled','true')}),m.forEach(function(a){googletag.display(a.id)}))}}var y=function(a){for(var b=[],c=1;c<arguments.length;c++)b[c-1]=arguments[c];for(var d,e=0,f=b;e<f.length;e++)for(var g in d=f[e],d)a[g]=d[g];return a}({"lib":"https://cdn.sstatic.net/clc/clc.min.js?v=0e634710bdce","style":"https://cdn.sstatic.net/clc/styles/clc.min.css?v=a49599567132","u":"https://clc.stackoverflow.com/markup.js","wa":true,"kt":2000,"tto":true,"h":"clc.stackoverflow.com","allowed":"^(((talent\\.)?stackoverflow)|(blog\\.codinghorror)|(serverfault|askubuntu)|([^\\.]+\\.stackexchange))\\.com$","wv":true,"al":false,"dh":[5171832659],"abd":true},a.options||{}),z=j(function(){var a=y.lib;n()&&(a=a.replace(/(\.min)?\.js(\?v=[0-9a-fA-F]+)?$/,'.ie$1.js$2')),k(a)}),A=a.cmd||[];Array.isArray(A)&&(0<A.length?z():m(A,z));var B=j(function(){y.targeting_consent||'undefined'==typeof y.targeting_consent?k('https://securepubads.g.doubleclick.net/tag/js/gpt.js'):k('https://pagead2.googlesyndication.com/tag/js/gpt.js')}),C='248424177',D=/^\/tags\//.test(location.pathname)||/^\/questions\/tagged\//.test(location.pathname)?'tag-pages':/^\/$/.test(location.pathname)||/^\/home/.test(location.pathname)?'home-page':'question-pages',E=location.hostname;var F={slots:{lb:[[728,90]],mlb:[[728,90]],smlb:[[728,90]],bmlb:[[728,90]],sb:function(a){return'dfp-tsb'===a?[[300,250],[300,600]]:[[300,250]]},"tag-sponsorship":[[730,135]],"mobile-below-question":[[320,50],[300,250]],msb:[[300,250],[300,600]],"talent-conversion-tracking":[[1,1]]},ids:{"dfp-tlb":'lb',"dfp-mlb":'mlb',"dfp-smlb":'smlb',"dfp-bmlb":'bmlb',"dfp-tsb":'sb',"dfp-isb":'sb',"dfp-tag":'tag-sponsorship',"dfp-msb":'msb',"dfp-m-aq":'mobile-below-question',"clc-tlb":'lb',"clc-mlb":'mlb',"clc-tsb":'sb',"clc-cpa":'talent-conversion-tracking'}},G=function(a){new Image().src='https://'+y.h+'/stalled.gif?'+a};(function(){var b=y.al;b&&A.push(function(){return a.load()})})(),p(),a.dfp={load:x},a.options=y,a.cmd=A})(this.clc=this.clc||{})}catch(a){window.console.error(a)}</script><script>
    var clc = clc || {};
    clc.collapse = { sb: !0, 'tag-sponsorship': !0, lb: !0, mlb: !0, smlb: !0, bmlb: !0, 'mobile-below-question': !0 };
    clc.options = clc.options || {};
    clc.options.sf = !1;
    clc.options.hb = !1;
    clc.options.ll = !0;
    clc.options.targeting_consent = !0;
    clc.options.performance_consent = !0;
        clc.dfp = clc.dfp || {};
        clc.dfp.targeting = {Registered:['false'],NumberOfAnswers:['4']};
        clc.dfp.targeting.TargetingConsent = ['true'];

        const urlParams = new URLSearchParams(window.location.search);
        if (urlParams.has('dfptestads')) {
            const dfptestads = urlParams.get('dfptestads');
            clc.dfp.targeting.DfpTestAds = dfptestads;
        }
        
        var googletag = googletag || {};
        googletag.cmd = googletag.cmd || [];
        googletag.cmd.push(function () { clc.dfp.load(); });
</script>

            <footer id="footer" class="site-footer js-footer" role="contentinfo">
        <div class="site-footer--container">
            <nav class="site-footer--nav">
                    <div class="site-footer--col site-footer--col__visible js-footer-col" data-name="default">
                        <h5 class="-title"><a href="/">Mathematics</a></h5>
                        <ul class="-list js-primary-footer-links">
                                    <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 2 })" href="/tour">Tour</a></li>
                                <li class="-item"><a href="/help" class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 3 })">Help</a></li>
                                    <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 5 })" href="https://chat.stackexchange.com?tab=site&host=math.stackexchange.com">Chat</a></li>
                            <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 13 })" href="/contact">Contact</a></li>
                                <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 14 })" href="https://math.meta.stackexchange.com">Feedback</a></li>
                                <li class="-item"><a onclick='StackExchange.switchMobile("on")' class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 12 })">Mobile</a></li>
                        </ul>
                    </div>
                <div class="site-footer--col site-footer--col__visible js-footer-col" data-name="default">
                    <h5 class="-title"><a class="js-gps-track" data-gps-track="footer.click({ location: 2, link: 1 })" href="https://stackoverflow.com/company">Company</a></h5>
                    <ul class="-list">
                            <li class="-item"><a href="https://stackoverflow.com" class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 15})">Stack Overflow</a></li>
                            <li class="-item"><a href="https://stackoverflow.com/teams" class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 29 })">For Teams</a></li>
                            <li class="-item"><a href="https://stackoverflow.com/advertising" class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 21 })">Advertise With Us</a></li>
                            <li class="-item"><a href="https://stackoverflow.com/talent" class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 20 })">Hire a Developer</a></li>
                            <li class="-item"><a href="https://stackoverflow.com/jobs" class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 17})">Developer Jobs</a></li>
                                <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 1 })" href="https://stackoverflow.com/company">About</a></li>
                        <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 27 })" href="https://stackoverflow.com/company/press">Press</a></li>
                        <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 7 })" href="https://stackoverflow.com/legal">Legal</a></li>
                        <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 8 })" href="https://stackoverflow.com/legal/privacy-policy">Privacy Policy</a></li>
                        <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 37 })" href="https://stackoverflow.com/legal/terms-of-service">Terms of Service</a></li>
                            <li class="-item" id="consent-footer-link"><a class="js-gps-track -link js-cookie-settings" data-gps-track="footer.click({ location: 2, link: 38 })" href="#" data-consent-popup-loader="footer">Cookie Settings</a></li>
                        <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link: 39 })" href="https://stackoverflow.com/legal/cookie-policy">Cookie Policy</a></li>
                    </ul>
                </div>
                <div class="site-footer--col site-footer--categories-nav site-footer--col__visible">
                    <a href="#" class="site-footer--back js-footer-back"><svg aria-hidden="true" class="svg-icon iconArrowLeftAlt" width="18" height="18" viewBox="0 0 18 18"><path d="M10.58 16L12 14.59 6.4 9 12 3.41 10.57 2l-7 7 7 7z"/></svg></a>
                    <div>
                        <h5 class="-title"><a href="https://stackexchange.com" data-gps-track="footer.click({ location: 2, link: 30 })">Stack Exchange<br> Network</a></h5>
                        <ul class="-list">
                            <li class="-item"><a href="#" class="-link _expandable js-footer-category-trigger js-gps-track" data-gps-track="footer.click({ location: 2, link: 24 })" data-target="Technology">Technology</a></li>
                            <li class="-item"><a href="#" class="-link _expandable js-footer-category-trigger js-gps-track" data-gps-track="footer.click({ location: 2, link: 24 })" data-target="Life / Arts">Life / Arts</a></li>
                            <li class="-item"><a href="#" class="-link _expandable js-footer-category-trigger js-gps-track" data-gps-track="footer.click({ location: 2, link: 24 })" data-target="Culture / Recreation">Culture / Recreation</a></li>
                            <li class="-item"><a href="#" class="-link _expandable js-footer-category-trigger js-gps-track" data-gps-track="footer.click({ location: 2, link: 24 })" data-target="Science">Science</a></li>
                            <li class="-item"><a href="#" class="-link _expandable js-footer-category-trigger js-gps-track" data-gps-track="footer.click({ location: 2, link: 24 })" data-target="Other">Other</a></li>
                        </ul>
                    </div>
                </div>
                <div class="site-footer--categories">
                        <div class="site-footer--col site-footer--category js-footer-col" data-name="Technology">
        <ul class="-list">
                <li class="-item"><a href="https://stackoverflow.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professional and enthusiast programmers">Stack Overflow</a></li>
                <li class="-item"><a href="https://serverfault.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="system and network administrators">Server Fault</a></li>
                <li class="-item"><a href="https://superuser.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="computer enthusiasts and power users">Super User</a></li>
                <li class="-item"><a href="https://webapps.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="power users of web applications">Web Applications</a></li>
                <li class="-item"><a href="https://askubuntu.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Ubuntu users and developers">Ask Ubuntu</a></li>
                <li class="-item"><a href="https://webmasters.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="pro webmasters">Webmasters</a></li>
                <li class="-item"><a href="https://gamedev.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professional and independent game developers">Game Development</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Technology"><ul class="-list">
                <li class="-item"><a href="https://tex.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="users of TeX, LaTeX, ConTeXt, and related typesetting systems">TeX - LaTeX</a></li>
                <li class="-item"><a href="https://softwareengineering.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professionals, academics, and students working within the systems development life cycle">Software Engineering</a></li>
                <li class="-item"><a href="https://unix.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="users of Linux, FreeBSD and other Un*x-like operating systems">Unix &amp; Linux</a></li>
                <li class="-item"><a href="https://apple.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="power users of Apple hardware and software">Ask Different (Apple)</a></li>
                <li class="-item"><a href="https://wordpress.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="WordPress developers and administrators">WordPress Development</a></li>
                <li class="-item"><a href="https://gis.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="cartographers, geographers and GIS professionals">Geographic Information Systems</a></li>
                <li class="-item"><a href="https://electronics.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="electronics and electrical engineering professionals, students, and enthusiasts">Electrical Engineering</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Technology"><ul class="-list">
                <li class="-item"><a href="https://android.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="enthusiasts and power users of the Android operating system">Android Enthusiasts</a></li>
                <li class="-item"><a href="https://security.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="information security professionals">Information Security</a></li>
                <li class="-item"><a href="https://dba.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="database professionals who wish to improve their database skills and learn from others in the community">Database Administrators</a></li>
                <li class="-item"><a href="https://drupal.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Drupal developers and administrators">Drupal Answers</a></li>
                <li class="-item"><a href="https://sharepoint.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="SharePoint enthusiasts">SharePoint</a></li>
                <li class="-item"><a href="https://ux.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="user experience researchers and experts">User Experience</a></li>
                <li class="-item"><a href="https://mathematica.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="users of Wolfram Mathematica">Mathematica</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Technology"><ul class="-list">
                <li class="-item"><a href="https://salesforce.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Salesforce administrators, implementation experts, developers and anybody in-between">Salesforce</a></li>
                <li class="-item"><a href="https://expressionengine.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="administrators, end users, developers and designers for ExpressionEngine&#xAE; CMS">ExpressionEngine&#xAE; Answers</a></li>
                <li class="-item"><a href="https://pt.stackoverflow.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="programadores profissionais e entusiastas">Stack Overflow em Portugu&#xEA;s</a></li>
                <li class="-item"><a href="https://blender.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people who use Blender to create 3D graphics, animations, or games">Blender</a></li>
                <li class="-item"><a href="https://networkengineering.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="network engineers">Network Engineering</a></li>
                <li class="-item"><a href="https://crypto.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="software developers, mathematicians and others interested in cryptography">Cryptography</a></li>
                <li class="-item"><a href="https://codereview.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="peer programmer code reviews">Code Review</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Technology"><ul class="-list">
                <li class="-item"><a href="https://magento.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="users of the Magento e-Commerce platform">Magento</a></li>
                <li class="-item"><a href="https://softwarerecs.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people seeking specific software recommendations">Software Recommendations</a></li>
                <li class="-item"><a href="https://dsp.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="practitioners of the art and science of signal, image and video processing">Signal Processing</a></li>
                <li class="-item"><a href="https://emacs.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="those using, extending or developing Emacs">Emacs</a></li>
                <li class="-item"><a href="https://raspberrypi.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="users and developers of hardware and software for Raspberry Pi">Raspberry Pi</a></li>
                <li class="-item"><a href="https://ru.stackoverflow.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="&#x43F;&#x440;&#x43E;&#x433;&#x440;&#x430;&#x43C;&#x43C;&#x438;&#x441;&#x442;&#x43E;&#x432;">Stack Overflow &#x43D;&#x430; &#x440;&#x443;&#x441;&#x441;&#x43A;&#x43E;&#x43C;</a></li>
                <li class="-item"><a href="https://codegolf.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="programming puzzle enthusiasts and code golfers">Code Golf</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Technology"><ul class="-list">
                <li class="-item"><a href="https://es.stackoverflow.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="programadores y profesionales de la inform&#xE1;tica">Stack Overflow en espa&#xF1;ol</a></li>
                <li class="-item"><a href="https://ethereum.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="users of Ethereum, the decentralized application platform and smart contract enabled blockchain">Ethereum</a></li>
                <li class="-item"><a href="https://datascience.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Data science professionals, Machine Learning specialists, and those interested in learning more about the field">Data Science</a></li>
                <li class="-item"><a href="https://arduino.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="developers of open-source hardware and software that is compatible with Arduino">Arduino</a></li>
                <li class="-item"><a href="https://bitcoin.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Bitcoin crypto-currency enthusiasts">Bitcoin</a></li>
                <li class="-item"><a href="https://sqa.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="software quality control experts, automation engineers, and software testers">Software Quality Assurance &amp; Testing</a></li>
                <li class="-item"><a href="https://sound.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="sound engineers, producers, editors, and enthusiasts">Sound Design</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Technology"><ul class="-list">
                <li class="-item"><a href="https://windowsphone.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="enthusiasts and power users of Windows Phone OS">Windows Phone</a></li>
                <li class="-item">
                    <a href="https://stackexchange.com/sites#technology" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 26 })">
                        <strong>
                            more (28)
                        </strong>
                    </a>
                </li>
        </ul>
    </div>
    <div class="site-footer--col site-footer--category js-footer-col" data-name="Life / Arts">
        <ul class="-list">
                <li class="-item"><a href="https://photo.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professional, enthusiast and amateur photographers">Photography</a></li>
                <li class="-item"><a href="https://scifi.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="science fiction and fantasy enthusiasts">Science Fiction &amp; Fantasy</a></li>
                <li class="-item"><a href="https://graphicdesign.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Graphic Design professionals, students, and enthusiasts">Graphic Design</a></li>
                <li class="-item"><a href="https://movies.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="movie and TV enthusiasts">Movies &amp; TV</a></li>
                <li class="-item"><a href="https://music.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="musicians, students, and enthusiasts">Music: Practice &amp; Theory</a></li>
                <li class="-item"><a href="https://worldbuilding.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="writers/artists using science, geography and culture to construct imaginary worlds and settings">Worldbuilding</a></li>
                <li class="-item"><a href="https://video.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="engineers, producers, editors, and enthusiasts spanning the fields of video, and media creation">Video Production</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Life / Arts"><ul class="-list">
                <li class="-item"><a href="https://cooking.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professional and amateur chefs">Seasoned Advice (cooking)</a></li>
                <li class="-item"><a href="https://diy.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="contractors and serious DIYers">Home Improvement</a></li>
                <li class="-item"><a href="https://money.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people who want to be financially literate">Personal Finance &amp; Money</a></li>
                <li class="-item"><a href="https://academia.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="academics and those enrolled in higher education">Academia</a></li>
                <li class="-item"><a href="https://law.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="legal professionals, students, and others with experience or interest in law">Law</a></li>
                <li class="-item"><a href="https://fitness.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="physical fitness professionals, athletes, trainers, and those providing health-related needs">Physical Fitness</a></li>
                <li class="-item"><a href="https://gardening.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="gardeners and landscapers">Gardening &amp; Landscaping</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Life / Arts"><ul class="-list">
                <li class="-item"><a href="https://parenting.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="parents, grandparents, nannies and others with a parenting role">Parenting</a></li>
                <li class="-item">
                    <a href="https://stackexchange.com/sites#lifearts" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 26 })">
                        <strong>
                            more (10)
                        </strong>
                    </a>
                </li>
        </ul>
    </div>
    <div class="site-footer--col site-footer--category js-footer-col" data-name="Culture / Recreation">
        <ul class="-list">
                <li class="-item"><a href="https://english.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="linguists, etymologists, and serious English language enthusiasts">English Language &amp; Usage</a></li>
                <li class="-item"><a href="https://skeptics.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="scientific skepticism">Skeptics</a></li>
                <li class="-item"><a href="https://judaism.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="those who base their lives on Jewish law and tradition and anyone interested in learning more">Mi Yodeya (Judaism)</a></li>
                <li class="-item"><a href="https://travel.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="road warriors and seasoned travelers">Travel</a></li>
                <li class="-item"><a href="https://christianity.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="committed Christians, experts in Christianity and those interested in learning more">Christianity</a></li>
                <li class="-item"><a href="https://ell.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="speakers of other languages learning English">English Language Learners</a></li>
                <li class="-item"><a href="https://japanese.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="students, teachers, and linguists wanting to discuss the finer points of the Japanese language">Japanese Language</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Culture / Recreation"><ul class="-list">
                <li class="-item"><a href="https://chinese.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="students, teachers, and linguists wanting to discuss the finer points of the Chinese language">Chinese Language</a></li>
                <li class="-item"><a href="https://french.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="students, teachers, and linguists wanting to discuss the finer points of the French language">French Language</a></li>
                <li class="-item"><a href="https://german.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="speakers of German wanting to discuss the finer points of the language and translation">German Language</a></li>
                <li class="-item"><a href="https://hermeneutics.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professors, theologians, and those interested in exegetical analysis of biblical texts">Biblical Hermeneutics</a></li>
                <li class="-item"><a href="https://history.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="historians and history buffs">History</a></li>
                <li class="-item"><a href="https://spanish.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="linguists, teachers, students and Spanish language enthusiasts in general wanting to discuss the finer points of the language">Spanish Language</a></li>
                <li class="-item"><a href="https://islam.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="Muslims, experts in Islam, and those interested in learning more about Islam">Islam</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Culture / Recreation"><ul class="-list">
                <li class="-item"><a href="https://rus.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="&#x43B;&#x438;&#x43D;&#x433;&#x432;&#x438;&#x441;&#x442;&#x43E;&#x432; &#x438; &#x44D;&#x43D;&#x442;&#x443;&#x437;&#x438;&#x430;&#x441;&#x442;&#x43E;&#x432; &#x440;&#x443;&#x441;&#x441;&#x43A;&#x43E;&#x433;&#x43E; &#x44F;&#x437;&#x44B;&#x43A;&#x430;">&#x420;&#x443;&#x441;&#x441;&#x43A;&#x438;&#x439; &#x44F;&#x437;&#x44B;&#x43A;</a></li>
                <li class="-item"><a href="https://russian.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="students, teachers, and linguists wanting to discuss the finer points of the Russian language">Russian Language</a></li>
                <li class="-item"><a href="https://gaming.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="passionate videogamers on all platforms">Arqade (gaming)</a></li>
                <li class="-item"><a href="https://bicycles.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people who build and repair bicycles, people who train cycling, or commute on bicycles">Bicycles</a></li>
                <li class="-item"><a href="https://rpg.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="gamemasters and players of tabletop, paper-and-pencil role-playing games">Role-playing Games</a></li>
                <li class="-item"><a href="https://anime.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="anime and manga fans">Anime &amp; Manga</a></li>
                <li class="-item"><a href="https://puzzling.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="those who create, solve, and study puzzles">Puzzling</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Culture / Recreation"><ul class="-list">
                <li class="-item"><a href="https://mechanics.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="mechanics and DIY enthusiast owners of cars, trucks, and motorcycles">Motor Vehicle Maintenance &amp; Repair</a></li>
                <li class="-item"><a href="https://boardgames.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people who like playing board games, designing board games or modifying the rules of existing board games">Board &amp; Card Games</a></li>
                <li class="-item"><a href="https://bricks.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="LEGO&#xAE; and building block enthusiasts">Bricks</a></li>
                <li class="-item"><a href="https://homebrew.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="dedicated home brewers and serious enthusiasts">Homebrewing</a></li>
                <li class="-item"><a href="https://martialarts.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="students and teachers of all martial arts">Martial Arts</a></li>
                <li class="-item"><a href="https://outdoors.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people who love being outdoors enjoying nature and wilderness, and learning about the required skills and equipment">The Great Outdoors</a></li>
                <li class="-item"><a href="https://poker.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="serious players and enthusiasts of poker">Poker</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Culture / Recreation"><ul class="-list">
                <li class="-item"><a href="https://chess.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="serious players and enthusiasts of chess">Chess</a></li>
                <li class="-item"><a href="https://sports.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="participants in team and individual sport activities">Sports</a></li>
                <li class="-item">
                    <a href="https://stackexchange.com/sites#culturerecreation" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 26 })">
                        <strong>
                            more (16)
                        </strong>
                    </a>
                </li>
        </ul>
    </div>
    <div class="site-footer--col site-footer--category js-footer-col" data-name="Science">
        <ul class="-list">
                <li class="-item"><a href="https://mathoverflow.net" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professional mathematicians">MathOverflow</a></li>
                <li class="-item"><a href="https://math.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people studying math at any level and professionals in related fields">Mathematics</a></li>
                <li class="-item"><a href="https://stats.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="people interested in statistics, machine learning, data analysis, data mining, and data visualization">Cross Validated (stats)</a></li>
                <li class="-item"><a href="https://cstheory.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="theoretical computer scientists and researchers in related fields">Theoretical Computer Science</a></li>
                <li class="-item"><a href="https://physics.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="active researchers, academics and students of physics">Physics</a></li>
                <li class="-item"><a href="https://chemistry.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="scientists, academics, teachers, and students in the field of chemistry">Chemistry</a></li>
                <li class="-item"><a href="https://biology.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="biology researchers, academics, and students">Biology</a></li>
                    </ul></div><div class="site-footer--col site-footer--category js-footer-col" data-name="Science"><ul class="-list">
                <li class="-item"><a href="https://cs.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="students, researchers and practitioners of computer science">Computer Science</a></li>
                <li class="-item"><a href="https://philosophy.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="those interested in the study of the fundamental nature of knowledge, reality, and existence">Philosophy</a></li>
                <li class="-item"><a href="https://linguistics.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="professional linguists and others with an interest in linguistic research and theory">Linguistics</a></li>
                <li class="-item"><a href="https://psychology.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="practitioners, researchers, and students in cognitive science, psychology, neuroscience, and psychiatry">Psychology &amp; Neuroscience</a></li>
                <li class="-item"><a href="https://scicomp.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="scientists using computers to solve scientific problems">Computational Science</a></li>
                <li class="-item">
                    <a href="https://stackexchange.com/sites#science" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 26 })">
                        <strong>
                            more (10)
                        </strong>
                    </a>
                </li>
        </ul>
    </div>
    <div class="site-footer--col site-footer--category js-footer-col" data-name="Other">
        <ul class="-list">
                <li class="-item"><a href="https://meta.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="meta-discussion of the Stack Exchange family of Q&amp;A websites">Meta Stack Exchange</a></li>
                <li class="-item"><a href="https://stackapps.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="apps, scripts, and development with the Stack Exchange API">Stack Apps</a></li>
                <li class="-item"><a href="https://api.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="programmatic interaction with Stack Exchange sites">API</a></li>
                <li class="-item"><a href="https://data.stackexchange.com" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 25 })" title="querying Stack Exchange data using SQL">Data</a></li>
        </ul>
    </div>

                </div>
            </nav>
            <div class="site-footer--copyright fs-fine">
                <ul class="-list">
                    <li class="-item"><a class="js-gps-track -link" data-gps-track="footer.click({ location: 2, link:4 })" href="https://stackoverflow.blog?blb=1">Blog</a></li>
                    <li class="-item"><a href="https://www.facebook.com/officialstackoverflow/" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 31 })">Facebook</a></li>
                    <li class="-item"><a href="https://twitter.com/stackoverflow" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 32 })">Twitter</a></li>
                    <li class="-item"><a href="https://linkedin.com/company/stack-overflow" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 33 })">LinkedIn</a></li>
                    <li class="-item"><a href="https://www.instagram.com/thestackoverflow" class="-link js-gps-track" data-gps-track="footer.click({ location: 2, link: 36 })">Instagram</a></li>
                </ul>

                <p class="mt-auto mb24">
site design / logo &#169; 2021 Stack Exchange Inc; user contributions licensed under <a href="https://stackoverflow.com/help/licensing">cc by-sa</a>.                    <span id="svnrev">rev&nbsp;2021.4.30.39183</span>
                </p>
            </div>
        </div>

    </footer>

            <script>StackExchange.ready(function () { StackExchange.responsiveness.addSwitcher(); })</script>
    <noscript>
        <div id="noscript-warning">Mathematics Stack Exchange works best with JavaScript enabled
            <img src="https://pixel.quantserve.com/pixel/p-c1rF4kxgLUzNc.gif" alt="" class="dno">
        </div>
    </noscript>

            <script>
(function(i, s, o, g, r, a, m) {
                i['GoogleAnalyticsObject'] = r; i[r] = i[r] || function() { (i[r].q = i[r].q || []).push(arguments) }, i[r].l = 1 * new Date(); a = s.createElement(o),
                m = s.getElementsByTagName(o)[0]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m);
            })(window, document, 'script', 'https://www.google-analytics.com/analytics.js', 'ga');

            StackExchange.ready(function () {

                StackExchange.ga.init({
                    autoLink: ["stackoverflow.blog","info.stackoverflowsolutions.com","stackoverflowsolutions.com"],
                    sendTitles: true,
                    tracker: window.ga,
                    trackingCodes: [
                        'UA-108242619-5'
                    ],
                        checkDimension: 'dimension42'
                });



                    StackExchange.ga.setDimension('dimension2', '|trigonometry|complex-numbers|');


                    StackExchange.ga.setDimension('dimension3', 'Questions/Show');


                StackExchange.ga.trackPageView();
            });
            
            var _qevents = _qevents || [],
            _comscore = _comscore || [];
            (function() {
                var s = document.getElementsByTagName('script')[0],
                    qc = document.createElement('script');
 qc.async = true;
                    qc.src = 'https://secure.quantserve.com/quant.js';
                    s.parentNode.insertBefore(qc, s);
                    _qevents.push({ qacct: "p-c1rF4kxgLUzNc" }); var sc = document.createElement('script');
                    sc.async = true;
                    sc.src = 'https://sb.scorecardresearch.com/beacon.js';
                    s.parentNode.insertBefore(sc, s);
                    _comscore.push({ c1: "2", c2: "17440561" });            })();
                </script>

        
    <div id="onetrust-consent-sdk" class="d-none"></div>
    <div id="onetrust-banner-sdk" data-controller="s-modal"></div>
    <div id="ot-pc-content" class="d-none"></div>
    <div id="onetrust-style" class="d-none">&nbsp;</div>
    <div class="d-none js-consent-banner-version" data-consent-banner-version="baseline"></div>

    
    </body>
    </html>
