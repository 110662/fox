# きつねだよ

これでスライドできるんだって。すごいね！！！
---

# きつねかわいいよ2

gitpitch用のテストリポジトリだよ

---

# グラフだよ1

<canvas data-chart="line">
    Month, 1月, 2月, 3月, 4月, 5月, 6月, 7月
    1980, 65, 59, 80, 81, 56, 55, 40
    2017, 28, 48, 40, 19, 86, 27, 90
</canvas>

---

# グラフだよ2

<canvas data-chart="bar">
    Month, 1月, 2月, 3月, 4月, 5月, 6月, 7月
    1980, 65, 59, 80, 81, 56, 55, 40
    2017, 28, 48, 40, 19, 86, 27, 90
</canvas>

---

# グラフだよ3

<canvas data-chart="pie">
    Month, 1月, 2月, 3月, 4月, 5月, 6月, 7月
    1980, 65, 59, 80, 81, 56, 55, 40
    2017, 28, 48, 40, 19, 86, 27, 90
</canvas>

---

# グラフだよ4

<canvas data-chart="radar">
    Month, 1月, 2月, 3月, 4月, 5月, 6月, 7月
    1980, 65, 59, 80, 81, 56, 55, 40
    2017, 28, 48, 40, 19, 86, 27, 90
</canvas>

---

# コードだよ

```
class DecimalEncoder(json.JSONEncoder):
    def default(self, o):
        if isinstance(o, decimal.Decimal):
            if o % 1 > 0:
                return float(o)
            else:
                return int(o)
        return super(DecimalEncoder, self).default(o)
```

---

# 数式もいけるらしいよ

$$\sum_{i=0}^n i^2 = \frac{(n^2+n)(2n+1)}{6}$$


