curl - file\_get\_contents() equivalent for Node.JS - Stack Overflow                             StackExchange.ready(function () { StackExchange.using("snippets", function () { StackExchange.snippets.initSnippetRenderer(); }); StackExchange.using("postValidation", function () { StackExchange.postValidation.initOnBlurAndSubmit($('#post-form'), 2, 'answer'); }); StackExchange.question.init({showAnswerHelp:true,totalCommentCount:5,shownCommentCount:5,highlightColor:'#F4A83D',backgroundColor:'#FFF',questionId:8775549}); styleCode(); StackExchange.realtime.subscribeToQuestion('1', '8775549'); StackExchange.using("gps", function () { StackExchange.gps.trackOutboundClicks('#content', '.post-text'); }); });  StackExchange.init({"locale":"en","serverTime":1551104988,"routeName":"Questions/Show","stackAuthUrl":"https://stackauth.com","networkMetaHostname":"meta.stackexchange.com","site":{"name":"Stack Overflow","description":"Q&A for professional and enthusiast programmers","isNoticesTabEnabled":true,"enableNewTagCreationWarning":true,"insertSpaceAfterNameTabCompletion":false,"id":1,"childUrl":"https://meta.stackoverflow.com","enableSocialMediaInSharePopup":true,"protocol":"https"},"user":{"fkey":"cc807f16f82e55e35b9b0c611a5e7261a7363758db74349b6c8f6c482eff948a","tid":"fb24e5fb-c6a7-8ee0-4265-3d241606939f","rep":0,"isAnonymous":true,"isAnonymousNetworkWide":true,"ab":{"inline\_signup\_hero":{"v":"d","g":2}}},"events":{"postType":{"question":1},"postEditionSection":{"title":1,"body":2,"tags":3}},"story":{"minCompleteBodyLength":75,"likedTagsMaxLength":300,"dislikedTagsMaxLength":300},"jobPreferences":{"maxNumDeveloperRoles":2,"maxNumIndustries":4},"svgIconPath":"https://cdn.sstatic.net/Img/svg-icons","svgIconHash":"840d669a9425"}, {"site":{"allowImageUploads":true,"enableUserHovercards":true,"styleCode":true,"enableImgurHttps":true,"forceHttpsImages":true},"userMessaging":{},"comments":{},"userProfile":{"openGraphAPIKey":"58740831ad23540e00c58987"},"tags":{},"accounts":{"currentPasswordRequiredForChangingStackIdPassword":true},"flags":{"allowRetractingFlags":true},"snippets":{"snippetsEnabled":true,"renderDomain":"stacksnippets.net"},"paths":{},"markdown":{"asteriskIntraWordEmphasis":true},"monitoring":{"clientTimingsAbsoluteTimeout":30000,"clientTimingsDebounceTimeout":1000},"mentions":{"maxNumUsersInDropdown":50},"slack":{"sidebarAdDismissCookie":"slack-sidebar-ad"}}); StackExchange.using.setCacheBreakers({"js/prettify-full.en.js":"2e06b23a0034","js/moderator.en.js":"619f4a15a66c","js/full-anon.en.js":"51dfbc6ea2f1","js/full.en.js":"634f6e54d02f","js/wmd.en.js":"1f66510bcf93","js/mobile.en.js":"30ceeb5f5bf6","js/help.en.js":"5130ad7e2fb6","js/tageditor.en.js":"da9334be6f55","js/tageditornew.en.js":"b4ae46c9652d","js/inline-tag-editing.en.js":"bd4171ec162a","js/revisions.en.js":"7c33989afe1c","js/review.en.js":"48c8679b88e0","js/tagsuggestions.en.js":"78eee7c19ab2","js/post-validation.en.js":"47ba88f720b7","js/explore-qlist.en.js":"fdeebc5008d7","js/events.en.js":"205b3a68758a","js/keyboard-shortcuts.en.js":"29fefd588c69","js/external-editor.en.js":"7d20a0b245c2","js/adops.en.js":"22a9bd59b1e9","js/begin-edit-event.en.js":"7415f5dee62d","js/stacks-polyfills.en.js":"741d0b19e030","js/external-editor.en.js":"7d20a0b245c2","js/snippet-javascript.en.js":"3959ddc8f13f","js/snippet-javascript-codemirror.en.js":"e4dd894b2a2f"}); StackExchange.using("gps", function() { StackExchange.gps.init(true); }); 

<style>body,.top-bar{margin-top:1.9em}</style>

[](#)[Stack Overflow](https://stackoverflow.com)

 

6.  [Log In](https://stackoverflow.com/users/login?ssrc=head&returnurl=https%3a%2f%2fstackoverflow.com%2fquestions%2f8775549%2ffile-get-contents-equivalent-for-node-js) [Sign Up](https://stackoverflow.com/users/signup?ssrc=head&returnurl=%2fusers%2fstory%2fcurrent)
7.  ### [current community](https://stackoverflow.com)
    
    *   [
        
        Stack Overflow](https://stackoverflow.com)
        
        [help](https://stackoverflow.com/help) [chat](https://chat.stackoverflow.com)
        
    *   [
        
        Meta Stack Overflow](https://meta.stackoverflow.com)
    
    ### your communities
    
    [Sign up](https://stackoverflow.com/users/signup?ssrc=site_switcher&returnurl=%2fusers%2fstory%2fcurrent) or [log in](https://stackoverflow.com/users/login?ssrc=site_switcher&returnurl=https%3a%2f%2fstackoverflow.com%2fquestions%2f8775549%2ffile-get-contents-equivalent-for-node-js) to customize your list.
    
    ### [more stack exchange communities](https://stackexchange.com/sites)
    
    [company blog](https://stackoverflow.blog)
    
    *   [Tour Start here for a quick overview of the site](/tour)
    *   [Help Center Detailed answers to any questions you might have](/help)
    *   [Meta Discuss the workings and policies of this site](https://meta.stackoverflow.com)
    *   [About Us Learn more about Stack Overflow the company](https://stackoverflow.com/company/about)
    *   [Business Learn more about hiring developers or posting ads with us](https://www.stackoverflowbusiness.com/?ref=topbar_help)
    

By using our site, you acknowledge that you have read and understand our [Cookie Policy](https://stackoverflow.com/legal/cookie-policy), [Privacy Policy](https://stackoverflow.com/legal/privacy-policy), and our [Terms of Service](https://stackoverflow.com/legal/terms-of-service/public).

StackExchange.ready(function () { StackExchange.topbar.init({ observeSize: true }); }); StackExchange.scrollPadding.setPaddingTop(50, 10);

2.  [Home](/)
3.  1.  Public
    2.  [Stack Overflow](/questions)
    3.  [Tags](/tags)
    4.  [Users](/users)
    5.  [Jobs](/jobs?med=site-ui&ref=jobs-tab)
4.  1.  **Teams** Q&A for work [Learn More](https://stackoverflow.com/teams)
        

.everyoneloves\_\_top-leaderboard:empty,.everyoneloves\_\_mid-leaderboard:empty,.everyoneloves\_\_bot-mid-leaderboard:empty{ height:90px;width:728px;box-sizing:border-box; }

[file\_get\_contents() equivalent for Node.JS](/questions/8775549/file-get-contents-equivalent-for-node-js)
===========================================================================================================

[Ask Question](/questions/ask)

11

I was wondering if there was any `file_get_contents()` equivalents in Node.JS modules or elsewhere. It has to lock the process until the download is finished, so the existing `request()` code in Node.js won't work. While it doesn't need to read into the string, the locking, synchronous nature is important.

If this doesn't exist, is using CURL via the OS module an efficient way of handling the same process?

[node.js](/questions/tagged/node.js "show questions tagged 'node.js'") [curl](/questions/tagged/curl "show questions tagged 'curl'") [file-get-contents](/questions/tagged/file-get-contents "show questions tagged 'file-get-contents'")

[share](/q/8775549 "short permalink to this question")|[improve this question](/posts/8775549/edit)

asked Jan 8 '12 at 5:14

[

![](https://www.gravatar.com/avatar/89971741cc73d7bd85a619766c4bddaa?s=32&d=identicon&r=PG)

](/users/140448/kyle-hotchkiss)

[Kyle Hotchkiss](/users/140448/kyle-hotchkiss)Kyle Hotchkiss

3,835164675

*   What are you trying to do? Tell us what your goal is, not how you want to reach it. – [thejh](/users/492364/thejh "33,604 reputation") Jan 8 '12 at 9:55
    
*   Why do you think you have to lock the whole process? – [thejh](/users/492364/thejh "33,604 reputation") Jan 8 '12 at 9:57
    
*   If your requirement is locking the whole process, then NodeJS is definitely not the technology for you. Why not just use PHP? Then you can use `file_get_contents()` itself. – [rossipedia](/users/115049/rossipedia "32,854 reputation") Jan 8 '12 at 10:00
    
*   @BryanRoss: That's not a requirement, I'd say it's more like a lack of knowledge. – [thejh](/users/492364/thejh "33,604 reputation") Jan 8 '12 at 10:08
    
*   Yeah, I don't think in async just yet... an acquired taste type of thing maybe? – [Kyle Hotchkiss](/users/140448/kyle-hotchkiss "3,835 reputation") Jan 8 '12 at 19:55
    

add a comment | [](# "expand to show all comments on this post")

3 Answers 3
-----------

[active](/questions/8775549/file-get-contents-equivalent-for-node-js?answertab=active#tab-top "Answers with the latest activity first") [oldest](/questions/8775549/file-get-contents-equivalent-for-node-js?answertab=oldest#tab-top "Answers in the order they were provided") [votes](/questions/8775549/file-get-contents-equivalent-for-node-js?answertab=votes#tab-top "Answers with the highest score first")

4

No, there's not. Do it asynchronously: Do stuff, and when the download completes and you've buffered it all into one place, emit an event or call a callback to do the work on the whole blob.

[share](/a/8775565 "short permalink to this answer")|[improve this answer](/posts/8775565/edit)

answered Jan 8 '12 at 5:16

[

![](https://www.gravatar.com/avatar/81a40f031a3f886de3e4e5ad39dea0aa?s=32&d=identicon&r=PG)

](/users/306320/aredridel)

[aredridel](/users/306320/aredridel)aredridel

1,3981214

*   2
    
    haha! Maybe Node.JS isn't the language for this project! – [Kyle Hotchkiss](/users/140448/kyle-hotchkiss "3,835 reputation") Jan 8 '12 at 5:22
    
*   "buffered it all into one place" - sometimes you can also operate on a rechunked stream. – [thejh](/users/492364/thejh "33,604 reputation") Jan 8 '12 at 9:54
    
*   @KyleHotchkiss: Do you think you fully understand how node.js works? The evented and async patterns? – [thejh](/users/492364/thejh "33,604 reputation") Jan 8 '12 at 9:56
    
*   1
    
    Never claimed to fully understand node.js. Don't think that as a requirement to experiment with it or to ask a question on SO. Coming from browser JS, there are still plenty of constraints to work on. – [Kyle Hotchkiss](/users/140448/kyle-hotchkiss "3,835 reputation") Jan 8 '12 at 19:57
    
*   It's actually not hard to do: all of this is a few lines of code. But node doesn't let you stop the world while something happens: If there's something to do, node runs it. If not, it stops entirely while waiting. But you can usually do that by just not continuing until the network responds and the pieces have come together. sometimes working this way is a little like setting up dominoes then setting them all falling at once. But it works, and it frees up the process to do a LOT of other things while it waits. – [aredridel](/users/306320/aredridel "1,398 reputation") Jan 9 '12 at 2:07
    

add a comment | [](# "expand to show all comments on this post")

17

[`fs.readFileSync`](http://nodejs.org/api/fs.html#fs_fs_readfilesync_filename_options) appears to do what you're asking. From the manual:

> fs.readFileSync(filename, \[options\])
> --------------------------------------
> 
> Synchronous version of `fs.readFile`. Returns the contents of the `filename`.
> 
> If the `encoding` option is specified then this function returns a string. Otherwise it returns a buffer.

[share](/a/17742315 "short permalink to this answer")|[improve this answer](/posts/17742315/edit)

answered Jul 19 '13 at 9:13

[

![](https://www.gravatar.com/avatar/75667cc10d735ebc4dcc6d2c61e795e4?s=32&d=identicon&r=PG)

](/users/895497/wildlyinaccurate)

[WildlyInaccurate](/users/895497/wildlyinaccurate)WildlyInaccurate

631512

add a comment | [](# "expand to show all comments on this post")

10

    const fs = require('fs');
    var contents = fs.readFileSync('inject.txt').toString();
    

[share](/a/34601185 "short permalink to this answer")|[improve this answer](/posts/34601185/edit)

[edited Sep 24 '17 at 20:33](/posts/34601185/revisions "show all edits to this post")

answered Jan 4 '16 at 22:40

[

![](https://i.stack.imgur.com/6rTV9.png?s=32&g=1)

](/users/979474/user956584)

[user956584](/users/979474/user956584)user956584

3,54423143

add a comment | [](# "expand to show all comments on this post")

  

Your Answer
-----------

StackExchange.ifUsing("editor", function () { StackExchange.using("externalEditor", function () { StackExchange.using("snippets", function () { StackExchange.snippets.init(); }); }); }, "code-snippets"); StackExchange.ready(function() { var channelOptions = { tags: "".split(" "), id: "1" }; initTagRenderer("".split(" "), "".split(" "), channelOptions); StackExchange.using("externalEditor", function() { // Have to fire editor after snippets, if snippets enabled if (StackExchange.settings.snippets.snippetsEnabled) { StackExchange.using("snippets", function() { createEditor(); }); } else { createEditor(); } }); function createEditor() { StackExchange.prepareEditor({ heartbeatType: 'answer', autoActivateHeartbeat: false, convertImagesToLinks: true, noModals: true, showLowRepImageUploadWarning: true, reputationToPostImages: 10, bindNavPrevention: true, postfix: "", imageUploader: { brandingHtml: "Powered by \\u003ca class=\\"icon-imgur-white\\" href=\\"https://imgur.com/\\"\\u003e\\u003c/a\\u003e", contentPolicyHtml: "User contributions licensed under \\u003ca href=\\"https://creativecommons.org/licenses/by-sa/3.0/\\"\\u003ecc by-sa 3.0 with attribution required\\u003c/a\\u003e \\u003ca href=\\"https://stackoverflow.com/legal/content-policy\\"\\u003e(content policy)\\u003c/a\\u003e", allowUrls: true }, onDemand: true, discardSelector: ".discard-answer" ,immediatelyShowMarkdownHelp:true }); } });

Thanks for contributing an answer to Stack Overflow!

*   Please be sure to _answer the question_. Provide details and share your research!

But _avoid_ …

*   Asking for help, clarification, or responding to other answers.
*   Making statements based on opinion; back them up with references or personal experience.

To learn more, see our [tips on writing great answers](/help/how-to-answer).

draft saved

draft discarded

 

### Sign up or [log in](/users/login?ssrc=question_page&returnurl=https%3a%2f%2fstackoverflow.com%2fquestions%2f8775549%2ffile-get-contents-equivalent-for-node-js%23new-answer)

StackExchange.ready(function () { StackExchange.helpers.onClickDraftSave('#login-link'); var $window = $(window), onScroll = function(e) { var $elem = $('.new-login-left'), docViewTop = $window.scrollTop(), docViewBottom = docViewTop + $window.height(), elemTop = $elem.offset().top, elemBottom = elemTop + $elem.height(); if ((docViewTop < elemTop) && (docViewBottom > elemBottom)) { StackExchange.using('gps', function() { StackExchange.gps.track('embedded\_signup\_form.view', { location: 'question\_page' }); }); $window.unbind('scroll', onScroll); } }; $window.on('scroll', onScroll); });

Sign up using Google

Sign up using Facebook

Sign up using Email and Password

  

### Post as a guest

Name

Email

Required, but never shown

StackExchange.ready( function () { StackExchange.openid.initPostLogin('.new-post-login', 'https%3a%2f%2fstackoverflow.com%2fquestions%2f8775549%2ffile-get-contents-equivalent-for-node-js%23new-answer', 'question\_page'); } );

<h3 class="grid--cell fs-title">Post as a guest</h3> <div class="grid--cell"> <div class="grid gs4 gsy fd-column"> <label class="s-label" for="display-name">Name</label> <div class="grid ps-relative"> <input class="s-input" id="display-name" name="display-name" maxlength="30" type="text" value="" tabindex="105" placeholder="" /> </div> </div> </div> <div class="grid--cell"> <div class="grid gs4 gsy fd-column"> <div class="grid--cell"> <div class="grid gs2 gsy fd-column"> <label class="grid--cell s-label" for="m-address">Email</label> <p class="grid--cell s-description">Required, but never shown</p> </div> </div> <div class="grid ps-relative"> <input class="s-input" id="m-address" name="m-address" type="text" value="" size="40" tabindex="106" placeholder="" /> </div> </div> </div>

Post Your Answer Discard

By clicking "Post Your Answer", you acknowledge that you have read our updated [terms of service](https://stackoverflow.com/legal/terms-of-service/public), [privacy policy](https://stackoverflow.com/legal/privacy-policy) and [cookie policy](https://stackoverflow.com/legal/cookie-policy), and that your continued use of the website is subject to these policies.

Not the answer you're looking for? Browse other questions tagged [node.js](/questions/tagged/node.js "show questions tagged 'node.js'") [curl](/questions/tagged/curl "show questions tagged 'curl'") [file-get-contents](/questions/tagged/file-get-contents "show questions tagged 'file-get-contents'") or [ask your own question](/questions/ask).
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

asked

**7 years, 1 month ago**

viewed

**11,012 times**

active

**[1 year, 5 months ago](?lastactivity "2017-09-24 20:33:06Z")**

;try{(function(a){function b(a){return'string'==typeof a?document.getElementById(a):a}function c(a){return a=b(a),!!a&&'none'===getComputedStyle(a).display}function d(a){return!c(a)}function e(a){return!!a}function f(a){return /^\\s\*$/.test(b(a).innerHTML)}function g(a){var b=a.style;b.height=b.maxHeight=b.minHeight='auto',b.display='none',\[\].forEach.call(a.children,g)}function h(a,b){var c;return function(){return a&&(c=a.call(b||this,arguments),a=null),c}}function i(a){var b=document.createElement('script');b.src=a,document.body.appendChild(b)}function j(a){return k(\[\],a)}function k(a,b){return a.push=function(a){return b(),delete this.push,this.push(a)},a}function l(){try{return!new Function('return async()=>{};')}catch(a){return!0}}function m(){return'undefined'!=typeof googletag&&!!googletag.apiReady}function n(){m()||(googletag={cmd:j(A)})}function o(){var a=document.createElement('div');a.className='adsbox',a.id='clc-abd',a.style.position='absolute',a.style.pointerEvents='none',a.innerHTML='&nbsp;',document.body.appendChild(a)}function p(a){var b=a.serviceName,c=a.slot,d=a.lineItemId;try{var e=c.getSlotElementId(),f=\[\];e||f.push('id=0');var h=document.getElementById(e);if(!e||h?h.hasAttribute('data-clc-stalled')&&f.push('st=1'):f.push('el=0'),0!==f.length)return void B(f.join('&'));-1===x.dh.indexOf(d)?h.setAttribute('data-clc-prefilled','true'):g(h),h.setAttribute('data-clc-ready','true')}catch(a){var i=document.querySelector('#dfp-tsb, #dfp-isb, #clc-tsb');i&&i.setAttribute('data-clc-ready','true'),B('e=1')}}function q(){return Object.keys(F.ids)}function r(a){var b=F.ids\[a\],c=F.slots\[b\];'function'==typeof c&&(c=c(a));return{path:'/'+C+'/'+E+'/'+b+'/'+D,sizes:c,zone:b}}function s(a){return!(clc.collapse&&void 0!==clc.collapse\[a\])||!!clc.collapse\[a\]}function t(a,b){'dfp-isb'===a&&b.setTargeting('Sidebar',\['Inline'\]),'dfp-tsb'===a&&b.setTargeting('Sidebar',\['Right'\]);var c=r(a),d=c.path,e=c.sizes,f=c.zone,g=googletag.defineSlot(d,e,a);s(f)&&g.setCollapseEmptyDiv(!0,!0),g.addService(b),!1}function u(b){var c=a.dfp&&a.dfp.targeting||{};Object.keys(c).forEach(function(a){b.setTargeting(a,c\[a\])})}function v(a){var g=a.map(b).filter(e);return{eligible:g.filter(f).filter(d).map(function(a){return a.id}),ineligible:g.filter(c)}}function w(b){if(void 0===b&&(b=q()),!m())return n(),void googletag.cmd.push(function(){return w(b)});var c=v(b),d=c.eligible,e=c.ineligible;if(e.forEach(g),0!==d.length){o(),googletag.destroySlots();var f=googletag.pubads();f.enableSingleRequest(),a.sreEvent||(f.addEventListener('slotRenderEnded',p),a.sreEvent=!0),u(f),d.forEach(function(a){return t(a,f)}),googletag.enableServices(),d.forEach(function(a){googletag.display(a)})}}var x=function(a){for(var b=\[\],c=1;c<arguments.length;c++)b\[c-1\]=arguments\[c\];for(var d,e=0,f=b;e<f.length;e++)for(var g in d=f\[e\],d)a\[g\]=d\[g\];return a}({"lib":"https://cdn.sstatic.net/clc/clc.min.js?v=04d772c81312","style":"https://cdn.sstatic.net/clc/styles/clc.min.css?v=768595a6d237","u":"https://clc.stackoverflow.com/markup.js","wa":true,"kt":2000,"tto":true,"h":"clc.stackoverflow.com","allowed":"^(((talent\\\\.)?stackoverflow)|(blog\\\\.codinghorror)|(serverfault|askubuntu)|(\[^\\\\.\]+\\\\.stackexchange))\\\\.com$","wv":true,"al":false,"dh":\[4385506061,4386578282,4386579572\]},a.options||{}),y=h(function(){var a=x.lib;l()&&(a=a.replace(/(\\.min)?\\.js(\\?v=\[0-9a-fA-F\]+)?$/,'.ie$1.js$2')),i(a)}),z=a.cmd||\[\];Array.isArray(z)&&(0<z.length?y():k(z,y));var A=h(function(){i('https://www.googletagservices.com/tag/js/gpt.js')}),B=function(a){new Image().src='https://'+x.h+'/stalled.gif?'+a},C='248424177',D=/^\\/tags\\//.test(location.pathname)||/^\\/questions\\/tagged\\//.test(location.pathname)?'tag-pages':'question-pages',E=location.hostname;var F={slots:{lb:\[\[728,90\]\],mlb:\[\[728,90\]\],smlb:\[\[728,90\]\],bmlb:\[\[728,90\]\],sb:function(a){return'dfp-tsb'===a?\[\[300,250\],\[300,600\]\]:\[\[300,250\]\]},"tag-sponsorship":\[\[730,135\]\],"mobile-below-question":\[\[320,50\],\[300,250\]\]},ids:{"dfp-tlb":'lb',"dfp-mlb":'mlb',"dfp-smlb":'smlb',"dfp-bmlb":'bmlb',"dfp-tsb":'sb',"dfp-isb":'sb',"dfp-tag":'tag-sponsorship',"dfp-m-aq":'mobile-below-question',"clc-tlb":'lb',"clc-mlb":'mlb',"clc-tsb":'sb'}};(function(){var b=x.al;b&&z.push(function(){return a.load()})})(),n(),a.dfp={load:w},a.options=x,a.cmd=z})(this.clc=this.clc||{})}catch(a){window.console.error(a)} var clc = clc || {}; clc.collapse = { sb: !0,'tag-sponsorship':!0,lb:!1,mlb:!1,smlb:!1,bmlb:!1,'mobile-below-question':!0}; clc.cmd = clc.cmd || \[\]; clc.cmd.push(function () { window.clc\_request='AvHeNrItm9YIAAAAAH3nhQACAAAAAgAAAAAgAAAAfG5vZGUuanN8Y3VybHxmaWxlLWdldC1jb250ZW50c3wAVNt01E\_vVSXwJQ'; clc.load(); }); clc.dfp = clc.dfp || {}; clc.dfp.targeting = {Registered:\['false'\],'so-tag':\['node.js','curl','file-get-contents'\]}; var googletag = googletag || {}; googletag.cmd = googletag.cmd || \[\]; googletag.cmd.push(function () { clc.dfp.load(); });

#### Related

[

1460

](/q/1911015 "Vote score (upvotes - downvotes)")[How do I debug Node.js applications?](/questions/1911015/how-do-i-debug-node-js-applications)

[

1265

](/q/2353818 "Vote score (upvotes - downvotes)")[How do I get started with Node.js](/questions/2353818/how-do-i-get-started-with-node-js)

[

1322

](/q/2496710 "Vote score (upvotes - downvotes)")[Writing files in Node.js](/questions/2496710/writing-files-in-node-js)

[

271

](/q/3629784 "Vote score (upvotes - downvotes)")[How is Node.js inherently faster when it still relies on Threads internally?](/questions/3629784/how-is-node-js-inherently-faster-when-it-still-relies-on-threads-internally)

[

2022

](/q/4351521 "Vote score (upvotes - downvotes)")[How do I pass command line arguments to a Node.js program?](/questions/4351521/how-do-i-pass-command-line-arguments-to-a-node-js-program)

[

1133

](/q/4870328 "Vote score (upvotes - downvotes)")[Read environment variables in Node.js](/questions/4870328/read-environment-variables-in-node-js)

[

2199

](/q/5062614 "Vote score (upvotes - downvotes)")[How to decide when to use Node.js?](/questions/5062614/how-to-decide-when-to-use-node-js)

[

1537

](/q/5266152 "Vote score (upvotes - downvotes)")[How to exit in Node.js](/questions/5266152/how-to-exit-in-node-js)

[

1315

](/q/5311334 "Vote score (upvotes - downvotes)")[What is the purpose of Node.js module.exports and how do you use it?](/questions/5311334/what-is-the-purpose-of-node-js-module-exports-and-how-do-you-use-it)

[

1394

](/q/6237295 "Vote score (upvotes - downvotes)")[How can I update NodeJS and NPM to the next versions?](/questions/6237295/how-can-i-update-nodejs-and-npm-to-the-next-versions)

#### [Hot Network Questions](https://stackexchange.com/questions?tab=hot)

*   [Reading Mishnayos without understanding](https://judaism.stackexchange.com/questions/99840/reading-mishnayos-without-understanding)
*   [How to fly a direct entry holding pattern when approaching from an awkward angle?](https://aviation.stackexchange.com/questions/60486/how-to-fly-a-direct-entry-holding-pattern-when-approaching-from-an-awkward-angle)
*   [Need help with a circuit diagram where the motor does not seem to have any connection to ground. Error with diagram? Or am i missing something?](https://electronics.stackexchange.com/questions/424258/need-help-with-a-circuit-diagram-where-the-motor-does-not-seem-to-have-any-conne)
*   [How to deal with an underperforming subordinate?](https://workplace.stackexchange.com/questions/129926/how-to-deal-with-an-underperforming-subordinate)
*   [Does the US government have any planning in place to ensure there's no shortages of food, fuel, steel and other commodities?](https://politics.stackexchange.com/questions/39012/does-the-us-government-have-any-planning-in-place-to-ensure-theres-no-shortages)
*   [Why did Luke use his left hand to shoot?](https://scifi.stackexchange.com/questions/206011/why-did-luke-use-his-left-hand-to-shoot)
*   [How to write cases in LaTeX?](https://tex.stackexchange.com/questions/476591/how-to-write-cases-in-latex)
*   [Case protection with emphasis in biblatex](https://tex.stackexchange.com/questions/476546/case-protection-with-emphasis-in-biblatex)
*   [Boss asked me to sign a resignation paper without a date on it along with my new contract](https://workplace.stackexchange.com/questions/129607/boss-asked-me-to-sign-a-resignation-paper-without-a-date-on-it-along-with-my-new)
*   [How bad is a Computer Science course that doesn't teach Design Patterns?](https://cseducators.stackexchange.com/questions/5417/how-bad-is-a-computer-science-course-that-doesnt-teach-design-patterns)
*   [Concatenating two int\[\]](https://stackoverflow.com/questions/54864223/concatenating-two-int)
*   [Why did Ylvis use "go" instead of "say" in phrases like "Dog goes 'woof'"?](https://english.stackexchange.com/questions/486885/why-did-ylvis-use-go-instead-of-say-in-phrases-like-dog-goes-woof)
*   [I have trouble understanding this fallacy: "If A, then B. Therefore if not-B, then not-A."](https://philosophy.stackexchange.com/questions/60623/i-have-trouble-understanding-this-fallacy-if-a-then-b-therefore-if-not-b-th)
*   [Potential client has a problematic employee I can't work with](https://workplace.stackexchange.com/questions/130112/potential-client-has-a-problematic-employee-i-cant-work-with)
*   [Allow console draw poker game to output more hands](https://codereview.stackexchange.com/questions/214221/allow-console-draw-poker-game-to-output-more-hands)
*   [Website seeing my Facebook data?](https://security.stackexchange.com/questions/204218/website-seeing-my-facebook-data)
*   [Single-row INSERT...SELECT much slower than separate SELECT](https://dba.stackexchange.com/questions/230651/single-row-insert-select-much-slower-than-separate-select)
*   [Why did Mr. Elliot have to decide whose boots were thickest in "Persuasion"?](https://literature.stackexchange.com/questions/9462/why-did-mr-elliot-have-to-decide-whose-boots-were-thickest-in-persuasion)
*   [Can a player sacrifice a creature after declaring that creature as blocker while taking lethal damage?](https://boardgames.stackexchange.com/questions/45276/can-a-player-sacrifice-a-creature-after-declaring-that-creature-as-blocker-while)
*   [Co-worker sabotaging/undoing my work](https://workplace.stackexchange.com/questions/130065/co-worker-sabotaging-undoing-my-work)
*   [Charging phone battery with a lower voltage, coming from a bike charger?](https://electronics.stackexchange.com/questions/424251/charging-phone-battery-with-a-lower-voltage-coming-from-a-bike-charger)
*   [Is there a way to pause a running process on Linux systems and resume later?](https://unix.stackexchange.com/questions/502065/is-there-a-way-to-pause-a-running-process-on-linux-systems-and-resume-later)
*   [How to create a label containing values from different layers in QGIS](https://gis.stackexchange.com/questions/313464/how-to-create-a-label-containing-values-from-different-layers-in-qgis)
*   [Sharepoint metadata URL](https://sharepoint.stackexchange.com/questions/258373/sharepoint-metadata-url)

[more hot questions](#)

[question feed](/feeds/question/8775549 "feed of this question and its answers")

StackExchange.ready(function(){$.get('/posts/8775549/ivc/f506');});

<div><img src="/posts/8775549/ivc/f506" class="dno" alt="" width="0" height="0"></div>

lang-js

##### [Stack Overflow](https://stackoverflow.com)

*   [Questions](/questions)
*   [Jobs](https://stackoverflow.com/jobs)
*   [Developer Jobs Directory](https://stackoverflow.com/jobs/directory/developer-jobs)
*   [Salary Calculator](https://stackoverflow.com/jobs/salary)
*   [Help](/help)
*   Mobile

##### [Products](https://www.stackoverflowbusiness.com)

*   [Teams](https://stackoverflow.com/teams)
*   [Talent](https://www.stackoverflowbusiness.com/talent)
*   [Engagement](https://www.stackoverflowbusiness.com/advertise)
*   [Enterprise](https://stackoverflow.com/enterprise)

##### [Company](https://stackoverflow.com/company/about)

*   [About](https://stackoverflow.com/company/about)
*   [Press](https://stackoverflow.com/company/press)
*   [Work Here](https://stackoverflow.com/company/work-here)
*   [Legal](https://stackoverflow.com/legal)
*   [Privacy Policy](https://stackoverflow.com/legal/privacy-policy)
*   [Contact Us](https://stackoverflow.com/company/contact)

[](#)

##### [Stack Exchange  
Network](https://stackexchange.com)

*   [Technology](#)
*   [Life / Arts](#)
*   [Culture / Recreation](#)
*   [Science](#)
*   [Other](#)

*   [Stack Overflow](https://stackoverflow.com "professional and enthusiast programmers")
*   [Server Fault](https://serverfault.com "system and network administrators")
*   [Super User](https://superuser.com "computer enthusiasts and power users")
*   [Web Applications](https://webapps.stackexchange.com "power users of web applications")
*   [Ask Ubuntu](https://askubuntu.com "Ubuntu users and developers")
*   [Webmasters](https://webmasters.stackexchange.com "pro webmasters")
*   [Game Development](https://gamedev.stackexchange.com "professional and independent game developers")

*   [TeX - LaTeX](https://tex.stackexchange.com "users of TeX, LaTeX, ConTeXt, and related typesetting systems")
*   [Software Engineering](https://softwareengineering.stackexchange.com "professionals, academics, and students working within the systems development life cycle")
*   [Unix & Linux](https://unix.stackexchange.com "users of Linux, FreeBSD and other Un*x-like operating systems")
*   [Ask Different (Apple)](https://apple.stackexchange.com "power users of Apple hardware and software")
*   [WordPress Development](https://wordpress.stackexchange.com "WordPress developers and administrators")
*   [Geographic Information Systems](https://gis.stackexchange.com "cartographers, geographers and GIS professionals")
*   [Electrical Engineering](https://electronics.stackexchange.com "electronics and electrical engineering professionals, students, and enthusiasts")

*   [Android Enthusiasts](https://android.stackexchange.com "enthusiasts and power users of the Android operating system")
*   [Information Security](https://security.stackexchange.com "information security professionals")
*   [Database Administrators](https://dba.stackexchange.com "database professionals who wish to improve their database skills and learn from others in the community")
*   [Drupal Answers](https://drupal.stackexchange.com "Drupal developers and administrators")
*   [SharePoint](https://sharepoint.stackexchange.com "SharePoint enthusiasts")
*   [User Experience](https://ux.stackexchange.com "user experience researchers and experts")
*   [Mathematica](https://mathematica.stackexchange.com "users of Wolfram Mathematica")

*   [Salesforce](https://salesforce.stackexchange.com "Salesforce administrators, implementation experts, developers and anybody in-between")
*   [ExpressionEngine® Answers](https://expressionengine.stackexchange.com "administrators, end users, developers and designers for ExpressionEngine® CMS")
*   [Stack Overflow em Português](https://pt.stackoverflow.com "programadores profissionais e entusiastas")
*   [Blender](https://blender.stackexchange.com "people who use Blender to create 3D graphics, animations, or games")
*   [Network Engineering](https://networkengineering.stackexchange.com "network engineers")
*   [Cryptography](https://crypto.stackexchange.com "software developers, mathematicians and others interested in cryptography")
*   [Code Review](https://codereview.stackexchange.com "peer programmer code reviews")

*   [Magento](https://magento.stackexchange.com "users of the Magento e-Commerce platform")
*   [Software Recommendations](https://softwarerecs.stackexchange.com "people seeking specific software recommendations")
*   [Signal Processing](https://dsp.stackexchange.com "practitioners of the art and science of signal, image and video processing")
*   [Emacs](https://emacs.stackexchange.com "those using, extending or developing Emacs")
*   [Raspberry Pi](https://raspberrypi.stackexchange.com "users and developers of hardware and software for Raspberry Pi")
*   [Stack Overflow на русском](https://ru.stackoverflow.com "программистов")
*   [Programming Puzzles & Code Golf](https://codegolf.stackexchange.com "programming puzzle enthusiasts and code golfers")

*   [Stack Overflow en español](https://es.stackoverflow.com "programadores y profesionales de la informática")
*   [Ethereum](https://ethereum.stackexchange.com "users of Ethereum, the decentralized application platform and smart contract enabled blockchain")
*   [Data Science](https://datascience.stackexchange.com "Data science professionals, Machine Learning specialists, and those interested in learning more about the field")
*   [Arduino](https://arduino.stackexchange.com "developers of open-source hardware and software that is compatible with Arduino")
*   [Bitcoin](https://bitcoin.stackexchange.com "Bitcoin crypto-currency enthusiasts")
*   [**more (31)**](https://stackexchange.com/sites#technology)

*   [Photography](https://photo.stackexchange.com "professional, enthusiast and amateur photographers")
*   [Science Fiction & Fantasy](https://scifi.stackexchange.com "science fiction and fantasy enthusiasts")
*   [Graphic Design](https://graphicdesign.stackexchange.com "Graphic Design professionals, students, and enthusiasts")
*   [Movies & TV](https://movies.stackexchange.com "movie and tv enthusiasts")
*   [Music: Practice & Theory](https://music.stackexchange.com "musicians, students, and enthusiasts")
*   [Worldbuilding](https://worldbuilding.stackexchange.com "writers/artists using science, geography and culture to construct imaginary worlds and settings")
*   [Seasoned Advice (cooking)](https://cooking.stackexchange.com "professional and amateur chefs")

*   [Home Improvement](https://diy.stackexchange.com "contractors and serious DIYers")
*   [Personal Finance & Money](https://money.stackexchange.com "people who want to be financially literate")
*   [Academia](https://academia.stackexchange.com "academics and those enrolled in higher education")
*   [Law](https://law.stackexchange.com "legal professionals, students, and others with experience or interest in law")
*   [**more (15)**](https://stackexchange.com/sites#lifearts)

*   [English Language & Usage](https://english.stackexchange.com "linguists, etymologists, and serious English language enthusiasts")
*   [Skeptics](https://skeptics.stackexchange.com "scientific skepticism")
*   [Mi Yodeya (Judaism)](https://judaism.stackexchange.com "those who base their lives on Jewish law and tradition and anyone interested in learning more")
*   [Travel](https://travel.stackexchange.com "road warriors and seasoned travelers")
*   [Christianity](https://christianity.stackexchange.com "committed Christians, experts in Christianity and those interested in learning more")
*   [English Language Learners](https://ell.stackexchange.com "speakers of other languages learning English")
*   [Japanese Language](https://japanese.stackexchange.com "students, teachers, and linguists wanting to discuss the finer points of the Japanese language")

*   [Arqade (gaming)](https://gaming.stackexchange.com "passionate videogamers on all platforms")
*   [Bicycles](https://bicycles.stackexchange.com "people who build and repair bicycles, people who train cycling, or commute on bicycles")
*   [Role-playing Games](https://rpg.stackexchange.com "gamemasters and players of tabletop, paper-and-pencil role-playing games")
*   [Anime & Manga](https://anime.stackexchange.com "anime and manga fans")
*   [Puzzling](https://puzzling.stackexchange.com "those who create, solve, and study puzzles")
*   [Motor Vehicle Maintenance & Repair](https://mechanics.stackexchange.com "mechanics and DIY enthusiast owners of cars, trucks, and motorcycles")
*   [**more (33)**](https://stackexchange.com/sites#culturerecreation)

*   [MathOverflow](https://mathoverflow.net "professional mathematicians")
*   [Mathematics](https://math.stackexchange.com "people studying math at any level and professionals in related fields")
*   [Cross Validated (stats)](https://stats.stackexchange.com "people interested in statistics, machine learning, data analysis, data mining, and data visualization")
*   [Theoretical Computer Science](https://cstheory.stackexchange.com "theoretical computer scientists and researchers in related fields")
*   [Physics](https://physics.stackexchange.com "active researchers, academics and students of physics")
*   [Chemistry](https://chemistry.stackexchange.com "scientists, academics, teachers, and students in the field of chemistry")
*   [Biology](https://biology.stackexchange.com "biology researchers, academics, and students")

*   [Computer Science](https://cs.stackexchange.com "students, researchers and practitioners of computer science")
*   [Philosophy](https://philosophy.stackexchange.com "those interested in the study of the fundamental nature of knowledge, reality, and existence")
*   [**more (10)**](https://stackexchange.com/sites#science)

*   [Meta Stack Exchange](https://meta.stackexchange.com "meta-discussion of the Stack Exchange family of Q&A websites")
*   [Stack Apps](https://stackapps.com "apps, scripts, and development with the Stack Exchange API")
*   [API](https://api.stackexchange.com "programmatic interaction with Stack Exchange sites")
*   [Data](https://data.stackexchange.com "querying Stack Exchange data using SQL")
*   [Area 51](https://area51.stackexchange.com "proposing new sites in the Stack Exchange network")

*   [Blog](https://stackoverflow.blog?blb=1)
*   [Facebook](https://www.facebook.com/officialstackoverflow/)
*   [Twitter](https://twitter.com/stackoverflow)
*   [LinkedIn](https://linkedin.com/company/stack-overflow)

site design / logo © 2019 Stack Exchange Inc; user contributions licensed under [cc by-sa 3.0](https://creativecommons.org/licenses/by-sa/3.0/) with [attribution required](https://stackoverflow.blog/2009/06/25/attribution-required/). rev 2019.2.25.32935

StackExchange.ready(function () { StackExchange.responsiveness.addSwitcher(); })

<div id="noscript-warning">Stack Overflow works best with JavaScript enabled <img src="https://pixel.quantserve.com/pixel/p-c1rF4kxgLUzNc.gif" alt="" class="dno"> </div>

(function(i, s, o, g, r, a, m) { i\['GoogleAnalyticsObject'\] = r; i\[r\] = i\[r\] || function() { (i\[r\].q = i\[r\].q || \[\]).push(arguments) }, i\[r\].l = 1 \* new Date(); a = s.createElement(o), m = s.getElementsByTagName(o)\[0\]; a.async = 1; a.src = g; m.parentNode.insertBefore(a, m); })(window, document, 'script', 'https://www.google-analytics.com/analytics.js', 'ga'); StackExchange.ready(function () { StackExchange.ga.init({ sendTitles: true, tracker: window.ga, trackingCodes: \[ 'UA-108242619-1' \] }); StackExchange.ga.setDimension('dimension2', '|node.js|curl|file-get-contents|'); StackExchange.ga.setDimension('dimension3', 'Questions/Show'); StackExchange.ga.trackPageView(); }); /\*\*/ var \_qevents = \_qevents || \[\], \_comscore = \_comscore || \[\]; (function() { var ssl = 'https:' == document.location.protocol, s = document.getElementsByTagName('script')\[0\], qc = document.createElement('script'); qc.async = true; qc.src = (ssl ? 'https://secure' : 'http://edge') + '.quantserve.com/quant.js'; s.parentNode.insertBefore(qc, s); \_qevents.push({ qacct: "p-c1rF4kxgLUzNc" }); /\*\*/ var sc = document.createElement('script'); sc.async = true; sc.src = (ssl ? 'https://sb' : 'http://b') + '.scorecardresearch.com/beacon.js'; s.parentNode.insertBefore(sc, s); \_comscore.push({ c1: "2", c2: "17440561" }); })();
