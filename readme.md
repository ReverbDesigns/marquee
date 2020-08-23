
<!--README-->

METHODS

getContent()	
Returns the actual content of the Marquee

This method does not accept any arguments

$('.str').liMarquee('getContent');

addContent(string)	
Adds to marquee the new content

string Type: string
The new content.
$('.str').liMarquee('addContent','New Content');

removeContent()	
Remove from marquee all content

This method does not accept any arguments

$('.str').liMarquee('removeContent');

changeOptions(options)	
Restarts line with the new settings

options Type: object
The new options.
$('.str').liMarquee('changeOptions',{direction:'right',circular:false});

destroy()	
Removes all the functionality of Marquee. It returns the element in the condition before the initialization of the plug-in

This method does not accept any arguments

$('.str').liMarquee('destroy');
stop()	
Stop movement Marquee

This method does not accept any arguments

This method does not accept any arguments

$('.str').liMarquee('stop');
start(delay)	
Start movement Marquee

options Type: Number
The delay before starting the animation, ms. Default Value: 0
$('.str').liMarquee('start', 300);
resetPosition()	
Reset start end end position of marquee Animation

This method does not accept any arguments

$('.str').liMarquee('resetPosition');
EVENTS
create()	
Triggered when the liMarquee is created

$('.str').liMarquee({
create: function(){}
});

moveStart()	
Triggered when motion starts

$('.str').liMarquee({
moveStart: function(){}
});

moveStop()	
Triggered when motion stops

$('.str').liMarquee({
moveStop: function(){}
});

drag()	
Triggered while the string is moved during the dragging

$('.str').liMarquee({
drag: function(){}
});

dragStart()	
Triggered when dragging starts

$('.str').liMarquee({
dragStart: function(){}
});

dragStop()	
Triggered when dragging stops

$('.str').liMarquee({
dragStop: function(){}
});

wayEnd()	
Triggered when way ended

$('.str').liMarquee({
wayEnd: function(){}
});


Code context

.contItem { display:inline-block; vertical-align:top; width:300px; padding:20px; white-space:normal;}
.contItemImage { width:100%;}
.contItemTitle { font:16px/1.2em Arial, Helvetica, sans-serif; display:block; padding:0 0 10px 0;}
.contItemText { font:16px/1.2em Arial, Helvetica, sans-serif; padding:20px 0; text-transform:none; text-align:left;}
</style>

<!-- Initialization of plugin -->
<script>
$(window).on('load',function(){
	$('.str3-2').liMarquee({circular:true, startShow:true});
})
</script> 


<!-- HTML code-->
<div class="str3-2 mWrap">
	<div class="contItem">
		<a href="#"><img src="pic/image.jpg" class="contItemImage"></a>
		<div class="contItemText">
			<a class="contItemTitle" href="#">Lorem ipsum</a> 
			Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
		</div>
	</div>
	<div class="contItem">
		<a href="#"><img src="pic/image.jpg" class="contItemImage"></a>
		<div class="contItemText">
			<a class="contItemTitle" href="#">Lorem ipsum</a> 
			Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
		</div>
	</div>
	<div class="contItem">
		<a href="#"><img src="pic/image.jpg" class="contItemImage"></a>
		<div class="contItemText">
			<a class="contItemTitle" href="#">Lorem ipsum</a> 
			Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
		</div>
	</div>
	<div class="contItem">
		<a href="#"><img src="pic/image.jpg" class="contItemImage"></a>
		<div class="contItemText">
			<a class="contItemTitle" href="#">Lorem ipsum</a> 
			Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
		</div>
	</div>
	<div class="contItem">
		<a href="#"><img src="pic/image.jpg" class="contItemImage"></a>
		<div class="contItemText">
			<a class="contItemTitle" href="#">Lorem ipsum</a> 
			Dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
		</div>
	</div>
</div>