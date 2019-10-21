# Python-Scripts
A repo for Python scripts and code snippets I frequently use. 

Pandas

* [Suppress Scientific Notation](https://github.com/hjhuney/Python-Scripts/blob/master/README.md#pandas-suppress-scientific-notation)

## Pandas: Suppress Scientific Notation

```
pd.set_option('display.float_format', lambda x: '%.2f' % x)
```
