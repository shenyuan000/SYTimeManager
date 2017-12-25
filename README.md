# SYTimeManager
封装GCD倒计时器

*样例*
```objc
    [SYTimeManager timeWithTimeOut:10 handler:^(int presentTime) {
        NSLog(@"time ---  %d",presentTime);
    } finish:^{
        NSLog(@"结束了");
    }];
```
