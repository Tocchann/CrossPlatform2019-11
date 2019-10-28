## Cross-Platform な
## アプリ開発をするときに
## 考えておきたい点

<https://gitpitch.com/Tocchann/CrossPlatform2019-11>

![QRCode](Resources/qrcode.png)

+++

### 自己紹介的な？

* とっちゃん  
わんくま同盟  
  * <http://blogs.wankuma.com/tocchann/default.aspx>

* 各種SNSとか  
Twitter
  * <https://twitter.com/Tocchann>  
Facebook
  * <https://www.facebook.com/toshiyuki.takahagi>  
Github
  * <https://github.com/tocchann>  

Microsoft MVP for Developer Technologies  
Since 2005/10～  
  * <https://mvp.microsoft.com/ja-jp/PublicProfile/32182>

+++

### わんくま同盟 東京勉強会 #119

2019/12/14 新宿お菜家で開催！  
私もしゃべります！  
(ここだけの話、まだ決めてない)

続報は <http://www.wankuma.com/seminar/> で！  
<https://wankuma.connpass.com/> でも告知！

---

### Cross-Platform な  
### アプリ開発をするときに  
### 考えておきたい点  

# とは？

---

### Cross-Platform なアプリ開発？

* Cross-Platform  
→ 複数環境  
Multi-Platform と呼ぶ場合もある

* アプリ開発  
→ エンドユーザーが利用するプログラムの開発

---

### 考えておきたい点？

* プログラムを作る上で考慮しておくべき  
事柄のうち  
特有なものを  
少しだけ並べてみました

---

### 一番大事なのは

* Cross-Platform(Multi-Platform) な  
(アプリ))開発においては  
**プロジェクト(プロダクト:製品)** の  
**ポータビリティ** を  
**高く維持した状態** で  
開発を継続すること

---

### ポータビリティとは

* ポータビリティ: Portability
* 英辞郎より
  1. 携帯できること、携帯性、可搬性、軽便
  1. 《コ》移植性

---

### ポータビリティを高く維持？

* 可搬性が高い
* ソースコードを **一切** 修正(変更)せずに  
複数の実行環境向けにプログラムを出力できる。

---

### ポータビリティを高く維持？

* 移植性が高い
* ソースコードを **極力** 修正(変更)せずに  
複数の実行環境向けにプログラムを出力できる。

---

### バイナリデータファイルの場合は？

* ビットイメージの同一化
* エンディアンを統一
* 文字コードの統一または、文字コードの明示

---

### テキストファイルの場合は？

* 文字コードの統一または、文字コードの明示
* 改行コードの取り扱いの多様性対応
* 規格にそって書式化テキストを扱っているか？
* CSV の対応書式は意思統一されているか？
  * UNICODE はあるが、UTF-8 は非公式

---

### もう少し具体的に！
