imgareaselect
=============

ImgAreaSelect is a jQuery plugin for selecting a rectangular area of an image. It allows web developers to easily implement image cropping functionality, as well as other user interface features, such as photo notes (like those on Flickr).

Basic Usage:
     ```<script type="text/javascript" >
               $(document).ready(function() {
               $('img#photo').imgAreaSelect({
                    handles: true;
                    onSelectEnd: alert("Selecionado!");
                   });
          });
      </script>
      ```
