## 1 - r"[a-c]*"

```
(a|b|c)*
```

## 2 - r"[ab]+"

```
(a|b)(a|b)*
```

## 3 - r"a?b?c?"

```
(a|ε)(b|ε)(c|ε)
```

## 4 - r"[abde]|ab|c?"

```
(a|b|d|e)|ab|(c|ε)
```