<template>
<div class="container">
    <div class="line-it-button" data-lang="ja" data-type="share-a" data-ver="3" data-url="https://ganbare-chiba.com" data-color="default" data-size="large" data-count="false" style="display: none;"></div>
    <script src="https://d.line-scdn.net/r/web/social-plugin/js/thirdparty/loader.min.js" async="async" defer="defer"></script>

    <a href="https://twitter.com/intent/tweet?button&ref_src=twsrc%5Etfw" class="twitter-hashtag-button" data-size="large" data-text="《千葉 台風15号被害》みんなができるアクションまとめ #みんなができるアクションまとめ #頑張ろう千葉 #がんばろう千葉 #台風 #千葉県停電" data-url="https://ganbare-chiba.com" data-show-count="false">Tweet #がんばろう千葉</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

    <div id="fb-root"></div><script async defer crossorigin="anonymous" src="https://connect.facebook.net/ja_JP/sdk.js#xfbml=1&version=v4.0&appId=477350585721496&autoLogAppEvents=1"></script>
    <div class="fb-share-button" data-href="https://ganbare-chiba.com" data-layout="button" data-size="large"><a target="_blank" href="https://www.facebook.com/sharer/sharer.php?u=https%3A%2F%2Fganbare-chiba.com%2F&amp;src=sdkpreparse" class="fb-xfbml-parse-ignore">シェア</a></div>
</div>
</template>

<script>
export default {
  components: {
  }
}
</script>

<style>
.container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: left;
  align-items: center;
  background: white;
}
.twitter-hashtag-button,
.fb-share-button {
    margin-left: 10px;
}
</style>
