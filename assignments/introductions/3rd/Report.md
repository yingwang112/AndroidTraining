Assignment Report for 1.3

3.(課題)作成した apk ファイルの中にあるファイル・ディレクトリを列挙してください。
90201687n:AndroidTraining ying.wang$ unzip homework01.apk 
Archive:  homework01.apk
  inflating: res/layout/activity_main.xml  
  inflating: res/menu/main.xml       
  inflating: AndroidManifest.xml     
 extracting: resources.arsc          
 extracting: res/drawable-hdpi/ic_launcher.png  
 extracting: res/drawable-mdpi/ic_launcher.png  
 extracting: res/drawable-xhdpi/ic_launcher.png  
 extracting: res/drawable-xxhdpi/ic_launcher.png  
  inflating: classes.dex             
  inflating: META-INF/MANIFEST.MF    
  inflating: META-INF/CERT.SF        
  inflating: META-INF/CERT.DSA

4.(課題)上記で列挙したファイル・ディレクトリについて、どのような役割を持っているか説明してください。

/layout/activity_main.xml
==> [UIデザイン]紐づいているものはMainActivityクラスと画面レイアウトファイルです。
     activity_main.xmlを変更するとアプリケーション画面に反映したのです。
　   画面に表示できる部品はたくさんの種類があります。（ボタン）　

res/menu/main.xml
==> メニューの設定

AndroidManifest.xml
==> マニフェストファイルです。Activityをはじめさまざまな情報がこのファイルにまとめられています。

resources.arsc          
==> リソースファイル　 

drawable(画面ファイル「.png,.jpg,.gif」や形状などを定義したXMLファイル )  
res/drawable-hdpi/ic_launcher.png 
==> 高解像度扱いの画像を格納( 240dpi, 72px)   
 
res/drawable-mdpi/ic_launcher.png
==> 中解像度扱いの画像を格納( 160dpi, 48px) 

res/drawable-xhdpi/ic_launcher.png ( 320dpi,96px)  
==> 超高い解像度扱いの画像を格納 

res/drawable-xxhdpi/ic_launcher.png( 480dpi,148px)   
==> 一番高い解像度扱いの画像を格納

classes.dex
==> Dalvik VMのバイトコードです。バイナリファイルなので、そのままでは中身を読むことができないです。
　　そこで、baksmaliというツールを使います。鄂ｲ蜷肴ｸ医∩繧｢繝励Μ縺ｮ菴懈��

META-INF(署名関係ファイル)
   * META-INF/MANIFEST.MF  ==>  定義
   * META-INF/CERT.SF      ==>  ( .sf = signature file )apkファイル中で全部のファイルとHash Valueを表示する 
   * META-INF/CERT.DSA     ==>  検証側でDSAサポートするようです。　























