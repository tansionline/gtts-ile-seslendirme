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

<h3>Hızlı test için </h3>

$ gtts-cli 'hello world' --output helloworld.mp3

 <h3>Modül yazımı ise </h3>

from gtts import gTTS

tts = gTTS('hello world')

tts.save('helloworld.mp3')