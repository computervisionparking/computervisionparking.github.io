
<html>



var tabletop = Tabletop.init({ 
  key: '1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE', 
  callback: showInfo 
})



<script src='https://cdnjs.cloudflare.com/ajax/libs/tabletop.js/1.5.1/tabletop.min.js'></script>
<script type='text/javascript'>    
  var publicSpreadsheetUrl = 'https://docs.google.com/spreadsheets/d/1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE/pubhtml';

https://docs.google.com/spreadsheets/d/1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE/edit?usp=sharing

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




</html>

 
 
 
