## ΢����SpringCloud����ѧϰ������

> �ҵĲ��ͣ�[https://blog.onfree.cn](https://blog.onfree.cn/)

### һ����������

1. ʲô��΢����΢����ܹ���

   - ΢����ǿ�����Ƿ���Ĵ�С������ע����ĳһ���㣬�Ǿ�����ĳһ������/�ṩ��ض�Ӧ�����һ������Ӧ�ã�����Ŀ������Կ���Ecipse�����һ����΢���񹤳�/����Module

   - ΢����ܹ�����һ�ּܹ�ģʽ�����ᳫ����һӦ�ó��򻮷ֳ�һ��С�ķ��񣬷���֮�以��Э����������ϣ�Ϊ�û��ṩ���ռ�ֵ��ÿ������������������Ľ����У����������������������ͨ�Ż��ƻ���Э����ͨ���ǻ���HTTPЭ���RESTfulAPl����ÿ������Χ���ž���ҵ����й����������ܹ��������Ĳ������������������������ȡ����⣬Ӧ����������ͳһ�ġ�����ʽ�ķ��������ƣ��Ծ����һ��������ԣ�Ӧ����ҵ�������ģ�ѡ����ʵ����ԡ����߶�����й�����

2. ΢�������ȱ�㣿

   - `�ŵ�`
     ÿ�������㹻�ھۣ��㹻С������������������ܾ۽�һ��ָ����ҵ���ܻ�ҵ�����󿪷��򵥡�����Ч����ߣ�һ��������ܾ���רһ��ֻ��һ���¡�

     ΢�����ܹ���С�Ŷӵ������������С�Ŷ���2��5�˵Ŀ�����Ա��ɡ�

     ΢����������ϵģ����й�������ķ����������ڿ����׶λ���׶ζ��Ƕ����ġ�

     ΢������ʹ�ò�ͬ�����Կ�����

     ���ں͵��������ɣ�΢�����������������ķ�ʽ�����Զ�����ͨ���������ɹ��ߣ���Jenkins��Hudson��bamboo��

     ΢�������ڱ�һ��������Ա��⣬�޸ĺ�ά��������С�Ŷ��ܹ�����ע�Լ��Ĺ����ɹ�������ͨ�������������ּ�ֵ��

     ΢���������������ں����¼�����

     ΢����ֻ��ҵ���߼��Ĵ��룬�����HTML��CSS���������������ϡ�ÿ��΢�������Լ��Ĵ洢�������������Լ������ݿ⡣Ҳ������ͳһ���ݿ⡣

   - `ȱ��`
     ������ԱҪ����ֲ�ʽϵͳ�ĸ�����

     �������ά�Ѷȣ����ŷ�������ӣ���ά��ѹ��Ҳ������ϵͳ��������

     �����ͨ�ų�

     ����һ����

     ϵͳ���ɲ���

     ���ܼ��..

3. SpringCloud��Dobbo������?
   SpringClou��ͨ�Ż����ǻ���HTTP��RESTful Api����Doboo��ʹ��RPC;

<img src="https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/SpringCloud%E5%AF%B9%E4%B8%8Ddobbo.png" alt="image" style="zoom: 67%;" />

3. SpringCloud��ʲô��

   SpringCloud������SpringBoot�ṩ��һ��΢������������������ע���뷢�֣��������ģ�ȫ��·��أ��������أ����ؾ��⣬�۶�������������˻���NetFlix�Ŀ�Դ������߶ȳ����װ֮�⣬����һЩѡ�������Ŀ�Դ�����

   Ҳ���Ƿֲ�ʽ΢����ܹ��µ�һվʽ����������Ǹ���΢����ܹ���ؼ����ļ����壬�׳�΢����ȫ��Ͱ��

4. SpringCloud��SpringBoot��ʲô��ϵ��

   SpringBootרע�ڿ��١�����Ŀ�����΢������壬SpringCloud��עȫ�ֵķ��������ܡ�

   SpringBootרע�ڿ��ٷ���Ŀ�����������΢����

   SpringCloud�ǹ�עȫ�ֵ�΢����Э�����������ܣ�����SpringBoot������һ��������΢�������ϲ�����������Ϊ����΢����֮���ṩ�����ù��������֡���·����·�ɡ�΢�����¼����ߡ�ȫ���������߾�ѡ���ֲ�ʽ�Ự�ȵȼ��ɷ�SpringBoot�����뿪SpringCloud����ʹ�ÿ�����Ŀ������SpringCloud�벻��SpringBoot�����������Ĺ�ϵ��

5. ΢������ջ

   ![image](https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%8A%80%E6%9C%AF%E6%A0%881.png)

   ![image](https://cdn.jsdelivr.net/gh/athink8/cdn/imgs/arctle/%E5%BE%AE%E6%9C%8D%E5%8A%A1%E6%8A%80%E6%9C%AF%E6%A0%882.png)

### ����SpringCloud

SpringCloud�ܹ���

![image](https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/SpringCloud%E6%9E%B6%E6%9E%84.png)

> API�ĵ���https://springcloud.cc/spring-cloud-dalston.html

���������

```xml
 <dependency>
                <groupId>org.springframework.boot</groupId>
                <artifactId>spring-boot-dependencies</artifactId>
                <version>2.2.5.RELEASE</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
           <dependency>
                <groupId>org.springframework.cloud</groupId>
                <artifactId>spring-cloud-dependencies</artifactId>
                <version>Hoxton.SR3</version>
                <type>pom</type>
                <scope>runtime</scope>
            </dependency>
```

�汾ѡ��

> [https://start.spring.io/actuator/info](https://start.spring.io/actuator/info)

> spring-boot  	2.2.5.RELEASE
>
> spring-cloud 	Hoxton.SR3
>
> netflix-eureka-server	2.2.1.RELEASE
>
> netflix-eureka-client	2.2.1.RELEASE
>
> netflix-ribbon	2.2.2.RELEASE
>
> config		2.2.2.RELEASE
>
> config-server  2.2.2.RELEASE
>
> openfeign 	2.2.2.RELEASE
>
> netflix-hystrix	2.2.2.RELEASE
>
> netflix-zuul		2.2.2.RELEASE		

#### 1. Eureka ����ע���뷢��

##### 1.1��ʲô��

Eureka��Netflix��һ����ģ�飬Ҳ�Ǻ���ģ��֮һ��Eureka��һ������REST�ķ������ڶ�λ������ʵ���ƶ��м������ֺ͹���ת�ơ�����ע���뷢�ֶ���΢����ܹ���˵�Ƿǳ���Ҫ�ģ����˷�������ע�ᣬֻ��Ҫʹ�÷���ı�ʶ�����Ϳ��Է��ʵ����񣬶�����Ҫ�޸ķ�����õ������ļ��ˡ�

> Netflix�����Eurekaʱ���صľ���APԭ��
>
> CAPԭ���ֳ�CAP����ָ������һ���ֲ�ʽϵͳ�У�Consistency��һ���ԣ��� Availability�������ԣ���Partition tolerance�������ݴ��ԣ������߲��ɼ��

##### 1.2�����ܹ�

Eureka ������ C-S ����Ƽܹ���Eureka Server ��Ϊ����ע�Ṧ�ܵķ����������Ƿ���ע�����ġ�

��ϵͳ�е�����΢����ʹ�� Eureka �Ŀͻ������ӵ� Eureka Server��ά���������ӡ�����ϵͳ��ά����Ա�Ϳ���ͨ�� Eureka Server �����ϵͳ�и���΢�����Ƿ��������С�SpringCloud ��һЩ����ģ�飨����Zuul���Ϳ���ͨ�� Eureka Server ������ϵͳ�е�����΢���񣬲�ִ����ص��߼���

<img src="https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/Eureka%E6%9E%B6%E6%9E%84.png" alt="image" style="zoom:67%;" />

> Eureka Server �ṩ����ע��ͷ���
>
> Service Provider�����ṩ�����������ע�ᵽEureka���Ӷ�ʹ�������ѷ��ܹ��ҵ�
>
> Service Consumer�������ѷ���Eureka��ȡע������б��Ӷ��ܹ����ѷ���

##### 1.3ʹ��

###### ��������

- pom:

  ```xml
          <dependency>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-web</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-eureka-server</artifactId>
          </dependency>
  ```

- yaml:

  ```yml
  server:
    port: 7001
  
  eureka:
    instance:
      hostname: localhost
    client:
      register-with-eureka: false #false��ʾ����ע������ע���Լ���
      fetch-registry: false #false��ʾ�Լ��˾���ע�����ģ��ҵ�ְ�����ά������ʵ����������Ҫȥ��������
      service-url:
        defaultZone: http://${eureka.instance.hostname}:${server.port}/eureka/
  ```

- ������

  ```
  @EnableEurekaServer
  ```

  

###### �ͻ���

- pom:

  ```xml
  <dependency>
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-actuator</artifactId>
  </dependency>
  <dependency>
      <groupId>org.springframework.cloud</groupId>
      <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
  </dependency>
  <dependency>
      <groupId>org.springframework.cloud</groupId>
      <artifactId>spring-cloud-starter-config</artifactId>
  </dependency>
  ```

- yml:

  ```yaml
  eureka:
    client:
      service-url:
        defaultZone: http://localhost:7001/eureka/
    instance:
      instance-id: ����1 #������
      prefer-ip-address: true #��ʾip
  info: #��Ϣ
    app.name: ����1-8081
    company.name: Athink
    build.artifactId: ${project.artifactId}
    build.version: ${project.version}
  ```

- ��pom:

  ```xml
  #Ϊ����ʾ����info��Ϣ    
  	<build>
          <finalName>${project.artifactId}</finalName>
          <resources>
              <resource>
                  <directory>src/main/resources</directory>
                  <filtering>true</filtering>
              </resource>
          </resources>
          <plugins>
              <plugin>
                  <groupId>org.apache.maven.plugins</groupId>
                  <artifactId>maven-resources-plugin</artifactId>
                  <configuration>
                      <delimiters>
                          <delimit>$</delimit>
                      </delimiters>
                  </configuration>
              </plugin>
              <plugin>
                  <groupId>org.springframework.boot</groupId>
                  <artifactId>spring-boot-maven-plugin</artifactId>
              </plugin>
          </plugins>
      </build>
  
  ```

- ������

  ```java
  //��ʵ������Բ���дҲͨ��  �����
  @EnableEurekaClient
  ```

  ##### 1.4������

����ע���eureka�����΢���񣬿���ͨ������������ø÷������Ϣ

- controller��

  ```java
  /*������*/
      @GetMapping("/discovery")
      public Object discovery() {
          List list = eurekaDiscoveryClient.getServices();
          System.out.println("**********" + list);
          List<ServiceInstance> srvList = eurekaDiscoveryClient.getInstances("demo1_provider_8081");
          for (ServiceInstance element : srvList) {
              System.out.println(element.getServiceId() + "\t" + element.getHost() + "\t" + element.getPort() + "\t"
                      + element.getUri());
          }
          return this.eurekaDiscoveryClient;
      }
  ```

- ������

  ```java
  @EnableDiscoveryClient
  ```

##### 1.5��Ⱥ

![image](https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/Eureka%E9%9B%86%E7%BE%A4.png)

###### ����ԭ��

��ͼ������eureka�Ĺٷ��ܹ�ͼ�����ǻ��ڼ�Ⱥ���õ�eureka�� 

\- ���ڲ�ͬ�ڵ��eurekaͨ��Replicate��������ͬ�� 

\- Application ServiceΪ�����ṩ�� 

\- Application ClientΪ���������� 

\- Make Remote Call���һ�η������

������������Eurekaע�ᣬEureka Server�Ὣע����Ϣ������Eureka Server����ͬ����������������Ҫ���÷����ṩ�ߣ��������ע�����Ļ�ȡ�����ṩ�ߵ�ַ��Ȼ��Ὣ�����ṩ�ߵ�ַ�����ڱ��أ��´��ٵ���ʱ����ֱ�Ӵӱ��ػ�����ȡ�����һ�ε��á�

������ע������Eureka Server��⵽�����ṩ����Ϊ崻�������ԭ�򲻿���ʱ�����ڷ���ע�����Ľ�������ΪDOWN״̬�����ѵ�ǰ�����ṩ��״̬�����߷��������Ĺ��ķ��������߸��±��ػ��档

�����ṩ���������������ԣ�Ĭ��30�룩��Eureka Server������������֤����ǰ�����ǿ���״̬��Eureka Server��һ����ʱ�䣨Ĭ��90�룩δ�յ��ͻ��˵�����������Ϊ����崻���ע����ʵ����

###### �ʹ��

- ��������pom:

  ```yml
  server:
    port: 7001
  
  eureka:
    instance:
      hostname: eureka1.cn
    client:
      register-with-eureka: false
      fetch-registry: false
      service-url:
        defaultZone: http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
  ```

- �ͻ��ˣ�

  ```yaml
  eureka:
    client:
     service-url:
       defaultZone: http://eureka1.cn:7001/eureka/,http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
  instance:
      instance-id: ����1
      prefer-ip-address: true #��ʾip
  
  info:
    app.name: ����1-8081
    company.name: Athink
    build.artifactId: ${project.artifactId}
    build.version: ${project.version}
  ```
  

> `ע�� �� ��������Ҫ��/eureka/����������Ӳſ��Է��ʣ�`

#### 2.Ribbon ���ؾ���

##### 2.1��ʲô?

Spring Cloud Ribbon�ǻ���Netflix Ribbonʵ�ֵ�һ��  **�ͻ���** ��**���ؾ���**  �Ĺ��ߡ�

�򵥵�˵��Ribbon��Netflix�����Ŀ�Դ��Ŀ����Ҫ�������ṩ�ͻ��˵�������ؾ����㷨����Netflix���м�����������һ��Ribbon�ͻ�������ṩһϵ�����Ƶ������������ӳ�ʱ�����Եȡ��򵥵�˵�������������ļ����г�Load Balancer�����LB���������еĻ�����Ribbon���Զ��İ��������ĳ�ֹ��������ѯ��������ӵȣ�ȥ������Щ����������Ҳ������ʹ��Ribbonʵ���Զ���ĸ��ؾ����㷨��

##### 2.2���ؾ���LB����

> [��������](https://github.com/Netflix/ribbon/wiki/Getting-Started)

LB�������ؾ���(Load Balance)����΢�����ֲ�ʽ��Ⱥ�о����õ�һ��Ӧ�á�

���ؾ���򵥵�˵���ǽ��û�������ƽ̯�ķ��䵽��������ϣ��Ӷ��ﵽϵͳ��HA��

�����ĸ��ؾ��������Nginx��LVS��Ӳ�� F5�ȡ�

��Ӧ�����м�������磺dubbo��SpringCloud�о��������ṩ�˸��ؾ��⣬SpringCloud�ĸ��ؾ����㷨�����Զ��塣

---

- ����ʽLB

  ���ڷ�������ѷ����ṩ��֮��ʹ�ö�����LB��ʩ(������Ӳ������F5, Ҳ�������������nginx), �ɸ���ʩ����ѷ�������ͨ��ĳ�ֲ���ת����������ṩ����

- ������LB

  ��LB�߼����ɵ����ѷ������ѷ��ӷ���ע�����Ļ�֪����Щ��ַ���ã�Ȼ���Լ��ٴ���Щ��ַ��ѡ���һ�����ʵķ�������

  Ribbon�����ڽ�����LB����ֻ��һ����⣬���������ѷ����̣����ѷ�ͨ��������ȡ�������ṩ���ĵ�ַ��

##### 2.3��������

- �ͻ���80

  - pom:

    ```xml
            <dependency>
                <groupId>org.springframework.cloud</groupId>
                <artifactId>spring-cloud-starter-netflix-ribbon</artifactId>
            </dependency>
            <dependency>
                <groupId>org.springframework.cloud</groupId>
                <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
            </dependency>
            <dependency>
                <groupId>org.springframework.cloud</groupId>
                <artifactId>spring-cloud-starter-config</artifactId>
            </dependency>
    ```

  - yml:

    ```yml
    server:
      port: 80
    
    eureka:
      client:
        register-with-eureka: false
        service-url:
          defaultZone: http://eureka1.cn:7001/eureka/,http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
    
    ```

  - beanConfig:

    ```java
    @Configuration
    public class beanConfig {
    
        @LoadBalanced //���
        @Bean
        public RestTemplate getRestTemplate()
        {
            return new RestTemplate();
        }
    
    }
    ```

  - �����ࣺ

    ```java
    @EnableEurekaClient //���
    ```

  - controller

    ```java
     //��ַ�޸�Ϊ ΢������ 
    //ע�� ΢������ Ϊspring: application��name: xxx
    //΢������ ��Ϊ��д  Сд�����
    //΢������ ���ɰ��� _
     private static final String REST_URL_PREFIX = "http://DEMO1PROVIDER8081"+"/user";
    ```

##### 2.4 Ribbon ���ؾ���

<img src="https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/Ribbon%E8%B4%9F%E8%BD%BD%E5%9D%87%E8%A1%A1%E6%9E%B6%E6%9E%84.png" alt="image" style="zoom: 67%;" />

> ͬ��΢�������д�����ֻҪspring: application��name: xxx ��ͬ���У�ÿ�����񶼿ɵ����������Լ������ݿ�
>
> �ͻ��˵��õ�ʱ��ֻ��ͨ�����������ã��ɿͻ��˵�Ribbon�����յ��趨�ĸ��ع���ȥִ�У�Ĭ����ѯ��

> �ܽ᣺Ribbon��ʵ����һ�����ؾ���Ŀͻ��������
>
> �����Ժ�������������Ŀͻ��˽��ʹ�ã���eureka���ֻ�����е�һ��ʵ����

##### 2.5Ribbon�������IRule

![image](https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/Ribbon%E7%9A%84IRule.jpg)

> IRule�������ض��㷨����ӷ����б���ѡȡһ��Ҫ���ʵķ���

```yml
#��ѯ
RoundRobinRule

#���
RandomRule

#���ȹ��˵����ڶ�η��ʹ��϶����ڶ�·����բ״̬�ķ���,���в�������������������ֵ�ķ���Ȼ���ʣ��ķ����б�����ѯ���Խ��з���
AvailabilityFilteringRule	

#����ƽ����Ӧʱ��������з����Ȩ�أ���Ӧʱ��Խ�����Ȩ��Խ��ѡ�еĸ���Խ�ߡ�
������ʱ���ͳ����Ϣ���㣬��ʹ��RoundRobinRule���ԣ���ͳ����Ϣ�㹻��
���л���WeightedResponseTimeRule
WeightedResponseTimeRule

#�Ȱ���RoundRobinRule�Ĳ��Ի�ȡ���������ȡ����ʧ������ָ��ʱ���ڻ�������ԣ���ȡ���õķ���
RetryRule

#���ȹ��˵����ڶ�η��ʹ��϶����ڶ�·����բ״̬�ķ���Ȼ��ѡ��һ����������С�ķ���
BestAvailableRule

#Ĭ�Ϲ���,�����ж�server������������ܺ�server�Ŀ�����ѡ�������
ZoneAvoidanceRule
```

##### 2.6�Զ��帺�ع���

> ���¾��ڿͻ���80��ִ��

> �ٷ��ĵ���ȷ�����˾��棺
>
> ����Զ��������಻�ܷ���@ComponentScan��ɨ��ĵ�ǰ�����Լ��Ӱ��£�
>
> ���������Զ�������������ͻᱻ���е�Ribbon�ͻ���������Ҳ����˵
>
> ���Ǵﲻ�����⻯���Ƶ�Ŀ���ˡ�

###### �򵥶���

- �����MyRibbonRule

  ```java
  @Configuration
  public class MyRibbonRule {
      @Bean
      public IRule myRule() {
          return new RandomRule();//RibbonĬ������ѯ�����Զ���Ϊ���
      }
  }
  ```

- ������

  ```java
  @SpringBootApplication
  @EnableEurekaClient
  //ָֻ��������Ч nameΪ������ configurationΪ�Զ��������
  @RibbonClient(name = "DEMO1PROVIDER1",configuration = MyRibbonRule.class) 
  
  //���з�����Ч
  //@RibbonClients(defaultConfiguration = MyRibbonRule.class)
  public class Demo1Consumer80Application {
  
      public static void main(String[] args) {
          SpringApplication.run(Demo1Consumer80Application.class, args);
      }
  
  }
  ```

###### �Զ�������㷨

> ��Ҫ�̳� AbstractLoadBalancerRule ��ʵ�ַ���

- �����MyRule1

  ```JAVA
  /**
   * author: jz
   * Time: 2020/3/17 23:12
   * ÿ���������4�Σ���ѯ��һ������
   **/
  public class MyRule1 extends AbstractLoadBalancerRule {
      private int sum = 0;    //�ܹ������õĴ�����ĿǰҪ��ÿ̨������3��
      private int currentIndex = 0;//��ǰ�ṩ����Ļ�����
  
      public MyRule1() {
      }
  
      @Override
      public void initWithNiwsConfig(IClientConfig iClientConfig) {
  
      }
  
      @Override
      public Server choose(Object key) {
          return this.choose(this.getLoadBalancer(), key);
      }
  
      public Server choose(ILoadBalancer lb, Object key) {
          if (lb == null) {
              return null;
          } else {
              Server server = null;
  
              while (server == null) {
                  if (Thread.interrupted()) {
                      return null;
                  }
  
                  List<Server> upList = lb.getReachableServers();
                  List<Server> allList = lb.getAllServers();
                  int serverCount = allList.size();
                  if (serverCount == 0) {
                      return null;
                  }
  
                  int index = this.chooseInt(serverCount);
                  server = (Server) upList.get(index);
                  if (server == null) {
                      Thread.yield();
                  } else {
                      if (server.isAlive()) {
                          return server;
                      }
  
                      server = null;
                      Thread.yield();
                  }
              }
  
              return server;
          }
      }
  
      /*ѡ���㷨*/
      public int chooseInt(int serverCount) {
          if(currentIndex>=0){
              sum++;
          }
          if(sum>=4){
              sum=0;
              currentIndex++;
          }
          if(currentIndex>=serverCount){
              sum=0;
              currentIndex=0;
          }
          return currentIndex;
      }
  }
  ```

- �����MyRibbonRule

  ```JAVA
  @Configuration
  public class MyRibbonRule {
      @Bean
      public IRule myRuleConfig() {
          return new MyRule1();
      }
  }
  ```

- ������

  ```JAVA
  @SpringBootApplication
  @EnableEurekaClient
  //ָֻ��������Ч nameΪ������ configurationΪ�Զ��������
  @RibbonClient(name = "DEMO1PROVIDER1",configuration = MyRibbonRule.class) 
  
  //���з�����Ч
  //@RibbonClients(defaultConfiguration = MyRibbonRule.class)
  public class Demo1Consumer80Application {
  
      public static void main(String[] args) {
          SpringApplication.run(Demo1Consumer80Application.class, args);
      }
  
  }
  ```

#### 3.openFeign���ؾ���

##### 3.1��ʲô��

> [����](https://projects.spring.io/spring-cloud/spring-cloud.html#spring-cloud-feign)

Feign��һ������ʽWebService�ͻ��ˡ�ʹ��Feign���ñ�дWeb Service�ͻ��˸��Ӽ�, ����ʹ�÷����Ƕ���һ���ӿڣ�Ȼ�����������ע�⣬ͬʱҲ֧��JAX-RS��׼��ע�⡣FeignҲ֧�ֿɰβ�ʽ�ı������ͽ�������Spring Cloud��Feign�����˷�װ��ʹ��֧����Spring MVC��׼ע���HttpMessageConverters��Feign������Eureka��Ribbon���ʹ����֧�ָ��ؾ��⡣

Feign��һ������ʽ��Web����ͻ��ˣ�ʹ�ñ�дWeb����ͻ��˱�÷ǳ����ף�ֻ��Ҫ����һ���ӿڣ�Ȼ�����������ע�⼴�ɡ�

##### 3.2�ܸ�ʲô

Feignּ��ʹ��дJava Http�ͻ��˱�ø����ס�

ǰ����ʹ��Ribbon+RestTemplateʱ������RestTemplate��http����ķ�װ�����γ���һ��ģ�滯�ĵ��÷�����������ʵ�ʿ����У����ڶԷ��������ĵ��ÿ��ܲ�ֹһ��������һ���ӿڻᱻ�ദ���ã�����ͨ���������ÿ��΢�������з�װһЩ�ͻ���������װ��Щ��������ĵ��á����ԣ�Feign�ڴ˻��������˽�һ����װ���������������Ƕ����ʵ����������ӿڵĶ��塣��Feign��ʵ���£�����ֻ�贴��һ���ӿڲ�ʹ��ע��ķ�ʽ��������(��ǰ��Dao�ӿ������עMapperע��,������һ��΢����ӿ������עһ��Feignע�⼴��)��������ɶԷ����ṩ���Ľӿڰ󶨣�����ʹ��Spring cloud Ribbonʱ���Զ���װ������ÿͻ��˵Ŀ�������

**Feign������Ribbon**

����Ribbonά����MicroServiceCloud-Dept�ķ����б���Ϣ������ͨ����ѯʵ���˿ͻ��˵ĸ��ؾ��⡣����Ribbon��ͬ���ǣ�ͨ��feignֻ��Ҫ�������󶨽ӿ���������ʽ�ķ��������Ŷ��򵥵�ʵ���˷������

##### 3.2����ʹ��

- pom

  ```xml
          <!--feign-->
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-openfeign</artifactId>
          </dependency>
         
  		<!--ribbon-->
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-ribbon</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-config</artifactId>
          </dependency>
  ```

- yml

  ```yml
  server:
    port: 80
  
  eureka:
    client:
     register-with-eureka: false
     service-url:
      defaultZone: http://eureka1.cn:7001/eureka/,http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
  #   enabled: true
  
  ```

- �����ӿ�

  ```java
  /**
   * author: jz
   * Time: 2020/3/18 13:30
   **/
  //ע������󶨵���΢����ʵ��
  //@RequestMapping("/user") ע��ǰ������Ӳ�����ôд��Ӧд path = "/user"
  @FeignClient(value = "DEMO1PROVIDER1"��path = "/user") //����ķ�����
  public interface UserClientService {
  
      @PostMapping("/")
      public boolean addUser(@RequestBody User user);
  
      @GetMapping("/id/{id}")
      public User findById(@PathVariable("id") Integer id);
  
      @GetMapping("/username/{username}")
      public User findByUsername(@PathVariable("username") String username);
  
      @GetMapping("/email/{email}")
      public User findByEmail(@PathVariable("email") String email);
  
      @GetMapping("/phone/{phone}")
      public User findByPhone(@PathVariable("phone") String phone);
  
      @GetMapping("/all")
      public List<User> findAll();
  
      /*������*/
      @GetMapping("/discovery")
      public Object discovery();
  }
  ```

- controller

  ```java
      @Autowired(required = false)
      UserClientService userClientService;
  ```

- ������

  ```java
  @EnableEurekaClient
  @EnableDiscoveryClient
  //ɨ����Ǳ����@FeignClient(value = "xx")�����
  //�����ͬһ������ģ�������ʡ�Բ���
  @EnableFeignClients(basePackages = {"demo1_api.FeignClientService"})
  ```

##### 3.3�ܽ�

 Feignͨ���ӿڵķ�������Rest����֮ǰ��Ribbon+RestTemplate����

�������͸�Eureka��������http://DEMO1PROVIDER1/user/all��,

ͨ��Feignֱ���ҵ�����ӿڣ������ڽ��з�����õ�ʱ���ں���Ribbon����������Ҳ֧�ָ��ؾ������á�

#### 4.Hystrix��·��

##### 4.1��ʲô��

HystrixҲ��Netflix�׼���һ����

Hystrix��һ�����ڴ���ֲ�ʽϵͳ���ӳٺ��ݴ�Ŀ�Դ�⣬�ڷֲ�ʽϵͳ�����������ɱ���Ļ����ʧ�ܣ����糬ʱ���쳣�ȣ�Hystrix�ܹ���֤��һ�����������������£����ᵼ���������ʧ�ܣ����⼶�����ϣ�����߷ֲ�ʽϵͳ�ĵ��ԡ�

����·����������һ�ֿ���װ�ã���ĳ������Ԫ��������֮��ͨ����·���Ĺ��ϼ�أ������۶ϱ���˿��������÷�����һ������Ԥ�ڵġ��ɴ���ı�ѡ��Ӧ��FallBack���������ǳ�ʱ��ĵȴ������׳����÷��޷�������쳣�������ͱ�֤�˷�����÷����̲߳��ᱻ��ʱ�䡢����Ҫ��ռ�ã��Ӷ������˹����ڷֲ�ʽϵͳ�е����ӣ�����ѩ����

<img src="https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/HystrixFallback.png" alt="image" style="zoom:80%;" />

---

##### 4.2�ܸ���

- �����۶�
- ���񽵼�
- ��������
- �ӽ�ʵʱ�ļ��

##### 4.3�����۶�

- pom

  ```xml
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-hystrix</artifactId>
          </dependency>
  ```

- controller

  ```java
      @HystrixCommand(fallbackMethod = "fallbackMethod")
      @GetMapping("/id/{id}")
      public User findById(@PathVariable("id") Integer id) {
         
          return userService.findById(id);
      }
  
      /*�����۶Ϸ��ط���*/
      public User fallbackMethod(@PathVariable("id") Integer id) {
          return new User().setName("�������");
      }
  ```

  > ע������۶Ϸ��ط�������ͼ�صķ����Ĳ����ͷ���ֵһ��
  >
  > ������׳� `fallback method wasn't found: defaultFallback`

- yml

  ```yaml
  hystrix: 
    command: 
      HelloClient	#toHello()://�������Ĭ����ȫ��
        execution: 
          isolation:
            thread:
              timeoutInMilliseconds: 500 #�̳߳�ʱ,����Fallback����
        circuitBreaker:
          requestVolumeThreshold: 3  #10���ڳ���3����������(���ٽ���ֵ),���ҳ�������50%����,������·��.
  ```

  

- ������

  ```java
  @EnableCircuitBreaker //���������۵�
  ```

---

��¼��@HystrixCommand**

```java
     public @interface HystrixCommand {

            // HystrixCommand ����������������ƣ�Ĭ��ע�ⷽ���������
            String groupKey() default "";

            // HystrixCommand �����keyֵ��Ĭ��ֵΪע�ⷽ��������
            String commandKey() default "";

            // �̳߳����ƣ�Ĭ�϶���ΪgroupKey
            String threadPoolKey() default "";
            // ������˷���������, �˷��������hystrix��ִ�з�������ͬ����
            String fallbackMethod() default "";
            // ����hystrix����Ĳ���
            HystrixProperty[] commandProperties() default {};
            // ����hystrix�������̳߳صĲ���
             HystrixProperty[] threadPoolProperties() default {};

            // ���hystrix�����׳����쳣����RUNTIME_EXCEPTION����ᱻ��װHystrixRuntimeException�쳣������Ҳ����ͨ���˷���������Щ��Ҫ���Ե��쳣
            Class<? extends Throwable>[] ignoreExceptions() default {};

            // ����ִ��hystrix observable�������ģʽ��������ϸ��ObservableExecutionMode
            ObservableExecutionMode observableExecutionMode() default ObservableExecutionMode.EAGER;

            // ���hystrix�����׳����쳣����RUNTIME_EXCEPTION����ᱻ��װHystrixRuntimeException�쳣���˷���������Ҫ�׳����쳣
            HystrixException[] raiseHystrixExceptions() default {};

            // ����ص�����������defaultFallback���ܴ�����������ز�����hystrix���������
            String defaultFallback() default "";
        }
```



##### 4.4���񽵼�(���Feign)

> @EnableFeignClients���Ѿ�Ĭ�ϴ��˶�·�����ܣ�����������������ϲ���Ҫ�ټ�@EnableCircuitBreakerע��
>
> ֻ��Ҫ��@FeignClient��Ϊfallback����ָ��fallback����

- pom

  ```xml
          <!--feign-->
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-openfeign</artifactId>
          </dependency>
          
          <!--ribbon-->
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-ribbon</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-config</artifactId>
          </dependency>
          
          <!--hystrix-->
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-hystrix</artifactId>
          </dependency>
  ```

- yml

  ```yaml
  #����feign��hystrix��֧��
  feign:
    hystrix:
      enabled: true
  ```

- service

  ```java
  //�ӿ�����1
  @FeignClient(value = "DEMO1PROVIDER1",path = "/user",fallback = Hystrixfallback.class)
  
  //�ӿ�����2
  //@FeignClient(value = "DEMO1PROVIDER1",path = "/user",fallbackFactory = Hystrixfallback.class)
  
  //ע������󶨵���΢����ʵ��
  public interface UserClientService {
  ```

- �����ӿ�Hystrixfallback

  - ��һ�֣��̳з���Ľӿ�

    ```java
    @Component //����  ��ӵ�����
    public class Hystrixfallback implements UserClientService {
    ```

  - �ڶ��֣��̳�FallbackFactory<xx>�Ľӿ�

    ```java
    @Component
    public class Hystrixfallback2 implements FallbackFactory<UserClientService> {
    
        @Override
        public UserClientService create(Throwable throwable) {
            return new UserClientService() {}
     	}
     }
    ```

##### 4.5������Hystrix Dashboard

###### - ����

- pom

  ```xml
          <dependency>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-actuator</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-hystrix</artifactId>
          </dependency>
  ```

- controller

  > ע��  ��������۶� ���ܱ���� 
  >
  > �۶Ϸ���̫��ʱ���鷳 ������ ��û�����ν��?

  ```java
      @HystrixCommand(fallbackMethod = "fallbackAll")
      @GetMapping("/all")
      public List<User> findAll() {
          return userService.findAll();
      }
      
      public List<User> fallbackAll() {
          List<User> users = new ArrayList<>();
          users.add(new User().setName("LIST �÷�"));
          return users;
      }
  ```

- ������

  ```JAVA
  @EnableCircuitBreaker
  ```

- ע��bean

  ```Java
  @Configuration
  public class beanConfig {
  
      //���bean��Ҫ�ǽ��/hystrix.stream��ͼ�޷��򿪵����⣻
      @Bean
      public ServletRegistrationBean getServlet() {
          HystrixMetricsStreamServlet streamServlet = new HystrixMetricsStreamServlet();
          ServletRegistrationBean registrationBean = new ServletRegistrationBean(streamServlet);
          registrationBean.setLoadOnStartup(1);
          registrationBean.addUrlMappings("/hystrix.stream");
          registrationBean.setName("HystrixMetricsStreamServlet");
          return registrationBean;
      }
  }
  ```

###### - Dashboard���

- pom

  ```xml
           <!--hystrix -->
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-hystrix</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-hystrix-dashboard</artifactId>
          </dependency>
  ```

- ������

  ```java
  @EnableHystrixDashboard
  ```

###### - ������

<img src="https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/HystrixDashboard.png" alt="image" style="zoom:67%;" />

ʵ��Բ���������ֺ��塣��ͨ����ɫ�ı仯������ʵ���Ľ����̶ȣ����Ľ����ȴ���ɫ����ʵ��Բ������ɫ�ı仯֮�⣬���Ĵ�СҲ�����ʵ�����������������仯������Խ���ʵ��Բ��Խ������ͨ����ʵ��Բ��չʾ���Ϳ����ڴ�����ʵ���п��ٵķ��ֹ���ʵ���͸�ѹ��ʵ����

���ߣ�������¼x��������������Ա仯������ͨ�������۲쵽�������������½����ơ�

#### 5.zuul·������

##### 5.1��ʲô��

Zuul��Ϊ΢����ϵͳ������������Ǵ��豸����վ��Netflix��Ӧ�ó����˵����������ǰ�š���Ϊ��Ե����Ӧ�ó���Zuulּ��ʵ�ֶ�̬·�ɣ���أ����ԺͰ�ȫ�ԡ�

> ע�⣺Zuul�������ջ��ǻ�ע���Eureka

##### 5.2�ܸ�ʲô?

Zuul��Ҫ����ʱAPI Gateway(api����)

- �����֤
- �������
- ѹ������
- ��˿ȸ����
- ��̬·��
- ����Ǩ��
- ���ط���
- ��ȫ
- ��̬��Ӧ����
- ����/������������

##### 5.3����

`zuul`��һ�����غ͸��ؾ�����,��ͨ��`ribbon`����`feign`ʵ���˿ͻ��˸��ؾ���֮��,`zuul`�ڷ����ʵ�ָ��ؾ��⡣`zuul`֧�����κ�`JVM`��������д����͹���������

����������΢����ܹ��в��ɻ�ȱ�Ĳ��֡�ͨ����������ͳһ����ϵͳ�ṩ`REST API`�Ĺ����У����˾߱�����·�ɡ����⸺�ع���֮�⣬�����߱���Ȩ�޿��Ƶȹ��ܡ�

 `Spring Cloud Netflix`�е�`Zuul`�͵�����������һ����ɫ��Ϊ΢����ܹ��ṩ��ǰ�ű��������ã�ͬʱ��Ȩ�޿�����Щ���صķ�ҵ���߼�����Ǩ�Ƶ�����·�ɲ��棬ʹ�÷���Ⱥ�����ܹ��߱����ߵĿɸ����ԺͿɲ����ԡ�

![image](https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/zuul%E4%BD%9C%E7%94%A8.jpg)

##### 5.3��̬·��

- pom

  ```xml
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-zuul</artifactId>
          </dependency>
  ```

- yml

  ```yaml
  server:
    port: 9999
  
  spring:
    application:
      name: springcloud-zuul
  
  eureka:
    client:
      service-url:
        defaultZone: http://eureka1.cn:7001/eureka/,http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
  
  zuul:
    ignored-services: "*"
    #ribbonIsolationStrategy: THREAD
    strip-prefix: false
    sensitive-headers: Access-Control-Allow-Origin
    #ignored-headers: Access-Control-Allow-Origin,H-APP-Id,APPToken
    #strip-prefix: true #ȫ��ȥ��ǰ׺
    #sensitive-headers: true
    #MyZuulFilter: #��������
      #pre: #��������
        #disable: true
    routes:
      demo1provider1: # ��ʶ ����д
        path: /p1/**  #����·��
        serviceId: demo1provider1 #������
      demo1_consumer_feign:
        serviceId: consumerfeign
        path: /c1/**
      a:
        path: /a/**
        #stripPrefix: true  #��ǰȥ��ǰ׺
      host:
        connect-timeout-millis: 60000
        socket-timeout-millis: 60000
  
  
  hystrix:
    command:
      default:
        execution:
          isolation:
            thread:
              timeoutInMilliseconds: 6000
  #���ؾ���
  ribbon:
    ConnectionTimeout: 500
    ReadTimeout: 2000
  ```

- ����

  ```JAVA
  @EnableEurekaClient
  @EnableZuulProxy
  ```

##### 5.4�Զ��������

> ��ʵ���Զ��������ʱ��������Ч

- �����MyZuulFilter

  ```java
  package demo1_zuul.config;
        
  /**
   * ������֤��������Demo��ʾ��ʵ�ʸ�������ҵ����ʵ�֣�
   *
   * @author jz
   * @date 2020-03-20.
   */
  @Component
  public class MyZuulFilter extends ZuulFilter {
  
      /**
       * per��·��֮ǰ����ʵ����֤����¼������Ϣ��
       * routing��·��ʱ
       * post��·�ɺ󣬱������HTTP Header
       * error����������ʱ����
       */
      @Override
      public String filterType() {
          return "pre";
      }
  
      /**
       * ������˳������@Filter�е�order
       */
      @Override
      public int filterOrder() {
          return 20;
      }
  
      /**
       * �������д�߼��жϣ��Ƿ�Ҫ���ˣ�����true,��Զ���ˡ�
       */
      @Override
      public boolean shouldFilter() {
          return true;
      }
  
      /**
       * �������ľ����߼������úܸ��ӣ�������sql��nosqlȥ�жϸ����󵽵���û��Ȩ�޷��ʡ�
       */
      @Override
      public Object run() {
          RequestContext requestContext = RequestContext.getCurrentContext();
          HttpServletRequest request = requestContext.getRequest();
  
          System.out.println("getServerName "+request.getServerName()); //localhost
          System.out.println("getRequestURL "+request.getRequestURL());
          //http://localhost:9999/p1/user/all
          System.out.println("getRequestURI "+request.getRequestURI()); //p1/user/all
          System.out.println("getServerPort "+request.getServerPort()); //9999
          System.out.println("authToken "+request.getHeader("authToken")); //��ȡ����ͷ��Ϣ
  
          String token = request.getParameter("token");
          if (token == null) {
              requestContext.setSendZuulResponse(false);
              requestContext.setResponseStatusCode(404);
              requestContext.setResponseBody("token cannot be empty");
          }
          requestContext.setSendZuulResponse(true);
          return null;
      }
  }
  ```

##### 5.5����۶�

> ��ʵ������۶�ʱ���۶���Ч 

- �����MyFallbackProvider

  ```java
  package demo1_zuul.config;
  
  @Component
  public class MyFallbackProvider implements FallbackProvider {
  
      /**
       * getRoute�����ķ���ֵ����Ҫ�����Ĺҵ���΢���������
       * �����Ҫ���з���������۶ϻ��ˣ���return "*" �� return null
       *
       * @return
       */
      @Override
      public String getRoute() {
          return "*";
      }
  
      /**
       * �������޷�ִ�е�ʱ�򣬷����е���Ϣ
       *
       * @param route
       * @param cause
       * @return
       */
      @Override
      public ClientHttpResponse fallbackResponse(String route, Throwable cause) {
          return new ClientHttpResponse() {
  
              /**
               * ClientHttpResponse��fallback��״̬��
               * @return
               * @throws IOException
               */
              @Override
              public HttpStatus getStatusCode() throws IOException {
                  return HttpStatus.OK;
              }
  
              /**
               * ClientHttpResponse��fallback��״̬��
               * @return
               * @throws IOException
               */
              @Override
              public int getRawStatusCode() throws IOException {
                  return this.getStatusCode().value();
              }
  
              /**
               * ClientHttpResponse��fallback��״̬��
               * @return
               * @throws IOException
               */
              @Override
              public String getStatusText() throws IOException {
                  return this.getStatusCode().getReasonPhrase();
              }
  
              /**
               * Close this response, freeing any resources created.
               */
              @Override
              public void close() {
  
              }
  
              /**
               * ������Ӧ��
               * @return
               * @throws IOException
               */
              @Override
              public InputStream getBody() throws IOException {
                  String content = "�÷��񲻿���!!";
                  return new ByteArrayInputStream(content.getBytes());
              }
  
              /**
               * ������Ӧͷ��Ϣ
               * @return
               */
              @Override
              public HttpHeaders getHeaders() {
                  HttpHeaders headers = new HttpHeaders();
                  MediaType mt = new MediaType("application", "json", Charset.forName("utf-8"));
                  headers.setContentType(mt);
  
                  return headers;
              }
          };
      }
  }
  ```

#### 6.SpringCloud Config�ֲ�ʽ��������

##### 6.1��ʲô��

SpringCloud ConfigΪ΢����ܹ��е�΢�����ṩ���л����ⲿ����֧�֣����÷�����Ϊ������ͬ΢����Ӧ�õ����л����ṩ��һ�����Ļ����ⲿ���á�

##### 6.2��ô��

SpringCloud Config��Ϊ����˺Ϳͻ��������֡�

�����Ҳ��Ϊ�ֲ�ʽ�������ģ�����һ��������΢����Ӧ�ã������������÷�������Ϊ�ͻ����ṩ��ȡ������Ϣ������/������Ϣ�ȷ��ʽӿ�

�ͻ�������ͨ��ָ������������������Ӧ����Դ���Լ���ҵ����ص��������ݣ�����������ʱ����������Ļ�ȡ�ͼ���������Ϣ���÷�����Ĭ�ϲ���git���洢������Ϣ�������������ڶԻ������ý��а汾�������ҿ���ͨ��git�ͻ��˹���������Ĺ���ͷ����������ݡ�

����SpringCloud ConfigĬ��ʹ��Git���洢�����ļ�(Ҳ��������ʽ,����֧��SVN�ͱ����ļ�)��

�����Ƽ��Ļ���Git������ʹ�õ���http/https���ʵ���ʽ

##### 6.3ʹ��

###### -�����

- pom

  ```xml
          <dependency>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-actuator</artifactId>
          </dependency>
  
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
          </dependency>
          <dependency>
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-config-server</artifactId>
          </dependency>
  ```

- yml

  ```yaml
  spring:
    #profiles:
      #active: native #�������������ļ�
    application:
      name: demo1config
    cloud:
      config:
        label: master # ���òֿ�ķ�֧
        server:
          git:
            # ����git�ֿ��ַ
            #uri: https://github.com/athink8/SpringCloud-Config.git
            uri: https://e.coding.net/athink8/SpringCloud-Config-coding.git
            # ���òֿ�·�µ����·��.����,���ö��
            #search-paths: /
            username: athink8@163.com # ����git�ֿ���û���
            password:  # ����git�ֿ������
          #native:  #���������ļ�
            #search-locations: file:///E:\yuyan\java\spring\other\SpringCloud\SpringCloud-Config\SpringCloud-Config
  
  server:
    port: 9200
  
  eureka:
    client:
      service-url:
        defaultZone: http://eureka1.cn:7001/eureka/,http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
    instance:
      instance-id: config9200
      prefer-ip-address: true #��ʾip
  ```

- ����

  ```java
  @EnableConfigServer
  @EnableEurekaClient
  @EnableDiscoveryClient
  ```

- ����

  ```yaml
  http://localhost:9200/application-dev.yml #ǰ��ʱ���git�ֿ�������ļ�profile
  ```

  > ���ʲ��ԣ�
  >
  > / {application} / {profile} [/ {label}]
  > /{application}-{profile}.yml
  > /{label}/{application}-{profile}.yml
  > /{application}-{profile}.properties
  > /{label}/{application}-{profile}.properties

###### -�ͻ���

- pom

  ```xml
          <dependency>
              <groupId>org.springframework.boot</groupId>
              <artifactId>spring-boot-starter-actuator</artifactId>
          </dependency>
  
          <dependency><!--config�ͻ���-->
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-config</artifactId>
          </dependency>
          <dependency><!--eureka�ͻ���-->
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-eureka-client</artifactId>
          </dependency>
          <dependency><!--hystrix�۶���-->
              <groupId>org.springframework.cloud</groupId>
              <artifactId>spring-cloud-starter-netflix-hystrix</artifactId>
          </dependency>
  ```

- git�ϴ��ļ�demo1_provider_1.yml

  ```yaml
  spring:
    profiles:
      active:
      - dev
      - demo1provider1_mysql_1
  ---
  #server:
    #port: 8081
  spring:
    profiles: dev
    application:
      name: demo1provider1
    #����Դ��������
    datasource:
      driver-class-name: com.mysql.jdbc.Driver
      type: com.alibaba.druid.pool.DruidDataSource
      #����Դ��������
      initialSize: 5
      minIdle: 5
      maxActive: 20
      maxWait: 60000
      timeBetweenEvictionRunsMillis: 60000
      minEvictableIdleTimeMillis: 300000
      validationQuery: SELECT 1 FROM DUAL
      testWhileIdle: true
      testOnBorrow: false
      testOnReturn: false
      poolPreparedStatements: true
      #���ü��ͳ�����ص�filters��ȥ�����ؽ���sql�޷�ͳ�ƣ�'wall'���ڷ���ǽ
      filters: stat,wall
      maxPoolPreparedStatementPerConnectionSize: 20
      useGlobalDataSourceStat: true
      connectionProperties: druid.stat.mergeSql=true;druid.stat.slowSqlMillis=500
  
  mybatis:
    type-aliases-package: demo1_api.entities    # ����Entity���������ڰ�
    config-location: classpath:mybatis/mybatis-config.xml #ָ��ȫ�������ļ���λ��
    mapper-locations: classpath:mybatis/mapper/*.xml  #ָ��sqlӳ���ļ���λ��
  
  #ʵ�ַ���Ⱥ�ܹ����Ӳ�ͬ�����ݿ�
  ---
  spring:
    profiles: demo1provider1_mysql_1
    datasource:
      username: root
      password: 123456
      url: jdbc:mysql:///athink_all?useUnicode=true&characterEncoding=UTF-8&serverTimezone=UTC
  ---
  spring:
    profiles: demo1provider1_mysql_2
    datasource:
      username: root
      password: 123456
      url: jdbc:mysql:///test1?useUnicode=true&characterEncoding=UTF-8&serverTimezone=UTC
  ---
  spring:
    profiles: demo1provider1_mysql_3
    datasource:
      username: root
      password: 123456
      url: jdbc:mysql:///test2?useUnicode=true&characterEncoding=UTF-8&serverTimezone=UTC
  ```

- bootstrap.yml����

  > ע�⣬��Ҫ��config���õ���Ϣ���浽bootstrap.yml,������application.yml
  >
  > bootstrap.yml ���ȼ�> application.yml��������bootstrap.yml

  ```yaml
  server:
    port: 8081
  spring:
    application:
      name: demo1provider1
    cloud:
      config:
        label: master # ���òֿ�ķ�֧
        #uri: http://localhost:9200 #ֱ����������config����
        name: demo1_provider_1 #��Ҫ��github�϶�ȡ����Դ���ƣ�ע��û��yml��׺��
        profile: dev,demo1provider1_mysql_1 #��������
        discovery:
          enabled: true #����������
          service-id: demo1config #��eureka��Ѱ�ҳ�config���ķ���
        #fail-fast: true
  
  #eureka����Ӧ������bootstrap.yml��
  eureka:
    client:
      service-url:
        defaultZone: http://eureka1.cn:7001/eureka/,http://eureka2.cn:7002/eureka/,http://eureka3.cn:7003/eureka/
    instance:
      instance-id: ����1-8081
      prefer-ip-address: true #��ʾip
  info:
    app.name: demo1provider1
    company.name: Athink
    build.artifactId: ${project.artifactId}
    build.version: ${project.version}
  ```

- ����

  ```java
  @EnableEurekaClient
  @EnableDiscoveryClient
  @EnableCircuitBreaker
  ```

#### 7.SpringCloud Sleuth��Zipkin��·����

##### 7.1����ʲô��

- Spring Cloud Sleuth

  Spring Cloud SleuthΪ����֮������ṩ��·׷�١�ͨ��Sleuth���Ժ�������˽⵽һ���������󾭹�����Щ����ÿ�����������˶೤���Ӷ������ǿ��Ժܷ���������΢�����ĵ��ù�ϵ������Sleuth���԰������ǣ�

  - ��ʱ����: ͨ��Sleuth���Ժܷ�����˽⵽ÿ����������ĺ�ʱ���Ӷ���������Щ������ñȽϺ�ʱ;
  - ���ӻ�����: ���ڳ���δ��׽���쳣������ͨ������Zipkin��������Ͽ���;
  - ��·�Ż�: ���ڵ��ñȽ�Ƶ���ķ��񣬿��������Щ����ʵʩһЩ�Ż���ʩ��

  spring cloud sleuth���Խ��zipkin������Ϣ���͵�zipkin������zipkin�Ĵ洢���洢��Ϣ������zipkin ui��չʾ���ݡ�

![Spring Cloud Sleuth����ͼ](https://cdn.jsdelivr.net/gh/athink8/cdn@master/imgs/arctle/spring%20cloud%20sleuth.png)

- Zipkin 

  Zipkin��һ������Դ����ֲ�ʽ�ĸ���ϵͳ����Twitter��˾��Դ�����������ռ�����Ķ�ʱ���ݣ��Խ��΢����ܹ��е��ӳ����⣬�������ݵ��ռ����洢�����Һ�չ�֡�

  ÿ��������zipkin�����ʱ���ݣ�zipkin����ݵ��ù�ϵͨ��Zipkin UI����������ϵͼ����ʾ�˶��ٸ�������ͨ��ÿ�����񣬸�ϵͳ�ÿ����߿�ͨ��һ�� Web ǰ�����ɵ��ռ��ͷ������ݣ������û�ÿ���������Ĵ���ʱ��ȣ��ɷ���ļ��ϵͳ�д��ڵ�ƿ����

  Zipkin�ṩ�˿ɲ�����ݴ洢��ʽ��In-Memory��MySql��Cassandra�Լ�Elasticsearch���������Ĳ���Ϊ����ֱ�Ӳ���In-Memory��ʽ���д洢�������Ƽ�Elasticsearch��

##### 7.2ʹ��

> ���������ã���Ҳ����ûɶѧϰ�ı�Ҫ��..

---

δ�����..

