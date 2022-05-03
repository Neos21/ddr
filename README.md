# DDR : DreamDaemonRevolution

TeamFlashSozai 様が製作された Flash ゲーム **「DreamDaemonRevolution」** をサルベージしました。

__[Enter The GitHub Pages](https://neos21.github.io/ddr/)__

__[Enter The DDR Page](https://neos21.github.io/ddr/ddr.html)__ (要 Flash Player)

## プレイ方法

- Flash Player のサポートは2020年12月31日に終了していますが、Flash Player が動作する環境を整えれば動作させられるでしょう (当方では未確認)
- **[MxNitro (Maxthon Nitro)](https://www.softpedia.com/get/Internet/Browsers/MxNitro.shtml)** という Flash Player 内蔵の Chromium ブラウザを使うと簡単に動作させられます
    - 当方では上のダウンロードサイトより `mxnitro1.0.1.3000_cc8a6485653fa5a52ba6d0896d0a2afc.exe` (Version 1.0.1.3000) をダウンロード・インストールし動作確認しました
- [BlueMaxima's Flashpoint](https://bluemaxima.org/flashpoint/) というツールでも動作させられるようです (当方では未検証)
- [swf2js](https://swf2js.com/)、[Ruffle](https://ruffle.rs/) といった **Flash エミュレータでは正常に起動・動作しませんでした**

当時のように Flash Player さえあれば GitHub Pages へのアクセスでも動作しますし、ローカルに各種アセットをダウンロードしても動作させられます (ローカル開発サーバ等を立てる必要はない)。

## サルベージ記録

2022-05-03 時点で、TeamFlashSozai 様の後継サイト `be-interactive.org` 配下に全てのアセットが存在するものの、ファイルパスに誤りがあり動作しない状況にある。

まずは以下の URL より `html`・`swf`・`bmslist.txt` ファイルを取得した。

- <http://www.be-interactive.org/works/ddr/ddr.html>
    - 本 HTML ファイル内の `DDR.swf` ファイルへのパスの記述に誤りがあった。本リポジトリ内の `ddr.html` はこのパスの記述のみ修正している
- <http://www.be-interactive.org/works/ddr/DDR.swf>
- <http://www.be-interactive.org/works/ddr/bmslist.txt>

次に、`bmslist.txt` ファイルの内容より、以下の `txt` ファイルの存在を確認し取得した。

- <http://www.be-interactive.org/works/ddr/azzuri.txt>
- <http://www.be-interactive.org/works/ddr/azzuriS.txt>
- <http://www.be-interactive.org/works/ddr/azzuriL.txt>
- <http://www.be-interactive.org/works/ddr/XYZL.txt>
- <http://www.be-interactive.org/works/ddr/XYZS.txt>
- <http://www.be-interactive.org/works/ddr/XYZH.txt>
- <http://www.be-interactive.org/works/ddr/sosH.txt>
- <http://www.be-interactive.org/works/ddr/sosS.txt>
- <http://www.be-interactive.org/works/ddr/sosL.txt>
- <http://www.be-interactive.org/works/ddr/ONG.txt>
- <http://www.be-interactive.org/works/ddr/ONGS.txt>
- <http://www.be-interactive.org/works/ddr/ONGL.txt>
- <http://www.be-interactive.org/works/ddr/drvH.txt>
- <http://www.be-interactive.org/works/ddr/drvS.txt>
- <http://www.be-interactive.org/works/ddr/drvL.txt>
- <http://www.be-interactive.org/works/ddr/pararedH.txt>
- <http://www.be-interactive.org/works/ddr/pararedS.txt>
- <http://www.be-interactive.org/works/ddr/pararedL.txt>

これらの `txt` ファイル内の記述より、以下の `jpg`・`mp3` ファイルの存在を確認し取得した。

- <http://www.be-interactive.org/works/ddr/azzuri.jpg>
- <http://www.be-interactive.org/works/ddr/drvbrmix.jpg>
- <http://www.be-interactive.org/works/ddr/onigirihc.jpg>
- <http://www.be-interactive.org/works/ddr/parared.jpg>
- <http://www.be-interactive.org/works/ddr/sos.jpg>
- <http://www.be-interactive.org/works/ddr/XYZ.jpg>
- <http://www.be-interactive.org/works/ddr/azzuri.mp3>
- <http://www.be-interactive.org/works/ddr/drvbrmix.mp3>
- <http://www.be-interactive.org/works/ddr/onigirihc.mp3>
- <http://www.be-interactive.org/works/ddr/paranoiared.mp3>
- <http://www.be-interactive.org/works/ddr/smotsmremx.mp3>
- <http://www.be-interactive.org/works/ddr/XYZ.mp3>

さらに、Ruffle でエミュレーションした際の起動画面より、以下のファイルの存在を確認し取得した。これらのファイルはメニュー画面でのプレビュー音源ファイルであり、ファイルがなくても動作はする。

- <http://www.be-interactive.org/works/ddr/azzuri_s.mp3>
- <http://www.be-interactive.org/works/ddr/drvbrmix_s.mp3>
- <http://www.be-interactive.org/works/ddr/onigirihc_s.mp3>
- <http://www.be-interactive.org/works/ddr/paranoiared_s.mp3>
- <http://www.be-interactive.org/works/ddr/smotsmremx_s.mp3>
- <http://www.be-interactive.org/works/ddr/XYZ_s.mp3>


## 参考

- <https://www.youtube.com/watch?v=Y5C3J2rx26U> … DDR のプレイ動画
- <https://ha-navi.com/flash-nitro> … Flash Player のサポート終了後、Flash を動作させるための選択肢解説
- <https://neos21.net/etc/ddr.html> … Neo's World - DreamDaemonRevolution ランキングページ


## Links

- [Neo's World](https://neos21.net/)


[![WTFPL](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png "WTFPL")](http://www.wtfpl.net/)
