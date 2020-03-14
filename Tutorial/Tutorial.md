# 使用指南

VideoSrt 利用公共云服务的接口，实现快速、批量的识别媒体文件语音，为媒体文件自动创建中/英文字幕文件。

VideoSrt 本身开源免费软件，但由于使用了第三方公共云服务的接口，所以你需要在相应的平台开通服务，然后再软件中进行配置，方可正常使用。

目前 VideoSrt 使用了 [阿里云OSS对象存储](https://www.aliyun.com/product/oss?spm=5176.12825654.eofdhaal5.13.e9392c4aGfj5vj&aly_as=K11FcpO8)、[阿里云录音文件识别](https://ai.aliyun.com/nls/filetrans?spm=5176.12061031.1228726.1.47fe3cb43I34mn) 、[百度翻译](http://api.fanyi.baidu.com/api/trans/product/index)、[腾讯云翻译](https://cloud.tencent.com/product/tmt) 的相关云服务接口。

- [阿里云OSS对象存储](https://www.aliyun.com/product/oss?spm=5176.12825654.eofdhaal5.13.e9392c4aGfj5vj&aly_as=K11FcpO8)
- [阿里云录音文件识别](https://ai.aliyun.com/nls/filetrans?spm=5176.12061031.1228726.1.47fe3cb43I34mn)（试用版每日 2小时 免费额度）
- [百度翻译](http://api.fanyi.baidu.com/api/trans/product/index)（标准版免费，高级版每月 200 万字免费）
- [腾讯云翻译](https://cloud.tencent.com/product/tmt)（每月免费额度 500万 字符）

[阿里云录音文件识别](https://ai.aliyun.com/nls/filetrans?spm=5176.12061031.1228726.1.47fe3cb43I34mn)、[百度翻译](http://api.fanyi.baidu.com/api/trans/product/index)、[腾讯云翻译](https://cloud.tencent.com/product/tmt) 等服务目前都有一定的免费额度，个人普通的需求量，使用软件可以做到基本零付费的。

综上所述，在使用 VideoSrt 前，你需要先开通相关的云服务。

开通教程，请往下看。

<br />

<a name="48Ozo"></a>
### 阿里云服务开通与配置

<a name="5VtUU"></a>
#### 1. 注册阿里云账号，并完成账号实名认证
<a name="3l2l6"></a>
#### 2. 开通访问控制
<a name="rqmmc"></a>
#### 3. 开通OSS对象存储
<a name="yKhSA"></a>
#### 4. 开通智能语音交互
<a name="KyqWk"></a>
#### 5. 设置软件配置

<a name="W4NEk"></a>
### 视频教程
[![阿里云操作22_音频.h265.mp4 (35.41MB)](https://cdn.nlark.com/yuque/0/2019/jpeg/695280/1577244187488-b1e5879f-c8ed-4b50-b692-0277e568da7c.jpeg?x-oss-process=image/resize,h_450)](https://www.yuque.com/viggo-t7cdi/videosrt/em4n10?_lake_card=%7B%22status%22%3A%22done%22%2C%22name%22%3A%22%E9%98%BF%E9%87%8C%E4%BA%91%E6%93%8D%E4%BD%9C22_%E9%9F%B3%E9%A2%91.h265.mp4%22%2C%22size%22%3A37126454%2C%22percent%22%3A0%2C%22id%22%3A%22I15Y8%22%2C%22videoId%22%3A%229e3f4490299c4afb8e099a55613afc08%22%2C%22aliyunVideoSrc%22%3Anull%2C%22taobaoVideoId%22%3A%22248967970649%22%2C%22uploaderId%22%3A695280%2C%22authKey%22%3A%22YXBwX2tleT04MDAwMDAwMTImYXV0aF9pbmZvPXsidGltZXN0YW1wRW5jcnlwdGVkIjoiZDVlNDMyNGQ4YWU2MmY5MjU0ZjQ5YWRmZjE2MDU3NWMifSZkdXJhdGlvbj0mdGltZXN0YW1wPTE1ODQwODE1MTY%3D%22%2C%22docUrl%22%3A%22https%3A%2F%2Fwww.yuque.com%2Fviggo-t7cdi%2Fvideosrt%2Fem4n10%22%2C%22coverUrl%22%3A%22https%3A%2F%2Fcdn.nlark.com%2Fyuque%2F0%2F2019%2Fjpeg%2F695280%2F1577244187488-b1e5879f-c8ed-4b50-b692-0277e568da7c.jpeg%22%2C%22card%22%3A%22video%22%7D#I15Y8)

<a name="JMPz9"></a>
### 
<a name="RFxDq"></a>
### 
<a name="DglM5"></a>
### 百度翻译服务开通与配置  

<a name="hdPlv"></a>
#### 1.注册百度账号
<a name="BXnae"></a>
#### 2.开通百度翻译 “通用翻译API”服务
<a name="zqqda"></a>
#### 3.设置软件配置

<a name="Z6OzH"></a>
### 视频教程

**(仅适用0.2.6及以下版本)**<br />**
[![百度翻译-加背景.h265.mp4 (15MB)](https://cdn.nlark.com/yuque/0/2019/jpeg/695280/1577591011002-fe368e03-0d82-45f9-a496-7792d25c9076.jpeg?x-oss-process=image/resize,h_450)](https://www.yuque.com/viggo-t7cdi/videosrt/em4n10?_lake_card=%7B%22status%22%3A%22done%22%2C%22name%22%3A%22%E7%99%BE%E5%BA%A6%E7%BF%BB%E8%AF%91-%E5%8A%A0%E8%83%8C%E6%99%AF.h265.mp4%22%2C%22size%22%3A15732913%2C%22percent%22%3A0%2C%22id%22%3A%22EUP2e%22%2C%22videoId%22%3A%22c0057ec8d5394b08b77dbf856131db07%22%2C%22aliyunVideoSrc%22%3Anull%2C%22taobaoVideoId%22%3A%22249300137686%22%2C%22uploaderId%22%3A695280%2C%22authKey%22%3A%22YXBwX2tleT04MDAwMDAwMTImYXV0aF9pbmZvPXsidGltZXN0YW1wRW5jcnlwdGVkIjoiZDVlNDMyNGQ4YWU2MmY5MjU0ZjQ5YWRmZjE2MDU3NWMifSZkdXJhdGlvbj0mdGltZXN0YW1wPTE1ODQwODE1MTY%3D%22%2C%22docUrl%22%3A%22https%3A%2F%2Fwww.yuque.com%2Fviggo-t7cdi%2Fvideosrt%2Fem4n10%22%2C%22coverUrl%22%3A%22https%3A%2F%2Fcdn.nlark.com%2Fyuque%2F0%2F2019%2Fjpeg%2F695280%2F1577591011002-fe368e03-0d82-45f9-a496-7792d25c9076.jpeg%22%2C%22card%22%3A%22video%22%7D#EUP2e)


更多教程正在制作 ..... 

如你在使用过程中出现问题或疑问，可以加入QQ交流群（[109695078](https://jq.qq.com/?_wv=1027&k=5Eco2hO)）求助
