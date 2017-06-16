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
* Receiver box  
　1. Open the "Receiver box" setting screen  
　2. Set the port number used for communication in "PORT" of the variable.  
　3. When inputting a signal to "onStart" in the box, it outputs a standby state to the log and waits for communication from the transmitter side.  
  
　* Transmitter box  
　1. Open the setting screen of "Transmitter box"  
　2. To the "IP" of the variable, specify the IP address of the Receiver box side (reception side).  
　3. Set the port number to be used for communication in the variable "PORT".  
　4. In the variable "FROM", specify the path of the file to be sent.  
　5. To the "TO" of the variable, specify the path of the file transfer destinatio  
　6. When you input a signal to "onStart" in the box, the file is sent to Receiver and output from "onStopped".  
  
■ ボックスの利用手順  
* Receiverボックス  
　1. 「Receiverボックス」の設定画面を開く  
　2. 変数の「PORT」に、通信に用いるポート番号を設定する。  
　3. ボックスの「onStart」に信号を入力すると、ログに待機状態を出力してTransmitter側からの通信を待機します。  
  
* Transmitterボックス  
　1. 「Transmitterボックス」の設定画面を開く  
　2. 変数の「IP」に、Receiverボックス側(受信側)のIPアドレスを指定する。  
　3. 変数の「PORT」に、通信に用いるポート番号を設定する。  
　4. 変数の「FROM」に、送信するファイルのパスを指定する。  
　5. 変数の「TO」に、ファイルの転送先のパスを指定する。  
　6. ボックスの「onStart」に信号を入力すると、Receiverにファイルを送信して「onStopped」から出力されます。  
  
■ 使用过程箱  
* Receiver 箱  
　1. 打开“Receiver箱”的设置屏幕  
　2. 到可变的“PORT”，设置要被用于通信的端口号。  
　3. 如果输入信号框中的“在onStart”，然后等待来自发射机端输出通信待机状态到日志中。  
  
* Transmitter 箱  
　1. 打开“Transmitter箱”的设置屏幕  
　2. 到“IP”的变量的，指定接收盒侧（接收侧）的IP地址。  
　3. 到可变的“PORT”，设置要被用于通信的端口号。  
　4. 在变量“FROM”，指定要发送的文件的路径。  
　5. 在变量的“TO”，指定文件路径的目的地。
　6. 如果输入信号框中的“在onStart”，并将文件发送到接收器将是从“onStopped”输出。  
  
====================  
  
■ Image of BOX  
Please put receiver.png and transmitter.png in the following directory.  
  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ BOXの画像  
receiver.pngとtransmitter.pngを下記ディレクトリに置いて下さい。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ 图像的BOX  
放置receiver.png和transmitter.png到以下目录。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
