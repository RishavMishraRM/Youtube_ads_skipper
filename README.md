# Youtube_ads_skipper
<h2><a href="https://github.com/RishavMishraRM/Youtube_ads_skipper/blob/main/prod.py">Program File</a></h2>
<a href="https://github.com/1993jayant/youtube_adskipper/blob/master/README.md"></a>
This is a program written in python programming language. It automatically clicks on the 'skip ad' button on the youtube ads. It uses opencv library's Template Matching functionality to do that.<br><br>
It loads templates of skip ad button for various resolution and zoom sizes of the screen to make it platform independent.<br><br>
It is successfully working on different machines with different resolutions.
I have used pyautogui library to take the screenshots of the screen and then in a while loop it matches with different templates for the screenshot. Whenever it finds a match with 70 percent confidence it clicks on the skip ad button automatically.<br><br>
