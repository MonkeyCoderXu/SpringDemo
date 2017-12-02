spring IOC的原理：
  Spring容器的原理，其实就是通过解析xml文件或注解（@Bean、@Component），获取到用户配置的bean，然后通过反射将这些bean挨个放到集合中，然后对外提供一个getBean()方法，以便我们获得这些bean。
  
  

