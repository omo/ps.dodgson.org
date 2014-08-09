---
title: "Lambda and Streams"
date: 2014-08-09 22:20 UTC
tags:
---

> * http://www.infoq.com/presentations/lambda-streams-java-8/
> * http://www.infoq.com/presentations/java-8-lambda-streams/
> * http://docs.oracle.com/javase/8/docs/api/java/util/function/package-summary.html
> * http://docs.oracle.com/javase/8/docs/api/java/util/stream/package-summary.html

全体的に Java らしく固い出来な印象。よいこった。

そしてなるほど、Lambda は functional interface というものになるだけなのか。これは Java7 と互換にできるということなんですかね・・・

> * http://stackoverflow.com/questions/16143684/can-java-8-code-be-compiled-to-run-on-java-7-jvm
> * https://github.com/orfjackal/retrolambda

とおもったけど extension method のせいでダメらしい。あんどろに来る日は遠そうだな・・・。もっともライブラリも埋めないとあかんのでどっちにしても遠そうだけど、Lambda きたらだいぶすっきりするとおもうんだけどねえ・・・

> http://stackoverflow.com/questions/23318109/is-it-possible-to-use-java-8-for-android-development

まあむりやり動かすなら Java じゃなくてもいいべ。

> http://blog.futurice.com/android-development-has-its-own-swift

Xtend が Android の Swift になる、という記事。Xtend は言語はよいので僕も一瞬期待したことがあったけれど、なにしろ Ecplise 出自のフレームワークにべったりくっつきすぎていてどうにもなんないかんじがする。むしろ RubyMotion みたいなかんじで IDE を捨てて Emacs で生きて行く、という前提の何かが登場するのを待つほうが良いのだろうねえ。

といいつつ Ruby Motion のあんどろ対応は個人的には特に期待していない. JNI でがんばってつなぐ、と主張しているけれどそんなら C++ でいいっすよ...Java で言語境界をまたぐのはどうにも遅いからねえ.

> http://blog.rubymotion.com/post/87048665656/rubymotion-3-0-sneak-peek-android-support

ただ RubyMotion というか MacRuby は Ruby と Obj-C を無理矢理ブリッジした狂気の実績があるので、何らかの魔改造をやってのける可能性はあるのかもしんない.

IntelliJ 親和性という意味では Kotlin どうなのかなあ. いちおう Lambda はある. 基本的な Type inferrence もある. 本家が動くと主張している... Lambda は Java みたいに functional interface 的に実装されているのだろうか...というと、SAM Convertion というのがあるっぽいな。それでよさげ。

> * http://blog.jetbrains.com/kotlin/2013/08/working-with-kotlin-in-android-studio/
> * http://blog.jetbrains.com/kotlin/running-hello-kotlin-on-android/
> * http://srackham.wordpress.com/2013/07/08/writing-android-event-handlers-in-kotlin/

JS サポートとか余計なことをやってんのが気になるけれど, サーバサイド の Better Java や AltJS はライバルいっぱいいるところに Better Android 言語はほぼ真空地帯なわけだから, そこに全力でつっこんでほしいもんです. とりあえず試すリストにはいれとこう...

> * http://blog.jetbrains.com/kotlin/2013/10/writing-kotlin-in-the-browser/
