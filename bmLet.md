# [bmLet](https://lynopus.github.io/bmLet.html) - Bookmark Let

- Flow :
  1. Visit [git](https://github.com/LynOpus/LynOpus.github.io/blob/master/bmLet.md)
  2. Click `Blame` button .
  3. Visit [html view](https://lynopus.github.io/bmLet.html) for resluts .

- [Useful Bookmarklet
](http://www.howtogeek.com/125846/the-most-useful-bookmarklets-to-enhance-your-browsing-experience/)

- [書籤工具](https://tw.piliapp.com/bookmarklet/)

- [gHacks bookmarklet](https://www.ghacks.net/?s=bookmarklet)

- [Convert bookmarklet to Chrome extension
](https://sandbox.self.li/bookmarklet-to-extension/)


## Markdown

- [#Chrono
](javascript:(function(d){var x=d.createElement('textarea');x.appendChild(d.createTextNode('\n## '+d.title+'\n\n['+d.lastModified+']('+d.URL+')\n\n'));d.body.appendChild(x);x.select();d.execCommand('copy');d.body.removeChild(x);})(document))

- [#MarkUP
](javascript:(function(d){var x=d.createElement('textarea');x.appendChild(d.createTextNode('\n## ['+d.title+'\n]('+d.URL+')\n'));d.body.appendChild(x);x.select();d.execCommand('copy');d.body.removeChild(x);})(document))
| [v1.0
](/"javascript:(function(d){var x=d.createElement('textarea');x.appendChild(d.createTextNode('\n## ['+d.title+'\n]('+d.URL+')\n'));d.body.appendChild(x);x.select();d.execCommand('copy');d.body.removeChild(x);})(document)")

- [+MarkDown
](javascript:(function(d){var x=d.createElement('textarea');x.appendChild(d.createTextNode('\n+ ['+d.title+'\n]('+d.URL+')\n'));d.body.appendChild(x);x.select();d.execCommand('copy');d.body.removeChild(x);})(document))

- [=MarkIt
](javascript:(function(d){var x=d.createElement('textarea');x.appendChild(d.createTextNode(d.title+'\n'+d.URL+'\n\n'));d.body.appendChild(x);x.select();d.execCommand('copy');d.body.removeChild(x);})(document))
| [v1.0
](ftp://bm.Let/javascript:(function(d){var x=d.createElement('textarea');x.appendChild(d.createTextNode(d.title+'\n'+d.URL+'\n\n'));d.body.appendChild(x);x.select();d.execCommand('copy');d.body.removeChild(x);})(document))

- [URL
](javascript:alert('\tdocument.URL\n'+document.URL+'\n\tdocument.lastModified\n'+document.lastModified+'\n\tlocation\n'+location);)


## Note

+ [Evernote
](https://www.evernote.com/Home.action)

  - [4Ever
](javascript:(function(d){z='http://www.evernote.com/';try{var x=d.createElement('SCRIPT');x.type='text/javascript';x.src=z+'public/bookmarkClipper.js?'+(new Date().getTime()/100000);d.getElementsByTagName('head')[0].appendChild(x);}catch(e){location.href=z+'clip.action?url='+encodeURIComponent(location.href)+'&title='+encodeURIComponent(d.title);}})(document);)
| [orig version
](javascript:(function(){EN_CLIP_HOST='http://www.evernote.com';try{var x=document.createElement('SCRIPT');x.type='text/javascript';x.src=EN_CLIP_HOST+'/public/bookmarkClipper.js?'+(new Date().getTime()/100000);document.getElementsByTagName('head')[0].appendChild(x);}catch(e){location.href=EN_CLIP_HOST+'/clip.action?url='+encodeURIComponent(location.href)+'&title='+encodeURIComponent(document.title);}})();)

  - [Print as Like
](javascript:(function(w,d){if(w['ppw']&&ppw['bookmarklet']){ppw.bookmarklet.toggle();}else{w._pwyl_home='http://www.printwhatyoulike.com/';w._pwyl_pro_id=null;w._pwyl_bmkl=d.createElement('script');w._pwyl_bmkl.setAttribute('type','text/javascript');w._pwyl_bmkl.setAttribute('src',w._pwyl_home+'static/compressed/pwyl_bookmarklet_10.js');w._pwyl_bmkl.setAttribute('pwyl','true');d.getElementsByTagName('head')[0].appendChild(w._pwyl_bmkl);}})(window,document))
| [orig version
](javascript:(function(){if(window['ppw']&&ppw['bookmarklet']){ppw.bookmarklet.toggle();}else{window._pwyl_home='http://www.printwhatyoulike.com/';window._pwyl_pro_id=null;window._pwyl_bmkl=document.createElement('script');window._pwyl_bmkl.setAttribute('type','text/javascript');window._pwyl_bmkl.setAttribute('src',window._pwyl_home+'static/compressed/pwyl_bookmarklet_10.js');window._pwyl_bmkl.setAttribute('pwyl','true');document.getElementsByTagName('head')[0].appendChild(window._pwyl_bmkl);}})();)

  - [Print Friendly
](javascript:(function(d){pfstyle='bk';_pnicer_script=d.createElement('SCRIPT');_pnicer_script.type='text/javascript';_pnicer_script.src='http://cdn.printfriendly.com/printfriendly.js?x='+(Math.random());d.getElementsByTagName('head')[0].appendChild(_pnicer_script);_pnicer_css=d.createElement('LINK');_pnicer_css.rel='stylesheet';_pnicer_css.href='http://cdn.printfriendly.com/printfriendly.css';_pnicer_css.type='text/css';_pnicer_css.media='screen';d.getElementsByTagName('head')[0].appendChild(_pnicer_css);})(document);)
| [orig version
](javascript:(function(){pfstyle='bk';_pnicer_script=document.createElement('SCRIPT');_pnicer_script.type='text/javascript';_pnicer_script.src='http://cdn.printfriendly.com/printfriendly.js?x='+(Math.random());document.getElementsByTagName('head')[0].appendChild(_pnicer_script);_pnicer_css=document.createElement('LINK');_pnicer_css.rel='stylesheet';_pnicer_css.href='http://cdn.printfriendly.com/printfriendly.css';_pnicer_css.type='text/css';_pnicer_css.media='screen';document.getElementsByTagName('head')[0].appendChild(_pnicer_css);})();)


## Readability

### [1st](http://www.readability.com/bookmarklets) shut down on 2016/09/30 .

### [Readable
](http://readable.tastefulwords.com/) : still work on 2020-10-26

  - [Read85%
](javascript:(function(){_readableOptions={'text_font':'quote(Palatino Linotype), Palatino, quote(Book Antigua), Georgia, serif','text_font_monospace':'quote(Courier New), Courier, monospace','text_font_header':'quote(Times New Roman), Times, serif','text_size':'16px','text_line_height':'1.5','box_width':'85%','color_text':'#282828','color_background':'#F5F5F5','color_links':'#0000FF','text_align':'normal','base':'blueprint','custom_css':''};if(document.getElementsByTagName('body').length>0);else{return;}if(window.$readable){if(window.$readable.bookmarkletTimer){return;}}else{window.$readable={};}window.$readable.bookmarkletTimer=true;window.$readable.options=_readableOptions;if(window.$readable.bookmarkletClicked){window.$readable.bookmarkletClicked();return;}_readableScript=document.createElement('script');_readableScript.setAttribute('src','http://readable-static.tastefulwords.com/target.js?rand='+encodeURIComponent(Math.random()));document.getElementsByTagName('body')[0].appendChild(_readableScript);})())

  - [Black
](javascript:(function(){_readableOptions={'text_font':'Helvetica, quote(Helvetica Neuve), Arial, Tahoma, sans-serif','text_font_monospace':'quote(Courier New), Courier, monospace','text_font_header':'Helvetica, quote(Helvetica Neuve), Arial, Tahoma, sans-serif','text_size':'18px','text_line_height':'1.5','box_width':'40em','color_text':'#F0F0F0','color_background':'#2C2D32','color_links':'#009900','text_align':'justified','base':'blueprint','custom_css':''};if(document.getElementsByTagName('body').length>0);else{return;}if(window.$readable){if(window.$readable.bookmarkletTimer){return;}}else{window.$readable={};}window.$readable.bookmarkletTimer=true;window.$readable.options=_readableOptions;if(window.$readable.bookmarkletClicked){window.$readable.bookmarkletClicked();return;}_readableScript=document.createElement('script');_readableScript.setAttribute('src','http://readable-static.tastefulwords.com/target.js?rand='+encodeURIComponent(Math.random()));document.getElementsByTagName('body')[0].appendChild(_readableScript);})())


### [Readability - An Arc90 Lab Experiment](http://ejucovy.github.io/readability/)


### rework on 2020/10/26 with [akaleeroy/Readable-Bookmarklet](https://gist.github.com/akaleeroy/855be4a4a690ff9dafa05234f2f35928)

+ [Readable](https://rdbl.us/)

  - [readable
](javascript:(function(){_readableOptions={text_font:"quote(Open Sans Light), quote(Segoe UI Light), quote(Lucida Sans Unicode), quote(Lucida Grande), Arial, Helvetica, sans-serif",text_font_monospace:"quote(Lucida Console), quote(Andale Mono), Monaco, monospace",text_font_header:"Tinos",text_size:"24px",text_line_height:"1.75",box_width:"30em",color_text:"#FDFDFD",color_background:"#000000",color_links:"#99CCFF",text_align:"normal",base:"blueprint",custom_css:"#box,#menu,#rtl_box{background-color:transparent}::-webkit-scrollbar,::-webkit-scrollbar-corner{background:#000!important}#floating{top:1em}#floating a{padding:0;color:#708090!important}#floating_close{font-size:0}#floating_close:before{content:quote(×);font-size:24px;padding-left:.45em;padding-right:.45em;margin-right:.7em;border:2px solid;border-radius:50%}#box_inner #menu a:hover,#floating a:hover{color:#a9a9a9!important}#menu,#rtl_box{border:2px solid #708090;border-radius:32px}#menu a,#rtl_box a{color:#708090;border-bottom:1px solid inherit;vertical-align:sub}#my_news{visibility:hidden}pre{overflow-x:scroll;}@media (max-width:920px){#floating{right: -5px;}#floating a,#floating a:before{margin:0!important}}#text a{word-wrap:break-word}"};if(document.getElementsByTagName("body").length>0);else{return}if(window.$readable){if(window.$readable.bookmarkletTimer){return}}else{window.$readable={}}window.$readable.bookmarkletTimer=true;window.$readable.options=_readableOptions;if(window.$readable.bookmarkletClicked){window.$readable.bookmarkletClicked();return}_readableScript=document.createElement("script");_readableScript.setAttribute("src","//rdbl.us/target.js?rand="+encodeURIComponent(Math.random()));document.getElementsByTagName("body")[0].appendChild(_readableScript)})();)
  - [.gray
](javascript:(function(d){_readableOptions={'text_font':'Helvetica,quote(Segoe UI Light),Arial,Tahoma,sans-serif','text_font_monospace':'Monaco,quote(Courier New),Courier,monospace','text_font_header':'Helvetica,Arial,Tahoma,sans-serif','text_size':'21px','text_line_height':'1.75','box_width':'40em','color_text':'#F0F0F0','color_background':'#2C2D32','color_links':'#009900','text_align':'justified','base':'blueprint','custom_css':''};if(d.getElementsByTagName('body').length<=0) return;if(window.$readable){if(window.$readable.bookmarkletTimer) return;}else{window.$readable={};}window.$readable.bookmarkletTimer=true;window.$readable.options=_readableOptions;if(window.$readable.bookmarkletClicked){window.$readable.bookmarkletClicked();return;}z=d.createElement('script');z.setAttribute('src','//rdbl.us/target.js?rand='+encodeURIComponent(Math.random()));d.getElementsByTagName('body')[0].appendChild(z);})(document))

 - [.Dark
](javascript:(function(){_readableOptions={'text_font':'Monaco','text_font_monospace':'Monaco','text_font_header':'','text_size':'20px','text_line_height':'1.5','box_width':'40em','color_text':'#FDFDFD','color_background':'#343A3A','color_links':'#99CCFF','text_align':'justified','base':'blueprint','custom_css':''};if(document.getElementsByTagName('body').length>0);else{return;}if(window.$readable){if(window.$readable.bookmarkletTimer){return;}}else{window.$readable={};}window.$readable.bookmarkletTimer=true;window.$readable.options=_readableOptions;if(window.$readable.bookmarkletClicked){window.$readable.bookmarkletClicked();return;}_readableScript=document.createElement('script');_readableScript.setAttribute('src','//rdbl.us/target.js?rand='+encodeURIComponent(Math.random()));document.getElementsByTagName('body')[0].appendChild(_readableScript);})())

### [mozilla version](https://github.com/viktor-evdokimov/bookmarklet-readability)


## DicT - Dictionary & Translator

- [同文堂
](javascript:(function(d){var s=d.getElementById('twLet');if(s!=null){d.body.removeChild(s);}s=d.createElement('script');s.language='javascript';s.type='text/javascript';s.src='https://lynopus.github.io/tongwen.js';s.id='twLet';d.body.appendChild(s);})(document);)

- [gTran
](javascript:(function(w,d){var u='https://translate.google.com/',e='&hl=en&langpair=auto|zh-TW&tbb=1&ie='+(d.charset||d.characterSet),z='getSelection',t=(''+(w[z]?w[z]():d[z]?d[z]():d.selection.createRange().text)).replace(/(^\s+|\s+$)/g,'');if(t!=''){y=w.open(u+'?text='+t+e,'','status=0,toolbar=0,width=800,height=640,resizable=1');}else{location.href=u+'translate?u='+encodeURIComponent(location.href)+e;}})(window,document))
| [old version
](javascript:var w=window,d=document,z='getSelection';var t=(''+(w[z]?w[z]():d[z]?d[z]():d.selection.createRange().text)).replace(/(^\s+|\s+$)/g,'');var e='&hl=en&langpair=auto|zh-TW&tbb=1&ie='+(d.charset||d.characterSet);if(t!=''){y=w.open('http://translate.google.com/?text='+t+e,'','status=0,toolbar=0,width=800,height=640,resizable=1');}else{location.href='http://translate.google.com/translate?u='+encodeURIComponent(location.href)+e;};)
| [elder
](javascript:var t=((window.getSelection&&window.getSelection())||(document.getSelection&&document.getSelection())||(document.selection&&document.selection.createRange&&document.selection.createRange().text));var e=(document.charset||document.characterSet);if(t!=''){location.href='http://translate.google.com/?text='+t+'&hl=en&langpair=auto|zh-TW&tbb=1&ie='+e;}else{location.href='http://translate.google.com/translate?u='+encodeURIComponent(location.href)+'&hl=en&langpair=auto|zh-TW&tbb=1&ie='+e;};)
: open window if selection, otherwise replace here.

- [~~~zh-TW~~~
](javascript:open('https://translate.google.com/translate?hl=zh-TW&sl=auto&tl=zh-TW&u='+encodeURIComponent(location.href));)
| [old version
](javascript:open('http://translate.google.com/translate?prev=hp&hl=zh-TW&sl=zh-CN&tl=zh-TW&u='+encodeURIComponent(location.href));)

- [|msTran
](javascript:window.open('https://www.translatetheweb.com/?to=zh-Hant&a='+encodeURIComponent(document.location)))
| [old version
](javascript:window.open('https://www.microsofttranslator.com/bv.aspx?to=zh-CHT&a='+encodeURIComponent(document.location)))
| [elder
](javascript:(function(){var s=document.createElement('script');s.type='text/javascript';s.src='http://labs.microsofttranslator.com/bookmarklet/default.aspx?f=js&to=zh-cht';document.body.insertBefore(s,document.body.firstChild);})())

+ [cDict](https://cdict.net/) : English-Chinese Dictionary (英漢字典) 

  - [cDic
](https://cdict.net/?q=yahoo)
  - [gDic
](http://www.google.com.tw/m/search?site=dictionary&gdm=1&q=welcome)
  - [yDic
](javascript:function se(d){return d.selection?d.selection.createRange().text:d.getSelection()} s=se(document); for(i=0;i<frames.length && !s; i++) s=se(frames[i].document); if (!s || s=='') s=prompt('Enter search word ',''); if(s) window.open('https://tw.dictionary.search.yahoo.com/search?p=' + encodeURIComponent(s),'', 'width=700,height=600').focus();)
| [orig version
](javascript:function se(d){return d.selection?d.selection.createRange().text:d.getSelection()} s=se(document); for(i=0;i<frames.length && !s; i++) s=se(frames[i].document); if (!s || s=='') s=prompt('Enter search word ',''); if(s) window.open('http://tw.dictionary.yahoo.com/dictionary?p=' + encodeURIComponent(s),'', 'width=700,height=600').focus();)

### expired

- [海詞
](javascript:(function(d){var s=d.getElementById('hzLet');if(s!=null){d.body.removeChild(s);} s=d.createElement('script');s.language='javascript';s. type='text/javascript';s.src='https://sites.google.com/site/bemehom/hz.js';s.id='hzLet';d.body.appendChild(s);})(document);)

- [釋義
](javascript:void((function(){var element=document.createElement('script');element.setAttribute('src', 'http://www.zdic.net/tools/xzsy/');document.body.appendChild(element);})()))


## Site

- [ms
](javascript:window.location.href='https://www.microsofttranslator.com/bv.aspx?to=zh-CHT&a='+encodeURIComponent(document.location);)

: take MicroSoft Translator as proxy

+ [Archive
](https://web.archive.org/)

  - [4Archive
](javascript:location.href='https://web.archive.org/save/'+document.location.href;)

  - [|Archive
](javascript:void(window.open('https://web.archive.org/save/'+document.location.href)))

- [gCache
](javascript:void((function(){var a=location.href.replace(/^http%5C:%5C/%5C/(.*)$/,'$1');location.href='http://www.google.com/search?q=cache:'+escape(a);})()))

- [Gem
](javascript:(function(d){window.open('http://mail.google.com/mail/?view=cm&fs=1&tf=1&to=opus.lin%252Blx@gmail.com&su='+encodeURIComponent(d.title)+'&body='+encodeURIComponent(d.location)+escape('\n\n\n\n'),'','width=800,height=600,top=40,left=40').focus()})(document))
| [old version
](javascript:(function(){var d=document;window.open('http://mail.google.com/mail/?view=cm&fs=1&tf=1&to=opus.lin%252Blx@gmail.com&su='+encodeURIComponent(d.title)+'&body='+encodeURIComponent(d.location)+escape('\n\n\n\n'),'','width=800,height=600,top=40,left=40').focus()})())

- [SE
](javascript:(function(w,d){var s=""+(w.getSelection?w.getSelection():d.getSelection?d.getSelection():d.selection.createRange().text);if(!s)s=prompt("\u8acb\u8f38\u5165\u641c\u5c0b\u7684\u95dc\u9375\u5b57%EF%BC%9A","");w.open('https://www.baidu.com/s?wd='+s);w.open('https://www.google.com/search?q='+s+'&ie=utf-8&oe=utf-8');w.open('https://www.bing.com/search?q='+s)})(window,document))
: multiple search engines

- [WGB
](javascript:(function(d,w){var s=''+(w.getSelection?w.getSelection():d.getSelection?d.getSelection():d.selection.createRange().text);if(s){s=encodeURIComponent(s);w.open('https://en.wikipedia.org//w/index.php?title=Special:Search&search='+s);w.open('https://www.google.com/search?ie=utf-8&oe=utf-8&q='+s);w.open('https://www.bing.com/search?q='+s)}})(document,window);)
: search Wiki / Google / Bing


## Utility

- Unblock right-click 解除鎖滑鼠右鍵 [Right
](javascript:(function(a,c){function b(d){var e='on'+d;if(c.addEventListener){c.addEventListener(d,function(f){for(var g=f.originalTarget;g;g=g.parentNode){g[e]=null}},true)}c[e]=null;a[e]=null;if(a.body){a.body[e]=null}}b('contextmenu');b('click');b('mousedown');b('mouseup');b('selectstart')})(document,window);)


+ [FlipBoard Social Plugins](https://about.flipboard.com/social-plugins/?tool=browser) : [+FlipIt
](javascript:void((function(d,w,p,s,r,t,l){t=(w.screenTop||w.screenY)+50;l=(w.screenX||w.screenLeft)+(w.innerWidth||d.documentElement.offsetWidth||0)/2-s/2;z=encodeURIComponent(w.location.href);w.__flipboard=w.open('https://share.flipboard.com/bookmarklet/popout?v=2&title='+encodeURIComponent(d.title)+'&url='+z+'&t='+p+'&utm_medium=bookmarklet&utm_campaign=tools&utm_source='+z,'__flipboard_flipit','width='+s+',height='+r+',top='+t+',left='+l+',location=no,resizable=yes,status=no,scrollbars=no,personalbar=no,toolbar=no,menubar=no');s=d.createElement('script');s.setAttribute('type','text/javascript');s.setAttribute('src','https://d2jsycj2ly2vqh.cloudfront.net/bookmarklet/js/popout-helper.min.js?t='+p);d.body.appendChild(s);setTimeout(function(){w.__flipboard.focus()},50);})(document,window,(new Date().getTime()),535,565)))


## MP3


+ [YouTube MP3 - Convert Youtube Video to MP3
](https://youtube-mp3.romanstefko.com/en) : info from PaleMoon portal

  + [=mp3
](javascript:(function(d){window.open('https://youtube-mp3.romanstefko.com/en/welcome/process?youtube_url='+encodeURIComponent(d.location),'','width=800,height=600,top=40,left=40').focus()})(document))
  + [.mp3
](javascript:void(window.open('https://youtube-mp3.romanstefko.com/en/welcome/process?youtube_url='+location.href)))


[eof]: # ( vim:set ft=markdown ts=4 sw=4 sts=2 tw=960 noai et list: -*- coding: utf-8 -*- )
