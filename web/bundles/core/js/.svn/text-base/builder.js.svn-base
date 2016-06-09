//system box drag and drop (move)

$( ".systemBox" ).draggable({start: function() {$('.dragFix').show()}, stop: function() {$('.dragFix').hide()}});

//tools -- dot to form a ploy shape
$('#mainSubject').click(function(e){
	 var posX = $(this).offset().left, posY = $(this).offset().top;
	 var relX= e.pageX - posX, relY=e.pageY - posY;
	 $(this).append('<div class="polyDot" style="position:absolute;top:'+relY+'px;left:'+relX+'px;"><div>');
	
});