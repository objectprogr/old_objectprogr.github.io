---
layout: countdown
title: Challenge
permalink: /challenge/
---
<div id="getting-started"></div>
<script type="text/javascript">
  $('#getting-started').countdown('2015/01/01', function(event) {
    $(this).html(event.strftime('%w weeks %d days %H:%M:%S'));
  });
</script>