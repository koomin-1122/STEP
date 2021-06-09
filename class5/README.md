# Week5 Homework
巡回セールスマン問題(TCP)に挑戦！

## プログラムの説明
greedyのアルゴリズムと、2-opt法のようなものを組み合わせた。<br>
two-opt関数では、交差しているかどうかに関わらず今つながっている辺よりも短いものがあれば繋ぎ変えている。

## スコア
|                     |greedy+2-opt (mine)<br>start with conter point| greedy+2-opt (mine) | greedy | Simulated Annealing | 
| ---------------     | :-------------------------------------------:| :-----------------: | :----: | :-----------------: | 
| input_0.csv (n=5)   |3418.10                                       |3418.10              |3418.10 |3291.62              | 
| input_1.csv (n=8)   |4019.57                                       |3832.29              |3832.29 |3778.72              | 
| input_2.csv (n=16)  |4670.27                                       |4994.89              |5449.44 |4494.42              | 
| input_3.csv (n=64)  |8736.94                                       |8970.05              |10519.16|8150.91              | 
| input_4.csv (n=128) |11216.04                                      |11489.79             |12684.06|10675.29             | 
| input_5.csv (n=512) |21536.66                                      | 21376.27            |25331.84|21119.55             | 
| input_6.csv (n=2048)|42596.79                                      | 42712.37            |49892.05|44393.89             | 