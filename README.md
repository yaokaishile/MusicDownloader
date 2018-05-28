原来的QQMUsicDownloader，代码重写了，顺便改名叫MusicDownloader，应该会比之前的更加健壮了
## 功能 ##

 1. 下载QQ音乐**单曲**
 2. 下载QQ音乐**专辑**下所有歌曲
 3. 下载QQ音乐**歌单**下所有歌曲
 4. 下载网易云音乐**歌单**下所有歌曲
 5. 只下载网易云音乐歌单中**灰掉**的歌曲
 6. 音质支持高清、无损，付费音乐以及灰掉的也能下载
 7. 由于直接下载的MP3文件标签内容中的编码不一致会有乱码，所以在程序里将MP3标签头用unicode编码重新编辑了，并插入了封面图
 8. 要下载单曲以及专辑，请使用QQ音乐中的链接

## 提示 ##
  1. 不支持短链接，QQ音乐软件复制出来的链接是短链接，要复制到浏览器之后再把链接粘贴过来
  2. 代理选项只支持socks5，一般在国外才需要使用代理，代理设置后重启生效，网上找来的代理速度一般及其慢，基本无法工作，最好找国内好点的socks5代理，或者自己假设服务器
  3. MAC请自行编译，release中只有Windows版本，编译之前应该需要安装OpenSSL库

## 使用说明 ##

 参考 [http://z52c.com/musicdownloader/][1]

 


  [1]: http://z52c.com/musicdownloader/
