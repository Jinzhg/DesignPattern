# DesignPattern

## 定义
模式是在特定环境下人们解决某类重复出现的问题的一套成功或有效的解决方案。

设计模式(Design Pattern)是一套被反复使用、多数人知晓的、经过分类编目的、代码设计经验的总结，使用设计模式是为了可重用代码、让代码更容易被他人理解并且保证代码可靠性。

## 面向对象设计原则（SOLID）
- **单一职责原则** (Single Responsibility Principle, SRP)：一个类只负责一个功能领域中的相应职责。就一个类而言，应该只有一个引起它变化的原因。
- **开闭原则** (Open-Closed Principle, OCP)：软件实体应对扩展开放，而对修改关闭。
- **里氏代换原则** (Liskov Substitution Principle, LSP)：所有引用基类对象的地方能够透明地使用其子类的对象。
- **接口隔离原则** (Interface Segregation Principle, ISP)：使用多个专门的接口，而不使用单一的总接口。
- **依赖倒转原则** (Dependence Inversion Principle, DIP)：抽象不应该依赖于细节，细节应该依赖于抽象。
- **合成复用原则** (Composite Reuse Principle, CRP)：尽量使用对象组合，而不是继承来达到复用的目的。
- **迪米特法则** (Law of Demeter, LoD)：一个软件实体应当尽可能少地与其他实体发生相互作用。

## 分类
设计模式可分为创建型(Creational)，结构型(Structural)和行为型(Behavioral)三种，其中创建型模式主要用于描述如何创建对象，结构型模式主要用于描述如何实现类或对象的组合，行为型模式主要用于描述类或对象怎样交互以及怎样分配职责。

### 创建型模式
- [简单工厂模式](01.%20简单工厂模式%20(Simple%20Factory%20Pattern).md) (Simple Factory Pattern)【学习难度：★★☆☆☆，使用频率：★★★☆☆】
- [工厂方法模式](02.%20工厂方法模式%20(Factory%20Method%20Pattern).md) (Factory Method Pattern)【学习难度：★★☆☆☆，使用频率：★★★★★】
- [抽象工厂模式](03.%20抽象工厂模式%20(Abstract%C2%A0%20Factory%20Pattern).md) (Abstract  Factory Pattern)【学习难度：★★★★☆，使用频率：★★★★★】
- [单例模式](04.%20单例模式%20(Singleton%20Pattern).md) (Singleton Pattern)【学习难度：★☆☆☆☆，使用频率：★★★★☆】
- [原型模式](05.%20原型模式%20(Prototype%20Pattern).md) (Prototype Pattern)【学习难度：★★★☆☆，使用频率：★★★☆☆】
- [建造者模式](06.%20建造者模式%20(Builder%20Pattern).md) (Builder Pattern)【学习难度：★★★★☆，使用频率：★★☆☆☆】

### 结构型模式
- [适配器模式](07.%20适配器模式%20(Adapter%20Pattern)%20-%20协调不兼容的结构.md) (Adapter Pattern) - 协调不兼容的结构【学习难度：★★☆☆☆，使用频率：★★★★☆】
- [桥接模式](08.%20桥接模式%20(Bridge%20Pattern)%20-%20处理多维度变化.md) (Bridge Pattern) - 处理多维度变化【学习难度：★★★☆☆，使用频率：★★★☆☆】
- [组合模式](09.%20组合模式%20(Composite%20Pattern)%20-%20处理树形结构.md) (Composite Pattern) - 处理树形结构【学习难度：★★★☆☆，使用频率：★★★★☆】
- [装饰模式](10.%20装饰模式%20(Decorator%20Pattern)%20-%20扩展系统功能.md) (Decorator Pattern) - 扩展系统功能【学习难度：★★★☆☆，使用频率：★★★☆☆】
- [外观模式](11.%20外观模式%20(Facade%20Pattern).md) (Facade Pattern)【学习难度：★☆☆☆☆，使用频率：★★★★★】
- [享元模式](12.%20享元模式%20(Flyweight%20Pattern)%20-%20实现对象的复用.md) (Flyweight Pattern) - 实现对象的复用【学习难度：★★★★☆，使用频率：★☆☆☆☆】
- [代理模式](13.%20代理模式%20(Proxy%20Pattern).md) (Proxy Pattern)【学习难度：★★★☆☆，使用频率：★★★★☆】

### 行为型模式
- [职责链模式](14.%20职责链模式%20(Chain%20of%20Responsibility%20Pattern)%20-%20请求的链式处理.md) (Chain of Responsibility Pattern) - 请求的链式处理【学习难度：★★★☆☆，使用频率：★★☆☆☆】
- [命令模式](15.%20命令模式%20(Command%20Pattern)%20-%20请求发送者与接收者解耦.md) (Command Pattern) - 请求发送者与接收者解耦【学习难度：★★★☆☆，使用频率：★★★★☆】
- [解释器模式](16.%20解释器模式%20(Interpreter%20Pattern)%20-%20自定义语言的实现.md) (Interpreter Pattern) - 自定义语言的实现【学习难度：★★★★★，使用频率：★☆☆☆☆】
- [迭代器模式](17.%20迭代器模式%20(Iterator%20Pattern)%20-%20遍历聚合对象中的元素.md) (Iterator Pattern) - 遍历聚合对象中的元素【学习难度：★★★☆☆，使用频率：★★★★★】
- [中介者模式](18.%20中介者模式%20(Mediator%20Pattern)%20-%20协调多个对象之间的交互.md) (Mediator Pattern) - 协调多个对象之间的交互【学习难度：★★★☆☆，使用频率：★★☆☆☆】
- [备忘录模式](19.%20备忘录模式%20(Memento%20Pattern)%20-%20撤销功能的实现.md) (Memento Pattern) - 撤销功能的实现【学习难度：★★☆☆☆，使用频率：★★☆☆☆】
- [观察者模式](20.%20观察者模式%20(Observer%20Pattern)%20-%20对象间的联动.md) (Observer Pattern) - 对象间的联动【学习难度：★★★☆☆，使用频率：★★★★★】
- [状态模式](21.%20状态模式%20(State%20Pattern)%20-%20处理对象的多种状态及其相互转换.md) (State Pattern) - 处理对象的多种状态及其相互转换【学习难度：★★★☆☆，使用频率：★★★☆☆】
- [策略模式](22.%20策略模式%20(Strategy%20Pattern)%20-%20算法的封装与切换.md) (Strategy Pattern) - 算法的封装与切换【学习难度：★☆☆☆☆，使用频率：★★★★☆】
- [模板方法模式](23.%20模板方法模式%20(Template%20Method%20Pattern).md) (Template Method Pattern)【学习难度：★★☆☆☆，使用频率：★★★☆☆】
- [访问者模式](24.%20访问者模式%20(Visitor%20Pattern)%20-%20操作复杂对象结构.md) (Visitor Pattern) - 操作复杂对象结构【学习难度：★★★★☆，使用频率：★☆☆☆☆】

## 参考
如有错误欢迎指正，如有侵权，请联系我删除。
- [史上最全设计模式导学目录（完整版）](https://blog.csdn.net/LoveLion/article/details/17517213) 
- [常用设计模式有哪些](https://refactoringguru.cn/design-patterns)