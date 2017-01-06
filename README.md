# blinkled

raspberry pi3用2色発光LEDの制御用デバイスドライバ  

pin22 出力１  
pin15 出力２  
pin40 GND  
出力1,2をLEDのアノードに、GNDをカソードに接続する  

使い方  
'$cd blinkled'  
'$make'  
'$insmod myled.ko'  
'$sudo chmod 666 /dev/myled0'  

'$echo 1 > /dev/myled0'  
出力１に接続したLEDが発光  

'$echo 0 > /dev/myled0'  
出力２に接続したLEDが発光  

動画  
https://youtu.be/GNHn6Q6AKCo
