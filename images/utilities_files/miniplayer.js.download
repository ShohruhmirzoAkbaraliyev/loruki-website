(function(g){var window=this;'use strict';var x3=function(a){g.W.call(this,{F:"div",L:"ytp-miniplayer-ui"});this.Se=!1;this.player=a;this.P(a,"minimized",this.gh);this.P(a,"onStateChange",this.IJ)},y3=function(a){g.WI.call(this,a);
this.j=new x3(this.player);this.j.hide();g.II(this.player,this.j.element,4);a.sf()&&(this.load(),g.O(a.getRootNode(),"ytp-player-minimized",!0))};
g.w(x3,g.W);g.k=x3.prototype;
g.k.lH=function(){this.tooltip=new g.hN(this.player,this);g.J(this,this.tooltip);g.II(this.player,this.tooltip.element,4);this.tooltip.scale=.6;this.Cc=new g.RJ(this.player);g.J(this,this.Cc);this.Lh=new g.W({F:"div",L:"ytp-miniplayer-scrim"});g.J(this,this.Lh);this.Lh.xa(this.element);this.P(this.Lh.element,"click",this.GC);var a=new g.W({F:"button",Ba:["ytp-miniplayer-close-button","ytp-button"],T:{"aria-label":"Close"},R:[g.DG()]});g.J(this,a);a.xa(this.Lh.element);this.P(a.element,"click",this.Nj);
a=new g.FZ(this.player,this);g.J(this,a);a.xa(this.Lh.element);this.qr=new g.W({F:"div",L:"ytp-miniplayer-controls"});g.J(this,this.qr);this.qr.xa(this.Lh.element);this.P(this.qr.element,"click",this.GC);var b=new g.W({F:"div",L:"ytp-miniplayer-button-container"});g.J(this,b);b.xa(this.qr.element);a=new g.W({F:"div",L:"ytp-miniplayer-play-button-container"});g.J(this,a);a.xa(this.qr.element);var c=new g.W({F:"div",L:"ytp-miniplayer-button-container"});g.J(this,c);c.xa(this.qr.element);this.BQ=new g.FL(this.player,
this,!1);g.J(this,this.BQ);this.BQ.xa(b.element);b=new g.DL(this.player,this);g.J(this,b);b.xa(a.element);this.nextButton=new g.FL(this.player,this,!0);g.J(this,this.nextButton);this.nextButton.xa(c.element);this.Oh=new g.UM(this.player,this);g.J(this,this.Oh);this.Oh.xa(this.Lh.element);this.uc=new g.QL(this.player,this);g.J(this,this.uc);g.II(this.player,this.uc.element,4);this.wC=new g.W({F:"div",L:"ytp-miniplayer-buttons"});g.J(this,this.wC);g.II(this.player,this.wC.element,4);a=new g.W({F:"button",
Ba:["ytp-miniplayer-close-button","ytp-button"],T:{"aria-label":"Close"},R:[g.DG()]});g.J(this,a);a.xa(this.wC.element);this.P(a.element,"click",this.Nj);a=new g.W({F:"button",Ba:["ytp-miniplayer-replay-button","ytp-button"],T:{"aria-label":"Close"},R:[g.JG()]});g.J(this,a);a.xa(this.wC.element);this.P(a.element,"click",this.NZ);this.P(this.player,"presentingplayerstatechange",this.Wc);this.P(this.player,"appresize",this.wb);this.P(this.player,"fullscreentoggled",this.wb);this.wb()};
g.k.show=function(){this.oe=new g.Dn(this.ls,null,this);this.oe.start();this.Se||(this.lH(),this.Se=!0);0!==this.player.getPlayerState()&&g.W.prototype.show.call(this);this.uc.show();this.player.unloadModule("annotations_module")};
g.k.hide=function(){this.oe&&(this.oe.dispose(),this.oe=void 0);g.W.prototype.hide.call(this);this.player.sf()||(this.Se&&this.uc.hide(),this.player.loadModule("annotations_module"))};
g.k.ea=function(){this.oe&&(this.oe.dispose(),this.oe=void 0);g.W.prototype.ea.call(this)};
g.k.Nj=function(){this.player.stopVideo();this.player.La("onCloseMiniplayer")};
g.k.NZ=function(){this.player.playVideo()};
g.k.GC=function(a){if(a.target===this.Lh.element||a.target===this.qr.element)this.player.S().K("kevlar_miniplayer_play_pause_on_scrim")?g.FF(this.player.xb())?this.player.pauseVideo():this.player.playVideo():this.player.La("onExpandMiniplayer")};
g.k.gh=function(){g.O(this.player.getRootNode(),"ytp-player-minimized",this.player.sf())};
g.k.Od=function(){this.uc.Sb();this.Oh.Sb()};
g.k.ls=function(){this.Od();this.oe&&this.oe.start()};
g.k.Wc=function(a){g.V(a.state,32)&&this.tooltip.hide()};
g.k.wb=function(){g.fM(this.uc,0,this.player.Ya().getPlayerSize().width,!1);g.TL(this.uc)};
g.k.IJ=function(a){this.player.sf()&&(0===a?this.hide():this.show())};
g.k.kc=function(){return this.tooltip};
g.k.Jf=function(){return!1};
g.k.gg=function(){return!1};
g.k.Fj=function(){return!1};
g.k.Cz=function(){};
g.k.fp=function(){};
g.k.yu=function(){};
g.k.Bp=function(){return null};
g.k.Yx=function(){return null};
g.k.Dj=function(){return new g.Yk(0,0,0,0)};
g.k.handleGlobalKeyDown=function(){return!1};
g.k.handleGlobalKeyUp=function(){return!1};
g.k.As=function(a,b,c,d,e){var f=0,h=d=0,l=g.ll(a);if(b){c=g.eo(b,"ytp-prev-button")||g.eo(b,"ytp-next-button");var m=g.eo(b,"ytp-play-button"),n=g.eo(b,"ytp-miniplayer-expand-watch-page-button");c?f=h=12:m?(b=g.jl(b,this.element),h=b.x,f=b.y-12):n&&(h=g.eo(b,"ytp-miniplayer-button-top-left"),f=g.jl(b,this.element),b=g.ll(b),h?(h=8,f=f.y+40):(h=f.x-l.width+b.width,f=f.y-20))}else h=c-l.width/2,d=25+(e||0);b=this.player.Ya().getPlayerSize().width;e=f+(e||0);l=g.Xf(h,0,b-l.width);e?(a.style.top=e+"px",
a.style.bottom=""):(a.style.top="",a.style.bottom=d+"px");a.style.left=l+"px"};
g.k.showControls=function(){};
g.k.Mm=function(){};
g.k.fm=function(){return!1};g.w(y3,g.WI);y3.prototype.create=function(){};
y3.prototype.hj=function(){return!1};
y3.prototype.load=function(){this.player.hideControls();this.j.show()};
y3.prototype.unload=function(){this.player.showControls();this.j.hide()};g.VI("miniplayer",y3);})(_yt_player);
