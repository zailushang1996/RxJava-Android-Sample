## fragments.ConcurrencyWithSchedulersDemoFragment

把耗时的一些IO操作或者需要长时间处理的计算放到其他线程，并在完成操作后回到主线程更新UI。

使用CompositeDisposable管理DisposableObserver，just操作符，map操作符

## fragments.BufferDemoFragment

使用buffer缓冲事件操作

2秒内点击多次按钮（多次操作），会在2秒后根据点击次数更新UI，显示点击了几次。

学习Disposable，map，buffer的使用

## fragments.DebounceSearchEmitterFragment

在输入框中输入完成后再执行相应操作（400ms），不会每输入一个字符就触发事件。

RxTextView类的使用，debounce操作符，filter操作符使用。

## fragments.RetrofitFragment

结合Retrofit请求GitHub的api，重点flatMap操作符的使用，zip操作符使用

## fragments.DoubleBindingTextViewFragment

使用PublishProcessor（发布处理器）实现数据的双向绑定

## fragments.PollingFragment

使用Flowable（解决背压）实现简单轮训及增长型轮训  interval操作符的使用

## rxbus.RxBusDemoFragment

使用rxJava实现事件总线，学习RxBus封装，Flowable背压的buffer操作符使用，debounce使用

## fragments.FormValidationCombineLatestFragment

使用combineLatest验证表单输入，DisposableSubscriber（一次性订阅者，用于Flowable）的使用

## fragments.PseudoCacheFragment

concat操作符，concatEager操作符等等的使用

## fragments.TimingDemoFragment

flowable被观察者（背压）的timer，interval，take等操作符的使用




