$(document).ready(function() {
   $('div').mouseenter(function() {
       $(this).animate({
           height: '+=10px'
       });
   });
   $('div').mouseleave(function() {
       $(this).animate({
           height: '-=10px'
       }); 
   });
   $('div').click(function() {
       $(this).toggle(1000);
   }); 
});



$(document).ready(function() {
    $('div' ).fadeOut(1000);
});

$(document).ready(function() {
    $('#green').fadeOut(1000);
});


$(document).ready(function(){
    $('div').slideDown('slow');
    
    });


$(document).ready(function(){
    
    $('div').mouseenter(function(){
        
        $('div').fadeTo('fast',1);
        
        });
    
    
    });
