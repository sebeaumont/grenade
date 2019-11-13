* With `ghc-8.8.1` and allow-newer: all => `singletons-2.4` this needs
  revision:
  
```
src/Grenade/Core/Shape.hs:90:1: error:
    • Wrong category of family instance; declaration was for a type family
    • In the data instance declaration for ‘Sing’
   |
90 | data instance Sing (n :: Shape) where
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^...
```
