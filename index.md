<!DOCTYPE html>
<html lang="en">
<head>

  <!-- Basic Page Needs
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta charset="utf-8">
  <title>Taffy - The chat-first way to meet new people.</title>
  <meta name="description" content="Taffy is the best way to meet new people.">

  <!-- Mobile Specific Metas
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <!-- FONT
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700" rel="stylesheet">

  <!-- CSS
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="stylesheet" href="/css/normalize.css">
  <link rel="stylesheet" href="/css/skeleton.css">
  <link rel="stylesheet" href="/css/site.css">

  <!-- Favicon
  –––––––––––––––––––––––––––––––––––––––––––––––––– -->
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  <link rel="manifest" href="/manifest.json">
  <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#f12b4c">
  <meta name="theme-color" content="#f12b4c">
  <meta name="apple-mobile-web-app-title" content="Taffy">
  <meta name="application-name" content="Taffy">

  <script type="text/javascript">
  (function(b, r, a, n, c, h, _, s, d, k) {
  if (!b[n] || !b[n]._q) {
    for (; s < _.length; ) c(h, _[s++]);
    d = r.createElement(a);
    d.async = 1;
    d.src = 'https://cdn.branch.io/branch-latest.min.js';
    k = r.getElementsByTagName(a)[0];
    k.parentNode.insertBefore(d, k);
    b[n] = h;
  }
})(
  window,
  document,
  'script',
  'branch',
  function(b, r) {
    b[r] = function() {
      b._q.push([r, arguments]);
    };
  },
  { _q: [], _v: 1 },
  'addListener applyCode banner closeBanner creditHistory credits data deepview deepviewCta first getCode init link logout redeem referrals removeListener sendSMS setBranchViewData setIdentity track validateCode'.split(
    ' ',
  ),
  0,
);
branch.init('key_live_ahxsTwxkm2xjr68WmfFHypngzvmBCxk3');
function sendSMS(form) {
  var phone = form.phone.value;
  var linkData = {
    tags: [],
    channel: 'Website',
    feature: 'TextMeTheApp',
  };
  var options = {};
  var callback = function(err, result) {
    if (err) {
      alert('Sorry, something went wrong - try again? 😢');
    } else {
      alert('Text message sent! Check your phone 😀');
      form.phone.value = '';
    }
  };
  branch.sendSMS(phone, linkData, options, callback);
}
</script>
</head>
<body class="homepage">
  <header>
    <div class="container">
      <div class="row">
        <div class="seven columns">
          <div class="logo">
            <img src="/images/mark.svg" class="mark" width=118 alt="Taffy Brand Mark">
            <img src="/images/logo.svg" width=227 alt="Taffy">
          </div>
          <h1>The <em>chat-first</em> way to meet <em>new people</em>.</h1>
          <form onsubmit="sendSMS(this); return false;">
            <div class="form-wrapper">
              <input id="phone" name="phone" class="phone" type="tel" placeholder="555-123-4567">
              <button type="submit" name="submit"><img src="http://res.cloudinary.com/taboo/image/upload/v1500054183/brand-mark_g0arvd.png" width=32> Text me the app</button>
            </div>
          </form>
          <a href="https://taffy.app.link/8a6MnQxlRD" class="mobile-button"><img src="http://res.cloudinary.com/taboo/image/upload/v1500054183/brand-mark_g0arvd.png" width=32> Get the App</a>
        </div>
        <div class="five columns align-right">
          <img src="/images/header-screenshot.png" width=300 alt="Looking for a guy with a sense of adventure." class="screenshot">
        </div>
      </div>
    </div>
  </header>
  <main>
    <div class="container">
      <div class="row">
        <div class="seven columns">
          <h2>meet new people.</h2>
          <p>Taffy is the social discovery app that sparks conversation through mystery and curiosity. It’s the chat-first way to meet people.</p>
        </div>
        <div class="five columns align-right">
          <img src="/images/posts-screenshot.jpg" width=300 alt="Taffy Posts" class="screenshot">
        </div>
      </div>

      <div class="row">
        <div class="five columns">
          <img src="/images/chat-screenshot.jpg" width=300 alt="Taffy Chat" class="screenshot">
        </div>
        <div class="seven columns">
          <h2>unblur your profile pics.</h2>
          <p>…by putting conversation first. Photos are blurry until you start chatting.</p>
          <p class="emoji"><img src="/images/emoji/speech-balloon.png" width=40 height=40> <img src="/images/emoji/right-pointing-backhand.png" width=40 height=40> <img src="/images/emoji/camera.png" width=40 height=40></p>
        </div>
      </div>
    </div>
  </main>
  <section>
    <div class="container">
      <h3>meet. chat. reveal.</h3>
      <form onsubmit="sendSMS(this); return false;">
        <div class="form-wrapper">
          <input id="phone" name="phone" class="phone" type="tel" placeholder="555-123-4567">
          <button type="submit" name="submit"><img src="http://res.cloudinary.com/taboo/image/upload/v1500054183/brand-mark_g0arvd.png" width=32> Text me the app</button>
        </div>
      </form>
      <a href="https://taffy.app.link/8a6MnQxlRD" class="mobile-button"><img src="http://res.cloudinary.com/taboo/image/upload/v1500054183/brand-mark_g0arvd.png" width=32> Get the App</a>
    </div>
  </section>
  <footer>
    <div class="container">
      <div class="row">
        <div class="eight columns">
          <img src="/images/mark-red.svg" width=50 alt="Taffy Brand Mark" class="mark">
          <ul>
            <li><a href="/privacy-policy.html">Privacy</a></li>
            <li><a href="/terms-of-use.html">Terms</a></li>
            <li><a href="https://angel.co/taffy-media/jobs">Jobs</a></li>
            <li><a href="mailto:hello@taffy.chat">Contact</a></li>
            <li><a href="https://medium.com/chewtaffy">Blog</a></li>
          </ul>
        </div>
        <div class="four columns align-right">
          <ul>
            <li><a href="https://twitter.com/chewtaffy"><img src="/images/twitter.svg" /></a></li>
            <li><a href="https://instagram.com/chewtaffy"><img src="/images/instagram.svg" /></a></li>
            <li><a href="https://facebook.com/chewtaffy"><img src="/images/facebook.svg" /></a></li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</body>
</html>
© 2019 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
