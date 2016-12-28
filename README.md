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


$(document).ready(function(){
    
    $('div').mouseenter(function(){
        
        $('div').fadeTo('fast',1);
        
        });
     $('div').mouseleave(function(){
         
         $('div').fadeTo('fast',0.5);
         
         
         }); 
    
    });


$(document).ready(function() {
    
    
    $('div').hide();
    
    
    });

$(document).ready(function() {
    $('div').click(function() {
        $('div').fadeOut('slow');
    });
});

// Write your jQuery code on line 3!
$(document).ready(function() {
var $target=$('#numar4');
    
    $target.fadeOut('fast');
});


$(document).ready(function() {
    
    $('div').fadeIn('slow');
    
    
    });

$(document).ready(function() {
    $('button').click(function() {
       $('.vanish').fadeOut('slow'); 
    });
});

$(document).ready(function() {
    $('button').click(function() {
        $('#blue').fadeOut('slow');
    });
});


$(document).ready(function() {
    $('.pink,.red').fadeTo('slow',0);
    
    
    });
    
    $(document).ready(function() {
    $('div').click(function() {
        $(this).fadeOut('slow');
    });
});



$(document).ready(function(){
    
    $('.pull-me').click(function(){
        
        $('.panel').slideToggle('slow');
        });
    
    });
    
    
    
    
var $h1=$("<h1>Hello </h1>");
