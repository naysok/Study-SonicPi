# Tutorial  

### Index  

- (1) ようこそ  
- (2) シンセ  
- (3) サンプル  
- (4) ランダム  
- (5) プログラミングの構造  
- (6) エフェクト  
- (7) コントロール  
- (8) データ構造  
- (9) ライブコーディング  
- (10) Time State  
- (11) MIDI  
- (12) OSC  
- (13) Multichannel Audio  


---  

### (1) ようこそ  

ループ演奏  
```rb
live_loop :flibble do

  # ここから
  play :C
  sleep 0.5
  play :D
  sleep 0.5
  play :E
  sleep 1
  # ここまで

end
```

---  

### (2) シンセ  


##### 2-1 初めての音  

音を出す  

play の後の数字は鍵盤の番号  
60 が、ド  
周波数でいうと 262Hz  

```rb
play 60
```


和音を出す  
```rb
play 72
play 75
play 79
```


メロディー  
```rb
play 72
sleep 1
play 75
sleep 1
play 79
sleep 1
```


アルペジオ  
```rb
play 72
sleep 0.5
play 75
sleep 0.5
play 79
sleep 0.5
```


コード  
```rb
play :C
sleep 0.5
play :D
sleep 0.5
play :Fs # F#
sleep 0.5
```

##### 2-2 シンセのオプション  






