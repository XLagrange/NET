{% if site.duoshuo %}
	{% if page.thread %}
	<ul class="ds-recent-comments" data-num-items="10" data-show-avatars="1" data-show-time="1" data-show-admin="1" data-excerpt-length="70"></ul>
	<script type="text/javascript">
	var duoshuoQuery = {short_name:"{{ site.duoshuo }}"};
	(function() {
	    var ds = document.createElement('script');
	    ds.type = 'text/javascript';ds.async = true;
	    ds.src = 'http://static.duoshuo.com/embed.js';
	    ds.charset = 'UTF-8';
	    (document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(ds);
	})();
	</script>
{% endif %}