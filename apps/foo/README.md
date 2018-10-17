# Umbrella app config spike

```
$ (cd apps/foo && iex -S mix)
iex(1)>  Application.get_all_env :foo
[foo: "foo!!!", included_applications: []]
iex(2)>  Application.get_all_env :bar
[bar: "bar!!!"]
```