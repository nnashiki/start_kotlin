# start

- intro
   - https://kotlinlang.org/docs/tutorials/getting-started.html
   - https://github.com/JetBrains/kotlin
- example
   - https://play.kotlinlang.org/byExample/01_introduction/01_Hello%20world

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

# web
- https://kotlinlang.org/docs/tutorials/spring-boot-restful.html

# 入門書
- https://www.amazon.co.jp/%E5%85%A5%E9%96%80%EF%BC%81%E5%AE%9F%E8%B7%B5%EF%BC%81%E3%82%B5%E3%83%BC%E3%83%90%E3%83%BC%E3%82%B5%E3%82%A4%E3%83%89Kotlin-%E6%8A%80%E8%A1%93%E3%81%AE%E6%B3%89%E3%82%B7%E3%83%AA%E3%83%BC%E3%82%BA%EF%BC%88NextPublishing%EF%BC%89-%E6%A8%AA%E5%B1%B1-%E6%81%AD%E5%A4%A7-ebook/dp/B082H8GWMR/ref=pd_vtp_1?pd_rd_w=F5imb&pf_rd_p=74e7e349-7116-4e20-9bd2-ff98ca6bd130&pf_rd_r=YDTBBHH3MRM48C16KAD1&pd_rd_r=4440c24a-b257-4e00-943b-a2e883a5dae5&pd_rd_wg=WYIdK&pd_rd_i=B082H8GWMR

# kotlin
- https://speakerdeck.com/m3_engineering/jjug-ccc-2018fall-kotlin-in-m3
- https://tech-lab.sios.jp/archives/9500

# gradle を使った設定
- https://medium.com/@deepak_v/kotlin-beginner-to-advance-build-real-command-line-tool-using-kotlinx-cli-608bbc6d9a3
- https://tech-lab.sios.jp/archives/9500