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
　1. Open the "Database box" setting screen.  
　2. In the variable "DB_FILE_PATH", specify a database file with an absolute path.  
　3. Write the SQL statement you want to execute in the variable "SQL".  
　4. When you input a signal to "onStart" in the box, the SQL execution result is output from "onStopped".  
　　 # When an error occurs, an error log is output to the log of the chart and output comes out from "onError".  
  
■ ボックスの利用手順  
　1. 「Databaseボックス」の設定画面を開く  
　2. 変数の「DB_FILE_PATH」に、絶対パスでデータベースファイルを指定する  
　3. 変数の「SQL」に、実行したいSQL文を記入する  
　4. ボックスの「onStart」に信号を入力すると、SQL実行結果が「onStopped」から出力されます  
　　 # エラー発生時はコレグラフのログにエラーログを出力し「onError」から出力が出ます  
  
■ 使用过程箱  
　1. 打开“数据库盒子”的配置屏幕  
　2. 该变量“DB_FILE_PATH”，你必须指定数据库文件的绝对路径  
　3. 为了变量“SQL”，填写您要运行的SQL语句  
　4. 如果输入信号到盒子“在onStart”，SQL执行结果是从“onStopped”输出  
　　 # 当发生错误时这将是从错误日志输出到日志Choregraphe的“的onError”  
  
====================  
  
■ Variable input value in BOX.  
* DB_FILE_PATH  
    * Please specify the database file with absolute path.  
    * Example : "/home/nao/db/test.db"  
  
* SQL  
    * Please fill in the SQL statement you want to execute.  
    * Example : "SELECT * FROM TEST"  
  
■ BOX内の変数入力値  
* DB_FILE_PATH  
    * 絶対パスでデータベースファイルを指定してください。  
    * 例 : "/home/nao/db/test.db"  
  
* SQL  
    * 実行したいSQL文を記入してください。  
    * 例 : "SELECT * FROM TEST"  
  
■ 在BOX变量的输入值  
* DB_FILE_PATH  
    * 请指定数据库文件的绝对路径。  
    * 案件 : "/home/nao/db/test.db"  
  
* SQL  
    * 请您要运行的SQL语句填充。  
    * 案件 : "SELECT * FROM TEST"  
  
====================  
  
■ Image of BOX  
Please put database.png in the following directory.  
  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ BOXの画像  
database.pngを下記ディレクトリに置いて下さい。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ 图像的BOX  
在database.png放置到以下目录。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
