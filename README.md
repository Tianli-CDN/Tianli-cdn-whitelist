# Tiancdn白名单目录  [![afadian](https://img.shields.io/badge/爱发电-@Tianli0-8F6ADB?style=flat-square)](https://afdian.net/@Tianli0)


后端：https://github.com/Tianli-CDN/cdn-server （来个Star,QAQ,不要...不要逼我求你！！！）

每2小时与服务器进行一次白名单同步

1. 如何使用？

   与往常一样。

2. 如何加入白名单？

   根据仓库json文件提交PR即可，如果未进入白名单，那么你将会被301到任意可以使用的镜像节点。

3. 白名单条件是什么？

   网站不违规违法，且github或者博客地址要有显著贡献，例如原创文章数量以及开源仓库数量。（无固定标准）

## 图片处理

1. 图片压缩，图片可以转webp，需跟随参数`?webp=true`

2. 图片主色调获取，需跟随参数`?get=theme`

   ```json
   {
   "theme": "#eaeaed"
   }
   ```

3. 图片高度宽度获取，需跟随参数`?get=size` 

   ```json
   {
   "width": 1660,
   "height": 302
   }
   ```

4. 服务器将自行对文件内容进行审核，如果出现违规（包括图片与词），该文件会被自动列入黑名单。

## 当前缓存周期：6H（指定版本号为7D）

## 清除缓存API：

GET [http://cdn1.tianli0.top/api/clear_cache?path=/gh/114514](http://cdn1.tianli0.top/api/clear_cache?path=/gh/114514)

path：路径

哦对了，饿饿！！！


