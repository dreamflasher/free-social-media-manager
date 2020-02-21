---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# layout: main
---
Free (open) and privacy-aware social media manager (posting/sharing on Twitter, LinkedIn, Facebook without giving access to your accounts). Also no tracking of what you post, where and when. 

<textarea id="post_message" rows="6" cols="85">This is an example post</textarea>
<input id="post_url" type="text" size="85" value="https://dreamflasher.github.io/free-social-media-manager/" />

<script>
share_facebook = function(){
    url = 'https://www.facebook.com/sharer/sharer.php?display=popup&u=' + document.getElementById('post_url').value + '&quote=' + document.getElementById('post_message').value;
    options = 'toolbar=0,status=0,resizable=1,width=626,height=436';
    window.open(url,'sharer',options);
}
</script>

<button onclick="share_facebook()">Share on Facebook</button>