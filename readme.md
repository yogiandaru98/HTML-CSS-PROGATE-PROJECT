 classDiagram
      Employee <|-- Duck
      Employee <|-- Zebra
      Employee : -int age
      Employee : -String name
      Employee: +isMammal()
      Employee: +mate()
      class Duck{
          +String beakColor
          +swim()
          +quack()
      }
      class Zebra{
          +bool is_wild
          +run()
      }
