# Uykulu araç kullanmayın.

## Fikir ve İlham

Bu web uygulaması, [OpenCV ile Sürücü Uyuşukluk Tespiti](https://www.youtube.com/watch?v=Q23K7G1gJgY)'den ilham almıştır.

## Uygulama ve kullanım

Biz insanız, yoruluruz, uykumuz gelir. Bölünmemiş dikkatimizi gerektiren en önemli zamanlardan biri, araba kullandığımız zamandır.
Bu uygulama uykulu olup olmadığınızı tespit edecek ve sizi basit ve etkili bir şekilde uyandırmak için bir alarm sesi çalacaktır.

## Yapılandırma

asset/js/main.js dosyasında "eyesClosedThreshold"u 0,5 ile 1 arasında değişen kesirli bir değere atayın. 
Aynı dosyada, alarmın çalması için gereken sürenin ardından milisaniye cinsinden `timeThreshold` değerini değiştirin. 
Şu anda algoritma 500 milisaniye bekliyor ve ardından alarmı çalıyor ancak bu ayarı değiştirebilirsiniz.


## Uyarılar 

1. Bu web uygulamasının çalışması için kameraya ihtiyacı var. Açıkçası kamera iznine de ihtiyacı olacak.
2. Alarm sesi sizi uyandırmak içindir, dolayısıyla oldukça yüksektir.
3. İzleyicinin çalışması için yüzünüzde düzgün ve eşit bir aydınlatmaya ihtiyacı var.