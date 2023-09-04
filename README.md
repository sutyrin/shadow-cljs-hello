# How to run 

```shell
docker run --rm -ti -v `pwd`:/app node:18.15 node /app/main.cjs
```

# Original source
```clojure
(ns flashcards-demo.core)

(println "Hello world (module level)!")

(defn main []
  (println "Hello world (main level)!"))
```
