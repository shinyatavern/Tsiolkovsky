# Tsiolkovsky
### 1.Tsiolkovsky.pdf
   ツィオルコフスキーの公式を題材に色々考察したやや稚拙(グラフが見づらい)な論文です。
### 2.Tsiolkovsky.c
   4次のルンゲクッタ法を用いてロケットの1次元軌道の数値計算ができます。  
   コンパイル後
   ```
   ./a.out > data.dat
   u e dt t
   ```
  で data.dat に軌道データが出力されます。
  ここで、u,e,dt,t は標準入力で  
  u : 推進剤を放出する相対速度  
  e : 単位時間あたりに放出する推進剤の質量  
  dt : 数値計算における差分方程式の時間幅(一般に時間幅が小さいほど精度は良くなる。小さすぎてはいけない。)  
  t : 発射を0sとして計測する時間、つまり時刻の最大値
