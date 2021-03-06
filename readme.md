# これは何
これは[SATySFi](https://github.com/gfngfn/satysfi)のパッケージです。
`\textcolor`コマンドと、幾つかの色を追加します。

textcolor.satyhを同じフォルダに入れ、`@import: textcolor`とします。

# 追加するコマンドと使い方
`\textcolor`を追加、提供します。

`\textcolor(<color>){<inline-text>}`で使うことができます。

color部分は`TextColor.blue`のように、下に書く色が入ります。
SATySFiが標準で提供する[colorパッケージ](https://github.com/gfngfn/SATySFi/blob/master/lib-satysfi/dist/packages/color.satyh)よりも多い量が提供されるはずです。

# 追加する色の定義の仕方
色の定義のしかたです

- Gray whiteを1、blackを0として、Gray(x)という風に数字を入れる。
- rgb colorパッケージにももとからあるものですが、`RGB(r,g,b)`のように入れます。　最大が1で最小が0です。
- cmyk CMYK(c, m, y, k)のように入れます

CMYKの値は[色見本と配色サイト](https://www.color-sample.com/)の該当色の「CMYK (Japan 標準紙)」というところの値を利用しました。

# 追加する色とその定義
追加する色と、その定義を書いておきます。

## Gray
- black Gray(0.)
- white Gray(1.)
- darkgray Gray(0.25)
- lightgray Gray(0.75)

## RGB
- red rgb = 1. 0. 0.
- yellow rgb = 1. 1. 0.
- orange rgb = 1. 0.5 0.
- blue rgb = 0. 0. 1.
- green rgb = 0. 1. 0.

## CMYK
- cmyk-cyan cmyk = 1. 0. 0. 0.
- cmyk-magenta cmyk = 0. 1. 0. 0.
- cmyk-yellow cmyk = 0. 0. 1. 0.
- cmyk-blue cmyk = 1. 1. 0. 0.
- cmyk-red cmyk = 0. 1. 1. 0.
- cmyk-green cmyk = 1. 0. 1. 0.
- cmyk-lime cmyk = 0.614 0. 1. 0.
- cmyk-pink cmyk = 0. 0.359 0.104 0.
- cmyk-violet cmyk = 0.679 0.786 0.103	0.
- cmyk-purple cmyk = 0.448 0.753 0. 0.
- cmyk-brown cmyk = 0.586 0.698 0.845 0.252
- cmyk-olive cmyk = 0.667 0.616 1. 0.261
- cmyk-orange cmyk = 0.069 0.614 0.929 0.
- cmyk-teal cmyk = 0.843 0.402 0.527 0.001

# LICENSE
(C) Naoki Kaneko and T. Suwa 2018