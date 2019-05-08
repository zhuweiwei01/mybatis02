总结：MyBatis里面用到了哪些设计模式？

1. 建造者模式 -- SqlSessionFactoryBuilder
2. 工厂模式 -- SqlSessionFactory
3. 代理模式 -- MapperProxy
4. 模板方法模式 -- BaseExecutor（doUpdate()由子类实现）
5. 装饰者模式 -- LruCache装饰PerpetualCache
6. 责任链模式 -- 拦截器的实现
