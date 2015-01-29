# -r-Gunners-code
Stylesheet for /r/Gunners
/* Key Colours:

Primary Arsenal Red: #EA2212;
Dark Arsenal Red: #DE0105;
Light Arsenal Red: FEEFF1;
White: #FFF;
Navy: #15212F;
Dark-Grey: #28292D

*/
/* Raerth's fix for RES messing with positioning */ 
.content {margin-top:30px;}

#sr-header-area, #sr-header-area .dropdown.srdrop {
	padding-left: 173px;
	background-color: #FFF;
}

.userkarma {
	color: #FFF;
}

.link {
        min-height: 65px;
}

.link.last-clicked {
        border: none;
}

/* testing out selector for 'res active element'.  Needs some TLC if it's going to work.

.thing .RES-keyNav-activeElement {
background-color: #EA2212 !important;
}

.thing .RES-keyNav-activeElement .title {
color: #FFF !important;
} 

*/

/* This is for the stylesheet */
.sheets .col {
    width: 99%;
}

#header-bottom-right .user {
       color: lightgray;
}

.RES-keyNav-activeElement {
       border: none;
}

#search input[type=text] {
        border-color: #EA2212;
        font-size: 14px;
        padding: 5px;
        width: 287px;
}

#header {

	margin-bottom: 50px;
	height: 145px;
	background: url(%%header-bg%%) no-repeat 50% 100%; 
        background-color: #EA2212;
}

#header-bottom-right {
	margin-bottom: 16px;
	background-color: #c70003;
}

#header-bottom-right a {
	color: white;
}

#userbarToggle {
	border: none !important;
	background-color: #F48178 !important;
	color: #15212f !important;

}

.arrow.upmod {
       background: url(%%arrow-up%%) no-repeat 0 0;
}

.arrow.up {
       background: url(%%arrow-up-grey%%) no-repeat 0 0;
}

.arrow.down {
       background: url(%%arrow-down-grey%%) no-repeat 0 0;
}

.arrow.downmod {
       background: url(%%arrow-down%%) no-repeat 0 0;
}

.link .score.likes {
       color: #EA2212;
}

.link .score.dislikes {
       color: #2F334C;
}

#header-bottom-left {
	margin-top: 120px;
	height: 9px;
	border-width: 0px 0px 17px 0px;
	border-style: solid;
	border-color: #15212F;
	background-color: #28292D;
}

#header-bottom-left .redditname a {
	position: absolute;
	display: inline-block;
	margin-top: -100px;
	margin-left: 171px;
	width: 220px;
	height: 55px;
	background-image: url(%%the-gunners%%);
	background-repeat: no-repeat;
	text-indent: -9999px;
}

#header-bottom-left .redditname a:hover {
	background-image: url(%%the-gunners-dark%%);
}

#header-bottom-left .redditname {
	color: #15212f;
}

#header-bottom-left .tabmenu {
	display: block;
	margin-top: -43px;
	margin-left: 180px;
}


 

.side {
	margin-top: -33px;
	padding-top: 311px;
	padding-left: 10px;
        padding-right: 10px;
        margin-right: 0px;
	width: 299px;
	border-left: #E1E1E1 solid 1px;
	background-color: #f5f5f5;
}

#header-bottom-left .tabmenu li {
	display: inline-block;
	height: 60px;
        margin: 0px;
        padding-left: 5px;
}

#header-bottom-left .tabmenu li:after {
	display: inline-block;
	color: white;
	content: "⋮";
        margin-right: -2px;
}

#header-bottom-left .tabmenu li:nth-last-of-type(1):after {
	content: "";
}

#header-bottom-left .tabmenu li a {
	background-color: transparent;
	color: white;
}

#header-bottom-left .tabmenu li a:hover {
	color: #15212f;
}

#header-bottom-left .tabmenu li.selected {
	background: url(%%active%%) 50% 19px no-repeat;
        margin-left: -3px;
}

#header-bottom-left .tabmenu li:first-of-type.selected {
        padding-left: 0px;
}

#header-bottom-left .tabmenu li.selected a {
	border: none;
	background-color: transparent;
	color: white;
}

.drop-choices {
        z-index: 9999;
        margin-left: 170px;
}

#header-img {
	margin-top: -135px;
	margin-left: 5px;
        z-index: 1000;
        position: absolute;
}

.entry .title a {
	color: #15212F !important;
}

.entry .title a:hover {
	color: #EA2212 !important;
}

.entry .title a:visited {
	color: #697E97 !important;
}

/* Removes the nub from the submit new link/post buttons */
.nub {
	display:none;
}

.morelink {
	border: none;
	background-color: #EA2212;
	background-image: none;

}

.morelink a:hover {
	background-color: #c70003;
}

.morelink a {
	color: white;
}

.morelink a[href="http://www.reddit.com/r/Gunners/submit?selftext=true"] {
	background-color: #15212f;
}

.morelink a[href="http://www.reddit.com/r/Gunners/submit?selftext=true"]:hover {
	background-color: #28292d;
}

#siteTable a.title[href*="/pre_match_thread"],
#siteTable a.title[href*="/prematch_thread"],
#siteTable a.title[href*="/match_thread"],
#siteTable a.title[href*="/post_match_thread"],
#siteTable a.title[href*="/post_match_reaction_thread"],
#siteTable a.title[href*="/postmatch_thread"],
#siteTable a.title[href*="/match_report"] {
	color: #EA2212 !important;
}

.tagline 
.stickied-tagline {
color: #EA2212!important;
}

#siteTable a.title[href*="/announcement"] {
	color: #EA2212 !important;
	font-weight: bold;
}

/* Sets styles for submit new link/post UI */

.tabmenu.formtab .selected a {
	background-color: #EA2212;
}

.formtabs-content {
	border-top: 4px solid #EA2212;
}

.roundfield {
	border: solid 1px #EA2212;
	background-color: #FEEFF1;
}

.roundfield .gray {

}

.roundfield .title {

}

.roundfield-content #suggested-reddits a {

}

.roundfield-content .bottom-area a {

}

.roundfield-content textarea, .roundfield-content input[type=url], .roundfield-content input[type=text] {
	border-color: lightgrey;
}

.tabmenu.formtab a {
	background-color: #FEEFF1;
	color: #EA2212;
}


.res-nightmode #siteTable a.title[href*="/match_thread"] {
	color: white !important;
}

div.titlebox span.word {
	display:none; 
}

div.titlebox span.number:after {
	content: " gooners";
}

.linkinfo {
	border-color: #EA2212;
	background-color: #FEEFF1;
}

/* From old subreddit design  */

#siteTable a.title {
	margin: 2px 0 0 0;
	vertical-align: middle;
	line-height: 22px;
}

#siteTable a.title:before {
	display: inline-block;
	margin-right: 3px;
	padding: 0;
	width: 20px;
	height: 20px;
	border-width: 0;
	background-color: transparent;
	background-image: url(%%icons-large%%);
	background-repeat: no-repeat;
	vertical-align: bottom;
	vertical-align: middle;
	cursor: default;
}

#siteTable a.title[href*="/pre_match_thread"],
#siteTable a.title[href*="/prematch_thread"],
#siteTable a.title[href*="/match_thread"],
#siteTable a.title[href*="/post_match_thread"],
#siteTable a.title[href*="/post_match_reaction_thread"],
#siteTable a.title[href*="/postmatch_thread"],
#siteTable a.title[href*="/match_report"] {
	color: green;
	line-height: 26px;
}
#siteTable a.title[href*="/pre_match_thread"]:before,
#siteTable a.title[href*="/prematch_thread"]:before,
#siteTable a.title[href*="/match_thread"]:before,
#siteTable a.title[href*="/post_match_thread"]:before,
#siteTable a.title[href*="/post_match_reaction_thread"]:before,
#siteTable a.title[href*="/postmatch_thread"]:before,
#siteTable a.title[href*="/match_report"]:before {
	width: 24px;
	height: 24px;
	background-position: 0 -204px;
	content: "";
	vertical-align: bottom;
}
#siteTable a.title[href*="/match_thread"]:before {
	background-position: 0 0;
}
#siteTable a.title[href*="/pre_match_thread"]:before,
#siteTable a.title[href*="/prematch_thread"]:before {
	background-position: 0 -34px;
}
#siteTable a.title[href*="/post_match_thread"]:before,
#siteTable a.title[href*="/post_match_reaction_thread"]:before,
#siteTable a.title[href*="/postmatch_thread"]:before {
	background-position: 0 -408px;
}

/* Icons */
#siteTable a[href^="//#"] {
	display: inline-block;
	width: 16px;
	height: 16px;
	line-height: normal;
	background-repeat: no-repeat;
	background-image: url(%%icons%%);
	vertical-align: middle;
	padding: 0;
	border-width: 0;
	background-color: transparent;
	cursor: default;
}
#siteTable  a[href^="//#"][href$="-big"] {
	width: 24px;
	height: 24px;
	line-height: 24px;
	background-image: url(%%icons-large%%);
}
#siteTable .comment a[href^="//#"] {
	display: none!important;
}

a[href^="//#"]{background-position: -999px -999px}
a[href^="//#ball"]{background-position:0 0}
a[href^="//#clock"]{background-position:0 -34px}
a[href^="//#down"]{background-position:0 -68px}
a[href^="//#flag"]{background-position:0 -102px}
a[href^="//#info"]{background-position:0 -136px}
a[href^="//#net"]{background-position:0 -170px}
a[href^="//#news"]{background-position:0 -204px}
a[href^="//#notes"]{background-position:0 -238px}
a[href^="//#red"]{background-position:0 -272px}
a[href^="//#stream"]{background-position:0 -306px}
a[href^="//#sub"]{background-position:0 -340px}
a[href^="//#up"]{background-position:0 -374px}
a[href^="//#whistle"]{background-position:0 -408px}
a[href^="//#yellow"]{background-position:0 -442px}

/* sidebar image */

.side .md > ul {
        background: url(%%roza2%%) no-repeat top ;
        width: 299px;
        margin: 0px;
        position: absolute;
        top: 175px;
        padding: 0px;
}

.side .md ul li {
        list-style-type: none;
}

.side .md > ul > li {
        position: relative;
        height: 300px;
        padding: 0px 10px;
}

.side .md > ul li ul {
        position: absolute;
        bottom: 0px;
        left: 0px;
        margin: 0px;
        text-align: justify;
        text-align: left;
        font-weight: normal;
        letter-spacing: -0.5px;
        font-size: 13px;
        padding: 10px;
        width: 279px;
        color: #f5f5f5;
        background: url(%%bg-semi-transparent%%);
}


/* Tables */
.md table {
	border: 2px solid white;
	background-color: white;
	box-shadow: 0 0 5px #ccc;
}
.md th, .md td {
	padding: 2px 1ex;
}
.md th {
	border-color: #ccc;
	background-color: #eee;
	color: black;
}
.md td[align=left],
.md th[align=left] {
	text-align: left;
}
.md td[align=center],
.md th[align=center] {
	text-align: center;
}
.md td[align=right],
.md th[align=right] {
	text-align: right;
}
.md th a {
	color: black;
}

/* Headings */
.md h1, .md h2, .md h3, .md h4 {
	margin: 1em 0;
	font-weight: bold;
}

.side .md th:last-of-type {
        border-right: 1px solid #EA2212;
}

.side .md table {
	margin: 3px 0px 30px;
	width: 100%;
	border: 1px solid #ccc;

}
.side .md th {
	padding: 6px 4px;
	border-top: none;
	border-right: 1px solid #ccc;
	border-bottom: 10px solid #15212f;
	border-left: none;
	background-color: #EA2212;
	color: #fafafa;
	text-align: center;
	font-weight: bold;
}
.side .md th a {
	color: #fafafa;
}

.side table thead tr:nth-child(1) {
        border: 1px solid #EA2212 !important;
}

.side tr:nth-child(even) {
	background-color: #feeff1;
}
.side .md td {
	padding: 4px;
	min-width: 2em;
	min-height: 28px;
	border-top: none;
	border-right: 1px solid #ccc;
	border-bottom: none;
	border-left: none;
	vertical-align: middle;
}
.side .md td a {
	color: #27262c;
}
.side table:nth-of-type(4) tr {
	border-bottom: 1px solid #ccc;
	background-color: white;
}

/* Players */
.side td a[href*="arsenal.com/first-team/players/"],
.side td a[href*="arsenal.com/academy/players/"] {
	display: block;
	margin-right: auto;
	margin-left: auto;
	width: 45px;
	height: 45px;
	background-color: transparent;
	background-repeat: no-repeat;
	content: "";
	content: "";
	text-indent: -9999px;
	white-space: nowrap;
}
.side td a[href*="arsenal.com/academy/players/"] {
	background-image: url(%%youth%%);
}
.side td a[href*="arsenal.com/first-team/players/"],
.side td a[href$="gibbs"] {
	background-image: url(%%players%%);
}

.side a[href$="ozil"]{background-position: 0 0;}
.side a[href$="arteta"]{background-position: 0 -48px;}
.side a[href$="campbell"]{background-position: 0 -140px;}
.side a[href$="cazorla"]{background-position: 0 -186px;}
.side a[href$="flamini"]{background-position: 0 -232px;}
.side a[href$="coquelin"]{ background-image:url(%%players%%)!important;background-position: 0 -278px;}
.side a[href$="gnabry"]{ background-image:url(%%players%%)!important;background-position: 0 -324px;}
.side a[href$="diaby"]{background-position: 0 -370px;}
.side a[href$="ospina"]{background-position: 0 -462px;}
.side a[href*="sanogo"]{background-position: 0 -554px;}
.side a[href$="gibbs"]{background-position: 0 -600px;}
.side a[href$="giroud"]{background-position: 0 -647px;}
.side a[href$="jenkinson"]{background-position: 0 -692px;}
.side a[href$="koscielny"]{background-position: 0 -738px;}
.side a[href$="sanchez"]{background-position: 0 -784px;}
.side a[href$="mertesacker"]{background-position: 0 -830px;}
.side a[href$="oxlade-chamberlain"]{background-position: 0 -876px;}
.side a[href$="podolski"]{background-position: 0 -968px;}
.side a[href$="ramsey"]{background-position: 0 -1014px;}
.side a[href$="rosicky"]{background-position: 0 -1060px;}
.side a[href$="miyaichi"]{background-position: 0 -1106px;}
.side a[href$="debuchy"]{background-position: 0 -1152px;}
.side a[href$="chambers"]{background-position: 0 -1201px;}
.side a[href$="monreal"]{background-position: 0 -1244px;}
.side a[href$="welbeck"]{background-position: 0 -1291px;}
.side a[href$="szczesny"]{ background-image:url(%%players%%)!important;background-position: 0 -1336px;}
.side a[href$="vermaelen"]{background-position: 0 -1382px;}
.side a[href$="walcott"]{background-position: 0 -1428px;}
.side a[href$="wilshere"]{background-position: 0 -1474px;}

.side a[href$="afobe"]{background-position:0 0;}
.side a[href$="akpom"]{background-position:0 -46px;}
.side a[href$="ampadu"]{background-position:0 -92px;}
.side a[href$="aneke"]{background-position:0 -138px;}
.side a[href$="angha"]{background-position:0 -184px;}
.side a[href$="ansah"]{background-position:0 -230px;}
.side a[href$="bellerin"]{background-position:0 -276px;}
.side a[href$="bihmoutine"]{background-position:0 -322px;}
.side a[href$="boateng"]{background-position:0 -368px;}
.side a[href$="charlescook"]{background-position:0 -414px;}
.side a[href$="dallison"]{background-position:0 -460px;}
.side a[href$="dawkins"]{background-position:0 -506px;}
.side a[href$="eastmond"]{background-position:0 -552px;}
.side a[href$="ebecilio"]{background-position:0 -598px;}
.side a[href$="eisfeld"]{background-position:0 -644px;}
.side a[href$="fagan"]{background-position:0 -690px;}
.side a[href$="galindo"]{background-position:0 -736px;}
.side a[href$="hajrovic"]{background-position:0 -828px;}
.side a[href$="hayden"]{background-position:0 -874px;}
.side a[href$="henderson"]{background-position:0 -920px;}
.side a[href$="iwobi"]{background-position:0 -966px;}
.side a[href$="jebb"]{background-position:0 -1012px;}
.side a[href$="jeffrey"]{background-position:0 -1058px;}
.side a[href$="kamara"]{background-position:0 -1104px;}
.side a[href$="lipman"]{background-position:0 -1150px;}
.side a[href$="martinez"]{background-position:0 -1196px;}
.side a[href$="meade"]{background-position:0 -1242px;}
.side a[href$="miquel"]{background-position:0 -1288px;}
.side a[href$="monteiro"]{background-position:0 -1334px;}
.side a[href$="mugabo"]{background-position:0 -1380px;}
.side a[href$="neita"]{background-position:0 -1426px;}
.side a[href$="olsson"]{background-position:0 -1472px;}
.side a[href$="ormondeottew"]{background-position:0 -1518px;}
.side a[href$="rees"]{background-position:0 -1564px;}
.side a[href$="roberts"]{background-position:0 -1610px;}
.side a[href$="shea"]{background-position:0 -1656px;}
.side a[href$="siemann"]{background-position:0 -1702px;}
.side a[href$="toral"]{background-position:0 -1748px;}
.side a[href$="uade"]{background-position:0 -1794px;}
.side a[href$="vickers"]{background-position:0 -1840px;}
.side a[href$="watt"]{background-position:0 -1886px;}
.side a[href$="wellington2"]{background-position:0 -1932px;}
.side a[href$="wynter"]{background-position:0 -1978px;}
.side a[href$="yennaris"]{background-position:0 -2024px;}

/* Sidebar icons */
.side a[href^="//#icon"] {
	background-image: url(%%sidebar-icons%%);
	background-repeat: no-repeat;
	background-color: transparent;
	display: block;
	cursor: default;
	content: "";
	margin-left: auto;
	margin-right: auto;
	text-indent: -9999px;
}

.side a[href^="//#icon-ball"]{background-position: 0 0; width: 16px; height: 16px;}
.side a[href^="//#icon-clock"]{background-position: 0 -17px; width: 16px; height: 16px;}
.side a[href^="//#icon-coc"]{background-position: 0 -34px; width: 19px; height: 24px;}
.side a[href^="//#icon-cup"]{background-position: 0 -59px; width: 20px; height: 20px;}
.side a[href^="//#icon-epl"]{background-position: 0 -80px; width: 20px; height: 20px;}
.side a[href^="//#icon-fa"]{background-position: 0 -101px; width: 20px; height: 27px;}
.side a[href^="//#icon-ucl"]{background-position: 0 -129px; width: 20px; height: 20px;}
.side a[href^="//#icon-ecup"]{background-position: 0 -150px; width: 20px; height: 20px;}
.side a[href^="//#icon-communityshield"]{background-position: 0 -175px; width: 20px; height: 20px;}

/* Link Flair */

.linkflair-one .linkflairlabel {
    background-color: #CC0000;
    font-size: 11px;
    font-weight: normal;
    vertical-align: middle;
    color: #FFF;
    border-color: #990000;
    border-width: 1px;
    border-radius: 5px;}

.linkflair-two .linkflairlabel {
    background-color: #FFF;
    font-size: 11px;
    font-weight: normal;
    vertical-align: middle;
    color: #CC0000;
    border-color: #CC0000;
    border-width: 1px;
    border-radius: 5px;}

.linkflair-three .linkflairlabel {
    background-color: #FFFFFF;
    font-size: 11px;
    font-weight: normal;
    vertical-align: middle;
    color: #00CC00;
    border-color: #00CC00;
    border-width: 1px;
    border-radius: 5px;}

.linkflair-four .linkflairlabel {
    background-color: #0099FF;
    font-size: 11px;
    font-weight: normal;
    vertical-align: middle;
    color: #FFF;
    border-color: #000099;
    border-width: 1px;
    border-radius: 5px;}

.linkflair-badge .linkflairlabel {
    background: url(%%badge2%%) no-repeat;
    border: 0;
    height: 26px;
    line-height: 26px;
    min-width: 24px;
    text-indent: 28px;
    vertical-align: middle;
}


.linkflair-bbc .linkflairlabel {
    background-color: #FFFF00;
    font-size: 11px;
    font-weight: normal;
    vertical-align: middle;
    color: #000000;
    border-color: #000000;
    border-width: 1px;
    border-radius: 5px;}

.linkflair-sky .linkflairlabel {
    background-color: #0101DF;
    font-size: 11px;
    font-weight: normal;
    vertical-align: middle;
    color: #FFFFFF;
    border-color: #000000;
    border-width: 1px;
    border-radius: 5px;}

.flair {
border: none !important;
padding:0px;
background: url(%%spritesheet%%) no-repeat -9999px -9999px;
display:inline-block;
}

.flair-1{ background-position: 0 0; min-width: 26px; min-height: 12px; text-indent: 35px; } 
.flair-2{ background-position: 0 -62px; min-width: 26px; min-height: 12px; text-indent: 35px; } 
.flair-3{ background-position: 0 -124px; min-width: 26px; min-height: 12px; text-indent: 35px; } 
.flair-4{ background-position: 0 -186px; min-width: 26px; min-height: 12px; text-indent: 35px; } 
.flair-5{ background-position: 0 -248px; min-width: 22px; min-height: 26px; text-indent: 35px; } 
.flair-6{ background-position: 0 -324px; min-width: 22px; min-height: 26px; text-indent: 35px; } 
.flair-7{ background-position: 0 -400px; min-width: 30px; min-height: 12px; text-indent: 35px; } 
.flair-8{ background-position: 0 -462px; min-width: 30px; min-height: 11px; text-indent: 35px; } 


.flair-eboue{ background-image: url(%%eboue%%); background-position: 0 0; min-width: 18px; min-height: 27px; text-indent: 25px;}
.flair-wenger{ background-image: url(%%eboue%%); background-position: 0 -77px; min-width: 18px; min-height: 25px; text-indent: 25px; } 
