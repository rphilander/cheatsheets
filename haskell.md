haskell
=======

**Record Syntax**

```haskell
data Car = Car {company :: String, model :: String, year :: Int} deriving (Show)
hotrod = Car {company="Ford", model="Mustang", year=1967}
```


**Type Parameters**
```haskell
data Maybe a = Nothing | Just a 
```
