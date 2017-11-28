### *Functions* ###

*Repaso:

&nbsp;

    .addClass()
    .removeClass()
    .toggleClass()

    .show()
    .hide()

    $('#enviar'). on('click', function(){
      //function lo dejo anonimo si es una función simple.
      o podría definir una función y llmarlo en todos los callback en los que lo necesito
    }

    document.getElementById('enviar').
    addEventListener(EVENT, CALLBACK)

    var x = $('#enviar')
          ¨¨¨¨¨¨¨¨¨¨¨¨
          Nodo HTML    

          CAllback respuesta a un evento. Respuesta a una interaccin externa.
_________________________________________________
    function animacion{
      $('#caja').animate();
    }

    //* $('#boton').on('click', function(){
    //* $('#caja').animate();
    //* }

    O PODRÍA SER EN LUGAR DE *
    $('#boton').on('click',animacion)
_____________________________________

    $(this).addClass('clicked'); o podría ser
            ¨¨¨¨¨¨¨¨¨¨¨¨¨¨¨¨¨¨
            prop("display": none;)

            class("Nombre propiedad": "valor");

            ____________________

            removeClass y luego addClass 
            o utilizo toggle que switchea

_____________________________________

    $(document).ready(function(){
      $("#btnMyEdit").on("click", function(){
        alert...El mensaje
      })
    });

_____________________________________

    $(document).ready(function(){
      $("#btnMyEdit").on("click", function(){
        alert...El mensaje
      })
    });

______________________________-
    $('button').attr("id"); Varsión vieja que funciona
    $('button').prop("id"); Versión actual
