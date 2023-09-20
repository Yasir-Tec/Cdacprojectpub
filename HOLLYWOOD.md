# HOLLYWOOD-
The Hollywood Principle which sometimes referred to as Inversion of Control says "Don't call us, we'll call you" Which in terms of software engineering it states that an object which depends on another one should not call it but should wait for the other to call it.

Event driven execution.
This principle defines the IOC with more abstraction. As you know IoC defines inversing the control of dependencies. So first of all you should have a control center responsible for controlling dependencies i.e for making instance of them. This control center then inverses the flow of making instance of classes. So when you want to use ClassA in ClassB, you won't create instance of ClassB then Call ClassA. You make instance of ClassA and pass it to ClassB using different techniques and use it.
