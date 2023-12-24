# 免费随机图片api
文档更新时间08/31/2023 12:36:06

#### **key**

暂公开key，不用私聊获取了 key=qq249663924 可直接调用，承诺无任何限制，可爬取

#### **反馈与收集**

[失效链接反馈](https://f.wps.cn/w/ncq51Lmv/) [游客图片采集](https://f.wps.cn/w/kNyYqYb5/)

#### **赞助**

[通道1](https://www.onexiaolaji.cn/reward/) [通道2](https://onexiaolaji.gitee.io/xiaolaji/pay/)

#### **友链**

[随缘图床](http://img.sybapi.cc/)

#### **更新日志**

#访问[./api/?key=联系qq249663924免费获取&type=update](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=update)即可查看更新日志

```
            

2023/8/31:更新1.02 兔玩印画、1.05 木花琳琳是勇者、1.06 少女秩序,新增1.10 高质量JK&日式&小清新(jk.rs)(1.1001 高质量JK,1.1002 日式,1.1003 小清新)、1.11 少女映画、1.12 喵糖映画、6 动漫/二次元

            

2023/7/7:新增秀人网,2.0205==>秀人网4001-4592期

            

2023/5/30:新增秀人网,2.0204==>秀人网3001-4000期

            

2023/5/20:更新video源

            

2023/1/14:对接了几个随机小姐姐视频接口,看腻了图片看看视频吧!分类名class=video

            

2023/1/6:暂公开key,不用私聊获取了 key=qq249663924  可直接调用,承诺无任何限制,可爬取

            

2022/11/10:2.0203更新完毕

            

2022/10/16:新增秀人网,2.0203==>秀人网2001-3000期

            

2022/10/4:再次更改命名编号;2.0202更新完毕;新增1.10 高质量JK(jk.rs);新增10 bing每日壁纸

            

2022/9/6:更新秀人网,2.0202==>秀人网1001-2000期

            

2022/8/23:秀人网0001-1000期更新完毕,鉴于图片太多,采用分段编码,即2.0201==>秀人网0001-1000期

 
            

2022/8/20:更新买家秀系列,新增4.2 七了个三店铺买家秀;继续更新2.2 秀人网

 
            

2022/8/18:更新2.2 秀人网（0000-0315期）

                
            

2022/8/17:更新2.2 秀人网（0000-0260期）

            

2022/8/16:更新2.2 秀人网（0000-0150期）,困死了,💤

            

2022/8/15:1.9 DJAWA现阶段更新完毕;新增2.2 秀人网

            

2022/8/14:2.2 DISI第四印象==>更改为1.8 DISI第四印象;2.3 DJAWA==>更改为1.9 DJAWA

            

2022/8/13:新增2.3 DJAWA

            

2022/8/12:更新2.1 舞蹈生日记；新增2.2 DISI第四印象

            

2022/8/11:更改分类规则,以数字代替名称（随时更改）{1.1 JKFUN;1.2 兔玩印画;1.3 喵写真;1.4 紧急企划;1.5 木花琳琳是勇者;1.6 少女秩序;1.7 耶米西奶露;2.1 舞蹈生日记;4 买家秀}

            

2022/7/11:更新文档,加入key

            

2022/7/11之前:不记得了

            
```

#### **图片分类**

#访问[./api/?key=联系qq249663924免费获取&type=class](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=class)获取图片分类

```
            

1      写真系列”:{1.01     JKFUN;1.02     兔玩印画;1.03     喵写真;1.04     紧急企划;1.05     木花琳琳是勇者;1.06     少女秩序;1.07     耶米西奶露;1.08     DISI第四印象;1.09     DJAWA;1.10     高质量JK(jk.rs)};

            

2      套图系列”:{2.01     舞蹈生日记;“2.02     秀人网”:{2.0201   0001-1000期;2.0202   1001-2000期;2.0203   2001-3000期}};

            

4      买家秀系列”:{4.01     七了个三店铺;4.02     其他店铺}

            

10     bing每日壁纸

            

video   随机小姐姐视频

            
            
            
            
            
            
            
            
            
```

#### **调用说明**

###### **参数**

```
            

"key":必填，联系qq249663924免费获取

            

"class":非必填，图片分类，不填默认调用全部图片随机

            

"id":非必填，图片id，供调用指定图片及反馈时有效(2022.8.12已关闭)

            

"type":非必填，可选参数{"amount":图片数量；"url":图片直链；"json":图片json；"JSON":图片JSON}

			
```

1、访问[./api/?key=联系qq249663924免费获取](https://www.onexiaolaji.cn/RandomPicture/api/?key=)即可跳转至图片地址

2、访问[./api/?key=联系qq249663924免费获取&class=1.1](https://www.onexiaolaji.cn/RandomPicture/api/?key=&class=1.1)随机输出类目jkfun下的图片

3、访问[./api/?key=联系qq249663924免费获取&type=amount](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=amount)返回图片总量，即id的最大值

4、访问[./api/?key=联系qq249663924免费获取&type=output](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=output)服务器读取后输出，一般不建议使用，默认禁用

5、访问[./api/?key=联系qq249663924免费获取&type=json](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=json)服务器输出随机图片json

```
			 `{"code":"200","url":"https:\/\/p.pstatp.com\/origin\/febe0002ea6d81bbc43c"}` 
			
```

7、访问[./api/?key=联系qq249663924免费获取&class=1.1&type=json](https://www.onexiaolaji.cn/RandomPicture/api/?key=&class=1.1&type=json)服务器随机输出类目jkfun下图片json

```
    		 `{"code":"200","url":"https:\/\/fp1.fghrsh.net\/2019\/07\/15\/8475093caeadeb7a726b5eec15a95b83.jpg"}` 
			
```

8、访问[./api/?key=联系qq249663924免费获取&type=json&id=1](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=json&id=1)服务器输出指定图片json

```
    		 `{"code":"200","url":"https:\/\/p.pstatp.com\/origin\/febe0002ea6d81bbc43c"}` 
			
```

9、访问[./api/?key=联系qq249663924免费获取&type=JSON](https://www.onexiaolaji.cn/RandomPicture/api/?key=&type=JSON)服务器读取随机图片信息后输出json，如非需要图片信息不建议使用

```
    		 `{"code":"200","url":"https:\/\/fp1.fghrsh.net\/2019\/07\/15\/c2549aaa63db078834ead6a92fe63b61.jpg","width":"1920","height":"1080","mime":"image\/jpeg","size":"821735"}` 
			
```