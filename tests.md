# Tests autour de l'intégration markdown de GitLab


## Grpahes avec plantuml

```plantuml
digraph G {
  A -> B 
  B -> C
  B -> A
}
```

```plantuml
class Car{
 -field1
 #field2
 ~method1()
 +method2()
}
note top: My defined class

Driver - Car : drives >
Car *- Wheel : have 4 >
Car -- Person : < owns
```
