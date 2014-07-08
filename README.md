jxa-expr
========

Joxa wrapper for expr

Installation
------------

Usage
-----

```lisp
(ns my-app
  (require jxa-expr))

(defn resolve ()
  :todo)

(defn+ literal ()
  (jxa-expr/do
      {resolve/7 :context}
    [1 2 3 4 5]))

(defn+ call ()
  (jxa-expr/do
      {resolve/7 :context}
    ))
```
