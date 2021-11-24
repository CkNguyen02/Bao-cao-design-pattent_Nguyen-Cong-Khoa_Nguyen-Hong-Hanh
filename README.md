# Báo cáo về Design Pattern

## Nguyễn Công Khoa 20021376
## Nguyễn Hồng Hạnh 20021343

### Link GitHub tham khảo:
> https://github.com/JamesZBL/java_design_patterns //Link github repo.

> https://viblo.asia/p/tong-hop-cac-bai-huong-dan-ve-design-pattern-23-mau-co-ban-cua-gof-3P0lPQPG5ox //Link 23 mẫu chuẩn.
__ __

###1. So sánh Abtract factory
* ConcreteFactory có được xây dựng nhưng không theo cấu trúc chuẩn
* AbstractProduct được khai báo chính xác
* Product đã được cài đặt chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/abstract-factory (Link repo)
* https://gpcoder.com/4365-huong-dan-java-design-pattern-abstract-factory/ (Link mẫu chuẩn)

###2. So sánh Adapter
* Adaptee đã được khai báo chính xác
* Adapter được khai báo chính xác
* Target được khai báo chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/adapter (Link repo)
* https://gpcoder.com/4483-huong-dan-java-design-pattern-adapter/ (Link mẫu chuẩn)

###3. So sánh Bridge
* Abstraction có một vài phần không theo cấu trúc chuẩn
* Refined Abstraction được cài đặt chính xác
* Implementor được khai báo chính xác
* ConcreteImplementor được khai báo chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/bridge (Link repo)
* https://gpcoder.com/4520-huong-dan-java-design-pattern-bridge/ (Link mẫu chuẩn)

###4. So sánh Builder
* Builder chưa phải là abstract class hay ìnterface
* ConcreteBuilder chưa kế thừa Builder
* Director đã được cài đặt chính xác
* Product  đã được cài đặt chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/builder (Link repo)
* https://gpcoder.com/4434-huong-dan-java-design-pattern-builder/ (Link mẫu chuẩn)

###5. So sánh Composite
* Base Component đã được khai báo chính xác
* Leaf đã được cài đặt nhưng chưa implement các phương thức của Component
* Composite đã được cài đặt chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/composite (Link repo)
* https://gpcoder.com/4554-huong-dan-java-design-pattern-composite/ (Link mẫu chuẩn)

###6. So sánh Decorator
* Component đã được cài đặt đúng
* ConcreteComponent đã được cài đặt chính xác
* Decorator đã được cài đặt chính xác
* ConcreteDecorator đã được cài đặt chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/decorator (Link repo)
* https://gpcoder.com/4574-huong-dan-java-design-pattern-decorator/ (Link mẫu chuẩn)

###7. So sánh Factory Method
* Super Class đã được cài đặt chính xác
* Sub Class đã được cài đặt chính xác
* Factory Class đã được cài đặt chính xác
* https://github.com/JamesZBL/java_design_patterns/tree/master/factory-method (Link repo)
* https://gpcoder.com/4352-huong-dan-java-design-pattern-factory-method/ (Link mẫu chuẩn)

###8. So sánh Flyweight
* Flyweight đã được cài đặt chính xác
* ConcreteFlyweight đã được cài đặt chính xác
* UnsharedFlyweight đã được cài đặt chính xác
* FlyweightFactory đã được cài đặt chính xác
* Client đã được cài đặt
* https://github.com/JamesZBL/java_design_patterns/tree/master/flyweight (Link repo)
* https://gpcoder.com/4626-huong-dan-java-design-pattern-flyweight/ (Link mẫu chuẩn)

###9. So sánh Prototype
* Prototype đã được cài đặt chính xác
* ConcretePrototype đã dược cài đặt chính xác
* Client đã được cài đặt
* https://github.com/JamesZBL/java_design_patterns/tree/master/prototype (Link repo)
* https://gpcoder.com/4413-huong-dan-java-design-pattern-prototype/ (Link mẫu chuẩn)

###10. So sánh Singleton
* Private Contructor đã được cài đặt
* Chưa cài đặt biến ở dưới dạng ***private static final***
* Đã có một method public static được cài đặt
* https://github.com/JamesZBL/java_design_patterns/tree/master/singleton (Link repo)
* https://gpcoder.com/4190-huong-dan-java-design-pattern-singleton/ (Link mẫu chuẩn)

###11. Chain of Responsibility:
* Mẫu thiết kế theo repo có cấu trúc giống 90% theo mẫu chuẩn, chỉ khác có thêm 2 lớp để khai báo.
* https://github.com/JamesZBL/java_design_patterns/tree/master/chain (Link repo)
* https://gpcoder.com/4665-huong-dan-java-design-pattern-chain-of-responsibility/ (Link mẫu chuẩn)

###12. Command:
* Mẫu thiết kế theo repo có đủ cấu trúc, đó là interface or abstract class, có implemention, có tiếp nhận request, tiếp nhật concrete và nơi nhận( giống 100%).
* https://github.com/JamesZBL/java_design_patterns/tree/master/command (Link repo)
* https://gpcoder.com/4686-huong-dan-java-design-pattern-command/ (Link mẫu chuẩn)

###13. Facade:
* Có đầy đủ các cấu trúc giống như định dạng chuẩn.
* https://github.com/JamesZBL/java_design_patterns/tree/master/facade (Link repo)
* https://gpcoder.com/4604-huong-dan-java-design-pattern-facade/ (Link mẫu chuẩn) 
