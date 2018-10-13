##fragments.ConcurrencyWithSchedulersDemoFragment

把耗时的一些IO操作或者需要长时间处理的计算放到其他线程，并在完成操作后回到主线程更新UI。

使用CompositeDisposable管理DisposableObserver，just操作符，map操作符

##fragments.BufferDemoFragment

使用buffer缓冲事件操作

2秒内点击多次按钮（多次操作），会在2秒后根据点击次数更新UI，显示点击了几次。

学习Disposable，map，buffer的使用