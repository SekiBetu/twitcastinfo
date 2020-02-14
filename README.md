# twitcastinfo
获取twitcasting频道的历史直播信息（直播链接，直播时间，是否有录播，直播时长，直播标题，直播简介）

### 方法  
`./twitcastinfo.sh "频道号码"`  
### 示例  
`./twitcastinfo.sh "c:annuuuu_cas"`  
`./twitcastinfo.sh "https://twitcasting.tv/c:annuuuu_cas" > twitcastinfo_c：annuuuu_cas.txt`  
### 输出格式示例
直播链接(直播时间)	是否有录播或需要密码(直播时长)	直播标题(直播简介)
```
/c:annuuuu_cas/movie/557767840(2019/07/25 22:00:45)	RECORD(2:11:49)	Radio 寝落ち◎初見さん◎ #557767840
/c:annuuuu_cas/movie/557710632(2019/07/25 16:00:08)	RECORD(1:32:27)	クリア【ベリーリトルナイトメア】
/c:annuuuu_cas/movie/557235222(2019/07/22 22:31:40)	RECORD(1:38:31)	Radio 寝落ち◎初見さん◎ #557235222
/c:annuuuu_cas/movie/557130809(2019/07/22 07:50:27)	RECORD(1:07:21)	Radio 支度しながら/BGM◎ #557130809
/c:annuuuu_cas/movie/557046765(2019/07/21 22:04:06)	RECORD(1:50:11)	Radio 寝落ち◎初見さん◎ #557046765
/c:annuuuu_cas/movie/557045762(2019/07/21 22:01:16)	RECORD(02:42)	Radio 初見さん◎雑談◎ #557045762
/c:annuuuu_cas/movie/556957734(2019/07/21 12:47:34)	RECORD(30:07)	Radio 寝起きボイス✧作業用BGM◎ #556957734
/c:annuuuu_cas/movie/556952041(2019/07/21 11:47:25)	RECORD(1:00:01)	Radio 寝起きボイス✧作業用BGM◎ #556952041
/c:annuuuu_cas/movie/556791501(2019/07/20 17:17:54)	RECORD(2:00:03)	Radio 初見さん◎BGM◎ #556791501
```

# twitcastcomment
获取twitcasting直播的历史评论信息（评论链接，评论时间，评论者名称，评论者链接，评论内容）

### 方法  
`./twitcastcomment.sh "直播链接"`  
### 示例  
`./twitcastcomment.sh "c:annuuuu_cas/movie/557767840"`  
`./twitcastcomment.sh "https://twitcasting.tv/c:annuuuu_cas/movie/557767840" > twitcastcomment_c：annuuuu_cas_movie_557767840.txt`  
### 输出格式示例
评论链接(评论时间)	评论者名称(评论者链接)	评论内容
```
/c:annuuuu_cas/comment/557767840-16488184923(Fri, 26 Jul 2019 00:12:18 +0900)	れん(@c:aaalen)	ゆっくりねてね！
/c:annuuuu_cas/comment/557767840-16488184254(Fri, 26 Jul 2019 00:12:14 +0900)	瀬乃くん☀ﾟ⚪️🐁🍡🔔(@SeNonkun)	ﾊﾞｲﾊﾞｲ(ヾ(´・ω・｀)
/c:annuuuu_cas/comment/557767840-16488183533(Fri, 26 Jul 2019 00:12:09 +0900)	エスタ(@Esta00Rossa1030)	おやすみ
/c:annuuuu_cas/comment/557767840-16488182475(Fri, 26 Jul 2019 00:12:03 +0900)	レンレン☀️゜(@c:200647)	まだ寝ないけどね！
/c:annuuuu_cas/comment/557767840-16488181590(Fri, 26 Jul 2019 00:11:58 +0900)	たくみ☀️゜(@takumi192525)	おやぷみ～
/c:annuuuu_cas/comment/557767840-16488180386(Fri, 26 Jul 2019 00:11:52 +0900)	￡sei(@seielis)	おやすみー！
/c:annuuuu_cas/comment/557767840-16488180154(Fri, 26 Jul 2019 00:11:50 +0900)	れん(@c:aaalen)	トコトコトコドテー
/c:annuuuu_cas/comment/557767840-16488177525(Fri, 26 Jul 2019 00:11:35 +0900)	れん(@c:aaalen)	あんちゃんとねないもーん
/c:annuuuu_cas/comment/557767840-16488174726(Fri, 26 Jul 2019 00:11:19 +0900)	🐟 ししゃも♂🐟(@HJdLjQagribJXxD)	おつ
/c:annuuuu_cas/comment/557767840-16488174609(Fri, 26 Jul 2019 00:11:18 +0900)	さこ☀︎*@倭国☀️゜(@c:Neo9369)	おつあん
/c:annuuuu_cas/comment/557767840-16488173781(Fri, 26 Jul 2019 00:11:14 +0900)	れん(@c:aaalen)	ねてた
/c:annuuuu_cas/comment/557767840-16488172785(Fri, 26 Jul 2019 00:11:08 +0900)	れん(@c:aaalen)	おつあん！
/c:annuuuu_cas/comment/557767840-16488170605(Fri, 26 Jul 2019 00:10:56 +0900)	レンレン☀️゜(@c:200647)	おつあんー♪☆♪
/c:annuuuu_cas/comment/557767840-16488167926(Fri, 26 Jul 2019 00:10:40 +0900)	🐟 ししゃも♂🐟(@HJdLjQagribJXxD)	わこ
/c:annuuuu_cas/comment/557767840-16488164224(Fri, 26 Jul 2019 00:10:18 +0900)	Y(@yuu______ta)	僕の楽しみは君なんよああ<img class="emoji" src="/img/e/k/32E.gif" width="14" height="15" />
```

# twitcast   
将历史直播信息保存到twitcastinfo_频道名称.log，将相应的历史评论信息保存到以频道名称命名的文件夹中的相应.log文件中  
### 方法  
`./twitcast.sh "频道号码" "获取此时间之后的评论"`  
### 示例  
`./twitcast.sh "c:annuuuu_cas" "2019/07/25 22:00:45"`   
`./twitcast.sh "https://twitcasting.tv/c:annuuuu_cas" "2019/07/25 22:00:45"`  
