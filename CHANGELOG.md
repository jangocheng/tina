# change

## 1.0.0
- 修复修复链式请求结果参数向下透传错误的bug。
- 优化了Automodel注解对Map类型的支持。
- 优化了初始线程池的配置。
- 缓存数据出现不匹配，自动清空不匹配数据并重新请求。
- 把request convert操作放入子线程。
- 增加未设置缓存目录的异常提醒。
- 增加缓存双回调机制。
- 优化@Cache注解，支持自定义cahce key，缓存key支持restful语法。
- 优化线程调度，大幅度降低主线程阻塞。