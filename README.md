# Hawkeye
单机版的方法调用链分析
- 想知道修改了一个方法，会影响哪些上游方法，需要分析方法调用链，解析Class 文件的方法代码中的字节码指令，invokevirtual,invokeinterfac,invokespecial,invokestatic

分布式的方法调用链分析
- 分布式环境下，如何分析一处修改会影响哪些上游类呢？（如何屏蔽或自适应具体服务化框架来分析分布式应用的修改影响,dubbo？ Sofa？，spring-cloud？）

