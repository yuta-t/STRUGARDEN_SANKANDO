### 起動パス
```
ST_224.exe MH:12 F:Tex.bin;191 F:TexInfo.bin;191 F:Anim.bin;024 F:AnimInfo.bin;024 F:Clump.bin;128 F:ClumpInfo.bin;128 F:IdTbl.bin;002 F:IdTblInfo.bin;002 F:Prt.bin;011 F:PrtInfo.bin;011 F:SE.bin;002 F:SEInfo.bin;002 F:Window.bin;100 F:WindowInfo.bin;100 WINDOWMODE SCREENMODE:800_600_16 DS:1_1_1_1 IP:1:202.210.185.89:8101 IP:1:202.210.185.89:8102 IP:1:202.210.185.89:8103 IP:1:202.210.185.89:8104 IP:0:202.210.185.91:8101 IP:0:202.210.185.91:8102 IP:0:202.210.185.91:8103 IP:0:202.210.185.91:8104 GG_MODE CLIENT_FLAG:1 106683700@HG 96968946 OTP:d8d693552e7cd99b7e5d31c0be532f2b
```
- `IP:1:202.210.185.89:8101`～ `IP:1:202.210.185.89:8104`～がレナングルムサーバーなので、適宜`127.0.0.1`に変更したりしよう
- `202.210.185.91`の方はナテルアサーバー。もしかしたら片方ローカル開発、片方共有サーバーとかにすると楽かもね
- 末尾の`106683700@HG`はID、`96968946`はパスワード。`OTP:～～`はワンタイムパスワード。IDとパスワードは変えても起動できる。OTPは文字列長さだけ見てる模様？ないと起動しないので適当に入れておく。

### レナングルムをローカル向きにした版
```
ST_224.exe MH:12 F:Tex.bin;191 F:TexInfo.bin;191 F:Anim.bin;024 F:AnimInfo.bin;024 F:Clump.bin;128 F:ClumpInfo.bin;128 F:IdTbl.bin;002 F:IdTblInfo.bin;002 F:Prt.bin;011 F:PrtInfo.bin;011 F:SE.bin;002 F:SEInfo.bin;002 F:Window.bin;100 F:WindowInfo.bin;100 WINDOWMODE SCREENMODE:800_600_16 DS:1_1_1_1 IP:1:127.0.0.1:8101 IP:1:127.0.0.1:8102 IP:1:127.0.0.1:8103 IP:1:127.0.0.1:8104 IP:0:202.210.185.91:8101 IP:0:202.210.185.91:8102 IP:0:202.210.185.91:8103 IP:0:202.210.185.91:8104 GG_MODE CLIENT_FLAG:1 alanlei 123 OTP:aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa
```
ID:alanlei, PASS:123 でのログインとなる。
