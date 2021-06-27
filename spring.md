Srping 如何加载一个bean：jvm启动的时候会把.class文件初始化到方法区里面去，Spring通过扫描指定包的class文件，将@Service、@Dao等等这些被标记为Spring bean 的类加载到 beanDefinition中，如果单例模式，会初始化实例，放在单例池中，多例模式不实例化对象，等到getbean时才实例化。

Spring bean :要从class到beandefinition，到对象创建，属性注入，Spring初始化，将对象放到单例池，才算是一个Spring bean

## Spring Bean 的生命周期

