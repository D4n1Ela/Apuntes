    
 
 
 
    $(document).ready(function(){
    $("#btnAdd").on("click", function(){
      var liText = $("#inpHomework").val();
      var myLi ='<li>. '+liText+'<button class="btnDelete" type="button">x</button></li>';
      $("#myUl").append(myLi);
      $("#inpHomework").val("");

      if ($("#checkUrgent").is(":checked")) {
          $("li").last().addClass("myRed");
        }

    $("#checkUrgent").prop('checked',false);	
		
    
*//OPCIÓN 1: Botón de borrado incluído dentro de la función que crea el elemento "li" al hacer click en el id "btnAdd"*

    /*
    $(".btnDelete").on("click", function(){
      $(this).parent().remove();
    })
    */


*//DENTRO DE LA FUNCIÓN: Esta función subraya y deshace el subrayado sobre el elemento "li".*

    /*     
    $("li").on("click", function(){
      $(this).toggleClass("underline");    		
    })
    */
    
    })

*//OPCIÓN 2: Botón de borrado fuera de la función, creamos la función "deleteParent" que borra al elemento padre y luego cargamos el documento al*
  *hacer click en el botón de id "btnDelete" en el cual se llama a la función creada anteriormente(deleteParent).*
  
    function deleteParent(){
      $(this).parent().remove();
    }
    $(document).on("click", ".btnDelete", deleteParent);


*//FUERA DE LA FUNCIÓN: Esta función subraya y deshace el subrayado sobre el elemento "li"*

    function underline(){
      $(this).toggleClass("underline");
    }
    $(document).on("click", "li", underline);
    })
