・何が起きているかを説明せよ。

trick関数により、char bの後のパディング領域に書き込みがされているため、printfの出力が同じであるにも関わらず、2回目のmemcmpでは、falseが出力される。

・上記の現象から構造体を比較する際になぜメンバを逐次比較する必要があるかについて記載せよ。

printf だけでは、２つの構造体の中身が異なるにも関わらず、見かけ上同じに見えてしまうことがあるから。

・struct_compare.c にコードを追加して、trickが行った細工 を見つけよ。

bの後のパディング領域にhelloと書かれている。

