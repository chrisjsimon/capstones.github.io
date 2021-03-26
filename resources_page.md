<script src="<files/focus.min.js"></script>
<link rel="stylesheet" type="text/css" href="files/popup.css">

<div data-trigger="accordion" data-target="#accordionExampleClosed">
  <span>
    Focus accordion example
    <span class="more">+</span>
    <span class="less">-</span>
  </span>
</div>
<div id="accordionExampleClosed" class="accordion-content" style="display:none;">
  <div class="accordion-inner">
    <p>
      This accordion is close to start with
    </p>
    <p>  
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
    </p>
  </div>
</div>

<script>
  var accordionExampleClosed = new Focus('#accordionExampleClosed', {
    triggerClass: 'open',
    slide: true
  });
</script>
