# jQuery-

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

### when we click on dropdown and show in textbox
```php
<input type="text" name=""  id="ascdesc">

<select name="sorting" id="sorting">
  <option value="volvo">Asc</option>
  <option value="saab">Desc</option>
</select>


   <script type="text/javascript">
     $(function(){
      $("#sorting").change(function(){
        var sorts = $("#sorting option:selected").text();
        $("#ascdesc").val(sorts);
        //alert("Selected Option Text: "+sorts);
      })
     })
   </script>
```
