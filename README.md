# Coffee_GoF
Uses following Design pattern:
Creational-
1)Singleton-Ensure only one CoffeeMachine instance exists.
2)Factory Method-Create coffee drinks(Espresso,Latte,Cappuccino) via a createCoffee() method.
3)Abstract Factory-Families of realted drinks:HotDrinkFactory(Espresso,Latte) or ColdDrinkFactory(Iced Latte,Cold Brew).
4)Builder-Step-by-step preparation:add espresso ->add steamed milk->add foam->add foam->add sugar.
5)Protoype-Clone a base recipe(eg, Standard Latte) and tweak it(extra shot,different milk)
