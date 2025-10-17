# Manufacturing an "Eco-capsule" 制造一个“生态智囊”

![c8ddd4fc6b1c3ca53877050a660db32e](https://github.com/user-attachments/assets/06d07b92-ff25-423f-a601-7bd636914c47)

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
  
## Complete workflow 完整工作流程
### Laser cutting fabrication section 激光切割制作部分

The material used is a 3mm thick wooden board. The cutting lines were drawn using Adobe Illustrator. Regular broken lines (with an interval of about 1.5mm) were evenly distributed at the areas where the board needs to be bent, enabling the board to be bent. The design of the interlacing structure achieves the effect of securely fixing the bottom and sides of the box.

材料选用3mm厚度木板，用Adobe Illustrator绘制切割线，在木板需要弯折处平均分布有规律的断线（间距在1.5mm左右），使得木板可以弯折。设计穿插结构达到盒子底面和侧面能够稳固固定的效果。

Small holes with a diameter of 5 mm are reserved on both sides at the bottom for inserting wooden rods.

两侧下方预留φ = 5 mm的孔，用于插入木棒。

<img width="1000" height="650" alt="ScreenShot_2025-10-17_001526_147" src="https://github.com/user-attachments/assets/e7b33e42-5127-48b9-aee2-1fbc96fb8271" />

![弯折处断线图](https://github.com/user-attachments/assets/56aded98-9196-4fdd-a15f-cbc04e0e7da5) 

![连接处图片](https://github.com/user-attachments/assets/1c7ea9e2-9dfe-45bd-a8b1-09942cb5de8b)

木板弯折部分可以跟随教程： https://www.xiaohongshu.com/discovery/item/67d980fb000000000603e88d?source=webshare&xhsshare=pc_web&xsec_token=ABpgH2o2D5XNq11hMo5kRL98Uif6uCw50IXxXVMM8jWAk=&xsec_source=pc_share

Inside the box, space is reserved for the Arduino board.

盒体内部，为arduino板预留空间。

![2e49939aa4efa1148da3a6538226a19f](https://github.com/user-attachments/assets/e1cbf0e8-2a05-4854-a6d2-315b059474f6)

### 3D printing for fabrication of parts 3D打印制作部分
Create a tire model using the Blender software.

运用Blender软件建立轮胎模型。

<img width="2880" height="1478" alt="ScreenShot_2025-10-17_122530_860" src="https://github.com/user-attachments/assets/713eee77-03c4-4545-ba88-75646ce8c64a" />

Import the model into Ultimaker Cura for adjustment and then start the printing process (pay attention to the printing direction).

将模型导入到Ultimaker Cura中进行调整后开始打印（注意打印方向）。

<img width="1920" height="1282" alt="ScreenShot_2025-10-17_122839_430" src="https://github.com/user-attachments/assets/c500540b-8afb-45e3-820d-51b4c11911f4" />

To fix the tire on the box using a 5 mm diameter wooden stick, and to secure the wheel on the stick: Fix iron wires at both ends of the wheel. (Note to leave a distance between the box, the iron wires and the wheel, otherwise the wheel will be difficult to roll due to friction.)

用φ = 5 mm的木棒穿过盒体，将轮胎固定在盒上，将轮子固定在木棒上的方法：轮子两端固定铁丝。（注意给盒体和铁丝、轮子之间预留距离，不然轮子会因为摩擦难以滚动）

![wheels](https://github.com/user-attachments/assets/809be857-c4d5-4003-bd5e-763f200e900d)

Done!

完成！

<img width="2917" height="2799" alt="chengpin" src="https://github.com/user-attachments/assets/1294147d-391a-4f9d-8dfa-e8d0eae2558d" />

## Thinking 思考

In the laser cutting section, since the machine requires dxf format files to import the files, after Adobe Illustrator finishes drawing the graphics, there might be a situation where the vector graphics have not been released and the dxf graphics are problematic. Therefore, the graphics should be exploded in AI first.

在激光切割部分中，因为机器导入文件需要dxf格式文件，当Adobe Illustrator绘制图形结束后，可能存在矢量图形未被释放而dxf图形出问题的情况。所以要在AI中先把图形炸开。

In the 3D printing section, the previous several printing attempts all failed. After finding the reason, it was discovered that in the previous several printings, the model was placed horizontally. Due to its convex and concave structure, it was difficult to print from bottom to top. Later, the model was changed to be placed vertically, and this problem was solved.

在3D打印部分中，前几次打印尝试都失败了，找到原因发现是在前几次打印中，将模型横向放置，由于其外凸内凹的结构，打印从下往上难以进行。后将模型改成纵向放置，解决了该问题。

![bcca996dbf867b5d86db7f974555b6c3](https://github.com/user-attachments/assets/be0ee1c2-b71b-493b-b342-fdac4cdc2e29)
<img width="724" height="686" alt="1d969390eb8d399dff25912bdded7acc" src="https://github.com/user-attachments/assets/837d86c0-eff0-4311-8b6b-6061003b7b8c" />

This box still has room for improvement. Due to the size and quantity of the tires, the box cannot be placed stably when left standing. The number of wheels can be changed to 4 or the thickness and radius of the wheels can be increased to solve this problem.

该盒体仍有优化空间，由于轮胎大小和个数问题，静置盒体的情况下盒子不能放稳。可以将轮子个数改成4个或者将轮子厚度、半径加大解决该问题。
