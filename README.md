# my2-Combe
# Gavon Combe
### My Bed
My bed is my favorite vacation place because it is the **only** place where I can relax and not worry about anything. My bed is a **great** place to go when I have the day off and can finally relax.
***
## Things to do in My Bed
I can do whatever I want in my bed be it sleep, scroll on my phone, or watch TV.
## Things I can eat
- Popcorn
- Eggs and bacon
- Chips

** [MyStats](MyStats.md) **

***
## Sports you should try
This next section will be a table that expresses the importance of the sports I think you should try along with the amount of time you should spend on each a week. Any physical activity is important though sports give a purpose and some fun to doing physical activity. <br>
|Sport | Reasoning | Hours per week|
|----- | --------- | --------------|
|Golf | Golf is a good way to move around and keep your joints healthy as every part of the sport is joint controll | 6 |
|Swimming | Swimming allows you to get all of the benefits of running without the sweating | 7 | 
|Weight lifting | This allows your muscles to continue growth and is good for the heart | 14|
|Skateboarding | Gets you places faster than walking and gives a little more of a work out, it also helps with balance | 10 |

***
> “Sometimes it pays to stay in bed on Monday, rather than spending the rest of the week debugging Monday’s code.” – *Dan Salomon, computer scientist*

> “Computers are incredibly fast, accurate, and stupid. Human beings are incredibly slow, inaccurate, and brilliant. Together they are powerful beyond imagination.”- *Albert Einstein, physicist*

***

> I have a site which is primarily for mobile users but desktop too.<br> On Mobile Safari, using <input type="number"> works great because it brings up the numerical keyboard on input fields which should only contain numbers.<br> In Chrome and Safari however, using number inputs displays spin buttons at the right side of the field, which looks like crap in my design. I really don't need the buttons, because they are useless when you need to write something like a 6-digit number anyway.<br> Is it possible to disable this with -webkit-appearance or some other CSS trick? I have tried without much luck. - pojo

Link to question <https://stackoverflow.com/questions/3975769/disable-webkits-spin-buttons-on-input-type-number> 

~~~
input[type=number]::webkit-inner-spin-button,
input[type=number]::webkit-outer-spin-button{
    -webkit-appearance: none;
    margin: 0;
}
~~~
Link to answer <https://css-tricks.com/snippets/css/turn-off-number-input-spinners/>
