# PowerPoint (VBA) による行き先表示器風の時計の製作

[![](https://img.youtube.com/vi/BRow4hzXKk0/0.jpg)](https://www.youtube.com/watch?v=BRow4hzXKk0)

![](https://github.com/7m4mon/ekimeihyo/blob/main/metro_hassyahyo_pptm.png)  

* 作者：7M4MON
* 作成環境：Microsoft PowerPoint 2010
* 想定解像度：1920 x 480 (ツイ廃液晶)

詳しい説明は以下  
http://nomulabo.com/hasshahyo_pptm/

パワーポイントで作成した駅名標です。  
駅名標の進行に合わせて発車メロディが鳴ります。  

* 東京メトロの行き先表示器風
* 先発の時刻は現在時刻を表示、次発は1分後
* 偶数分は荻窪 (M01) 行き、奇数分は新宿 (M08) 行き
* 毎00秒に発車状態になり走行音が流れる。（スライド３）
* しばらくすると近接状態になり「電車がまいります」が点滅表示され、近接案内が流れる（スライド１）
* 近接案内が終了すると、到着状態となり、到着案内→発車メロディ→発車案内が流れる。（スライド２）
* 偶数分は新宿３丁目駅、奇数分は赤坂見附駅の案内と発車メロディとした。
* 音源は「東京メトロ丸ノ内線 駅発車メロディー & 駅ホーム自動放送」を適宜編集して使用
* 日本語、英語の駅名表示切り替えは３秒毎
* フォントは、日本語が「A-OTF 新ゴ Pro M」、英語は「Frutiger LT Std 55 Roman」、ナンバリングは「Futura Std Book」
* 音源はマクロの上部で定数で定義していますが、以下のファイル名です。  
新宿三丁目A線【1番線】_荻窪行き_1.wav、赤坂見附A線【2番線】_新宿行き_1.wav、新宿三丁目A線【1番線】_荻窪行き_2.wav、赤坂見附A線【2番線】_新宿行き_2.wav、走行音_丸ノ内支線.wav   
スライドショーと同じフォルダに入れる必要があります。  
音源は「東京メトロ丸ノ内線 駅発車メロディー & 駅ホーム自動放送」から取り込んで適宜、分割結合をしています。


路線追加、レイアウト改善などの Fork / PullRequest は大歓迎です。
フォントがインストールされていないとレイアウトが崩れます。

## おまけ
JR東日本の山手線と総武線各駅停車の発車標も作ってみました。
力尽きたので、レイアウトのみです。
![](https://github.com/7m4mon/ekimeihyo/blob/main/jre_hasshahyo_yamanote.png)  
![](https://github.com/7m4mon/ekimeihyo/blob/main/jre_hasshahyo_sobu_local.png)  
