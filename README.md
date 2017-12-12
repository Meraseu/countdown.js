# countdown.js

----

## Sample Usage

```
var countdown = new Countdown(document.querySelector('.countdown'), {
    number : {
        days : 1,
        hours : 1,
        minutes : 1,
        seconds : 10
    },
    end : function() {
        console.log('end');
    }
});
```