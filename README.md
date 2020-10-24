# start

https://github.com/JetBrains/kotlin  

## why kotlin
- https://stepney141.hatenablog.com/entry/2019/05/07/002007
- http://shoheyhey0821.hatenablog.jp/entry/2018/01/03/111411
- https://plasmic.space/tech/2018/10/getting_started_kotlin_against_my_will/
- kotlin は better なjava

## command line
https://kotlinlang.org/docs/tutorials/command-line.html

```
$ kotlin -version
Kotlin version 1.4.10-release-411 (JRE 1.8.0_202-b08)
```

-includ-runtime オプションは、生成された .jar ファイルに Kotlin ランタイムライブラリを含めることで、自己完結型で実行可能なファイルにします。

```
kotlinc hello.kt -include-runtime -d hello.jar
```

```
$ java -jar hello.jar "abc"   
Hello, World!
```

# setting

```
cat /Users/niten.nashiki/ghq/github.com/github/gitignore/Java.gitignore >> .gitignore
```




