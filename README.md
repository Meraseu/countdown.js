# countdown.js

countdown 자바스크립트 라이브러리 입니다.

## Sample Usage

```
var countdown = new Countdown('.countdown', {
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