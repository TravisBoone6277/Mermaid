``` mermaid
classDiagram
    Travis <|-- Duck
   Boone <|-- Fish
    Is <|-- Zebra
   Amazing : +int age
    Person : +String gender
    Excellence: +isMammal()
    Power: +mate()
    class Duck{
      +String beakColor
      +swim()
      +quack()
    }
    class Fish{
      -int sizeInFeet
      -canEat()
    }
    class Zebra{
      +bool is_wild
      +run()
    }
```
