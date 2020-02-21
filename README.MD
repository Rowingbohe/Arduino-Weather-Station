<h1 align="center"> Arduino Weather Station</h1>
<h2 align="center">This is an Arduino Weather Station Program.</h2>
<p>In this program,you can use your Arduino Uno Rev3 and DHT Tempture sensor with 1602A LCD monitor to make a weather station easily.This source come from https://miymakers.wordpress.com/ and in this course of study I find some wrong and fixed in this page.</p>
<p>This station will use 3.3V port on Arduino.</p>
<h3 align="center">Connect</h3>
<h4 align="center">LCD Connect</h4>
<p>D7- DIGITAL PIN 2</br>D6 �C 3</br>D5 �C 4</br>D4 �C 5</br>E �C 11</br>RS �C 12</br>VDD (+) RAIL BREADBOARD</br>A (+)RAIL BREADBOARD</br>VSS (-)RAIL BREADBOARD</br>K (-)RAIL BREADBOARD</br>RW (-)RAIL BREADBOARD</br>VO �C  Potentiometer Middle Pin</p>
<h4 align="center">DHT sensor Connect</h4>
<p>We will be perforated positive side and left to right a total of 4 pins(may be your only have 3 pins but that is better).</br>The first pin is VCC,can work on 3.3V to 5.5V</br>The second pin is DATA PIN,you need connect this pin to A1 port on board.</br>The third pin is empty (3 pins DHT sensor don't have this pin)</br>The fourth pin is GND</br>Caution!You need use this pin and in the orginal course of study,they teach you use third pin and that is WRONG!</p>
<h3 align="center">Flash the sourse to board</h3>
<p>And now,you need install DHT repo to your Arduino software,you can see a zip package named DHT.zip in this repo.Caution!You must install this package and if you don't install this you may be get so many errors </p>
<h3 align="center">congratulation!Now you can see Temp and Humidity data in your 1602A monitor throught adjustment potentiometer if you connect right!</h3>

<h2 align="center">����һ������ Arduino ����վ��С��Ŀ</h2>
<p>�����ͨ�������Ŀ���ɵ�ʹ����� Arduino Uno �� DHT ��ʪ�ȴ������Լ� 1602A ������������һ��С�� Arduino ����վ.����Ŀ��Դ������ https://miymakers.wordpress.com/ ������̳��г�����һ��С�����һ��ں���Ľ̳��о�����</p>
<p>������վ��ʹ��3.3V����.</p>
<h3 align="center">����</h3>
<h4 align="center">LCD ��ʾ��������</h4>
<p>D7 - 2 �Žӿ�</br>D6 �C 3 �Žӿ�</br>D5 �C 4 �Žӿ�</br>D4 �C 5 �Žӿ�</br>E �C 11 �Žӿ�</br>RS �C 12 �Žӿ�</br>VDD �����Դ����</br>A �����Դ����</br>VSS �����Դ����</br>K �����Դ����</br>RW �����Դ����</br>VO �C  ��λ�����м��</p>
<h4 align="center">DHT ������������</h4>
<p>�������кܶ�׵�һ��Ϊ���棬������һ����4�����ţ�������ֻ�����������Ǹ��ã�.</br>��һ�����Žӵ�Դ������������ѹ��Χ�� 3.3V �� 5.5V</br>�ڶ�������������ţ�����Ҫ�������ӵ� A1 �ӿ�</br>���������ǿ��ýţ������� DHT ֻ������������Ĵ�������û������ţ�</br>���ĸ��Žӵ�Դ����</br>ע�⣬ԭʼ�Ľ̳�������ѵ������Žӵ� A1 �ӿ��ϣ����Ǵ����</p>
<h3 align="center">��дԴ��</h3>
<p>���ڣ�����Ҫ�����Arduino��д�����а�װ�����е� DHT.zip ����Ŀ���.ע�⣬����밲װ����⣬��������ڱ�������г��ִ���</p>
<h3 align="center">��ϲ����������û����Ļ��������Ѿ�����ͨ��������λ��������Ļ����ʾ�������ˣ�</h3>

<h2 aligh="center">This is connect picture / ����ͼʾ</h2>
<img src="./connectteach.jpg" align="center">