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
* Speech Scenario Compile box  
　1. Open the "Speech Scenario Compile box" setting screen.  
　2. Please fill in the "word list" of the variable, separated by ";" for words you want Pepper to recognize.  
　3. In the variable "BNF_FILE_PATH", specify the absolute path to generate the BNF file.  
　4. In the variable "LCF_FILE_PATH", specify the absolute path to generate the LCF file.  
　5. When inputting a signal to "onStart" in the box, a BNF file is generated, compiled into an LCF file, and output from "onStopped".  
　　 # When an error occurs, an error log is output to the log of the chart and output comes out from "onError".  
  
* Custom Speech Reco box  
　1. Please specify the path of the LCF file to be used as the absolute path in the variable "LCF_FILE_PATH".  
　2. Other than that, it is the same as the conventional "Speech Reco. Box".  
  
■ ボックスの利用手順  
* Speech Scenario Compileボックス  
　1. 「Speech Scenario Compileボックス」の設定画面を開く  
　2. 変数の「Word list」に、Pepperに認識させたい単語を";"で区切って記入して下さい。  
　3. 変数の「BNF_FILE_PATH」に、BNFファイルを生成するパスを絶対パスで指定して下さい。  
　4. 変数の「LCF_FILE_PATH」に、LCFファイルを生成するパスを絶対パスで指定して下さい。  
　5. ボックスの「onStart」に信号を入力すると、BNFファイルを生成し、LCFファイルにコンパイルして「onStopped」から出力されます  
　　 # エラー発生時はコレグラフのログにエラーログを出力し「onError」から出力が出ます  
  
* Custom Speech Reco. ボックス  
　1. 変数の「LCF_FILE_PATH」に、使用するLCFファイルのパスを絶対パスで指定して下さい。  
　2. それ以外は従来の「Speech Reco. box」と変わりません。  
  
■ 使用过程箱  
* Speech Scenario Compile 箱  
　1. 打开设置“讲话场景编译箱”屏幕  
　2. 在变量的“词汇表”，你想要的字辣椒被识别，请填补“”隔开  
　3. 变量“BNF_FILE_PATH”，您必须指定路径，产生具有绝对路径的BNF文件  
　4. 变量“LCF_FILE_PATH”，您必须指定路径生成具有绝对路径的LCF文件  
　5. 如果输入信号框中的“在onStart”，生成一个BNF文件，在LCF文件编制是从“onStopped”输出  
　　 # 当发生错误时这将是从错误日志输出到日志Choregraphe的“的onError”  
  
* Custom Speech Reco. 箱  
　1. 为了变量“LCF_FILE_PATH”，你必须指定的路径要使用绝对路径的LCF文件  
　2. 否则，它不改变传统的“语音RECO。盒子”  
  
====================  
  
■ Variable input value in BOX.  
* Word list  
    * Try to recognize words from the list of words set in the parameters of the box.Please enter multiple words separated by ";".  
    * Example : "a;b;c;d;e"  
  
* BNF_FILE_PATH  
    * Please specify the absolute path to generate the BNF file.  
    * Example : "/home/nao/asr/test.bnf"  
  
* LCF_FILE_PATH  
    * Please specify the absolute path to generate the LCF file.  
    * Example : "/home/nao/asr/test.lcf"  
  
■ BOX内の変数入力値  
* Word list  
    * パラメータに設定されている単語のリストから単語を認識します。複数の単語を";"で区切って記入して下さい。  
    * Example : "a;b;c;d;e"  
  
* BNF_FILE_PATH  
    * BNFファイルを生成するパスを絶対パスで指定して下さい。  
    * Example : "/home/nao/asr/test.bnf"  
  
* LCF_FILE_PATH  
    * LCFファイルを生成するパスを絶対パスで指定して下さい。  
    * Example : "/home/nao/asr/test.lcf"  
  
■ 在BOX变量的输入值  
* Word list  
    * 单词的列表，这是在参数中设置将尝试从认识的单词。请填写由分离;多个单词“;”的。  
    * Example : "a;b;c;d;e"  
  
* BNF_FILE_PATH  
    * 请注明完整路径生成一个BNF文件。  
    * Example : "/home/nao/asr/test.bnf"  
  
* LCF_FILE_PATH  
    * 请注明完整路径生成一个LCF文件。  
    * Example : "/home/nao/asr/test.lcf"  
  
====================  
  
■ Image of BOX  
Please put compile.png in the following directory.  
  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ BOXの画像  
compile.pngを下記ディレクトリに置いて下さい。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
  
■ 图像的BOX  
在compile.png放置到以下目录。  
"C:\Program Files (x86)\Aldebaran\Choregraphe Suite 2.4\share\choregraphe\media\images\box"  
