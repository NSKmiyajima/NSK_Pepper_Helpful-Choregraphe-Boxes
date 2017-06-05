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
  
■ Description of Box  
* PersonDetection box  
　1. Signal onStart of "Person Detection box". 
　2. Wait for the person to enter into sight. 
　3. Measure the distance to the detected person in the field of view with Zone. 
　4. For people who are close in distance to Zone 1, Zone 2, check if the face can be seen. 
　　# When you detect with Zone 3, measure the distance in meters and announce that "Please come a little closer". 
　6. If a face is detected, it is determined that a person can be detected, and output is output from onStopped. 
  
■ ボックスの説明  
* PersonDetectionボックス  
　1. 「PersonDetectionボックス」のonStartに信号を与えます。  
　2. 人物が視界の中に入るのを待機します。  
　3. 視界の中に検知した人物との距離をZoneで測ります。  
　4. Zone1, Zone2内の距離の近い人の場合、顔が見えるかどうかを確認します。  
　　 # Zone3で検知した場合、距離をメートルで測定し、「もう少し近くに来てください」とアナウンスをします。  
　6. 顔が検出されれば人を検知できたとして、onStoppedから出力が出ます。  
  
■盒说明  
* PersonDetection箱  
　1.给出了一个信号，以“PersonDetection盒”的调用onStart。  
　2.人们会等待进入视野。  
　3.测量谁在看在园区现场检测到人之间的距离。  
　4.1区，接近2区的距离，一个人的情况下，看是否面对的是可见的。  
　　# 如果在3区检测，距离以米为单位，并宣布“请再靠近一点点。”  
　6.脸上能如果检测来检测一个人，你会从onStopped输出。  
