<!DOCTYPE html>
<html>
  <body>

    <p id="food"></p>

    <script type="text/javascript" src="../../src/tabletop.js"></script>
    <script type="text/javascript">
      var public_spreadsheet_url = 'https://docs.google.com/spreadsheets/d/1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE/edit?usp=sharing';
      function init() {
        Tabletop.init( { key: 1kXDKj9emWwKn5DzXgH83uEOFzxsS06k-we05TGma1cE,
                         callback: showInfo,
                         simpleSheet: true } );
      }
      window.addEventListener('DOMContentLoaded', init)
      function showInfo(data) {
        // data comes through as a simple array since simpleSheet is turned on
        alert("Successfully processed " + data.length + " rows!")
        document.getElementById("food").innerHTML = "<strong>Foods:</strong> " + [ data[0].Name, data[1].Name, data[2].Name ].join(", ");
        console.log(data);
      }
      document.write("The published spreadsheet is located at <a target='_new' href='" + public_spreadsheet_url + "'>" + public_spreadsheet_url + "</a>");        
    </script>
  </body>
</html>



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

 
 
 
