# Study-SonicPi  


Sonic Pi  
>The Live Coding Music Synth for Everyone.  
Welcome to the future of music.  
**Simple** enough for computing and music lessons.  
**Powerful** enough for professional musicians.  
**Free** to download with a friendly tutorial.  
**Diverse** community of over one million live coders.  

[http://sonic-pi.net/](http://sonic-pi.net/)  



> Sonic Piは、日本発で世界的に活用されているRuby言語（まつもとゆきひろ氏作）と音響合成言語のSuperCollider とQt等を使って作られています。  
プログラムで本格的に音を出し音楽とすることのできる環境の中では、容易さや音質の面で最も優れていると思われます。  
音を出し耳で確認しながらプログラミングができるので、英国の特にケンブリッジでは子供のプログラミング入門用(文法はほぼRuby)として大いに用いられているようで、世界中に広まりつつあります  

[http://www-b.uec.tmu.ac.jp/shakuhachi/SonicPi/](http://www-b.uec.tmu.ac.jp/shakuhachi/SonicPi/)  


SuperCollider のシンセが音を作っているっぽい。  
それは、SuperCollider が、操作する Client と、音を作る（シンセ？） Server が分かれていて、Client から、値を飛ばす構成になっているので、Sonic Pi でも、この Server を利用している。（？）  



---  

Python で使う  

[https://pypi.org/project/python-osc/](https://pypi.org/project/python-osc/)  

インストール  

```bash
pip(3) install python-sonic
```

音を鳴らす  
```python
from psonic import *

play(70)
```


---  

---  

### Ref  

Elixir と SuperCollider で音楽を奏でてみる(Qiita)
[https://qiita.com/reprimande/items/2e868e3368ae746e6a34](https://qiita.com/reprimande/items/2e868e3368ae746e6a34)  

