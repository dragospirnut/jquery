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
    
    
    var main = function() {
  
  $('#top-text').keyup(function(){
    
   $('.top-caption').text($('#top-text').val());
    
     });
    
    $('#bottom-text').keyup(function(){
      
      $('.bottom-caption').text($('#bottom-text').val());
      
    });
 
 $('#image-url').keyup(function(){
   
  var toAdd = $('#image-url').val();
   $('img').attr('src',toAdd);
   
 });
  
  
};
 
$(document).ready(main);

var main = function() {
  $('form').submit(function() {
    var firstName = $('#first').val();
    
    if(firstName === "") {
      
     $('.first-name-error').text("Please enter your first name");
    }

    return false;
    
  });
  
  
  $('form').submit(function(){
    
    var lastName = $('#last').val();    
    
    if (lastName === "") {
        
        $('.last-name-error').text("Please enter your last name");
        
        }
    
  });
  
  $('form').submit(function(){
    
    var email = $('#email').val();
    
    if (email === "" ) {
      
      
      $('.email-error').text("Please enter your e-mail address");
    } else if(email ==="dragospirnut@yahoo.com" ) {
              
       $('.email-error').text("This e-mail is already taken");       
              
              }
    
    
  });
  
  
  $('form').submit(function(){
    
    var password = $('#password').val();
    
    if (password === "") {
      
      $('.password-error').text("Please enter your password");
      
    } else if(password.length <8) {
              
              
       $('.password-error').text("Short passwords are easy to guess. Try one with at least 8 characters");       
              }
    
  });
  
};

$(document).ready(main);

var main = function() {
  $('form').submit(function() {
    
    var comment = $('#comment').val();
    
    
    if(comment !== "") {
      var html = $('<li>').text(comment);
     html.prependTo('.comments');
      $('#comment').val("");
      
          }

    return false;
  });
};

$(document).ready(main);

var main = function() {
  $('.day').click(function(){
    
    $(this).next('div').toggle();
    $(this).find('span').toggleClass('glyphicon-minus');
  });
  
 
  
};

$(document).ready(main);



var main = function() {
  $('.nav li').click(function() {
    var category = $(this).attr('class');

    
    $('.nav li').removeClass('active');
    $(this).addClass('active');

    if('nav-consumer' === category) {
      
      $('.thumbnail').removeClass('selected');
     $('.consumer').addClass('selected');
      
    }else if (category === 'nav-mobile') {
              
              $('.thumbnail').removeClass('selected');
      				$('.mobile').addClass('selected');
              
              } else if (category === "nav-commerce") {
                
                $('.thumbnail').removeClass('selected');
                $('.commerce').addClass('selected');
                
                
              } else if (category === "nav-enterprise") {
                
                $('.thumbnail').removeClass('selected');
                $('.enterprise').addClass('selected');
                
              } else if (category === "nav-all") {
                
                $('.thumbnail').removeClass('selected');
                
              }
    
    
  });
};
 
$(document).ready(main);

var template = function(text) {
  return '<p><input type="checkbox"><i class="glyphicon glyphicon-star"></i><span>' + text + '</span><i class="glyphicon glyphicon-remove"></i></p>';
};

var add = function(item) {
  var html = template(item);
  $('.list').append(html);  
};

var main = function() {
  $('form').submit(function() {
      
    var text = $('#todo').val();
    var html = template(text);
        $('.list').append(html);
    		$('#todo').val("");
    
    return false;  
  });
  
   $(document).on("click",".glyphicon-star", function() {
    $(this).toggleClass('active');
  });
  
  $(document).on('click','.glyphicon-remove', function(){
    $(this).parent().remove();
  });
  
  if (annyang) { 
          var commands = {
        'add *item' : add,
      };
          annyang.addCommands(commands);
          annyang.start();
   };
  
};

$(document).ready(main);

var main = function() {
 
  $('img').click(function(){
    
    $('.dropdown-menu').toggle(250);
    
  });
};
 
$(document).ready(main);


var main = function() {
  
$('.notification').click(function(){
  
  $('.notification-menu').toggle();
  
});  
  
  $('.post .btn').click(function(){
    
    $(this).toggleClass('.btn');
        
  });
  
};

$(document).ready(main);


var main = function() {

  $('.more-btn').click(function(){
    
    $(this).next().toggle('.more-menu');
    
  });
  
  $('.share').click(function(){
    
    $(this).next().toggle();
  });
  
  $('.notification').click(function(){
    
    $(this).toggleClass('active');
    
  });
  
};

$(document).ready(main);

var main = function() {
  
  var cities = [
    
    "Romania",
    "Ukraine",
    "Great Britain",
    "New Zeeland"
    ];
    $('#inputcity').autocomplete({
    
    source: cities
    });
    
  
};
 
$(document).ready(main);




var template = function(text) {
  return '<p><input type="checkbox"><i class="glyphicon glyphicon-star"></i><span>' + text + '</span><i class="glyphicon glyphicon-remove"></i></p>';
};

var add = function(item) {
  var html = template(item);
  $('.list').append(html);  
};

var main = function() {
  $('form').submit(function() {
      
    var text = $('#todo').val();
    var html = template(text);
        $('.list').append(html);
    		$('#todo').val("");
    
    return false;  
  });
  
   $(document).on("click",".glyphicon-star", function() {
    $(this).toggleClass('active');
  });
  
  $(document).on('click','.glyphicon-remove', function(){
    $(this).parent().remove();
  });
  
  if (annyang) { 
          var commands = {
        'add *item' : add,
      };
          annyang.addCommands(commands);
          annyang.start();
   };
  
};

$(document).ready(main);



var main = function(){  
  $('img').click(function() {    
    $('.dropdown-menu').toggle();
  });
  
  $('form').submit(function(){
    var email = $('#email').val();
    var password = $('#password').val();     
    if(email === "" ) {    
      $('.email-error').text("Please enter your email");     
     }    
    if (password === "") {      
      $('.password-error').text("Please enter your password");     
    }
    return false;  
  });
};
$(document).ready(main);


var main = function(){
  
 
  $('.dropdown').click(function () {
    $(this).find('.dropdown-menu').toggle();
  });
};


$(document).ready(main);

var main = function (){
  
  $('.login').click(function(){
    
    $(this).find('.dropdown-menu').toggleClass();
    
  });
  
  $('#accordion').accordion();
  
}; 

$(document).ready(main);


//Lite Brite last project

function main(){
  
  var colorClass = '';
  
  $('.select-color').on('click', function(){
    
			 
    	var selectedColor = $(this).attr('class');
    
    switch(selectedColor) {
        
        
      case 'select-color cyan not-selected':
       
        colorClass = 'cyan';
        
        break;
       
       case'select-color yellow not-selected':
        
        colorClass = 'yellow';
         
        break;
        
        case'select-color magenta not-selected':
        
        colorClass = 'magenta';
        
        break;
     }
    
    	$(this).removeClass('not-selected');
    	
    	$(this).siblings().addClass('not-selected');
  });
  
 $('.box').on('click', function(){
   
   $(this).toggleClass(colorClass);
   
 });
  
  $('.toggle-blink').click(function(){
    
    if(colorClass) {
       
       $('.toggle-blink').toggleClass('opacity');
              
       } 
    
    setInterval(function() {
      $('.box.cyan, .box.yellow, .box.magenta').toggleClass('blink');
      
    }, 350);
    
  });
  
};

$(document).ready(main);
