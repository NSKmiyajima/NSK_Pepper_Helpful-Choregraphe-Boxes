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
* Server box  
　1. Open the "server box" setting screen  
　2. In the variable "PORT", specify the port number to be used for socket communication on the receiving side.  
　3. When inputting a signal to "onStart" in the box, it outputs the standby state to the log and is output from "onStopped"  
  
　* Client box  
　1. Open the setting screen of "client box"  
　2. In the variable "HOST", specify the IP address of the server side of the socket communication.  
　3. In the variable "PORT", specify the port number of the socket communication server. 
　4. In the variable "FILE_PATH", specify the absolute path of the file to be sent.  
　5. When you input a signal to "onStart" in the box, the file is sent to server and output from "onStopped".  
  
※  The transmitted file is transferred under "/ tmp / socket_HHMMSS /" directory.
  
■ ボックスの利用手順  
* serverボックス  
　1. 「serverボックス」の設定画面を開く  
　2. 変数の「PORT」に、受け側のソケット通信をする際に使用するポート番号を指定する。  
　3. ボックスの「onStart」に信号を入力すると、ログに待機状態を出力してclient側からの通信を待機します。  
  
* clientボックス  
　1. 「clientボックス」の設定画面を開く  
　2. 変数の「HOST」に、ソケット通信のサーバーのIPアドレスを指定する。  
　3. 変数の「PORT」に、ソケット通信のサーバーのポート番号を指定する。  
　4. 変数の「FILE_PATH」に、送信するファイルの絶対パスを指定する。  
　5. ボックスの「onStart」に信号を入力すると、サーバーにファイルを送信して「onStopped」から出力されます。  
  
※送信したファイルは"/tmp/socket_HHMMSS/"ディレクトリ配下に転送されます。  
  
■ 使用过程箱  
* server 箱  
　1. 打开“server箱”的设置屏幕  
　2. 到可变的“PORT”，以指定的端口号使用时套接字通信的接收侧。  
　3. 如果输入信号框中的“在onStart”，并输出日志处于待机状态将从“onStopped”输出。  
  
* client 箱  
　1. 打开“client箱”的设置屏幕  
　2. 该变量的“HOST”，指定socket通信的服务器端的IP地址。  
　3. 该变量的“PORT”，指定socket通信服务器的端口号。  
　4. 该变量的“FILE_PATH”，指定要发送的文件的完整路径。  
　5. 如果输入信号框中的“在onStart”，并发送文件到服务器会从“onStopped”输出。  
  
※提交的文件将在“/ tmp目录/ socket_HHMMSS/”目录下被转移到。  
  
====================  
  
■ Image of BOX  
Please put server.png and client.png in the following directory.  
  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ BOXの画像  
server.pngとclient.pngを下記ディレクトリに置いて下さい。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ 图像的BOX  
放置server.png和client.png到以下目录。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
