### This README is just for practicing with markdown on [github](http://github.com)

* List
 * Sub One
 * Sub Two
* List 2
 * Sub One
 * Sub Two

#### Practice code alignment

```
(sc
 .parallelize(xrange(10))
 .filter(lambda x: x % 2 == 0)
 .map(lambda x: (x, x ** 2))
 .mapValues(lambda x: x + 3)
 .collect())
```
