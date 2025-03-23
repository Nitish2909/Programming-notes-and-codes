jQUERY : 
jquery is a lightweight " write less ,do more"  javascript library.
The purpose of this library is to make the use of javascript in the websites.
It is created by "John Resig" in 2006 .

features of jquery:
1.HTML/DOM manipulation.
2.CSS manipulation.
3.HTML methods and elements.
4.AJAX
5.effects and animation.

WHY USING JQUERY:-
There are many other javascript library are avilable but jquery is most popular and most extendable javascript library.
Many big tech companies use jquery suc as:
Netflix
IBM
Microsoft
Google

JQUERY SYNTAX:-
 
 $(selector).action()

 here,
 $ sign define/access jQuery.
 (selector) to Find HTML elements.
 A jQuery acton() to be performed on the elements.

 examples:
1.hide the current element.

 $(this).hide() 

 2.hide all <h> elements.

 $("h").hide()

 3.hide all elements with class 

 $(".classname).hide()

 4.hide all the elements with id.

 $("#id").hide()

	THE DOCUMENT READY EVENT :-
	The document ready event is to prevent any jquery code from running before the document is finished loading.The code is wriiten between $(document).ready() is executed only when the page is ready for javascript code to execute. It is good practice to wait for the document to be fully loaded and ready before working with it.

	syntax :-
	$(document).ready(function){
	
	}

There are also a shorter method for the document ready event:
$(function(){

}

example:-
<!DOCTYPE html>
<html lang="en">
<head>
<title>document.ready example</title>
<script
  src="https://code.jquery.com/jquery-3.7.1.js"
  integrity="sha256-eKhayi8LEQwp4NKxN+CfCh+3qOVUtJn3QNZ0TciWLP4="
  crossorigin="anonymous"></script>
</head>
<body>
    <h1>this is the example of document ready event</h1>
    <script>
        $(document).ready(function(){
        $('h1').click(function()
        {
            alert('this is the example of document ready event');
        });
    });
    </script>
</body>
</html>
