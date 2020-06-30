# gtts ile yazıları seslendirme
<p>
gtts diğer ismi ile Google Text-to-Speech elimden geldiğince açıklıyacağım.
<p>

# Kurulum
<p> 
gtts çalıştırmak için öncelikle cihazınızda pip ve python 2.7 ve üzeri bir sürümünün kurulu olması gereklidir.
</p>

$ pip install gTTS

veya

$ sudo pip install gTTS

Hızlı test için 

$ gtts-cli 'hello world' --output helloworld.mp3

 Modül yazımı ise 

from gtts import gTTS
tts = gTTS('hello world')
tts.save('helloworld.mp3')