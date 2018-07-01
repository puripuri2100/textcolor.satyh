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

- gray colorパッケージにももとからあるものですが、blackを0、whiteを1として、値xを`Gray(x)`のように入れます。
- rgb colorパッケージにももとからあるものですが、`RGB(r,g,b)`のように入れます。　

# 追加する色とその定義
追加する色と、その定義を書いておきます。colorパッケージに元からあった色とその定義に関しては「（標準）」と書いておきます。

- black （標準）gray 0.
- white （標準）gray 1.
- red （標準）rgb = 1. 0. 0.
- yellow （標準）rgb = 1. 1. 0.
- orange （標準）rgb = 1. 0.5 0.
- blue （標準）rgb = 0. 0. 1.