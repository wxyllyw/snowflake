# snowflake
snowflake, simple and effective handle clock moved backwards.

---
Example:
```java
public class Sample {

    public static void main(String[] args) {
        ZookeeperWorker.init("127.0.0.1");
        System.out.println(SnowFlakeWorker.getInstance().nextId());
        System.out.println(SnowFlakeWorker.getInstance().nextId());
    }
}
```