# css
/* Variable definitions    ==================== &lt;Variable name="keycolor" description="Main Color" type="color" default="#6FCD6F" value="#6FCD6F"/> &lt;Group description="links color" selector="body"> &lt;Variable name="main.color" description="Main Theme Color" type="color" default="#6FCD6F" value="#6FCD6F"/> &lt;/Group>  */ html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline} article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block} body{line-height:1;display:block} *{margin:0;padding:0} html{display:block} ol,ul{list-style:none} blockquote,q{quotes:none} blockquote:before,blockquote:after,q:before,q:after{background:transparent} table{border-collapse:collapse;border-spacing:0} .navbar,.post-feeds,.feed-links{display:none} .section,.widget{margin:0;padding:0} strong,b{font-weight:700} strong,b:hover{right:-.1em;content:'[';-webkit-transform:translateX(-100%);transform:translateX(-100%)} cite,em,i{font-style:italic} a:link{text-decoration:none;outline:none;transition:all .25s;color:$(main.color)} a:visited{color:#666;text-decoration:none} a:link:hover{text-decoration:none;color:$(main.color)} a:visited:hover{color:#2D3E52;text-decoration:none} a img{border:none;border-width:0;outline:none} img{max-width:100%;vertical-align:middle;border:0} abbr,acronym{cursor:help} sup,sub{vertical-align:baseline;position:relative;top:-.4em;font-size:86%} sub{top:.4em} small{font-size:86%} mark{background-color:#ffce00;color:#182025} p,blockquote,pre,table,figure,hr,ol,ul,dl{margin:1.5em 0} hr{height:1px;border:none;background-color:#444} #layout ul{display:none} .top-wrapper{overflow:hidden;position:relative} h1,h2,h3,h4,h5,h6{font-family:'Lato',sans-serif;font-weight:700;line-height:normal;margin:0 0 .6em} h1{font-size:200%} h2{font-size:180%} h3{font-size:160%} h4{font-size:140%} h5{font-size:120%} h6{font-size:100%} input,button,select,textarea{font-size:100%;line-height:normal;vertical-align:baseline} textarea{display:block;box-sizing:border-box} pre,code{font-family:'Signika',sans-serif;color:#444} pre{white-space:pre;word-wrap:normal;overflow:auto} blockquote{font-style:italic;position:relative;font-size:14px;padding:0;padding-right:60px;margin:40px 0;border:0;font-weight:400} pre,code{font-family:'Signika',sans-serif;color:#444} pre{white-space:pre;word-wrap:normal;overflow:auto} blockquote{background-color:#f9f9f9;border-right:8px solid #bfcada;padding:10px;margin:10px} :focus{outline:0!important} ul,dl{margin:.5em 3em .5em 0} ol{list-style:decimal outside} ul{list-style:disc outside} li{margin:.5em 0} div.clear{clear:both} .clear{clear:both} dt{font-weight:700} dd{margin:0 2em .5em 0} .post ul li span{position:relative;margin:0;padding:5px 8px;margin-bottom:10px;text-decoration:none;transition:all .3s ease-out} ol{counter-reset:li;list-style:none;padding:0;margin-bottom:4em;text-shadow:0 1px 0 rgba(255,255,255,.5)} ol ol{margin:0 2em 0 0} .post ol li{position:relative;display:block;padding:.4em .8em .4em .4em;margin:.5em 2.5em .5em 0;background:#fff;color:#666;text-decoration:none;transition:all .3s ease-out} .post ol li:before{content:counter(li);counter-increment:li;position:absolute;right:-2.5em;top:50%;margin-top:-1em;height:2em;width:2em;line-height:2em;text-align:center} .post-body table th,.post-body table td,.post-body table caption{border:1px solid #eee;padding:10px;text-align:right;vertical-align:top} .post-body table.tr-caption-container{border:1px solid #eee} .post-body th{font-weight:700} .post-body table caption{border:none;font-style:italic} .post-body td,.post-body th{vertical-align:top;text-align:right;font-size:13px;padding:3px 5px;border:1px solid #eee} .post-body th{background:#fafafa} .post-body table.tr-caption-container td{border:none;padding:8px} .post-body table.tr-caption-container,.post-body table.tr-caption-container img,.post-body img{max-width:100%;height:auto} .post-body td.tr-caption{color:#666;font-size:80%;padding:0 8px 8px!important} img{max-width:100%;height:auto;border:none} table{max-width:100%;width:100%;margin:1.5em auto} table.section-columns td.first.columns-cell{border-right:none} table.section-columns{border:none;table-layout:fixed;width:100%;position:relative} table.columns-2 td.columns-cell{width:50%} table.columns-3 td.columns-cell{width:33.33%} table.columns-4 td.columns-cell{width:25%} table.section-columns td.columns-cell{vertical-align:top} table.tr-caption-container{padding:4px;margin-bottom:.5em} td.tr-caption{font-size:80%} .widget ul{padding:0} .quickedit{display:none;visibility:hidden} body{background:#f1f1f1;color:#656e7f;font-family:'tharabic',sans-serif;font-size:16px;font-weight:300;line-height:27px;margin:0} body#layout #mainbwrap{width:100%;float:right} body#layout #sidebar-wrapper{width:33%;right:0;padding:0;float:left} body#layout .sidebar-area{width:100%;margin:0;padding:0} body#layout #bwrapcontent,body#layout #sidebar-wrapper{padding:0} body#layout .content-area{width:65%} hr{background-color:#242d36;height:1px;margin-bottom:26px;padding:0} blockquote{color:#9ba2af;font-family:'Lato',sans-serif;border-right:5px solid rgba(155,162,175,0.25);margin-right:0;margin-left:0;margin-bottom:27px;padding-right:27px} blockquote blockquote{font-size:inherit} img{height:auto;max-width:100%} a{color:$(main.color);text-decoration:none;-webkit-transition:all .2s ease-in-out;-moz-transition:all .2s ease-in-out;-o-transition:all .2s ease-in-out;transition:all .2s ease-in-out} a:visited{color:$(main.color)} a:hover,a:focus,a:active{color:$(main.color);-webkit-transition:all .2s ease-in-out;-moz-transition:all .2s ease-in-out;-o-transition:all .2s ease-in-out;transition:all .2s ease-in-out} .site-header{background:#242d36;border-bottom:5px solid #1e252d;margin:0;position:relative;width:100%;z-index:100} .site-header img{display:block;margin:0 auto;max-height:200px} .content-area{float:right;margin:0 auto;width:67.62%} #main-nav .current-menu-item a{background-color:$(main.color);color:#fff} #main-nav a:hover{color:#fff;background-color:$(main.color)} #searchsubmit{background-color:$(main.color)} .widget-title{background:none repeat scroll 0 0 #4B3F57;color:#FFF;font-size:16px;font-weight:400;text-transform:uppercase;margin:0 0 5px;position:relative;transition:all .5s ease-out 0} .sidebar-area{float:left;overflow:hidden;width:30.69%} #sidebar .widget h2{font-size:15px;font-weight:900;color:#555;margin:0 0 1px;padding:10px} #sidebar .widget h2:before{content:"\f046";font-family:FontAwesome;display:inline-block;margin-left:6px;color:$(main.color)} #sidebar .widget{margin-bottom:12px;background:#fff;padding:10px;border:1px solid rgb(230,230,230)} .site-footer{background:#FFF;clear:both;color:#535354;font-size:12px;font-weight:400;line-height:1.8em;padding:10px;text-align:center;overflow:hidden;border-top:1px solid rgb(230,230,230)} .site-info{float:right;line-height:35px} .footerlinks{float:left;line-height:35px} .site-footer a{color:#535354;text-decoration:none;font-weight:600} .post-body a.img,.post-body .separator a{margin-right:0!important;margin-left:0!important} .imageContainer{width:120px;height:80px;overflow:hidden;float:right;margin-left:8px} .recent .title{line-height:32px;color:#19232D;margin-bottom:10px;text-align:center;font-size:16px;background:url(https://lh3.googleusercontent.com/-Dm8yPXEZEb8/U2qdIaxbm4I/AAAAAAAAEEs/nNS9zkdI8UQ/h120/dot.png) rgba(0,0,0,0.06)} .recent .title a{color:#fff;background-color:$(main.color);display:inline-block;padding:3px 15px;font-family:Solaimanlipi,Kalpurush,Siyam Rupali} .recent a{color:#111} .recent .title a:hover{text-decoration:underline} .recent ul{padding-top:15px;padding-bottom:15px} .label_thumb{position:relative;max-width:none!important;margin-right:0;transform:scale(1.0);transition:.9s} .label_title{display:block;font-size:15px;line-height:23px;color:#2D2D2D!important} .label_title:hover{color:#32aae1!important} .post-date{font-size:11px;font-weight:400;color:#888!important;margin-left:8px} .post-date:before{content:"\f073";font-family:FontAwesome;display:inline-block;margin-left:3px} .recent-com{color:#888!important;font-size:11px} .recent-com:before{content:"\f0e6";font-family:FontAwesome;display:inline-block;margin-left:3px} .toe{overflow:hidden;display:block;margin-bottom:5px} .post-summary{line-height:18px} .ro{margin-bottom:15px;overflow:hidden} .recent{background-color:#FFF;overflow:hidden} .avatar-image-container img{height:70px;width:70px;overflow:hidden;float:right;margin-left:20px;max-width:100%!important} .post-info{margin-bottom:15px;margin-left:10px;color:#8c919b;font-size:11px;font-weight:600;padding:5px} .post-info a{display:inline;background:transparent;color:#8c919b;padding:5px;padding-right:0;margin-bottom:10px;transition:all .3s ease-out} .post-info a:hover{background:transparent} .author-info,.comment-info,.time-info{display:inline} .author-info,.comment-info{display:none} #main-nav ul li ul a:hover{color:#fff} .comments .comments-content .comment{padding:20px} #comments{padding:0!important;margin-top:20px} .comments .avatar-image-container{max-height:100%!important;width:70px!important;margin-left:10px;border-radius:100%;border:4px solid $(main.color)} .comment-block{border-bottom:1px solid #ecedee;margin-bottom:20px;padding-bottom:20px;overflow:hidden;position:relative} .comment-header a{font-size:14px;font-style:normal;display:inline-block;margin-bottom:5px;color:#34495E;font-family:'Lato',sans-serif} .comments .comments-content .datetime a{font-size:11px;font-weight:600} .comments .comments-content .datetime,.comments .comment .comment-actions a{float:left} .comment-actions a:hover{background:$(main.color);color:#fff;text-decoration:none} .comment-actions a{color:$(main.color);background:#fff;border:2px solid $(main.color);font-size:13px;padding:5px 20px!important;margin-right:10px;font-weight:600;font-family:'Lato',sans-serif} .comments .comments-content .comment-header{background:#fff;padding:5px;margin-bottom:0;border:1px solid #ddd} .comments .comment .comment-actions a{padding:0} .comments .comment .comment-actions a:hover{text-decoration:none} .comments .continue{cursor:pointer;margin-top:-30px;margin-bottom:30px} .comments .continue a{display:block;color:#333;font-size:11px;font-weight:400;padding:0} .comments .comments-content .icon.blog-author{height:initial;width:initial;margin:0 12px -4px 0;font-weight:700;color:#FFF;font-size:11px;background:$(main.color);padding:3px;border-radius:3px} .comments .comments-content .icon.blog-author:after{content:"Admin"} .comments .comments-content .comment-content{text-align:right;padding:20px;background:#ebebeb;font-family:'Merriweather',serif;color:#232323;border:1px solid #DEDEDE;border-top:0} .FollowByEmail .follow-by-email-inner .follow-by-email-address{height:40px!important;border:none;padding:5px;width:96%;margin-bottom:5px;background:#EAE9E9;font-family:Open Sans;border-radius:3px;text-align:center;font-size:15px} .FollowByEmail .follow-by-email-inner .follow-by-email-submit{font-family:'Roboto',sans-serif;height:50px!important;width:100%;margin-right:0;background:$(main.color);font-size:16px;font-weight:700;text-transform:uppercase;border:1px solid #fff;padding:10px;border-radius:3px} #footer2{max-width:600px;margin:auto;padding:10px 15px} #FollowByEmail1 h2{color:#fff;font-size:20px;font-family:'Roboto',sans-serif;text-align:center;border-bottom:4px solid #fff;border-bottom-style:double;padding-bottom:10px;text-transform:uppercase} .followbytext{font-size:15px;color:#fff;text-align:center;font-family:'Merriweather',serif;font-weight:700} h2.date-header{margin:10px 0;display:none} #header-wrapper{overflow:hidden;padding:0 20px;position:relative;max-width:1060px;margin:0 auto} #header{float:right;width:100%;color:#222;margin:0} #header h1,#header h2,#header p{display:inline-block;font-size:28px;font-weight:800;color:#6FCD6F;line-height:2.1;margin:0} #header a:hover{color:#ff675c} #header .description{font-size:14px;font-weight:700;text-transform:none;line-height:normal;margin:0;display:none} .header img{display:block;max-width:150px} .header-left{float:left;padding:0;overflow:hidden;margin:0;width:100%;max-width:728px} .header-left img{display:block;float:left} #comments{padding:15px;margin-bottom:15px;background:#fff;border:1px solid rgb(230,230,230)} #comments h4{font-size:15px;font-weight:900;color:#555;margin:0 0 1px;padding:15px;border-bottom:1px solid #F1F4F9} #comments h4:before{content:"\f0e6";font-family:FontAwesome;display:inline-block;margin-left:6px} .deleted-comment{font-style:italic;color:gray} #outer-wrapper{max-width:1050px;margin:auto} #banner{background:#fff;border:1px solid;border-color:#e5e6e9 #dfe0e4 #d0d1d5;text-align:center;padding:10px;margin:15px} .cloud-label-widget-content{display:inline-block;text-align:right;margin-top:10px} .cloud-label-widget-content .label-size{display:inline-block;float:right;font-size:10px;line-height:normal;margin:0 0 5px 5px;opacity:1} .cloud-label-widget-content .label-size a{background:$(main.color);color:#fff;float:right;font-weight:600;line-height:100%;margin:0;padding:10px 8px;transition:all .6s;font-size:12px;border-radius:3px;border:2px solid} .cloud-label-widget-content .label-size a:hover{background:#fff;color:$(main.color);border:2px solid $(main.color);border-radius:0} .cloud-label-widget-content .label-size .label-count{background:$(main.color);color:#fff;white-space:nowrap;display:inline-block;padding:6px 8px;margin-right:-3px;line-height:normal;border-radius:0 2px 2px 0;font-size:11px;font-weight:600} .Label li{position:relative;padding:5px 20px 10px 30px!important;list-style:disc;display:block;font-size:14px;font-weight:700} .Label li:before{content:"\f061";font-family:fontAwesome;color:#ccc;font-size:8px;margin-right:15px;position:absolute;top:9px;left:0;padding:0;text-decoration:none;margin-top:1px} .Label li a{color:#666} .Label li:hover:before{color:$(main.color);transition:all .6s} .Label li span{padding:0 10px;display:block;line-height:20px;position:absolute;left:15px;top:10px;font-size:11px;background:$(main.color);color:#fff} .Label li:hover span{background:#FC3931;transition:all .6s} .sidebar ul li a{color:rgba(29,28,28,0.8);font-weight:400;font-size:15px;transition:all .3s;font-family:'} .pagenav{clear:both;margin:-5px 0 10px;width:89%;margin-bottom:20px;padding:15px;text-align:center;font-size:13px;font-weight:600;font-family:'Merriweather',serif} .showpagePoint{background:$(main.color)!important;color:#fff;font-weight:700} .viewall{position:relative;overflow:hidden;font-size:12px;font-weight:700;transition:all 0.5s ease-out;float:left;padding:0 0 0 6px;border-right:1px solid #ddd;background:rgba(240,241,243,0.48)} .viewall a{color:#555} #error404,.followby,.modalDialog{background:$(main.color)} #error-text a{color:$(main.color)} .home-link{background:$(main.color);padding:12px 17px 12px 20px;position:absolute;color:#fff!important} #blog-pager-newer-link{float:right} #blog-pager-older-link{float:left} #blog-pager a{color:#333;text-transform:uppercase;font-size:13px;font-weight:600;line-height:1.3} #blog-pager{text-align:center;margin-top:10px} .related-postbwrap{float:right;background:#fff;margin-top:15px;border:1px solid rgb(230,230,230)} .related-postbwrap h4{font-size:15px;font-weight:900;color:#555;margin:0 0 1px;padding:15px} .related-postbwrap h4:before{content:"\f0c9";font-family:FontAwesome;display:inline-block;margin-left:6px} .related-post-style-2,.related-post-style-2 li{list-style:none;margin:0} .related-post-style-2 li{overflow:hidden;padding:10px;padding-left:5px;width:30.9333%;float:right;border:1px solid #ddd;border-bottom:0;border-left:0;border-style:dotted} .related-post-style-2 .related-post-item-thumbnail{width:72px;height:72px;max-width:none;max-height:none;background-color:transparent;border:none;float:right;margin:2px 0 0 10px;padding:0} .related-post-style-2 .related-post-item-title{color:rgba(51,51,51,0.84);text-decoration:none;font-size:13px;font-weight:700;transition:all 0.3s ease-out;line-height:1.4} .related-post-style-2 .related-post-item-summary{display:block;font-size:12px;margin-top:5px;line-height:1.3;display:none} .related-post-item-more{display:none} .top-header{padding:20px 0;max-width:1090px;margin:auto} .fixed_widget{background:none!important;position:fixed!important;top:25px;z-index:99;-webkit-transform:translateZ(0)} .label_thumb{margin-right:0;transform:scale(1.0);transition:.9s} .label_title{display:block;font-size:15px;line-height:23px;font-family:'lefteous',cursive;color:#595757!important} .label_title:hover{color:$(main.color)!important} .post-date{font-size:11px;font-weight:400;color:#888!important;margin-left:8px} .post-date:before{content:"\f017";font-family:FontAwesome;display:inline-block;margin-left:3px} .recent-com{color:#888!important;font-size:11px} .recent-com:before{content:"\f086";font-family:FontAwesome;display:inline-block;margin-left:3px} .post-summary{padding-top:0!important;text-align:justify} img.recent_thumb{width:80px;height:80px;float:right;margin-bottom:5px;transition:.9s;margin-left:10px} img.recent_thumb:hover{opacity:.5;transition:.6s} ul.recent_posts_with_thumbs{padding:0!important;margin-top:5px} .recent_posts_with_thumbs{float:right;width:100%;min-height:100%;margin:5px 0;padding:0;font-size:12px} ul.recent_posts_with_thumbs li{padding-bottom:15px;min-height:60px;border-bottom:1px solid rgba(206,206,206,0.38);margin-bottom:10px;list-style:none} ul.recent_posts_with_thumbs li:last-child{border-bottom:none;margin:0;padding:0} ul.recent_posts_with_thumbs li p{margin:.3em 0;font-size:11px} .recent_posts_with_thumbs a{text-decoration:none;color:rgba(51,51,51,0.84);text-decoration:none;font-size:15px;font-weight:700;transition:all 0.3s ease-out;line-height:1.4} .recent_posts_with_thumbs strong{font-size:10px} #header-area{background:#fff} input#sq{border:1px solid $(main.color)} #searchsubmit{background:$(main.color);border:1px solid $(main.color)} #header-ad{text-align:center} #adpost2{margin-bottom:10px} .PopularPosts ul li .item-title a:hover,.PopularPosts ul li a:hover{color:$(main.color)} .sticky{position:fixed!important;top:0;z-index:99;-webkit-transform:translateZ(0)} .at-share-btn-elements{text-align-last:right} .post-info{text-align-last:right} input#sq{text-align-last:right}} .widget-content{text-align-last:right} .title22{text-align-last:right} .widget-content{text-align-last:right} perfil-wrapper{font-family:'tharabic',Arial;padding:0 0 20px;background:#fff;box-shadow:0 2px 5px 0 rgba(0,0,0,0.16),0 2px 10px 0 rgba(0,0,0,0.12);max-width:400px} perfil-wrapper .perfilimg{width:100%;height:130px;float:right;overflow:hidden} img.profilex{width:60px;border-radius:100%;float:right;margin:-35px 20px 0;box-shadow:rgba(0,0,0,0.2) 0 8px 17px 0,rgba(0,0,0,0.188235) 0 6px 20px 0;backface-visibility:hidden} img{height:auto;max-width:100%} img{max-width:100%;height:auto;border:none} img{max-width:100%;vertical-align:middle;border:0} perfil-wrapper h4{line-height:3;font-weight:400;font-size:15px} perfil-wrapper p{padding:0 20px} a.linkcircle{color:#fff;background-color:#da1b1b;position:absolute;top:120px;left:30px;border-radius:100%;height:20px} body{background:#f1f1f1;color:#656e7f;font-family:'farhat-font',sans-serif;font-size:16px;font-weight:300;line-height:27px;margin:0} ELYAZPRO.TECH */  #wrap{margin:20px auto;text-align:center} #wrap br{display:none} .btn-slide,.btn-slide2{position:relative;display:inline-block;height:50px;width:200px;line-height:50px;padding:0;border-radius:50px;background:#363050;border:2px solid #0099cc;margin:10px;transition:.5s} .btn-slide2{border:2px solid #558FEB} .btn-slide:hover{background-color:#0099cc} .btn-slide2:hover{background-color:#DB5252} .btn-slide:hover span.circle,.btn-slide2:hover span.circle2{left:100%;margin-left:-45px;background-color:#fdfdfd;color:#0099cc} .btn-slide2:hover span.circle2{color:#DB5252} .btn-slide:hover span.title,.btn-slide2:hover span.title2{left:40px;opacity:0} .btn-slide:hover span.title-hover,.btn-slide2:hover span.title-hover2{opacity:1;left:40px} .btn-slide span.circle,.btn-slide2 span.circle2{display:block;background-color:#2e9fff;color:#fff;position:absolute;float:left;margin:5px;line-height:42px;height:40px;width:40px;top:0;left:0;transition:.5s;border-radius:50%} .btn-slide2 span.circle2{background-color:#DB5252} .btn-slide span.title,.btn-slide span.title-hover,.btn-slide2 span.title2,.btn-slide2 span.title-hover2{position:absolute;left:90px;text-align:center;margin:0 auto;font-size:16px;font-weight:bold;color:#30abd5;transition:.5s} .btn-slide2 span.title2,.btn-slide2 span.title-hover2{color:#2FA8D1;left:80px} .btn-slide span.title-hover,.btn-slide2 span.title-hover2{left:80px;opacity:0} .btn-slide span.title-hover,.btn-slide2 span.title-hover2{color:#fff}