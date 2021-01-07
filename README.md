# Algorithmic-Trading-PlayingAround
Algorithmic Trading by investigating Apple from 2015 - 2021 
Reference from Computer Science Youtuber video


AAPL Adjusted Close Price History
![AAPL](https://user-images.githubusercontent.com/52622346/103859478-b9034500-507f-11eb-82b4-858db08546ac.PNG)


**Simple Moving Average Method**

Comparing the SMA30 & SMA100 

![Capture](https://user-images.githubusercontent.com/52622346/103859725-29aa6180-5080-11eb-9a6f-8ac0ff0c2879.PNG)

Next, a function was created so that when the SMA30 first intersects with SMA100, it would buy at that rate. Vice-versa, the next rising SMA30 that meets with SMA100 would be a selling point.

![Capture](https://user-images.githubusercontent.com/52622346/103860105-cd940d00-5080-11eb-87fc-43b30f3e7978.PNG)


**RESULT**<br/>
From 0 - 400 points on the timeline: LOSS<br/>
400 - 800 :  GAIN<br/>
From 800 - 1000 : LOSS<br/>
1000 - 1300: GAIN<br/>

This was a very simple method but does not seem to be a trustworthy method to gain profit. 

