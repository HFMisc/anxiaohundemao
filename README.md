PE下还原GHO镜像和备份GHO镜像

常用方案一：

准备工作：一个>=8GB的U盘 📢⚠️里面资料提前备份！！！以下工作会格式化整个U盘！

1、访问SYSCEO官网：https://www.sysceo.com/usm
   
   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/474b49b0-3cef-4431-a669-7ffaf9625948)
   
   下载版本个人推荐V6版本

2、下载之后安装或者解压，找到exe运行文件。可以参考：

   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/573741c8-a3a9-44e5-8776-9f8da78b3540)
   
3、运行界面如下：插入准备好的U盘，配置可以参考。

   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/072bc09b-5987-4d8e-9384-ba48cdfd664c)

   如果U盘空间有限导致报错，请参照下图进行挑选PE（非必要全制作）
   
   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/818630c9-c3ff-4d60-8cf8-76b240b35259)

   
4、点击一键制作，等待制作完成，时间由硬件性能决定（20-30min不等），期间不要拔出U盘。 再次说明⚠️：此步骤会格式化整个U盘，请务必将U盘资料提前备份。

   此处不再附截图。

5、将制作好的U盘拔出，插入代还原GHI镜像的电脑。（尽量接入高速USB口）

6、开机并持续按F12进入启动项选择界面。（此处以LENOVO联想电脑为例，其他型号请自行查询）

   启动项选择界面参考如下：
   
   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/82647596-3d16-4fac-947e-dbc9884e66d9)
   
   选择USB类启动设备
   
   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/84d471dd-75b5-4fe0-98d4-8ea7b4ed3753)
   
   推荐选择第一项全功能版
   
7.进入系统后可选择重新分区（⚠️：请谨慎操作）

  此图HD1是系统盘，整个1个分区OS（F:)，其它为数据存储盘及存储分区。
  
  ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/d18c878e-9b33-420d-9198-aa5d05ddfad6)
  
  如需重新分区推荐参考下图：
  
  ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/be3a3d88-c7df-49d0-b130-eb18510f336e)

8、分区完成后，打开安装系统工具

   按照如下步骤操作（第三步请检查分区选择无误！第四步请选择自己GHO文件的路径！慎重确认后再点击第五步执行！⚠️第五步会将第三步中选择的分区进行格式化操作！）
   
   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/e0e113d9-c61d-4c8e-bc99-f6ffcb8b547e)

   确认弹窗点击按钮“是”（如果需要终止此还原操作，请点击“否”）

   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/ae604971-2e2b-40a8-9dbb-4718a0c8bae3)

   接下来的过程请耐心等待，持续时间20-30min（这里参照固态硬盘时长，依据电脑性能而定）

   ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/183693fb-5071-452a-b83a-2f8e56bb3ff6)

   此过程中请勿给电脑断电，U盘可以在此过程中移除（不推荐），移除后可重复以上步骤还原其它电脑。
   
9、还原成功后重启电脑即可。如遇到蓝屏或者缺少引导，可以重新执行还原过程，也可以尝试引导修复，参考如下：

--------------------------------------------------------------------------------------------------------------------------------------------------------
这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线  这是一条分割线 
--------------------------------------------------------------------------------------------------------------------------------------------------------



备用方案二：

适用于没有合适U盘，但是待还原电脑可以开机进系统的情况,前提是GHO镜像已经拷贝到此电脑的C盘以外的分区。

1、选择‘硬盘模式’，并选择一个非C盘的分区进行如下操作

![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/85334663-e6b6-433b-a9ca-8a40aefd3755)


2、点击制作

  等待制作完成
  
  ![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/19f24a4e-8051-4aa7-a675-1e7d9ca9f88c)


3、制作完成

![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/6b192836-c216-43e4-a741-11662db0a24f)

关闭制作窗口

4、重启电脑，选择如下启动项

![image](https://github.com/HFMisc/anxiaohundemao/assets/45294062/50c1bf69-cd86-4744-9576-800f8c0da43c)


进入PE系统，进行如方案一操作方法。






   
   


   

   

  


