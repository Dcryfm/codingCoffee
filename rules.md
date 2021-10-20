# `coffee` 编码的个人风格

## 创建函数表达式、对象方法，函数调用时，使用 `()` 圆括号

```coffee
fn = () -> 'ok'

object = {
  fn: () -> 'ok'
}

fn = (arg) -> arg * 2

fn(arg)
```

## 换行后不使用 `,` 逗号

```coffee
object = {
  name: 'Dcryfm'
  age: 30
}

array = [
  1, 0, 1
  0, 1, 0
  1, 1, 0
]
```

## 对象字面量使用 `{}` 花括号

```coffee
object = {
  name: 'Dcryfm'
  age: 30
}
```
