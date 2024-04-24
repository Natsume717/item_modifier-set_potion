# item_modifier-set_potion
item_modifierの1項目であるset_potionに関するサンプルになります。

詳しくはブログ記事『[【マイクラ】set_potionでポーション効果を付与【item_modifier】](https://natsumake.com/item_modifier-set_potion/)』を参考にしてください。

<h3>概要</h3>
ポーションや水入り瓶に対して、ポーション効果を適用させることが出来ます。

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

タラを倒すことで、透明化のポーションをドロップします。<br>
効果のないポーションをドロップするよう指示していますが、同時にset_potionで透明化のエフェクトを指示しているため、透明化のポーションをドロップするようになっています。

また、手元にポーションや水入り瓶を持っている状態で以下のコマンドを実行することで、水中呼吸のポーションと変化します。

```copy
/item modify entity @s weapon.mainhand sample:set_potion
```
