
<html>




<!-- Text between angle brackets is an HTML tag and is not displayed.
Most tags, such as the HTML and /HTML tags that surround the contents of
a page, come in pairs; some tags, like HR, for a horizontal rule, stand 
alone. Comments, such as the text you're reading, are not displayed when
the Web page is shown. The information between the HEAD and /HEAD tags is 
not displayed. The information between the BODY and /BODY tags is displayed.-->

<head>
<title>Enter a title, displayed at the top of the window.</title>
</head>
<!-- The information between the BODY and /BODY tags is displayed.-->
<body>
<h1>Computer Vision Parking.</h1>
  
<p>made by:
<p>Elliot Tomasello	Ganesh Thaker
<p>Allan Phung	Luke Ramoutar
<p>Saulo Olvera	Dhruve Patel

<p>Testing <b>bold</b> command. Put them in a list: </p>
<ul>
<li>The first item in your list</li>
<li>Testing <i>italicize</i> key words</li>
</ul>
<p>Test image. </p>
<p><img src="http://www.animatedimages.org/data/media/56/animated-computer-image-0004.gif" alt="A Great HTML Resource"></p>
<p>Link <a href="https://www.msn.com/">This is a Web site</a>.
<!-- Break up your page with a horizontal rule or two. </p>
<hr>
<p>Finally, link to <a href="page2.html">another page</a> in your own Web site.</p>
<!-- And add a copyright notice.-->
<!-- <p>&#169; Wiley Publishing, 2011</p>
</body>
</html>

<script src='https://cdnjs.cloudflare.com/ajax/libs/tabletop.js/1.5.1/tabletop.min.js'></script>
<script type='text/javascript'>    
  var publicSpreadsheetUrl = 'https://docs.google.com/spreadsheets/d/1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE/pubhtml';

  function init() {
    Tabletop.init( { key: publicSpreadsheetUrl,
                     callback: showInfo,
                     simpleSheet: true } )
  }

  function showInfo(data, tabletop) {
    alert('Successfully processed!')
    console.log(data);
  }

  window.addEventListener('DOMContentLoaded', init)
</script>

<!-- And add a copyright notice.-->

function init() {
 Tabletop.init( { key: ‘https://docs.google.com/spreadsheets/d/1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE/',
 callback: function(data, tabletop) { xSFE
 console.log(data)
 },
 simpleSheet: true } )
}
window.addEventListener(‘DOMContentLoaded’, init)


