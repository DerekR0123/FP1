## Derek Ross - Exploration 1 - OPL - Fred Martin -  Final Project

## My Library ###
Library Name: Web Applications In Racket  -  #lang web-server/insta   <br>
My name: Derek Ross <br>
My Email: Derek_Ross@student.uml.edu <br>
My GitHub: https://github.com/DerekR0123 <br>
Where to Find Code: This repository located in the above github. <br>
<br>
What I did: <br>
<br>
I started off by opening the document recommended and scrolling through till I seen Web Applications In Racket. A light bulb popped 
in my head instantly because I love to create and design websites! I followed this neat little tutorial that was listed and understood some of the code provided through the use of the library. To Summarize what I actually did I would describe it like this: I followed some tutorial examples and set out to provide a few key components from the idea's behind Web Design. I created a Title / Header for the tab of the page, a paragraph to introduce the page as well as a link to some other pages I have created, and ended it with a list of my favorite activities! <br>  Below is an example of the code:<br>
<br>
****************** START OF CODE SAMPLE *****************************<br>
<br>
```
 #lang web-server/insta 
;;Library used to create the websites


(define (start request)
  ;;Sends a request to your web browser
  
  (response/xexpr
   ;;The request is picked up and opens something in the following format
   
   '(html
   
   ## Anything you wish to add to the page goes here! You will see more cool stuff in my full example of the code! ##
   )))
   ```
   <br>
   <br>
   ****************** END OF CODE SAMPLE **********************************<br>
   <br>
   <br>
   That is just a small snippit of the code with some comments. You can find the full source in this repository. Here is what<br>
   the output result of the code looks like:<br>
   <br>
   <br>
   <img src="https://i.gyazo.com/8f56ab0a7e5a278d962c30eff093ef5f.png" width="15%"></img>
   <br>
   A Diagram for the library can be found below:
   <br>
   <img src="https://i.gyazo.com/e7690ad4a8263a641cb612a87e68b281.png" width="15%"></img>
   <br>
   <br>
   <br>
   ##End Of Document##
   
