# 极客大学

## java中线程有三个层次

1. Java层面
   1. Thread#start(); Thread#run()
      1. 都是代码层面的东西
2. jvm层面
   1. JavaThread     OSThrad      Stack      TLAB    
3. OS层面
   1. 系统线程（JavaThrad  OSThread）   ready(Thread,run()):启动     Terminate(Thrad.run()):终结

![image.png](https://i.loli.net/2021/11/08/d5wQjmpxInavtzG.png)

