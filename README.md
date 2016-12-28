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


$(document).ready(function(){
    
    $('body').append("<p>I`m a paragraph! </p>");
    });


$(document).ready(function(){
    
    $('#one').after('<p>Paragraful meu </p>');
    
    });
    
    
    
$(document).ready(function(){
    
    $('#one').after('<p>Paragraful meu </p>');
    
    var $div= $("p");
    $("#two").after($("p"));
    
    });
    
    
    
    (document).ready(function(){
    
    $('#one').after('<p>Paragraful meu </p>');
    
    var $div= $("p");
    $("#two").after($("p"));
    $("p").remove();
    });
    
    
    $(document).ready(function(){
    
    $("#text").click(function(){
        
        $(this).addClass('highlighted');
        
        });
    
    
    });
    
    
    $(document).ready(function(){
    
    $("#text").click(function(){
        
        $(this).toggleClass('highlighted');
        
        });
    
    
    });
    
    
    $(document).ready(function(){
    
    $("div").height("200px");
    $("div").width("200px");
    $("div").css("border-radius","10px");
    
    
    });
    
    
    $(document).ready(function(){

$("p").html("jQuery magic in action!");

});


$(document).ready(function(){
    
    $("#button").click(function(){
        
        var toAdd = $('input[name=toAdd]').val());
        
        });
    
    });
    
    
    $(document).ready(function(){
    
    $("#button").click(function(){
        
        var toAdd = $('input[name=toAdd]').val());
        $(".list").append("<div class="item">" + toAdd + "</div>");
            
            
           
        
        
        });
    
    });
    
    
    $(document).ready(function(){
    
    $("#button").click(function(){
        
        var toAdd = $('input[name=toAdd]').val();
        $(".list").append("<div class="item">" + toAdd + "</div>");
            
            
           
        
        
        });
    
    $(document).on('click', '.item', function(){
        
        $(this).remove();
        
        });
    });
    
    
    $(document).ready(function() {
    $('button').click(function() {
    	var toAdd = $("input[name=message]").val();
        $('#messages').append("<p>"+toAdd+"</p>");
    });
});


$(document).ready(function(){
    
    $('div').fadeOut('fast');
    });
    
    
    $(document).ready(function(){
    
    $('div').click(function() {
        
        $('div').fadeOut('fast');
        
        });
    
    });
    
    $(document).ready(function(){
    
    $('div').click(function() {
                
        $('div').fadeOut('fast');
        
        });
        
        $('div').hover(function(){
            
            $('div').addClass('red');
            
            });
        
    
    });
    
    
    $(document).ready(function(){
    
    $('div').dblclick(function(){
        
        $(this).fadeOut('fast');
        
        
        });
    
    
    });
    
    
    $(document).ready(function(){

  $('div' ).hover(
    function(){
        
    $(this).addClass('active');    
    
    },
    function(){
        
    $(this).removeClass('active');   
    }
  );

});


$(document).ready(function(){
    
    
    $('input').focus(function(){
        
        $(this).css('outline-style', 'solid');
        
        
        });
    
    });
    
    
    $(document).ready(function(){
    
    $(document).keydown(function(){
        
        $('div').animate({left:'+=10px'},500 );
        
        });    
    
    });
    
    
    
    $(document).ready(function(){
    
    $(document).keydown(function(){
        
        $('div').animate({left:'+=10px'},500 );
        
        });    
    
    });
    
    
    
    $(document).ready(function() {
    $(document).keydown(function(key) {
        switch(parseInt(key.which,10)) {
			// Left arrow key pressed
			case 37:
				$('img').animate({left: "-=10px"}, 'fast');
				break;
			// Up Arrow Pressed
			case 38:
				// Put our code here
				$('img').animate({top: "-=10px"},'fast');
				break;
			// Right Arrow Pressed
			    
			case 39:
				// Put our code here
				$('img').animate({left:"+=10px"},'fast');
				break;
			// Down Arrow Pressed
			case 40:
				// Put our code here
				$('img').animate({top: "+=10px"},'fast');
				break;
		}
	});
});


$(document).ready(function(){

    // Fill in the blanks!
    $('img' ).animate({ top:'+=100px'}, 1000);
});


$(document).ready(function(){
    
    $('div').click(function(){
        
        $(this).effect('explode');
        });
    });
    
    
    $(document).ready(function(){
    
    $('div').click(function(){
        
        $(this).effect('bounce',{times:3},500);
        });
    });
    
    
    $(document).ready(function(){
    
    $('div').click(function(){
        
        $(this).effect('slide');
        });
    });
    
    
    $(document).ready(function() {
    $("#menu").accordion({collapsible: true, active: false});
});


$(document).ready(function(){
    
    $('#car').draggable();
    });
    
    
    $(document).ready(function(){
    
    $('div').resizable();
    
    });
    
    
    $(document).ready(function(){
    
    $('ol').selectable();
    
    });
    
    
    $(document).ready(function(){
    
    $('ol').sortable();
    
    });
    
    
    
