# Manufacturing an "Eco-capsule" 制造一个“生态智囊”
## About 关于
This is an attempt to create a concept shell using 3D printing and laser cutting in HTAM course.
## Design Concept 设计概念
  In 2045, artificial intelligence evolved into "environmental intelligence". And the Arduino box, which seemed rather rudimentary in 2025, has now evolved into an astonishing product: Eco-Capsule. 
  
  This product is equipped with precise environmental sensors that can detect data far beyond what human senses can perceive, such as changes in subtle compounds in the air, the condition of the surrounding soil, and the electrical signals released by plants, etc.
  
  Its core function is to "translate" all of this into a language that humans can understand, and then convey the information through the speaker, such as "The little daisy on the balcony is currently very content. The amount of water today is just right", "The indoor carbon dioxide concentration has increased, and it is necessary to open the windows for ventilation". 
  
  This capsule will become a smart entity in our living environment.
  
  2044年，人工智能进化成了“环境智能”，而在2024年看起来略显简陋的Arduino盒子，已经进化成了一个令人惊叹的产品：Eco-Capsule。
  
  这个产品内置了精准的环境传感器，能感知远超人类感官的数据，例如空气中的细微化合物变化、周边土壤的状况、植物释放的电信号等等。
  
  它的核心功能是将这一切“翻译”成人类可以理解的语言，并通过扬声器向人类传达信息，例如“阳台上的小雏菊此刻感到非常满足，今天的水分恰到好处”，“室内二氧化碳浓度升高，需要开窗通风”。
  
  这个胶囊将成为我们生活环境中一个智慧的存在。
## 完整工作流程
### 激光切割制作部分
材料选用3mm厚度木板，用Adobe Illustrator绘制切割线，在木板需要弯折处平均分布有规律的断线（间距在1.5mm左右），使得木板可以弯折。设计穿插结构达到盒子底面和侧面能够稳固固定的效果。

<img width="2222" height="1372" alt="ScreenShot_2025-10-17_001526_147" src="https://github.com/user-attachments/assets/e7b33e42-5127-48b9-aee2-1fbc96fb8271" />

![6957677a349eaf012e80bc6352df6b99](https://github.com/user-attachments/assets/56aded98-9196-4fdd-a15f-cbc04e0e7da5) ![Uploading 183324e761dcb4e9240bc25b3f7cd570.jpg…]()





木板弯折部分可以跟随教程： https://www.xiaohongshu.com/discovery/item/67d980fb000000000603e88d?source=webshare&xhsshare=pc_web&xsec_token=ABpgH2o2D5XNq11hMo5kRL98Uif6uCw50IXxXVMM8jWAk=&xsec_source=pc_share
为arduino板预留空间
### 3D打印制作部分
运用Blender软件建立轮胎模型
导入到Ultimaker Cure中进行调整后开始打印
多次打印失败，寻找原因：外凸内凹的模型表面让模型打印难以开始，重新调整打印方向，成功打印轮子
在木板上打φ = 5 mm的孔，让木棒能够穿插在盒体中
将轮子固定在木棒上的方法：轮子两端固定铁丝

## 迭代、思考过程
