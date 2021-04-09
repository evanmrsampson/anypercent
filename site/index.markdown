---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: homepage
---
<div id="youtube-wrapper">
    <iframe id="youtube" width="1280" height="720" src="https://www.youtube.com/embed/+latest?listType=playlist&list=PL5Jv0Ues3VCik4UaY3hY6JPTdPZHlMOZi" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<script>
  $(document).ready(function(){
    $("#youtube-wrapper").fitVids();
  });
</script>
<div id="links">
    <a href="https://open.spotify.com/show/5qQmwBns0lthPQalQrOxcL">
        <div class="link-wrapper">
            <h2>Spotify</h2>
        </div>
    </a>
    <a href="https://anchor.fm/any-percent">
        <div class="link-wrapper">
            <h2>Anchor</h2>
        </div>
    </a>
    <a href="https://twitter.com/anypercentcast">
        <div class="link-wrapper">
            <h2>Twitter</h2>
        </div>
    </a>
    <a href="https://www.youtube.com/channel/UCS5H_1HSuWhXA7Rt100Rxjw">
        <div class="link-wrapper">
            <h2>Youtube</h2>
        </div>
    </a> 
    <a href="https://www.twitch.tv/anypercentcast">
        <div class="link-wrapper">
            <h2>Twitch</h2>
        </div>
    </a>
</div>