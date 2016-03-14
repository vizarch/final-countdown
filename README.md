# Final countdown

<img width="400" alt="final-countdown" src="https://cloud.githubusercontent.com/assets/9873/13755264/abbca4f2-ea1a-11e5-971e-ad7fdbaba65b.png">
<img width="400" alt="final-countdown-alert" src="https://cloud.githubusercontent.com/assets/9873/13755518/ed9d2c1a-ea1b-11e5-9fd6-dcc482538f3a.png">


Simple online clock that can work as a stopwatch or countdown timer with start, pause and reset functions. 

Total and alert times and count direction can be changed using query params, e.g.
https://szimek.github.io/final-countdown/?time=60&alert=30
<br>
https://szimek.github.io/final-countdown/?time=10&alert=5&direction=up

#### Actions
* click        - start or pause timer
* double click - reset timer

#### Options

The defaults are:
```
total time: 1200 seconds (20 minutes)
alert time:  180 seconds (3 minutes)
direction:  down
```

Click to start or pause the timer, double click to reset.

Uses [RxJS](https://github.com/ReactiveX/RxJS), because why not.
