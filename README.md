# game

<html>
  <head><script type="text/javascript">window.NREUM||(NREUM={}),__nr_require=function(e,t,n){function r(n){if(!t[n]){var o=t[n]={exports:{}};e[n][0].call(o.exports,function(t){var o=e[n][1][t];return r(o||t)},o,o.exports)}return t[n].exports}if("function"==typeof __nr_require)return __nr_require;for(var o=0;o<n.length;o++)r(n[o]);return r}({1:[function(e,t,n){function r(){}function o(e,t,n){return function(){return i(e,[f.now()].concat(u(arguments)),t?null:this,n),t?void 0:this}}var i=e("handle"),a=e(2),u=e(3),c=e("ee").get("tracer"),f=e("loader"),s=NREUM;"undefined"==typeof window.newrelic&&(newrelic=s);var p=["setPageViewName","setCustomAttribute","setErrorHandler","finished","addToTrace","inlineHit","addRelease"],d="api-",l=d+"ixn-";a(p,function(e,t){s[t]=o(d+t,!0,"api")}),s.addPageAction=o(d+"addPageAction",!0),s.setCurrentRouteName=o(d+"routeName",!0),t.exports=newrelic,s.interaction=function(){return(new r).get()};var m=r.prototype={createTracer:function(e,t){var n={},r=this,o="function"==typeof t;return i(l+"tracer",[f.now(),e,n],r),function(){if(c.emit((o?"":"no-")+"fn-start",[f.now(),r,o],n),o)try{return t.apply(this,arguments)}catch(e){throw c.emit("fn-err",[arguments,this,e],n),e}finally{c.emit("fn-end",[f.now()],n)}}}};a("setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),function(e,t){m[t]=o(l+t)}),newrelic.noticeError=function(e){"string"==typeof e&&(e=new Error(e)),i("err",[e,f.now()])}},{}],2:[function(e,t,n){function r(e,t){var n=[],r="",i=0;for(r in e)o.call(e,r)&&(n[i]=t(r,e[r]),i+=1);return n}var o=Object.prototype.hasOwnProperty;t.exports=r},{}],3:[function(e,t,n){function r(e,t,n){t||(t=0),"undefined"==typeof n&&(n=e?e.length:0);for(var r=-1,o=n-t||0,i=Array(o<0?0:o);++r<o;)i[r]=e[t+r];return i}t.exports=r},{}],4:[function(e,t,n){t.exports={exists:"undefined"!=typeof window.performance&&window.performance.timing&&"undefined"!=typeof window.performance.timing.navigationStart}},{}],ee:[function(e,t,n){function r(){}function o(e){function t(e){return e&&e instanceof r?e:e?c(e,u,i):i()}function n(n,r,o,i){if(!d.aborted||i){e&&e(n,r,o);for(var a=t(o),u=m(n),c=u.length,f=0;f<c;f++)u[f].apply(a,r);var p=s[y[n]];return p&&p.push([b,n,r,a]),a}}function l(e,t){v[e]=m(e).concat(t)}function m(e){return v[e]||[]}function w(e){return p[e]=p[e]||o(n)}function g(e,t){f(e,function(e,n){t=t||"feature",y[n]=t,t in s||(s[t]=[])})}var v={},y={},b={on:l,emit:n,get:w,listeners:m,context:t,buffer:g,abort:a,aborted:!1};return b}function i(){return new r}function a(){(s.api||s.feature)&&(d.aborted=!0,s=d.backlog={})}var u="nr@context",c=e("gos"),f=e(2),s={},p={},d=t.exports=o();d.backlog=s},{}],gos:[function(e,t,n){function r(e,t,n){if(o.call(e,t))return e[t];var r=n();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:r,writable:!0,enumerable:!1}),r}catch(i){}return e[t]=r,r}var o=Object.prototype.hasOwnProperty;t.exports=r},{}],handle:[function(e,t,n){function r(e,t,n,r){o.buffer([e],r),o.emit(e,t,n)}var o=e("ee").get("handle");t.exports=r,r.ee=o},{}],id:[function(e,t,n){function r(e){var t=typeof e;return!e||"object"!==t&&"function"!==t?-1:e===window?0:a(e,i,function(){return o++})}var o=1,i="nr@id",a=e("gos");t.exports=r},{}],loader:[function(e,t,n){function r(){if(!x++){var e=h.info=NREUM.info,t=d.getElementsByTagName("script")[0];if(setTimeout(s.abort,3e4),!(e&&e.licenseKey&&e.applicationID&&t))return s.abort();f(y,function(t,n){e[t]||(e[t]=n)}),c("mark",["onload",a()+h.offset],null,"api");var n=d.createElement("script");n.src="https://"+e.agent,t.parentNode.insertBefore(n,t)}}function o(){"complete"===d.readyState&&i()}function i(){c("mark",["domContent",a()+h.offset],null,"api")}function a(){return E.exists&&performance.now?Math.round(performance.now()):(u=Math.max((new Date).getTime(),u))-h.offset}var u=(new Date).getTime(),c=e("handle"),f=e(2),s=e("ee"),p=window,d=p.document,l="addEventListener",m="attachEvent",w=p.XMLHttpRequest,g=w&&w.prototype;NREUM.o={ST:setTimeout,SI:p.setImmediate,CT:clearTimeout,XHR:w,REQ:p.Request,EV:p.Event,PR:p.Promise,MO:p.MutationObserver};var v=""+location,y={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net",agent:"js-agent.newrelic.com/nr-1071.min.js"},b=w&&g&&g[l]&&!/CriOS/.test(navigator.userAgent),h=t.exports={offset:u,now:a,origin:v,features:{},xhrWrappable:b};e(1),d[l]?(d[l]("DOMContentLoaded",i,!1),p[l]("load",r,!1)):(d[m]("onreadystatechange",o),p[m]("onload",r)),c("mark",["firstbyte",u],null,"api");var x=0,E=e(4)},{}]},{},["loader"]);</script><script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","queueTime":0,"licenseKey":"1c6ed9743c","agent":"","transactionName":"M1IHN0NYXEZWAEFRCgoYIxZfWkZcWA0aSBcLXQAARUocQ14GQktfNEUKCVRaRnBaAVBcMw1SEk1WXEY=","applicationID":"2845391","errorBeacon":"bam.nr-data.net","applicationTime":22}</script>
    <script>
    

var Scratch = Scratch || {};
Scratch.INIT_DATA = Scratch.INIT_DATA || {};



Scratch.INIT_DATA.ADMIN = false;
Scratch.INIT_DATA.LOGGED_IN_USER = {
  
  options: {
     
    
  }
};
Scratch.INIT_DATA.comment_posting = true;

Scratch.INIT_DATA.BROWSERS_SUPPORTED = {

  chrome: 35,
  firefox: 31,
  msie: 8,
  safari: 7
};

Scratch.INIT_DATA.TEMPLATE_CUES = {

  unsupported_browser: true,
  welcome: true,
  confirmed_email: false
};
  



Scratch.INIT_DATA.PROJECT = {
  model: {
    id: 49385578,
    title: 'RUN 3 !!!!!!!!',
    creator: 'zjjc'
  }
}




Scratch.INIT_DATA.IS_IP_BANNED = false;

Scratch.INIT_DATA.GLOBAL_URLS = {
  'media_url': '//uploads.scratch.mit.edu/',
  'static_url': '//cdn.scratch.mit.edu/scratchr2/static/__d546685378fddc123394fa4d610b60eb__/',
  'static_path': '/scratchr2/static/__d546685378fddc123394fa4d610b60eb__/'
}

Scratch.INIT_DATA.IS_SOCIAL = false;

Scratch.ALERT_MSGS = {
  'error': 'Oops! Something went wrong',
  'inappropriate-generic': 'Hmm...the bad word detector thinks there is a problem with your text. Please change it and remember to <a target="_blank" href="/community_guidelines/">be respectful</a>.',
  'image-invalid': 'Upload a valid image. The file you uploaded was either not an image or a corrupted image.',
  'thumbnail-missing': 'Missing file',
  'thumbnail-upload-bad': 'Bad upload',
  'thumbnail-too-large': 'Maximum file size is 1 MB.',

  'inappropriate-comment': 'Hmm...the bad word detector thinks there is a problem with your comment. Please change it and remember to <a target="_blank" href="/community_guidelines/">be respectful</a>.',
  'comment-has-chat-site': 'Uh oh! This comment contains a link to a website with unmoderated chat. For safety reasons, please do not link to these sites!',

  'empty-comment': "You can't post an empty comment!",
  'delete_comment': '<div title="Delete Comment?"><p>Are you sure you want to delete this comment? If the comment is mean or disrespectful, please click report instead, to let the Scratch Team know about it.</p></div>',
  'report_comment': '<div title="Report Comment?"></p>Are you sure you want to report this comment?</p></div>',
  'report_comment_educator': '<div title="Delete Comment?"></p>Are you sure you want to delete this comment?</p></div>',
  'followed': 'You are now following ',
  'unfollowed': 'You are no longer following ',
  'comment-spam': "Hmm, seems like you've posted the same comment a bunch of times. Please don't spam.",
  'comment-flood': "Woah, seems like you're commenting really quickly. Please wait longer between posts.",
  'comment-muted': "Hmm, the filterbot is pretty sure your recent comments weren't ok for Scratch, so your account has been muted for the rest of the day. :/",
  'comment-unconstructive': "Hmm, the filterbot thinks your comment may be mean or disrespectful. Remember, most projects on Scratch are made by people who are just learning how to program. Read the <a href='/community_guidelines'>community guidelines</a>, and be nice.",
  'comment-disallowed': "Hmm, it looks like comments have been turned off for this page. :/",
  'project-complaint-length': "That's too short. Please describe in detail what's inappropriate or disrespectful about the project.",
  'project-complaint-buglength': "That's too short! Please describe in detail what you expected the project to do, and how exactly it is broken. Thanks!",
  'editable-text-too-long': "That's too long! Please find a way to shorten your text."

}


    </script>
    <script type="text/javascript" src="//cdn.scratch.mit.edu/scratchr2/static/__d546685378fddc123394fa4d610b60eb__/js/jquery.min.js"></script>
    <script type="text/javascript" src="//cdn.scratch.mit.edu/scratchr2/static/__d546685378fddc123394fa4d610b60eb__/js/swfobject.js"></script>
  </head>
  <body style="overflow:hidden; margin:0px;">
  <script type="text/javascript">
      $(function() {
          // The flashvars tell flash about the project data (and autostart=true)
          var flashvars = {
              autostart: "false",
              server: encodeURIComponent(location.host),
              cdnToken: "d546685378fddc123394fa4d610b60eb",
              urlOverrides: {
                  sitePrefix: "http://scratch.mit.edu/",
                  siteCdnPrefix: "http://cdn.scratch.mit.edu/",
                  assetPrefix: "http://assets.scratch.mit.edu/",
                  assetCdnPrefix: "http://cdn.assets.scratch.mit.edu/",
                  projectPrefix: "http://projects.scratch.mit.edu/",
                  projectCdnPrefix: "http://cdn.projects.scratch.mit.edu/",
                  internalAPI: "internalapi/",
                  siteAPI: "site-api/",
                  staticFiles: "scratchr2/static/"
              }
          };
          $.each(Scratch.INIT_DATA.PROJECT.model, function(i, val) { flashvars['project_'+i] = encodeURIComponent(val); });

          var params = {
              allowscriptaccess: 'always',
              allowfullscreen: 'false',
              wmode: 'direct',
              menu: 'false'};

          swfobject.embedSWF("//cdn.scratch.mit.edu/scratchr2/static/__d546685378fddc123394fa4d610b60eb__/Scratch.swf", "scratch", "100%", "100%", "10.2.0", "//cdn.scratch.mit.edu/scratchr2/static/__d546685378fddc123394fa4d610b60eb__/expressInstall.swf", flashvars, params);
          $('#scratch').css('visibility', 'visible');
      });
  </script>

  <div id="scratch" style="text-align:center;margin:10px;visibility:hidden;">
      <img src="//uploads.scratch.mit.edu/projects/thumbnails/4938/5578.png" style="height:169px;"/>
      <p style="color:#aaa;font-size:22px;margin-top:14px;line-height:28px;">
        Oh no! We're having trouble displaying this Scratch project.<br/>
        If you are on a mobile phone or tablet, try visiting this project on a computer.<br/>
        If you're on a computer, your Flash player might be disabled, missing, or out of date. Visit <a href="https://get.adobe.com/flashplayer/">this page</a> to update Flash.<br/>
      </p>
      <a href="http://www.adobe.com/go/getflashplayer">
          <img src="//www.adobe.com/images/shared/download_buttons/get_flash_player.gif" alt="Get Adobe Flash player" target="_blank" />
      </a>
  </div>
  </body>
</html>
