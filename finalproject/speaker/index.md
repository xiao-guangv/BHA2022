### 1th May ~
#### Making seperate speakers

I would like to build speakers talking to E. coli like these sketches.<br>
こういう感じで、大腸菌に話しかけるスピーカーを作りたい。<br>
<img width="80%" alt="img" src="images/IMG_4475.jpeg"><br>
<img width="80%" alt="img" src="images/IMG_4609.jpeg"><br>

This time, I will use Arduino and DFPlayer mini.<br>
Arduinoと、DFPlayer miniを使うことにする。<br>
[DFPlayer Official site 公式サイト](https://wiki.dfrobot.com/DFPlayer_Mini_SKU_DFR0299#Sample_Code)<br>
The wiring looks like this.<br>
配線はこんな感じ。
<img width="80%" alt="img" src="images/03.png"><br>

To use DFPlayer mini, you have to import the libraries.<br>
DFPlayerのライブラリをインポートする。<br>
[DFPlayer library](https://github.com/DFRobot/DFRobotDFPlayerMini)<br>
<img width="90%" alt="img" src="images/01.png"><br>

After downlaiding ZIP file, unzip it.<br>
download ZIPしたら、ZIPを解凍する。

Add the unzip folder to your Arduino libraries folder.<br>
自分のPC内で、Arduino > Libraries　に、解凍したフォルダを追加すればOK。<br>
<img width="90%" alt="img" src="images/02.png"><br>

