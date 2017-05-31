■ Steps for adding a box library  
　1. Download "***.cbl" from this page.  
　2. Select "Open box library" from within the chart.  
　3. Select the downloaded "***.cbl" and add it.  
  
■ ボックスライブラリの追加手順  
　1. 本ページより、「***.cbl」をダウンロードする  
　2. コレグラフ内から、「ボックスライブラリを開く」を選択  
　3. ダウンロードした「***.cbl」を選択し、追加する  
  
■ 指令盒库  
　1. 在这个页面，请下载“***.cbl”  
　2. 选择从Choregraphe“打开命令框库”  
　3. 选择“***.cbl”您下载的  
  
====================  
  
■ Procedure for using the box  
* Mattermost box  
　1. Open the setting screen of "Mattermost Box"  
　2. Please specify the login ID of Mattermost in "login id" of the variable.  
　3. Please specify Mattermost's login password in the variable "password".  
　4. In the variable 'username', specify the name of the person who sent the notification.  
　6. Specify the channel name to send the notification to the "channel" of the variable.  
　7. In the variable "channel id", specify the channel ID to send the notification.  
　8. For "variable url", specify "Webhook URL" with mattermost "inward web hook".  
　9. If you enter a value from "sendData Box" in box "onStart", notification is sent to mattermost and output from "onStopped"  
　　 # When an error occurs, an error log is output to the log of the chart and an output is output from "onError"  
  
* sendData box  
　1. In the variable "message", specify the message you want to notify.  
　2. The variable "sendImage" specifies whether or not to send the image file.  
　　 In case of True, send it. If it is False it will not be sent.  
　3. When set to "2.", please specify the path of the image file you want to send to "imagePath" of the variable.  
  
■ ボックスの利用手順  
* Mattermostボックス  
　1. 「Mattermostボックス」の設定画面を開く  
　2. 変数の「login id」に、MattermostのログインIDを指定して下さい。  
　3. 変数の「password」に、MattermostのログインPasswordを指定して下さい。  
　4. 変数の「username」に、通知を送信した人の名前を指定して下さい。  
　6. 変数の「channel」に、通知を送るチャンネル名を指定して下さい。  
　7. 変数の「channel id」に、通知を送るチャンネルIDを指定して下さい。  
　8. 変数の「url」に、mattermostの"内向きのウェブフック"で"Webhook URL"を指定して下さい。  
　9. ボックスの「onStart」に「sendDataボックス」から値を入力すると、mattermostに通知を送信して「onStopped」から出力されます  
　　 # エラー発生時はコレグラフのログにエラーログを出力し「onError」から出力が出ます  
  
* sendData ボックス  
　1. 変数の「message」に、通知したいメッセージを指定して下さい。  
　2. 変数の「sendImage」では、画像ファイルを送信するかどうかを指定します。  
　　 Trueの場合は送信する。Falseの場合は送信しません。  
　3. 「2.」でTrueにした場合は変数の「imagePath」に送信したい画像ファイルのパスを指定して下さい。  
  
■ 使用过程箱  
* Mattermost 箱  
　1. 打开“Mattermost箱”的设置屏幕  
　2. 在“登录ID”变量，你必须指定Mattermost的登录ID。  
　3. 变量的“密码”，你必须指定Mattermost的登录密码。  
　4. 在“用户名”的变量，你必须指定谁提交通知的人的姓名。  
　6. 在变量的“通道”，您必须指定频道的名称发送通知。  
　7. “通道ID”变量，你必须指定通道ID发送通知。  
　8. 变量“URL”，则必须在“向内网钩” mattermost的指定“网络挂接URL”。  
　9. 如果你输入从盒子“送出数据框”到“在onStart”的值，并传送到mattermost通知将从“onStopped”输出  
　　 # 当发生错误时这将是从错误日志输出到日志Koregurafu的“的onError”  
  
* sendData 箱  
　1. 在变量的“消息”，则必须指定要注意的消息。  
　2. 在变量“sendImage”，您可以指定是否发送图像文件。  
　　 在真实的情况下发送。不要在虚假的情况下发送。  
　3. “2”。如果你为True请指定路径要发送到的变量“的ImagePath”的图像文件。  
  
====================  
  
■ Image of BOX  
Please put Mattermost.png in the following directory.  
  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ BOXの画像  
Mattermost.pngを下記ディレクトリに置いて下さい。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ 图像的BOX  
在Mattermost.png放置到以下目录。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
