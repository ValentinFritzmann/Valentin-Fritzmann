/*
body.listing-page > .content:before {
    content: "This is a test announcement";
    display: block;
    background: #638be4;
    color: rgba(255, 255, 255, 0.8);
    padding: 0 8px;
    font-family: Helvetica, sans-serif;
    font-size: 14px;
    height: 32px;
    line-height: 32px;
    opacity: 0.9;
}
*/

/* Listing page announcement (Sidebar) */

.side .usertext-body h3:first-of-type {
    display: none;
    background: #638be4;
    color: rgba(255, 255, 255, 0.9);
    padding: 0 8px 0 10px;
    font-family: Helvetica, sans-serif;
    font-size: 14px;
    height: 38px;
    line-height: 38px;
    opacity: 0.9;
    position: absolute;
    z-index: 9;
    border: none;
    left: 41px;
    right: 341px;
    width: auto;
    top: 162px;
    text-align: left;
    font-weight: normal;
}

.listing-page .side .usertext-body h3:first-of-type {
    display: block;
}

.side .usertext-body h3:first-of-type a {
    color: #ADD8E6;
}

body.listing-page > .content {
    padding-top: 34px !important;
}

/* End of sidebar announcement */

body {
    background: #2c404a;
}
body > .content {
    position: relative;
    top: 12px;
    margin-left: 40px;
    margin-right: 340px;
    margin-bottom: 60px;
    background: #fff;
    padding: 0;
    padding-top: 1px;
    position: relative;
    border: 1px solid #1c323b;
    border-top: none;
}

.tabmenu {
    position: absolute;
    left: 40px;
    top: 130px;
    right: 340px;
    background: #638be4;
    height: 40px;
    padding: 0;
    margin: 0;
    padding-left: 108px;
    border: 1px solid #1c323b;
    border-bottom: none;
}

/* Menu colours and info bars for tags */

body.post-linkflair-indepth > .content:before,
body.post-linkflair-mega > .content:before,
body.post-linkflair-selfie > .content:before,
body.post-linkflair-advice > .content:before,
body.post-linkflair-vent > .content:before,
body.post-linkflair-locked > .content:before,
body.post-linkflair-random > .content:before {
    display: block;
    color: rgba(255, 255, 255, 0.8);
    padding: 0 8px 0 13px;
    font-family: Helvetica, sans-serif;
    font-size: 14px;
    height: 32px;
    line-height: 32px;
}

body.post-linkflair-indepth .tabmenu {
    background: #a876ff;
}
body.post-linkflair-indepth > .content:before {
    content: "This is an in-depth thread, top level comments should be elaborative and at least around 250 characters long.";
    background: #a876ff;
    opacity: 0.9;
}

body.post-linkflair-mega .tabmenu {
    background: #4ec6c6;
}
body.post-linkflair-mega > .content:before {
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    background: #4ec6c6;
    opacity: 0.9;
}

body.post-linkflair-selfie .tabmenu {
    background: #4C69DB;
}
body.post-linkflair-selfie > .content:before {
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    background: #4C69DB;
    opacity: 0.9;
}

body.post-linkflair-advice .tabmenu {
    background: #6B4CDB;
}
body.post-linkflair-advice > .content:before {
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    background: #6B4CDB;
    opacity: 0.9;
}

body.post-linkflair-vent .tabmenu {
    background: #964CDB;
}
body.post-linkflair-vent > .content:before {
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    content: "This is a megathread, most if not all other threads related to this topic will be removed.";
    background: #964CDB;
    opacity: 0.9;
}

body.post-linkflair-random .tabmenu {
    background: #ffb263;
}
body.post-linkflair-random > .content:before {
    content: "This is a random thread, the thread will be sorted in contest mode.";
    background: #ffb263;
    opacity: 0.9;
}

body.post-linkflair-locked .tabmenu {
    background: #dd7680;
}
body.post-linkflair-locked > .content:before {
    content: "This thread has been locked, any new comments will be removed. Sort comments by /new to see why.";
    content: "This thread has been locked, any new comments will be removed. Sort comments by /new to see why.";
    background: #dd7680;
    opacity: 0.9;
}

body.post-linkflair-modpost .tabmenu {
    background: #4fc761;
}

body.post-linkflair-removed .tabmenu {
    background: #999;
}

body.post-linkflair-random .tabmenu {
    background: #ffb263;
}

body.post-linkflair-community .tabmenu {
    background: #65a4ed;
}

body.post-linkflair-neat .tabmenu {
    background: #edc365;
}

.content .tabmenu {
    position: static;
    display: block;
    padding-left: 0;
    border: none;
}
.tabmenu.formtab {
    padding-left: 0 !important;
}
.tabmenu.formtab a {
    border: none;
}
.formtabs-content {
    border-top: none;
}
.tabmenu.formtab .selected a {
    background-color: #4C69DB !important;
}
body:not(.listing-page) .tabmenu {
    padding-left: 4px;
}
.tabmenu li {
    margin: 0;
}
.tabmenu li a {
    margin: 0;
    display: inline-block;
    height: 100%;
    border: none;
    padding: 0 8px;
    line-height: 40px;
    color: rgba(255, 255, 255, 0.7);
    font-weight: normal;
    background: transparent;
}
.tabmenu li.selected a {
    border: none;
    color: rgba(255, 255, 255, 0.9);
    background: transparent;
}
#header {
    /*background: #1c323b;*/
    background: rgb(38, 71, 108) url(http://b.thumbs.redditmedia.com/ie2721t-EOmoPODTqPSLSkJswhpontHNcL5srZSd36E.jpg) 0 0 repeat;
    background-size: 600px;
    /*background: #1c323b url(http://b.thumbs.redditmedia.com/ie2721t-EOmoPODTqPSLSkJswhpontHNcL5srZSd36E.jpg) 0 0 repeat;*/
    height: 150px;
    border-bottom: 1px solid #1c323b !important;
    position: relative;
    z-index: 9999;
}
#sr-header-area {
    background-color: rgba(255, 255, 255, 0.05);
    border: none;
    /*margin-right: 400px;*/
    height: 26px;
}
#sr-header-area .width-clip,
#RESShortcutsViewport {
    margin-right: 400px;
    padding-right: 60px;
}
#sr-more-link {
    background: transparent;
}
#sr-header-area a {
    color: #fff;
    line-height: 26px;
}
#sr-header-area span {
    line-height: 26px;
}
#sr-header-area:hover #RESShortcutsEditContainer {
    opacity: 1 !important;
}
#RESShortcutsEditContainer {
    opacity: 0 !important;
    right: 400px !important;
    background: #1c323b !important;
    height: 26px !important;
}
#RESShortcutsEditContainer div {
    background: transparent !important;
    line-height: 23px !important;
}

#header-img.default-header, #header-img {
					z-index: 99;
					width: 0px;
					padding-left: 48px;
					height: 48px;
					background-image: url(http://b.thumbs.redditmedia.com/9IPvkgAuGs3mfvpzwBLPzhZzqy658GrKU2iUuIChC2k.png);
					background-position: -208px -48px;
					position: relative;
					top: 0px;
					margin: 0;
				}

					#header-img.default-header:hover, #header-img:hover {background-position: -208px -96px;}


			 	

/*end*/

#header-img {
display: none;
}
#header-bottom-left > span {
    position: absolute;
    top: 55px;
    left: 95px;
    display: inline-block;
}


#header-bottom-left > span a {
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    font-weight: 300;
    font-size: 0px;
    color: #fff;
    width: 435px;
    height: 45px;
    background-image: url(http://b.thumbs.redditmedia.com/e6FA89qFvYCyDXBp2M3-6Z2lqcTubLL4WPU3xuAkG9M.png);
    background-size: 85%;
    background-repeat: no-repeat;
    display: block;
}


#header-bottom-right {
    background: rgba(255, 255, 255, 0);
    top: 0 !important;
    right: 0;
    padding: 0 !important;
    height: 26px !important;
    line-height: 26px;
    padding-left: 8px !important;
    padding-right: 8px !important;
    color: #fff;
}
#header-bottom-right .user {
    font-size: 0px;
}
#header-bottom-right .user > a {
    font-size: 13px;
}
#header-bottom-right a {
    color: #fff;
}
#userbarToggle {
    background: rgba(255, 255, 255, 0) !important;
    border-radius: 0 !important;
    border: 0 !important;
    left: 0 !important;
    top: 0 !important;
    height: 25px !important;
}
#RESAccountSwitcherIcon {
    position: relative;
    top: -4px;
}
.userattrs {
    font-size: 0;
}
.userattrs a {
    background: #aaa;
    width: 15px;
    height: 15px;
    text-align: center;
    font-size: 10px;
    font-family: Helvetica, sans-serif;
    display: inline-block;
    color: #fff !important;
    vertical-align: bottom;
    line-height: 15px;
    border-radius: 4px;
}
.userattrs a:hover {
    text-decoration: none;
}
.thing .tagline a.author.moderator {
    background: transparent !important;
    color: #4fc761 !important;
    border: 1px solid #4fc761 !important;
    padding: 0 4px;
    border-radius:4px;
}
.userattrs a.moderator {
    background: #4fc761;
}
.thing .tagline a.author.submitter {
    background: transparent !important;
    color: #638BE4 !important;
    border: 1px solid #638BE4 !important;
    padding: 0 4px;
    border-radius:4px;
}
.userattrs a.submitter {
    background: #638BE4;
}
.comment .usertext-body {
    margin-right: 10px !important;
}
.nav-buttons {
    margin: 10px 26px;
}
.link.last-clicked {
    border: none;
}
.link {
    margin: 6px 4px;
    padding-top: 14px;
    border-top: 1px solid #eee !important;
}
.link.stickied {
    /*border-bottom: 1px solid #eee;*/
    /*padding-bottom: 10px;*/
}
.link:first-child {
    border-top: none !important;
}
.link a.title {
    color: #5892e2;
}
.link .rank {
    display: none;
}
.link .entry .expando-button {
    width: 20px;
    height: 20px;
    margin: 4px 8px 0 0;
    background: url(http://b.thumbs.redditmedia.com/NpzFWWGqFP5ogd7xsXfqIGPV7M-0IQ9Ey5nb2Riw-bk.png) no-repeat -9999px -9999px!important;
}
.link .expando-button:hover {
    cursor: pointer;
}
.link .entry .expando-button.selftext.collapsed {
    background-position: 0 -38px!important;
}
.link .entry .expando-button.selftext.collapsed:hover {
    background-position: -20px -38px!important;
}
.link .entry .expando-button.selftext.expanded {
    background-position: 0 -58px!important;
}
.link .entry .expando-button.selftext.expanded:hover {
    background-position: -20px -58px!important;
}
.link .entry .expando-button.video.collapsed,
.link .entry .expando-button.video.expanded {
    background-position: 0 -78px!important;
}
.link .entry .expando-button.video.collapsed:hover,
.link .entry .expando-button.video.expanded:hover {
    background-position: -20px -78px!important;
}
.res .link .entry .expando-button.image.collapsedExpando,
.res .link .entry .expando-button.image.expanded {
    background-position: 0 -98px!important;
}
.res .link .entry .expando-button.image.collapsedExpando:hover,
.res .link .entry .expando-button.image.expanded:hover {
    background-position: -20px -98px!important;
}
.link .RES-keyNav-activeElement {
    background-color: transparent !important;
}
.link .RES-keyNav-activeElement .tagline {
    position: relative;
}
.listing-page .thing .RES-keyNav-activeElement .tagline:after {
    top: 50%;
    right: 2px;
    border: solid transparent;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none;
    border-color: rgba(136, 183, 213, 0);
    border-right-color: #638BE4;
    border-width: 12px;
    margin-top: -15px;
    z-index: 999;
    opacity: 0.5;
}
.entry .buttons .approve-button a {
    color: #4fc761 !important;
}
.thing .arrow {
    background-size: 32px;
    width: 32px;
    height: 16px;
    background-position: center !important;
}
.thing .arrow.up {
    background-image: url(http://b.thumbs.redditmedia.com/U2f3GM6Z5z7UWhYOjlcm8OOTIy_IUO8ty2uxnq1CinQ.png);
}
.thing .arrow.upmod {
    background-image: url(http://b.thumbs.redditmedia.com/PHU9t5grK84zhXgjCIQSgLQfq_y1X1km93igtQgucdE.png);
}
.thing .arrow.down {
    background-image: url(http://b.thumbs.redditmedia.com/akq_xxbyrqLoIMB18dl7cME1Elr_kKlKBWj_9fwTvnk.png);
}
.thing .arrow.downmod {
    background-image: url(http://b.thumbs.redditmedia.com/Io1Y5neDgYnFdyS2yI1sBcRQ5W6Oe6YgYsKVif4fd5E.png);
}
.thing .midcol {
    position: relative;
    top: -4px;
    width: 40px !important;
}
.thing.comment .midcol {
    width: 30px !important;
}
.thing .midcol .score {
    line-height: 20px;
}
.link .linkflairlabel {
    /*min-width: 60px;*/
    padding: 2px 4px;
    color: #fff;
    border: none;
    border-radius: 0;
}
.link .usertext-body .md {
    max-width: none;
    background: #fafafa;
    border-color: #aaa;
    border-radius: 0;
}
.linkinfo {
    width: 281px;
    position: relative;
    left: -5px;
    color: #eaeaea;
    border: none;
    border-radius: 0;
    padding: 10px;
    background: #37515E;
}
.side {
    background: transparent;
    /*margin-top: 70px;*/
    width: 296px;
    margin-right: 20px !important;
}
.side .md {
    color: #ddd;
}
.side .md a{
    color: #ADD8E6;
}
.side  redditname { line-height: 0} 

/*Changes submit buttons*/

.morelink {
  font-weight:normal;
  letter-spacing:0;
  color: white;
  border-radius: 13px 13px 13px 13px;
  border: 1px #b4cfd8;
  background: #1a2e39;
  transition: background .3s ease-in;
  -moz-transition: background .3s ease-in;
  -webkit-transition: background .3s ease-in;
}

.morelink:hover {
  font-weight:normal;
  letter-spacing:0;
  background: #2c404a;
  color: black;
}

.morelink a { color: white }

.morelink .nub { display: none }

.sidebox.submit:hover:before{
    position:fixed;
    display:block;
    top:0;
    text-align:center;
    background-color:#82afbe; /*Edit to your liking*/
    color:white; /*Font color*/
    z-index:1000;
    padding:5px 0;
    width:100%;
    left:0;
    font-size:15px;
    font-weight:normal;
    content:"Please read the rules before posting."
}
#search {
    position: relative;
    /*right: 6px;*/
    width: 290px;
    margin-top: 18px;
}
#search input[type="text"] {
    width: 290px;
    height: 40px;
    border: none;
    border: 1px solid #1c323b;
}
#searchexpando {
    background: #37515E;
    border: 1px solid #1c323b;
    color: #ddd;
}
.side .redditname {
    display: none;
}
.titlebox form.toggle
 {
    background: transparent;
    color: #eee;
    font-size: 10px;
}
.leavemoderator {
  background: transparent;
  color: #eee;
  font-size: 0px!important;
  top: 50px;
  position: relative;
  left: 7px;
  z-index: 9999;
}
.side h1 {
    /*width: 288px;*/
    background: #37515E;
    /*position: relative;*/
    /*right: 4px;*/
    padding: 4px;
    margin: 0 !important;
    font-size: 16px !important;
    color: #ddd;
}
.side h1:last-of-type {
    background: #1a2e39;
    text-align: center;
    color: #fff;
}
.side h1:nth-of-type(1):before {
    content: "- ";
    color: #88B33A;
}
.side h1:nth-of-type(2):before {
    content: "- ";
    color: #B64840;
}
.side h1:nth-of-type(3):before {
    content: "- ";
    color: #B64840;
}
.side h1:nth-of-type(4):before {
    content: "- ";
    color: #B64840;
}
.side h1:nth-of-type(5):before {
    content: "- ";
    color: #B64840;
}
.side h1:nth-of-type(6):before {
    content: "- ";
    color: #88B33A;
}
.side h1:nth-of-type(7):before {
    content: "- ";
    color: #88B33A;
}
.side h1 + ul {
    /*width: 272px;*/
    background: #3e5c6a;
    /*position: relative;*/
    /*right: 4px;*/
    padding: 0 8px;
    margin: 0 !important;
    /*margin-bottom: 6px !important;*/
    border-bottom: 4px solid #2c404a;
    height: auto;
    max-height: 0;
    overflow: hidden;
    -webkit-transition: all 0.3s;
    transition: all 0.3s;
}
.side h1 + ul a {
    color: #eee;
}
.side h1 + ul sup {
    margin-top: 6px;
    display: block;
}
.side h1:hover {
    cursor: pointer;
}
.side h1:hover + ul,
.side h1 + ul:hover {
    padding: 8px;
    max-height: 400px;
}
.side td,
.side th {
    border-color: #3e5c6a;
}
.side .usertext {
    /*background: rgb(66,84,93);*/
    background: #37515E;
    /*border: 1px solid #1c323b;*/
}
.side code {
    background: transparent;
}
.side .usertext p {
    padding: 4px 8px;
}
.side .usertext h3 {
    /*padding: 4px 8px;*/
    /*white-space: nowrap;*/
    /*font-size: 16px;*/
    /*font-family: Helvetica, sans-serif;*/
    /*text-align: center;*/
    /*color: #f2f2f2;*/
    /*background: #638be4;*/
    background: #1a2e39;
    /*border: 1px solid #1c323b;*/
    border-bottom: none;
    color: #fff;
    padding: 8px 8px;
    display: block;
    width: 280px;
    position: relative;
    /*left: -9px;*/
    top: -9px;
    font-size: 14px;
    font-weight: bold;
    font-family: Helvetica, sans-serif;
    text-align: center;
    margin-bottom: -10px;
    /*margin-top: 0;*/
}
.side .helplink {
    /*padding: 4px 8px;*/
    /*white-space: nowrap;*/
    /*font-size: 16px;*/
    /*font-family: Helvetica, sans-serif;*/
    /*text-align: center;*/
    /*color: #f2f2f2;*/
    /*background: #638be4;*/
    background: #638be4;
    /*border: 1px solid #1c323b;*/
    border-bottom: none;
    color: #fff;
    padding: 14px 8px;
    display: block;
    width: 280px;
    /*position: relative;*/
    /*left: -9px;*/
    /*top: -9px;*/
    font-size: 16px;
    /*font-weight: bold;*/
    font-family: Helvetica, sans-serif;
    text-align: center;
    margin-bottom: 20px;
    /*margin-top: 10px;*/
    /*margin-top: 0;*/
}
.side a[href$="wiki_rules"] {
    /*top: -10px;*/
    color: #fff;
}
.side hr {
    border: none;
    background: #2c404a;
    height: 14px;
    margin: 0;
}
.side .usertext p:nth-of-type(1) {
    background: #2c404a;
    padding: 0;
    margin: 0;
}
.side .usertext p:nth-of-type(3) {
    background: #2c404a;
    padding: 0;
    margin: 0;
}
.side .usertext p:nth-of-type(2) {
    background: #2c404a;
    padding: 20px 0;
    margin: 0;
}
.side .usertext p:nth-of-type(2) a {
    background: #1a2e39;
    /*background: #4C69DB;*/
    border: 1px solid #000;
    width: 93px;
    display: inline-block;
    margin: 0;
    text-align: center;
    padding: 8px 0;
    color: #fff;
}
.side .usertext p:nth-of-type(2) a:nth-of-type(1),
.side .usertext p:nth-of-type(2) a:nth-of-type(2) {
    margin-right: 1.25px;
}
.side .usertext p:nth-of-type(2) a:nth-of-type(4) {
    margin-right: 1.5px;
}
.side .usertext p:nth-of-type(2) a:nth-of-type(4),
.side .usertext p:nth-of-type(2) a:nth-of-type(5) {
    width: 143px;
    margin-top: 6px;
}
.side a[href$="Valentin_Fritzmann/comments/"] {
    display: none;
}
.listing-page .side a[href$="Valentin_Fritzmann/comments/"] {
    display: inline-block;
    position: absolute;
    left: 50px;
    top: 143px;
    color: rgba(255, 255, 255, 0.7);
    z-index: 9999;
}
.side form.flairtoggle {
    background: #FDFDFD;
    padding-left: 8px;
    padding-top: 10px;
    padding-bottom: 4px;
    height: 44px;
    margin-top: 10px;
    border: 1px solid #1c323b;
    border-bottom: none;
    border-top: none;
}
.side form.flairtoggle:before {
    background: #638BE4;
    border: 1px solid #1c323b;
    border-bottom: none;
    color: rgba(255, 255, 255, 0.7);
    height: 30px;
    line-height: 30px;
    display: block;
    content: "Set your user flair";
    width: 294px;
    position: relative;
    left: -9px;
    top: -10px;
    font-size: 14px;
    font-family: Helvetica, sans-serif;
    text-align: center;
}
.side .tagline {
    position: relative;
}
.side .tagline > span.flair {
    overflow: visible;
    position: static;
    text-indent: -9999px;
    transition: max-width 0.4s, padding 0.4s, color 0.4s, text-indent 0s;
    -webkit-transition: max-width 0.4s, padding 0.4s, color 0.4s, text-indent 0s;
    white-space: nowrap;
}
.side .tagline > span.flair:hover {
    text-indent: 12px;
    color: #fff;
}

/* Flair header colour */

.side .tagline > span.flair:before {
    text-indent: 0px;
    pointer-events: none;
    border: 1px solid #1c323b;
    border-bottom: none;
    color: #333;
    height: 30px;
    line-height: 30px;
    display: none;
    content: "Set your user flair";
    width: 294px;
    position: absolute;
    left: -1px;
    top: -58px;
    font-size: 14px;
    font-family: Helvetica, sans-serif;
    text-align: center;
}
.side .tagline > span.flair-red:before {
    background: #dd7680;
    display: block;
}
.side .tagline > span.flair-orange:before {
    background: #ffb263;
    display: block;
}
.side .tagline > span.flair-yellow:before {
    background: #edc365;
    display: block;
}
.side .tagline > span.flair-green:before {
    background: #4fc761;
    display: block;
}
.side .tagline > span.flair-blue:before {
    background: #65a4ed;
    display: block;
}
.side .tagline > span.flair-turquoise:before {
    background: #4ec6c6;
    display: block;
}
.side .tagline > span.flair-purple:before {
    background: #a876ff;
    display: block;
}
.side .tagline > span.flair-magenta:before {
    background: #ff7cff;
    display: block;
}
.side .tagline > span.flair-pink:before {
    background: #FFC0EB;
    display: block;
}
.side .tagline > span.flair-grey:before {
    background: #999;
    display: block;
}
.side .tagline > span.flair-rainbow:before {
     color: #fff;
    background: #ff0;
    background-image: -webkit-linear-gradient(left, red, orange, yellow, green, blue, indigo, violet);
    background-image: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
    display: block;
}
.side .flairselector {
    left: initial !important;
    right: -1px !important;
    top: 30px !important;
    box-shadow: none !important;
}
.side form.flairtoggle label {
    font-size: 0px;
}
.side form.flairtoggle label:after {
    font-size: 10px;
    content: "Show my flair on this subreddit";
    color: #666;
}
.side .tagline {
    background: #FDFDFD;
    padding: 8px;
    margin: 0;
    color: #aaa;
    font-size: 12px;
    border: 1px solid #1c323b;
    border-top: none;
}
.side .tagline a {
    color: #666;
}
.side .tagline a:nth-of-type(2) {
    font-size: 0px;
    color: #73a5ea;
}
.side .tagline a:nth-of-type(2):after {
    font-size: 12px;
    content: "change";
}
.side .md > blockquote:first-child {
    position: absolute;
    top: 48px;
    right: 338px;
    z-index: 88888;
    display: block;
    white-space: nowrap;
    padding: 14px;
    margin: 0;
    border: none;
    border-radius: 10px;
    background: #2c404a;
    border: 1px solid #1c323b;
    font-family: "HelveticaNeue-Light", "Helvetica Neue Light", "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    font-weight: 300;
       box-shadow: 0px 1px 5px rgba(0,0,0,0.24)!important;
  transition: all 0.25s ease;
}
.side .md > blockquote:first-child:after {
    top: 50%;
    left: 100%;
    border: solid transparent;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none;
    border-color: rgba(255, 255, 255, 0);
    border-left-color: #2c404a;
    border-width: 16px;
    margin-top: -16px;
}
.side .md > blockquote:first-child:before {
    top: 50%;
    left: 100%;
    border: solid transparent;
    content: " ";
    height: 0;
    width: 0;
    position: absolute;
    pointer-events: none;
    border-color: rgba(255, 255, 255, 0);
    border-left-color: #1c323b;
    border-width: 17px;
    margin-top: -17px;
}
.side .md > blockquote:first-child p {
    background: transparent;
    color: #fff;
    text-align: center;
    font-size: 13px;
    font-weight: 300;
    letter-spacing: .04em;
}
.side .md > blockquote:first-child a {
    display: inline-block;
    padding: 7px;
    border-radius: 10px;
    color: #fff;
    text-align: center;
    font-size: 13px;
    font-weight: 300;
    letter-spacing: .04em;
}
.side .md > blockquote:first-child a:nth-child(1) {
    background: #4C69DB;
       box-shadow: 0px 1px 5px rgba(0,0,0,0.24)!important;
  transition: all 0.25s ease;
}
.side .md > blockquote:first-child a:nth-child(2) {
    background: #6B4CDB;
    margin: 0 5px;
       box-shadow: 0px 1px 5px rgba(0,0,0,0.24)!important;
  transition: all 0.25s ease;
}
.side .md > blockquote:first-child a:nth-child(3) {
    background: #964CDB;
       box-shadow: 0px 1px 5px rgba(0,0,0,0.24)!important;
  transition: all 0.25s ease;
}
.RESshortcutside, 
.RESshortcutside.remove, 
.RESDashboardToggle, 
.RESDashboardToggle.remove {
    background: transparent !important;
    color:#1a2e39 !important;
    border:0 !important;
    position: relative;
    left: 65px;
}
.subscribe-button {
    display: block !important;
    margin-top: 10px;
}
.subscribe-button a {
    text-align: center;
    font-family: Helvetica, sans-serif;
    font-size: 18px !important;
    padding: 8px 0 !important;
}
.subscribe-button a.add {
    background: #9FDF59 !important;
       box-shadow: 0px 1px 5px rgba(0,0,0,0.24)!important;
  transition: all 0.25s ease;
}
.subscribe-button a.remove {
    background: transparent !important;
    color: #1a2e39;
    font-weight: normal;
    border: 1px solid #1a2e39;
}
.subscribe-button a.active {
    display: block !important;
}
.side .subscribers {
    color: #eee;
    font-size: 15px;
    font-family: Helvetica, sans-serif;
    padding: 8px 0;
    display: block;
    margin-top: 14px;
    letter-spacing: .5px;
}
.side .subscribers .word {
    font-size: 0px;
}
.side .subscribers .word:after {
    font-size: 15px;
    content: "Valentin_Fritzmann Fans";
}
.side .users-online {
    color: #ccc;
    font-size: 14px;
    font-family: Helvetica, sans-serif;
    margin-bottom: 0px;
    display: block;
}
.side .users-online:before {
    background: #91bc3f;
    border-radius: 10px;
    width: 10px;
    height: 10px;
}
.sidecontentbox h1 {
    background: transparent;
    color: #eee;
}
.sidecontentbox h1:before {
    content: none !important;
}
.sidecontentbox a {
    color: #eee;
    background: transparent;
}
.side del {
    color: #ccc !important;
}
.sidebox.create {
    display: none;
}
#progressIndicator {
    width: auto !important;
    border-radius: 0 !important;
    border: none !important;
}
.hover-bubble {
    z-index: 999999;
}
.flair {
    min-width: 14px;
    max-width: 14px;
    height: 14px;
    line-height: 14px;
    border-radius: 14px;
    border: none;
    overflow: hidden;
    padding: 0;
    vertical-align: middle;
    font-size: 11px !important;
    -webkit-transition: all 0.3s;
    transition: all 0.3s;
    position: relative;
    text-indent: 12px;
}

/* User */

.flair:hover {
    max-width: 500px;
    padding: 0 5px;
    color: #fff
}
.flair-blue {
    background: #65a4ed;
    color: #65a4ed
}
.flair-red {
    background: #dd7680;
    color: #dd7680
}
.flair-yellow {
    background: #edc365;
    color: #edc365
}
.flair-grey {
    background: #999;
    color: #999
}
.flair-green {
    background: #4fc761;
    color: #4fc761
}
.flair-pink {
    background: #FFC0EB;
    color: #FFC0EB;
}
.flair-magenta {
    background: #ff7cff;
    color: #ff7cff;
}
.flair-orange {
    background: #ffb263;
    color: #ffb263;
}
.flair-purple {
    background: #a876ff;
    color: #a876ff;
}
.flair-turquoise {
    background: #4ec6c6;
    color: #4ec6c6;
}
.flair-rainbow {
    color: #fff;
    background: #ff0;
    background-image: -webkit-linear-gradient(left, red, orange, yellow, green, blue, indigo, violet);
    background-image: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
}
.flair-mod {
    background: #638BE4;
    color: #638BE4;
    text-indent: 12px;
}
.flair-mod-purple {
    background: #a876ff;
    color: #a876ff;
    text-indent: 12px;
}
.flair-mod:before, .flair-mod-purple:before {
        content: "m";
    color: #FDFDFD;
  width: 14px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: 0px;
  text-indent: 0;
  font-size: 6px;
}
.flair-ircmod {
    background: #dd7680;
    color: #dd7680;
    text-indent: 13px;
}
.flair-ircmod:before {
    content: "i";
    color: white;
    width: 14px;
    height: 16px;
    display: inline-block;
    position: absolute;
    left: 0px;
    text-align: center;
    top: -1px;
    text-indent: 0;
    font-size: 10px;
}
.flair-ircmod2 {
    background: #a876ff;
    color: #a876ff;
    text-indent: 13px;
}
.flair-ircmod2:before {
    content: "i";
    color: white;
    width: 14px;
    height: 16px;
    display: inline-block;
    position: absolute;
    left: 0px;
    text-align: center;
    top: -1px;
    text-indent: 0;
    font-size: 10px;
}
.flair-petal {
    background: #ADD8E6;
    color: #ADD8E6;
    text-indent: 13px;
}
.flair-petal:before {
      content: "m";
    color: #0A1E29;
  width: 14px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: 0px;
  text-indent: 0;
  font-size: 6px;
}
.flair-mod2 {
    background: #4fc761;
    color: #4fc761;
    text-indent: 13px;
}
.flair-mod2:before {
      content: "m";
    color: #FDFDFD;
  width: 14px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: 0px;
  text-indent: 0;
  font-size: 6px;
}

/* random special user flairs */

.flair-skittle {
    background: #4fc761;
    color: #4fc761;
    text-indent: 13px;
}
.flair-skittle:before {
    content: "s";
    color: white;
  width: 13px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: -1px;
  text-indent: 0;
  font-size: 10px;
}
.flair-bar {
    background: #4fc761;
    color: #4fc761;
    text-indent: 13px;
}
.flair-bar:before {
    content: "▮";
    color: white;
  width: 13px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: -1px;
  text-indent: 0;
  font-size: 10px;
}
.flair-sheriff {
    background: #D4AF37;
    color: #D4AF37;
    text-indent: 12px;
    box-shadow: 0 0 12px 1px rgba(234, 206, 114, 0.7);
    -moz-box-shadow: 0 0 12px 1px rgba(234, 206, 114, 0.7);
    -webkit-box-shadow: 0 0 12px 1px rgba(234, 206, 114, 0.7);
}
.sidecontentbox .flair-sheriff, .flair-sheriff:hover {
    box-shadow: none !important;
}
.flair-sheriff:before {
  content: "★";
  color: #996515;
  width: 13px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: -1px;
  text-indent: 0;
  font-size: 10px;
}

.flair-zombs {
    background: #8e65d6;
    color: #8e65d6;
    text-indent: 12px;
    box-shadow: 0 0 12px 1px rgba(142, 101, 214, 0.6);
    -moz-box-shadow: 0 0 12px 1px rgba(142, 101, 214, 0.6);
    -webkit-box-shadow: 0 0 12px 1px rgba(142, 101, 214, 0.6);
}
.flair-zombs:hover {
    box-shadow: none;
}
.flair-zombs:before {
  content: "★";
  color: #442c6d;
  width: 13px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: -1px;
  text-indent: 0;
  font-size: 10px;
}

.flair-noodle {
    background: #0B6121;
    color: #0B6121;
    text-indent: 13px;
}
.flair-noodle:before {
    content: "♛";
    color: white;
  width: 13px;
  height: 13px;
  display: block;
  position: absolute;
  text-align: center;
  left: 0;
  top: -1px;
  text-indent: 0;
  font-size: 10px;
}

button {
    border-radius: 0;
    border: none;
    color: #fff;
    background: #638BE4;
    padding: 4px 8px;
    font-size: 12px;
}
.side .bottom {
    font-size: 0;
}
.side .bottom span {
    display: none;
}
.side .bottom:after {
    font-size: 10px;
    content: "/r/Valentin_Fritzmann";
}
.linkflairlabel {
    /*min-width: 50px;*/
    background: #999;
    text-align: center;
    font-size: 12px;
    color: #fff !important;
    padding: 2px 4px !important;
    border: none !important;
    opacity: 0.8;
    padding-left: 20px !important;
    vertical-align: middle;
    border-radius: 2px !important;
}
.sidecontentbox .score {
    color: #aaa !important;
}
.sidecontentbox .linkflairlabel {
    padding-left: 4px !important;
}
.linkflair-locked .linkflairlabel {
    background: #dd7680 url(http://b.thumbs.redditmedia.com/KfSN61og7R4pQfEIG7b2WBUrKnHBvONPbhK4yD0jMXQ.png) 4px 3px no-repeat;
    background-size: 12px
}
.linkflair-modpost .linkflairlabel {
    background: #4fc761 url(http://a.thumbs.redditmedia.com/5AQvnGXkBR6kwjwCnLjQrHw7-h6uR0F_AuuWCLWGFk4.png) 4px 4px no-repeat;
    background-size: 12px
}
.linkflair-removed .linkflairlabel {
    background: #999 url(http://b.thumbs.redditmedia.com/qIAO4-KAwGb0cGeQhmk3LG5bQC53U4XNGPLiMTXbdrQ.png) 4px 4px no-repeat;
    background: #999 url(http://b.thumbs.redditmedia.com/qIAO4-KAwGb0cGeQhmk3LG5bQC53U4XNGPLiMTXbdrQ.png) 4px 4px no-repeat;
    background-size: 12px
}
.linkflair-selfie .linkflairlabel {
    background: #4C69DB url(http://b.thumbs.redditmedia.com/5DIUwViYn5RF8xHrbH74smCGsg39UVA4rUuMzT76o_c.png) 4px 4px no-repeat;
    background-size: 12px
}
.linkflair-advice .linkflairlabel {
    background: #6B4CDB url(http://b.thumbs.redditmedia.com/AQ77FEOCZ2J6tsucImO6owXyjKmL14a8ZCzkG9dDGdk.png) 4px 4px no-repeat;
    background-size: 12px
}
.linkflair-vent .linkflairlabel {
    background: #964CDB url(http://a.thumbs.redditmedia.com/V6WQVFhq2g8h7MoDMSI43z0H08VZaVJHtJcBp5xUiF0.png) 4px 4px no-repeat;
    background-size: 12px
}
.linkflair-random .linkflairlabel {
    background: #ffb263 url(http://b.thumbs.redditmedia.com/PtEGbWkR6rc-9bnR9I3rs3y1QuAlfoVP4Olx67EVEbU.png) 4px 3px no-repeat;
    background-size: 16px;
    padding-left: 25px !important;
}
.linkflair-community .linkflairlabel {
    background: #65a4ed url(http://a.thumbs.redditmedia.com/fkIY4_F7ZMO96HUPODrPSYceyPaUUCdwGlAQkVoDH20.png) 4px 4px no-repeat;
    background-size: 12px
}
.linkflair-indepth .linkflairlabel {
    background: #a876ff url(http://b.thumbs.redditmedia.com/Aeo5q2ECXANCy6GyFiDzCai2fLo301qPZ30DidPnW0w.png) 4px 4px no-repeat;
    background-size: 11.5px
}
.linkflair-neat .linkflairlabel {
    background: #edc365 url(http://a.thumbs.redditmedia.com/k_RZuF5x-mtmhk5OaLiwADrvQgdB8xUpwoWiZ7b67u4.png) 4px 3px no-repeat;
    background-size: 13px
}
.linkflair-mega .linkflairlabel {
    background: #4ec6c6 url(http://a.thumbs.redditmedia.com/QTJodxJRkIxBY2O1bmFEx1fvIJeN7Tu8QBzq93lENB8.png) 4px 1px no-repeat;
    background-size: 16px;
    padding-left: 25px !important;
}

/*UpQuotes
**********************/

.thing .upmod:focus:after {
    content: "";
    display: block;
    font-size: 12px;
    margin-left: 1px;
    position: relative;
    background: transparent !important;
    color: #0065bf;
    bottom: 18px;
    opacity: 0.0;
    -webkit-animation-name: dcupmod;
    -moz-animation-name: dcupmod;
    -webkit-animation-duration: 5.0s;
    -moz-animation-duration: 5.0s;
    -webkit-animation-timing-function: ease-out;
    -moz-animation-timing-function: ease-out;
    -webkit-animation-iteration-count: 1;
    -moz-animation-iteration-count: 1;
    -webkit-animation-name: dcupmod;
    animation-name: dcupmod;
    -webkit-animation-duration: 5.0s;
    animation-duration: 5.0s;
    -webkit-animation-timing-function: ease-out;
    animation-timing-function: ease-out;
    -webkit-animation-iteration-count: 1;
    animation-iteration-count: 1;
    -webkit-animation-play-state: running;
    animation-play-state: running;
    z-index: 9999;
    pointer-events: none;
}
@-webkit-keyframes dcupmod {
    0% {
        color: #0065bf
    }
    8% {
        bottom: 23px;
        opacity: 1.0
    }
    15% {
        bottom: 28px
    }
    30% {
        color: #0065bf
    }
    50% {
        color: red;
        bottom: 33px
    }
    60% {
        color: #0065bf
    }
    100% {
        bottom: 38px;
        opacity: 0.0
    }
}
@keyframes dcupmod {
    0% {
        color: #0065bf
    }
    8% {
        bottom: 23px;
        opacity: 1.0
    }
    15% {
        bottom: 28px
    }
    30% {
        color: #0065bf
    }
    50% {
        color: #0065bf;
        bottom: 33px
    }
    60% {
        color: #0065bf
    }
    100% {
        bottom: 38px;
        opacity: 0.0
    }
}
.thing[data-fullname$="a"]>.midcol>.upmod:focus:after {
    content: "Top floor comment, please!"
}
.thing[data-fullname$="b"]>.midcol>.upmod:focus:after {
    content: "Huehuehue"
}
.thing[data-fullname$="c"]>.midcol>.upmod:focus:after {
    content: "4 8 15 16 23 42"
}
.thing[data-fullname$="d"]>.midcol>.upmod:focus:after {
    content: "I'm a karma loving whore!"
}
.thing[data-fullname$="e"]>.midcol>.upmod:focus:after {
    content: "I vote with a quote!"
}
.thing[data-fullname$="f"]>.midcol>.upmod:focus:after {
    content: "Heh, that tickles~"
}
.thing[data-fullname$="g"]>.midcol>.upmod:focus:after {
    content: "Don't drink and drive, eat sweet banana cream pie"
}
.thing[data-fullname$="h"]>.midcol>.upmod:focus:after {
    content: "Crouching Tiger, hidden upvote"
}
.thing[data-fullname$="i"]>.midcol>.upmod:focus:after {
    content: "It's never lupus. Except when it is."
}
.thing[data-fullname$="j"]>.midcol>.upmod:focus:after {
    content: "One time I threw a brick at a duck.."
}
.thing[data-fullname$="k"]>.midcol>.upmod:focus:after {
    content: "wat is this? i dont even"
}
.thing[data-fullname$="l"]>.midcol>.upmod:focus:after {
    content: "Never pay full price for late pizza"
}
.thing[data-fullname$="m"]>.midcol>.upmod:focus:after {
    content: "The Canada of Reddit"
}
.thing[data-fullname$="n"]>.midcol>.upmod:focus:after {
    content: "Is Tiz a male or is it a long con?"
}
.thing[data-fullname$="o"]>.midcol>.upmod:focus:after {
    content: "I AM ERROR"
}
.thing[data-fullname$="p"]>.midcol>.upmod:focus:after {
    content: "Don’t fry bacon in the nude."
}
.thing[data-fullname$="q"]>.midcol>.upmod:focus:after {
    content: "If I agreed with you we'd both be wrong."
}
.thing[data-fullname$="r"]>.midcol>.upmod:focus:after {
    content: "Shit just got casual up in dis bitch"
}
.thing[data-fullname$="s"]>.midcol>.upmod:focus:after {
    content: "SAYYAYGIRL is 2cute4me"
}
.thing[data-fullname$="t"]>.midcol>.upmod:focus:after {
    content: "luminouu is the prettiest mod"
}
.thing[data-fullname$="u"]>.midcol>.upmod:focus:after {
    content: "WHOOMP THERE IT IS!!"
}
.thing[data-fullname$="v"]>.midcol>.upmod:focus:after {
    content: "If opportunity doesn't knock, build a door."
}
.thing[data-fullname$="w"]>.midcol>.upmod:focus:after {
    content: "you are not Illiterate"
}
.thing[data-fullname$="x"]>.midcol>.upmod:focus:after {
    content: "I'm gonna poke it with a stick"
}
.thing[data-fullname$="y"]>.midcol>.upmod:focus:after {
    content: "Quote not found? Abort, Retry, Ignore."
}
.thing[data-fullname$="z"]>.midcol>.upmod:focus:after {
    content: "Cortye Hacked the CSS!"
}
.thing[data-fullname$="0"]>.midcol>.upmod:focus:after {
    content: "r u an elephant?"
}
.thing[data-fullname$="1"]>.midcol>.upmod:focus:after {
    content: "Anyone else think robonoodles is the best irc mod?"
}
.thing[data-fullname$="2"]>.midcol>.upmod:focus:after {
    content: "Onion is the devil apple."
}
.thing[data-fullname$="3"]>.midcol>.upmod:focus:after {
    content: "Quick_man IS Ringo Starr in To Catch a Man"
}
.thing[data-fullname$="4"]>.midcol>.upmod:focus:after {
    content: "RECTANGLES FOR SALE!! $90!!"
}
.thing[data-fullname$="5"]>.midcol>.upmod:focus:after {
    content: "Sha-la-la-la kiss the girl"
}
.thing[data-fullname$="6"]>.midcol>.upmod:focus:after {
    content: "MARK, I DID NOT HEET HER"
}
.thing[data-fullname$="7"]>.midcol>.upmod:focus:after {
    content: "OH, HAI MARK"
}
.thing[data-fullname$="8"]>.midcol>.upmod:focus:after {
    content: "We met our upquota"
}
.thing[data-fullname$="9"]>.midcol>.upmod:focus:after {
    content: "I got a case of the cuddles ^o^"
}
.thing .upmod:focus:after {
    white-space: nowrap
}
.midcol,
.last-clicked.midcol {
    overflow: visible!important
}
.midcol,
.last-clicked.midcol {
    overflow: visible!important
}
.res-commentBoxes .commentarea .comment {
    overflow: visible!important
}

/*Konami Code WIP*/

#baconBit {
    position: fixed;
    color: blue!important;
    width: 320px;
    height: 200px;
    background-image:url(http://b.thumbs.redditmedia.com/NPmBniIHdky-hM5AwHFqJ-1mmtld3rXphGWkWn2CezU.png) !important;
    top: -5%;
    left: -5%;
    z-index: 999999;
    -webkit-transform: scale(3, 3), rotate(0deg);
    -ms-transform: scale(3, 3), rotate(0deg);
    transform: scale(3, 3), rotate(0deg);
}
#baconBit.makeitrain {
    top: 100%;
    left: 100%;
    -webkit-transform: rotate(0deg);
    -moz-transform: rotate(0deg);
}
#baconBit {
    -webkit-transition: all 5s linear !important;
    -moz-transition: all 5s linear !important;
    -o-transition: all 5s linear !important;
    -ms-transition: all 5s linear !important;
}
#text-field textarea {
    background: url(http://b.thumbs.redditmedia.com/2jN8_03Qc6aRELtZYklCWhVm5nTG_NkF7YKZKB8-yxg.png) no-repeat
}
#text-field textarea:focus {
    background: #ffffff
}

/*CSS3 sticky comments by /u/creesch */

.comments-page .sitetable.nestedlisting {
    display: -webkit-flex;
    display: -ms-flexbox;
    display: flex;
    -webkit-flex-direction: column;
    -ms-flex-direction: column;
    flex-direction: column;
    -webkit-flex-wrap: nowrap;
    -ms-flex-wrap: nowrap;
    flex-wrap: nowrap;    
}

.comments-page .sitetable.nestedlisting>.thing.id-t1_addcommentidhere,
.comments-page .sitetable.nestedlisting>.thing.id-t1_cl7mbk5,
.comments-page .sitetable.nestedlisting>.thing.id-t1_cmu4qoy,
.comments-page .sitetable.nestedlisting>.thing.id-t1_cnht8k8,
.comments-page .sitetable.nestedlisting>.thing.id-t1_cq8sw8o,
.comments-page .sitetable.nestedlisting>.thing.id-t1_cov0egy,
.comments-page .sitetable.nestedlisting>.thing.id-t1_cqj15lq

{
    -webkit-order: -1;
    -ms-flex-order: -1;
    order: -1;
    border: solid 1px green !important;
    background-color: #E9F4E4 !important;
    margin-bottom: 10px;
    padding-top: 8px;
}
/* SUBMIT PAGE */

.submit .gray {
    content: " " !important;
    font-size: 0px;
}
.submit span.gray:after {
    content: "(mandatory)"!important;
    font-size: large;
    color: #808080;
}
#reddit-field {
    display: none
}
.roundfield {
    width: 500px;
    background-color: #e2e2e2;
    padding: 5px 10px 10px 10px;
    font-size: large
}
#newlink .infobar {
    background-color: transparent;
    padding: 0;
    margin: 0;
    font-size: 0;
    border: 0;
    text-indent: -10000px;
    position: absolute;
    left: 5px;
    right: 5px;
    top: 78px;
}
#newlink .infobar:after {
    text-indent: 0;
    background-color: #4C69DB;
    color: white !important;
    padding: 10px;
    font-size: 12pt;
    display: block;
    margin-top: 5px
}
.content > .infobar:first-child {
    margin-left: 8px;
    position: relative;
    top: 65px;
}
.wiki-page .wiki-page-content {
    margin-right: 15px;
}
.wiki-page .infobar{
    top:0px !important;
    position: relative;
}
#text-desc:after {
    content: "To promote Valentin_Fritzmann, we ask that you post comments on existing threads before creating your own thread. "
}
#link-desc:after {
    content: "To promote Valentin_Fritzmann, we ask that you post comments on existing threads before creating your own thread. Link post must promote Valentin_Fritzmann or it will be removed. No NSFW links. No memes.";
    content: "To promote Valentin_Fritzmann , we ask that you post comments on existing threads before creating your own thread. Link post must promote Valentin_Fritzmann or it will be removed. No NSFW links. No memes."
}
.submit-page .formtabs-content {
    padding-top: 40px;
}
.searchpane {
    margin: 0;
    border: none;
}
.drop-choices {
    background: #fff;
    border: 1px solid #1c323b;
}
.srdrop span {
    color: #eee !important;
}
.drop-choices a.choice {
    color: #333 !important;
}
.drop-choices a.choice:hover {
    color: #638BE4 !important;
    background: transparent;
}


.thing .arrow.down {
    display: none !important;
}

body.subscriber .thing:not(.comment) .arrow.down {
    display: block !important;
}

    a[href*="possibleisnothing"] {
	background:0;
	color:#3a960b; 
	-webkit-animation:rainbow 4s linear infinite;
	-moz-animation:rainbow 4s linear infinite;
	animation:rainbow 4s linear infinite;
}
@keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960be;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}
@-moz-keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960b;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}
@-webkit-keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960b;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}

a[href*="_____----------_____"] {
	background:0;
	color:#3a960b; 
	-webkit-animation:rainbow 4s linear infinite;
	-moz-animation:rainbow 4s linear infinite;
	animation:rainbow 4s linear infinite;
}
@keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960be;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}
@-moz-keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960b;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}
@-webkit-keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960b;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}

a[href*="BeBeINC"] {
	background:0;
	color:#3a960b; 
	-webkit-animation:rainbow 4s linear infinite;
	-moz-animation:rainbow 4s linear infinite;
	animation:rainbow 4s linear infinite;
}
@keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960be;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}
@-moz-keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960b;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}
@-webkit-keyframes rainbow {0% {color:#3a960b;}14% {color:#3a960b;}28% {color:#09a186;}42% {color:#0c6587;}56% {color:#00b8bd;}70% {color:#4B0082;}84% {color:#00b8bd;}}

/* Spoilers */
a[href$="/s"],
a[href$="/spoiler"],
a[href$="/spoilers"]{
    background: #72D280 !important;
    color: #72D280 !important;
    }
a[href$="/s"]:hover,
a[href$="/spoiler"]:hover,
a[href$="/spoilers"]:hover{
    color: #000 !important;
    cursor: default;
    }



/*----------Removing Create Subreddit ----------*/

.sidebox.create .morelink {display: none;}
.sidebox.submit .spacer , .sidebox.create .spacer  {display: none; }


div.titlebox span.word {
    display: none;
    }

div.titlebox span.number:after {
    content: ",002 Online";
 }

div.titlebox .subscribers span.number:after{
    content: "62,000 Fans";
}

div.titlebox .users-online span.number:after{
    content: ",002 Online";
}

/*----------change the rank colour ----------*/

.link:hover {
  background-color: #EBF1F1;
  margin: 0;
  border-bottom: 1px solid #dfdfdf
}

.link:hover {
  border-left:  5px #214048 solid!important;
}
