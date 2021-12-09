## 病虫害，农业作物数据集

#### 1. IP102: A Large-Scale Benchmark Dataset for Insect Pest Recognition(https://github.com/xpwu95/IP102)

下载地址: https://drive.google.com/drive/folders/1svFSy2Da3cVMvekBwe13mzyx38XZ9xWo?usp=sharing

数据集简要说明: 超过 75,000 张图片，共102类（https://github.com/xpwu95/IP102/blob/master/classes.txt）

检测任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/04/GTHrKYEWLSamgvi.jpg" style="zoom: 50%;" />



标注示例：

```
<annotation>
	<folder>IP103_final_new1</folder>
	<filename>IP000000000.jpg</filename>
	<path>/home/ubuntu2/Desktop/IP103_final_new1/IP000000000.jpg</path>
	<source>
		<database>Unknown</database>
	</source>
	<size>
		<width>650</width>
		<height>420</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>0</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>99</xmin>
			<ymin>231</ymin>
			<xmax>524</xmax>
			<ymax>334</ymax>
		</bndbox>
	</object>
</annotation>
```

分类任务：

*图片示例：*

![00037](https://s2.loli.net/2021/12/04/S7upTnxDzXlO9I1.jpg)



分类类别：

（https://github.com/xpwu95/IP102/blob/master/classes.txt）

```
1  rice leaf roller 			
2  rice leaf caterpillar 		
3  paddy stem maggot 			
4  asiatic rice borer 			
5  yellow rice borer 			
6  rice gall midge 			
7  Rice Stemfly 	     		
8  brown plant hopper 			
9  white backed plant hopper 	
10 small brown plant hopper 	
11 rice water weevil 			
12 rice leafhopper 			
13 grain spreader thrips 		
14 rice shell pest 			
15 grub 		            	
16 mole cricket 			    
17 wireworm 			        
18 white margined moth 		
19 black cutworm 			    
20 large cutworm 			    
21 yellow cutworm 		        
22 red spider 			        
23 corn borer 			        
24 army worm 			        
25 aphids 			            
26 Potosiabre vitarsis 		
27 peach borer 		     	
28 english grain aphid 		
29 green bug 			        
30 bird cherry-oataphid 		
31 wheat blossom midge 		
32 penthaleus major 			
33 longlegged spider mite 		
34 wheat phloeothrips 			
35 wheat sawfly					
36 cerodonta denticornis			
37 beet fly						
38 flea beetle						
39 cabbage army worm				
40 beet army worm					
41 Beet spot flies					
42 meadow moth						
43 beet weevil						
44 sericaorient alismots chulsky 	
45 alfalfa weevil					
46 flax budworm					
47 alfalfa plant bug				
48 tarnished plant bug 			
49 Locustoidea							
50 lytta polita					
51 legume blister beetle 			
52 blister beetle					
53 therioaphis maculata Buckton 	
54 odontothrips loti				
55 Thrips							
56 alfalfa seed chalcid 			
57 Pieris canidia					
58 Apolygus lucorum				
59 Limacodidae						
60 Viteus vitifoliae				
61 Colomerus vitis					
62 Brevipoalpus lewisi McGregor 	
63 oides decempunctata 			
64 Polyphagotars onemus latus		
65 Pseudococcus comstocki Kuwana 	
66 parathrene regalis				
67 Ampelophaga						
68 Lycorma delicatula				
69  Xylotrechus						
70  Cicadella viridis				
71  Miridae							
72  Trialeurodes vaporariorum						
73  Erythroneura apicalis			
74  Papilio xuthus			
75  Panonchus citri McGregor		
76  Phyllocoptes oleiverus ashmead	
77  Icerya purchasi Maskell			
78  Unaspis yanonensis				
79  Ceroplastes rubens				
80  Chrysomphalus aonidum			
81  Parlatoria zizyphus Lucus		
82  Nipaecoccus vastalor			
83  Aleurocanthus spiniferus		
84  Tetradacus c Bactrocera minax	
85  Dacus dorsalis(Hendel)			
86  Bactrocera tsuneonis			
87  Prodenia litura					
88  Adristyrannus					
89  Phyllocnistis citrella Stainton	
90  Toxoptera citricidus			
91  Toxoptera aurantii				
92  Aphis citricola Vander Goot		
93  Scirtothrips dorsalis Hood		
94  Dasineura sp					
95  Lawana imitata Melichar			
96  Salurnis marginella Guerr		
97  Deporaus marginatus Pascoe		
98  Chlumetia transversa			
99  Mango flat beak leafhopper		
100 Rhytidodera bowrinii white		
101 Sternochetus frigidus			
102 Cicadellidae	
```

### **2. PlantVillage**(https://tensorflow.google.cn/datasets/catalog/plant_village?hl=zh-cn)

下载地址: https://data.mendeley.com/datasets/tywbtsjrjv/1

数据集简要说明: 54303 健康与不健康的叶子图片，按物种和疾病分为38类（https://github.com/xpwu95/IP102/blob/master/classes.txt）

分类任务：

*图片示例*：

<img src="https://storage.googleapis.com/tfds-data/visualization/fig/plant_village-1.0.2.png" alt="Visualization" style="zoom: 50%;" />****



标注示例：

```
FeaturesDict({
    'image': Image(shape=(None, None, 3), dtype=tf.uint8),
    'image/filename': Text(shape=(), dtype=tf.string),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=38),
})
```

### **3. Citrus Pest Benchmark**

下载地址: https://github.com/edsonbollis/Citrus-Pest-Benchmark

数据集简要说明: 10,816 张多类图像分为七类：(i) 1,902 张带有红蜘蛛螨（Panonychus citri、Eutetranychus banksi、Tetranychus mexicanus）的图像； (ii) 1,426 张 Phytoseiid 螨（Euseius citrifolius、Iphiseiodes zuluagai）的图像； (iii) 1,386 张锈螨（Phyllocoptruta oleivora）图像； (iv) 1,750 张假蜘蛛螨 (Brevipalpus phoenicis) 的图像； (v) 806 幅布螨（Polyphagotarsonemus latus）图像； (vi) 696 张双斑叶螨图像； (vii) 3,455 张负样本。训练集、验证集和测试集，包含来自每个类别的大约 60%、20% 和 20% 的螨虫，分别总计 6380、2239 和 2197 张图像。

分类任务：

*图片示例*：

****

<img src="https://github.com/edsonbollis/Citrus-Pest-Benchmark/raw/master/mites.png" alt="img" style="zoom:33%;" />

分类示例：

| images              | Mite | Negative |
| ------------------- | ---- | -------- |
| 20180619_153204.jpg | 1    | 0        |

### **4. SAUTAG**

下载地址: https://github.com/SAUTEG/version_1.0

数据集简要说明: 

### 分类任务

##### 目录结构

```
//涉及的作物种类名、虫害名、病害名应该优先使用拉丁学名
SATEG
├─Oryza sativa L        //涉及作物种类的拉丁学名
│  ├─Diseases           //此文件夹用于存放该作物的病害数据集
│  │  ├─!Phytophthora fragariae Hickm.var.oryzo-bladis Wang et Lu    //当样本数量过少应在样本前加"!"符号
│  │  ├─Entyloma oryzae Syd
│  │  └─Fusarium moniliforme Sheld
│  └─Pests             //此文件夹用于存放该作物的虫害数据集
│      ├─!Ancyllomia japonica zeller
│      ├─Aleurocybotus indicus David et Subramaniam
│      ├─Ampullaria gigas Spix
└─Sample               //此文件夹用于存放优化后的病虫害训练样本（可快速用于训练模型）
   └─Oryza sativa L.Pests     //其中的一个训练样本,分号分割作物种类和样本类型(这里代表该优化训练样本为Oryza sativa L的Pests)
        ├─test                //这里是测试数据集文件夹
        │  ├─Aleurocybotus indicus David et Subramaniam
        │  └─Ampullaria gigas Spix
        |─train               //这里是训练数据集文件夹
        |   ├─Aleurocybotus indicus David et Subramaniam
        |   └─Ampullaria gigas Spix
        └─README             //该训练样本的说明文档，当对数据集进行特殊处理后（例如改变了默认的训练样本文档目录结构），应在这里进行说明
                              
```

- 涉及的作物种类名、虫害名、病害名为**拉丁学名**
- 文件夹名前`!`代表样本数量过少
  例如:
  `!Phytophthora fragariae Hickm.var.oryzo-bladis Wang et Lu //该样本数量不足`
- 根目录下作物拉丁学名的文件夹包含该作物的原始数据，内有`Diseases`存放病害数据和`Pets`存放虫害数据
- `Diseases`和`Pets`文件夹内的数据应以拉丁学名为文件夹分类存储
- 文件夹名的`&`连接不同种类数据,里面存取的是相似的病害和虫害
  例如:
  `Cletus punctiger&Clketus trigonus //该文件夹存有两种相识虫害`

> 在使用该方式时,种类有极大相似性,在防治角度没有分开的必要性

- 部分文件夹拉丁学名超过**GitHub最大长度**时,使用了首字母缩写格式,在对应根目录有`README`文件进行了说明
  例如:
  `H.S.2F.M为5种相识种类合并后导致的文件夹名过长,使用缩写形式,在根目录建立`README`文件进行说明`
- `Sample`文件夹存储可以直接可以用于训练的样本，样本文件夹名采用`作物名.类别`的命名方式
- 样本文件夹根目录可能有`README`文件，对数据集进行进行说明

##### 快速上手

##### 极速开始

  如果你想快速搭建你的识别模型,只需按需在`Sample`文件夹找到预先设计过数据集,数据集已按照`作物名.类别`的命名方式对样本的数据类型说明。（文件夹中可能有`README`文件对样本详细情况进行说明）

##### 原始数据

  原始数据在数据集根目录下以作物拉丁学名为文件夹存放，内有`Diseases文件夹`存放病害数据和`Pets文件夹`存放虫害数据。



*图片示例*：

****

![image-20211204111514857](https://s2.loli.net/2021/12/05/8ROMNL9jI3SFgHy.png)

### **5. PestDataset**

下载地址: https://github.com/FelipeVein/PestDataset

数据集简要说明: 1036 张多类图像分为九类。

分类任务：

*图片示例*：

****

<img src="https://github.com/FelipeVein/PestDataset/blob/master/data/images/Anthonomus%20grandis-green---115.%20300px-curculio_nucum01.jpg?raw=true" alt="Anthonomus grandis-green---115. 300px-curculio_nucum01.jpg" style="zoom:50%;" />

标注示例：

```
"images":{"id":3,"width":480,"height":360,"file_name":"./data/images/alabama---3. thumbnail.jpg","license":0,"flickr_url":"./data/images/alabama---3. thumbnail.jpg","coco_url":"./data/images/alabama---3. thumbnail.jpg","date_captured":""}

"annotations":{"segmentation":[[238,227,237,228,236,228,235,229,233,229,233,230,232,231,232,232,230,234,230,236,229,237,216,237,215,238,210,238,209,237,204,237,203,236,200,236,199,235,197,235,196,236,180,236,178,234,176,234,175,233,168,233,167,232,166,232,165,233,150,233,149,234,145,234,144,233,136,233,135,234,134,234,133,235,132,235,130,237,127,237,126,238,124,238,121,241,120,241,119,242,118,242,118,244,120,246,120,247,124,251,128,251,130,249,131,249,132,248,133,248,134,247,135,247,136,246,138,246,139,245,143,245,144,246,149,246,150,247,151,247,152,248,154,248,156,250,157,250,158,251,165,251,166,252,186,252,187,253,204,253,205,252,215,252,216,253,221,253,222,254,231,254,232,253,235,253,236,252,237,252,239,250,239,249,241,247,241,246,243,244,243,241,244,240,244,233,243,232,243,230,242,229,241,229,239,227]],"area":3402,"bbox":[118,227,126,27],"iscrowd":0,"id":1,"image_id":0,"category_id":1}
```

### **6. pest-dataset(10 classes)**

下载地址: https://sejonguniversity-my.sharepoint.com/:f:/g/personal/hanxiang_sju_ac_kr/EvrsNaKE_DZBgcHNG7fbQWgB0432dI0B7YfzzDUgEWEKCw

数据集简要说明: 5869张多类图像分为10类。

分类任务：

*图片示例*：

****

![1355010](https://s2.loli.net/2021/12/05/UBzIDMgFaw2tr9k.jpg)

分类类别：

```
Cydia pomonella
Gryllotalpa
leafhopper
locust
Oriental fruit fly
Pieris rapae Linnaeus
snail
Spodoptera litura
stinkbug
Weevil
```

### **7. AI CHANLLENGER--Plant Disease Recognition**

下载地址: https://pan.baidu.com/s/1TH9qL7Wded2Qiz03wHTDLw

数据集简要说明: 训练集和验证集包含10种作物品种的健康样本和27种病害样本，其中24种进行了病害程度的分析，剩余3种发病程度相似。测试集图片均属于这10种作物的健康或病害样本。

分类任务：

*图片示例*：

****

![image-20211204121928209](https://s2.loli.net/2021/12/05/i5asCYcVAbkuPIj.png)

分类示例：

```
{"disease_class": 1, "image_id": "43234193db4aefa1245592ab36d6c946.jpg"}
```

### **8. Rice Leaf Diseases Data Set**

下载地址: https://archive.ics.uci.edu/ml/machine-learning-databases/00486/

数据集简要说明: 包含120张图片，分为三类/疾病：细菌性叶枯病，褐斑病和叶黑穗病，每个都有40张图像。

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211205114141456.png" alt="image-20211205114141456" style="zoom: 50%;" />

### **9. **Plant Leaves

下载地址: https://data.mendeley.com/datasets/hb74ynkjcn/1

数据集简要说明: 包含 4502 张健康和不健康植物叶子的图像，按物种和健康状况分为 22 个类别。

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211204180857999.png" alt="image-20211204180857999" style="zoom:33%;" />

分类类别：

```
Alstonia Scholaris (P2) (DISEASED/HEALTHY)

Arjun (P1) (DISEASED/HEALTHY)

Bael (P4) (DISEASED/HEALTHY)

Basil (P8) (DISEASED/HEALTHY)

Chinar (P11) (DISEASED/HEALTHY)

Gauva (P3) (DISEASED/HEALTHY)

Jamun (P5) (DISEASED/HEALTHY)

Jatropha (P6) (DISEASED/HEALTHY)

Lemon (P10) (DISEASED/HEALTHY)

Mango (P0) (DISEASED/HEALTHY)

Pomegranate (P9) (DISEASED/HEALTHY)

Pongamia Pinnata (P7) (DISEASED/HEALTHY)
```

### **10. **Plantae_k

下载地址: https://data.mendeley.com/datasets/hb74ynkjcn/1

数据集简要说明: 包含 2153 张健康和不健康植物叶子的图像，按物种和健康状况分为 16 个类别.

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211204181116802.png" alt="image-20211204181116802" style="zoom: 50%;" />

分类类别：

```
APPLE (DISEASED/HEALTHY)
APRICOT (DISEASED/HEALTHY)
CHERRY (DISEASED/HEALTHY)
CRANBERRY (DISEASED/HEALTHY)
GRAPES (DISEASED/HEALTHY)
PEACH (DISEASED/HEALTHY)
PEAR (DISEASED/HEALTHY)
WALNUT (DISEASED/HEALTHY)
```

### **11. **A database of eight common tomato pest images

下载地址: https://data.mendeley.com/datasets/s62zm6djd2/1

数据集简要说明: 该数据库基于八种常见番茄害虫，包括 (1) Tetranychus urticae、(2) Bemisia argentifolii、(3) Zeugodacus cucurbitae、(4) Thrips palmi、(5) Myzus persicae、(6) Spodoptera litura、(7) Spodoptera exigua 和 (8) Helicoverpa armigera。
原始图像来自 IPMImages 数据库 (https://www.ipmimages.org/index.cfm)、国家农业昆虫资源局 (NBAIR) (https://www.nbair.res.in /Databases/insectpests/ index.php）和谷歌搜索。 图像数据库包含8类609幅原始图像，采用图像增强技术进行放大，增强后共有4263幅图像。 图像增强技术包括90度旋转、180度旋转、270度旋转、水平翻转、垂直翻转和裁剪。 最后，图片大小统一为299*299，图片格式为.JPG文件。

分类任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/05/jUv1qrbBxfgeJZX.jpg" alt="ZC (2)" style="zoom: 50%;" />



分类类别：

```
(1) Tetranychus urticae、
(2) Bemisia argentifolii、
(3) Zeugodacus cucurbitae、
(4) Thrips palmi、
(5) Myzus persicae、
(6) Spodoptera litura、
(7) Spodoptera exigua
(8) Helicoverpa armigera
```

### **12. **林业有害生物分类数据集

下载地址: https://aistudio.baidu.com/aistudio/datasetdetail/105865

数据集简要说明: 包括有:黑蚱蝉,蟪蛄,蒙古寒蝉等99种生物,共近2000张图片,各生物种类数据数量基本平衡.

分类任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/05/vpcu1bL7DISTxko.jpg" alt="11" style="zoom:50%;" />



### **13. **华农bug和fruit bug数据集

下载地址: https://bj.bcebos.com/v1/ai-studio-online/df0ba590801145d59b8eccf67ba4a8d0ae817b734a524bbe93f0b0660345976c?responseContentDisposition=attachment%3B%20filename%3Dbug.zip&authorization=bce-auth-v1%2F0ef6765c1e494918bc0d4c3ca3e5c6d1%2F2021-07-17T13%3A17%3A05Z%2F-1%2F%2F209af583f99889481166a34da9f36969200220b58335fadcbffb3f84b82d768b

数据集简要说明: 包括有bug和fruit bug, 共8333张图片,各生物种类数据数量基本平衡.

分类与检测任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/05/mgiT4saZxyQAzEo.jpg" alt="1" style="zoom: 50%;" />





标注示例：

```
<annotation>
            <folder>JPEGImages</folder>
            <filename>1880.jpg</filename>
            <source>
                <database>Unknown</database>
            </source>
            <segmented>0</segmented>
        	
        <size>
            <width>768</width>
            <height>768</height>
            <depth>3</depth>
        </size>
        
            <object>
            <name>fruit bug</name>
            <pose>Unspecified</pose>
            <truncated>0</truncated>
            <difficult>0</difficult>
            <bndbox>
                <xmin>38</xmin>
                <ymin>406</ymin>
                <xmax>342</xmax>
                <ymax>594</ymax>
            </bndbox>
            </object>
            
        </annotation>
```

### **14. **中科院农作物病虫害样本数据集

下载地址: https://aistudio.baidu.com/aistudio/datasetdetail/57324

数据集简要说明: 包括127张图片,样本较少。

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211205113622997.png" alt="image-20211205113622997" style="zoom:33%;" />



目录结构：

```
数据集介绍
├─大豆病害
│  ├─大豆根腐病
│  ├─大豆细菌性斑疹病
│  └─大豆花叶病毒病
├─小麦病害
│  ├─小麦叶锈病
│  ├─小麦梭条斑花叶病
│  ├─小麦白粉病
│  ├─小麦赤霉病
│  └─小麦雪霉叶枯病
├─水稻病害
│  ├─水稻白叶枯病
│  ├─水稻纹枯病
│  ├─水稻细菌性条斑病
│  ├─水稻胡麻斑病
│  ├─稻曲病
│  └─稻瘟病
├─水稻虫害
│  ├─二化螟
│  ├─二化螟为害状
│  ├─水稻大螟
│  ├─水稻大螟为害状
│  ├─稻棘缘蝽
│  ├─稻水象甲为害状
│  ├─稻纵卷叶螟
│  ├─稻纵卷叶螟为害状
│  ├─稻纵卷叶螟视频
│  ├─稻蝗
│  ├─稻象甲为害状
│  └─稻飞虱
├─玉米病害
│  ├─玉米南方锈病
│  ├─玉米大斑病
│  ├─玉米小斑病
│  └─玉米锈病
├─玉米虫害
│  ├─玉米叶夜蛾
│  ├─玉米粘虫为害状
│  └─红缘灯蛾
├─葡萄病害
│  ├─葡萄花叶病毒病
│  ├─葡萄霜霉病
│  └─葡萄黑霉病
├─豇豆病害
│  ├─豇豆褐斑病
│  └─豇豆锈病
└─黄瓜病害
    ├─黄瓜炭疽病
    ├─黄瓜白粉病
    ├─黄瓜霜霉病
    └─黄瓜靶斑病
```

### **15. **Dataset for pest classification in Mango farms from Indonesia

下载地址: https://md-datasets-cache-zipfiles-prod.s3.eu-west-1.amazonaws.com/94jf97jzc8-1.zip

数据集简要说明: 数据集集合包含 510 张图像，其中包括影响芒果叶的 15 类害虫以及在 6 个月内收集的芒果叶的原始外观（产生 16 类）。数据增强过程的结果产生总共 62,047 个图像样本。该数据集包括从现场捕获的原始图像和增强图像样本的图像样本注释。原始数据和增强数据都被归类为训练、验证和测试。整个数据集分为 3 部分，即版本 0、版本 1 和版本 2。版本 0 由原始数据集组成，有 310 张用于训练的图像，103 张用于验证的图像，最后是 97 张用于测试的图像。数据集的第 1 版包括 46,500 个用于训练的图像样本，在应用数据增强过程之后，随后是 103 个用于验证的原始图像和 97 个用于测试的图像。最后，数据集的版本 2 使用 47, 500 张图像进行训练，使用 15, 450 张图像进行验证，使用 97 张图像进行测试。

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211205114344395.png" alt="image-20211205114344395" style="zoom: 50%;" />

目录结构：

<img src="https://s2.loli.net/2021/12/06/ESmusljFBxrYfvg.png" alt="image-20211205114411528" style="zoom: 67%;" />

### **16. **ZIZANIA AND APPLE IMAGE DATASET

下载地址: https://ieee-dataport.org/documents/zizania-and-apple-image-dataset#files

数据集简要说明: zizania 图像数据集由总共 4900 个 zizanias 组成。 优质样本数量为2648个，缺陷质量样本数量为2252个。苹果图像数据集中有四类，分别是直径大于90mm、80-90mm之间、小于80mm、病虫害的苹果。 上述类别的数量分布为3647（51.19%）、2464（34.59%）、558（7.83%）、455（6.39%）。

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211205114344395.png" alt="image-20211205114344395" style="zoom: 50%;" />



### 17. Flavia

（http://flavia.sourceforge.net/）

下载地址: https://sourceforge.net/projects/flavia/files/Standard%20Leaf%20Images/0.1/standardleaves.tar.bz2/download

数据集简要说明: 约600张，33类。

分类任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/06/VR6dIhZtMD1w2pL.png" alt="image-20211205121550250" style="zoom: 25%;" />

目录结构：

| label | Scientific Name                                  | Common Name(s)             | filename  |
| ----- | ------------------------------------------------ | -------------------------- | --------- |
| 1     | Phyllostachys edulis (Carr.) Houz.               | pubescent bamboo           | 1001-1059 |
| 2     | Aesculus chinensis                               | Chinese horse chestnut     | 1060-1122 |
| 3     | Berberis anhweiensis Ahrendt                     | Anhui Barberry             | 1552-1616 |
| 4     | Cercis chinensis                                 | Chinese redbud             | 1123-1194 |
| 5     | Indigofera tinctoria L.                          | true indigo                | 1195-1267 |
| 6     | Acer Palmatum                                    | Japanese maple             | 1268-1323 |
| 7     | Phoebe nanmu (Oliv.) Gamble                      | Nanmu                      | 1324-1385 |
| 8     | Kalopanax septemlobus (Thunb. ex A.Murr.) Koidz. | castor aralia              | 1386-1437 |
| 9     | Cinnamomum japonicum Sieb.                       | Chinese cinnamon           | 1497-1551 |
| 10    | Koelreuteria paniculata Laxm.                    | goldenrain tree            | 1438-1496 |
| 11    | Ilex macrocarpa Oliv.                            | Big-fruited Holly          | 2001-2050 |
| 12    | Pittosporum tobira (Thunb.) Ait. f.              | Japanese cheesewood        | 2051-2113 |
| 14    | Chimonanthus praecox L.                          | wintersweet                | 2114-2165 |
| 15    | Cinnamomum camphora (L.) J. Presl                | camphortree                | 2166-2230 |
| 16    | Viburnum awabuki K.Koch                          | Japan Arrowwood            | 2231-2290 |
| 17    | Osmanthus fragrans Lour.                         | sweet osmanthus            | 2291-2346 |
| 18    | Cedrus deodara (Roxb.) G. Don                    | deodar                     | 2347-2423 |
| 19    | Ginkgo biloba L.                                 | ginkgo, maidenhair tree    | 2424-2485 |
| 20    | Lagerstroemia indica (L.) Pers.                  | Crape myrtle, Crepe myrtle | 2486-2546 |
| 21    | Nerium oleander L.                               | oleander                   | 2547-2612 |
| 22    | Podocarpus macrophyllus (Thunb.) Sweet           | yew plum pine              | 2616-2675 |
| 23    | Prunus serrulata Lindl. var. lannesiana auct.    | Japanese Flowering Cherry  | 3001-3055 |
| 24    | Ligustrum lucidum Ait. f.                        | Glossy Privet              | 3056-3110 |
| 25    | Tonna sinensis M. Roem.                          | Chinese Toon               | 3111-3175 |
| 26    | Prunus persica (L.) Batsch                       | peach                      | 3176-3229 |
| 27    | Manglietia fordiana Oliv.                        | Ford Woodlotus             | 3230-3281 |
| 28    | Acer buergerianum Miq.                           | trident maple              | 3282-3334 |
| 29    | Mahonia bealei (Fortune) Carr.                   | Beale's barberry           | 3335-3389 |
| 30    | Magnolia grandiflora L.                          | southern magnolia          | 3390-3446 |
| 31    | Populus ×canadensis Moench                       | Canadian poplar            | 3447-3510 |
| 32    | Liriodendron chinense (Hemsl.) Sarg.             | Chinese tulip tree         | 3511-3563 |
| 33    | Citrus reticulata Blanco                         | tangerine                  | 3566-3621 |

### 18. Swedish Leaf

下载地址: https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/

数据集简要说明: 600张，33类。

*文件命名样例：*

l9nr003.tif

l 是叶子的缩写
9是树类九
nr 是数字的缩写
003 是特定树类的叶子数

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211205122058381.png" alt="image-20211205122058381" style="zoom: 50%;" />

目录结构：

- [1. Ulmus carpinifolia ](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf1.zip): 240 MB
- [2. Acer](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf2.zip): 659 MB
- [3. Salix aurita](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf3.zip): 227 MB
- [4. Quercus](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf4.zip): 137 MB
- [5. Alnus incana](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf5.zip): 71 MB
- [6. Betula pubescens](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf6.zip): 204 MB
- [7. Salix alba 'Sericea'](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf7.zip): 95 MB
- [8. Populus tremula](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf8.zip): 203 MB
- [9. Ulmus glabra](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf9.zip): 320 MB
- [10. Sorbus aucuparia](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf10.zip): 554 MB
- [11. Salix sinerea](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf11.zip): 121 MB
- [12. Populus](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf12.zip): 243 MB
- [13. Tilia](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf13.zip): 180 MB
- [14. Sorbus intermedia](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf14.zip): 279 MB
- [15. Fagus silvatica](https://www.cvl.isy.liu.se/en/research/datasets/swedish-leaf/leaf15.zip): 172 MB

### 19. UCI Leaf

（http://archive.ics.uci.edu/ml/datasets/Leaf）

下载地址: http://archive.ics.uci.edu/ml/machine-learning-databases/00288/

数据集简要说明: 340张图片，每张图片16类属性标注。

属性：

```
1. Class (Species)
2. Specimen Number
3. Eccentricity
4. Aspect Ratio
5. Elongation
6. Solidity
7. Stochastic Convexity
8. Isoperimetric Factor
9. Maximal Indentation Depth
10. Lobedness
11. Average Intensity
12. Average Contrast
13. Smoothness
14. Third moment
15. Uniformity
16. Entropy
```

分类任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/06/jMEnAQv3iuW8gT7.png" alt="image-20211205122913938" style="zoom:50%;" />

*类别示例：*

数据库包括 40 种不同的植物物种。

<img src="https://s2.loli.net/2021/12/06/4plXGv9BcqKugFr.png" alt="image-20211205122842218" style="zoom: 67%;" />

### 20. BRACOL - A Brazilian Arabica Coffee Leaf images dataset to identification and quantification of coffee diseases and pests

（https://data.mendeley.com/datasets/yy2k5y8mxg/1）

下载地址: https://md-datasets-cache-zipfiles-prod.s3.eu-west-1.amazonaws.com/yy2k5y8mxg-1.zip

数据集简要说明: 共收集了 1747 张阿拉比卡咖啡叶的图像，包括健康叶和病叶。从获得的照片中生成了两个数据集，包含整个叶子的原始图像数据集和仅包含症状图像的数据集。

叶子数据集：它由整个叶子的原始图像组成。这些图像根据每片叶子病害程度进行了标记。使用 Manso 等人提出的自动图像处理方法，使用症状和叶子分割掩码计算严重程度。对于某些严重程度范围，标签分配如下：健康 (< 0:1%)、非常低 (0.1% - 5%)、低 (5% - 10%)、高 (10% - 15%) 和非常高(> 15%)。

症状数据集：该数据集是通过从只有当方面生物病害的原始图像中裁剪而创建的。总共裁剪了 2147 张图像。

每个数据集分为训练、验证和测试。

分类任务：

*图片示例*：

<img src="https://s2.loli.net/2021/12/06/UPze8HlQ5byxa3O.jpg" alt="20" style="zoom:33%;" />

### 21. Data for: A Low Shot Learning Method for Tea Leaf’s Disease Identification

（https://data.mendeley.com/datasets/dbjyfkn6jr/1）

下载地址: https://md-datasets-cache-zipfiles-prod.s3.eu-west-1.amazonaws.com/dbjyfkn6jr-1.zip

数据集简要说明: 该数据包含茶红斑病、茶红斑病和茶叶枯病3种茶叶病害的120幅图像。

分类任务：

*图片示例*：

![9](https://s2.loli.net/2021/12/06/WbELFUVPNpHZw6D.jpg)

### 22. Rice-Disease-DataSet

下载地址: https://github.com/aldrin233/RiceDiseases-DataSet

数据集简要说明: 该数据包含细菌性叶枯病 (BLB)，稻瘟病，棕斑3种病害的276幅图像。

分类与检测任务：

*图片示例*：

<img src="https://github.com/aldrin233/RiceDiseases-DataSet/blob/master/brownspot/orig/brownspot_orig_098.jpg?raw=true" alt="brownspot_orig_098.jpg" style="zoom: 50%;" />

标注示例：

```

<annotation>
	<folder>orig</folder>
	<filename>blight_orig_001.jpg</filename>
	<path>G:\BLB\orig\blight_orig_001.jpg</path>
	<source>
		<database>Unknown</database>
	</source>
	<size>
		<width>300</width>
		<height>300</height>
		<depth>3</depth>
	</size>
	<segmented>0</segmented>
	<object>
		<name>Bacterial_Blight</name>
		<pose>Unspecified</pose>
		<truncated>0</truncated>
		<difficult>0</difficult>
		<bndbox>
			<xmin>43</xmin>
			<ymin>8</ymin>
			<xmax>238</xmax>
			<ymax>284</ymax>
		</bndbox>
	</object>
```

### 23. Rice Diseases Image Dataset

下载地址: https://www.kaggle.com/minhhuy2810/rice-diseases-image-dataset

数据集简要说明: 该数据包含健康，希斯帕病，稻瘟病，棕斑4种病害的5447幅图像。

分类任务：

*图片示例*：

<img src="https://storage.googleapis.com/kagglesdsdata/datasets/193945/796736/LabelledRice/Labelled/Hispa/IMG_20190419_094245.jpg?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=databundle-worker-v2%40kaggle-161607.iam.gserviceaccount.com%2F20211203%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20211203T132254Z&X-Goog-Expires=345599&X-Goog-SignedHeaders=host&X-Goog-Signature=027dc271a446fbd0d30bd93105fc25755fcdc70ca5a04eb5e3b5f96fcc522542e035befe31e4a676188c8f583e5e6a712c3a6228b439ff9d87adb589f9120bdb0def98acaa9024b0dc3c4f78895d66a64fb818c9373f634c8ee9b955cfa6a6934961329c38395a359eb624c7e1852931f7c541e2acf0b63966238eeefd6acded0f302bbcb167184c3f26bd5bb87b6e44426cafcf87143dec7a9b3a0a294142c427decb6190415c11ab4213b4ce63a476da1af151f0c2ba4553ff27b9301e4f9183e39a2c1c424e86a18a2fc7c75956eadeb360534ed4d3bcb89f342a205dd1e5345894349c1f57f490dea35392b4ae9fccf33c0da1127f2d1e3a0670df4d16c8" alt="img" style="zoom: 25%;" />



### 24. Corn or Maize Leaf Disease Dataset

下载地址: https://www.kaggle.com/minhhuy2810/rice-diseases-image-dataset

数据集简要说明: 该数据包含健康，枯萎病，常见锈病，灰叶斑4种病害的4188幅图像。

分类任务：

*图片示例*：

<img src="C:\Users\Huang\AppData\Roaming\Typora\typora-user-images\image-20211205130539765.png" alt="image-20211205130539765" style="zoom:33%;" />

### 25. Plant CV

下载地址: https://plantcv.danforthcenter.org/pages/data.html

数据集简要说明: 

| Plant Species                      | Number of Images | Plants Per Image | Image Type(s)     | Tissue Type | Experiment Type                | Publication                                                  | Link to Data                                                 |
| :--------------------------------- | :--------------- | :--------------- | :---------------- | :---------- | :----------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| *Oryza sativa*                     | ~57,000          | 1                | VIS               | Root        | Growth                         | [Topp et al. 2013](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3645568/) | [Link](https://www.danforthcenter.org/scientists-research/principal-investigators/chris-topp/resources) |
| *Oryza sativa*                     | ~1,400           | 1                | 3D reconstruction | Root        | Growth                         | [Topp et al. 2013](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3645568/) | [Link](https://www.danforthcenter.org/scientists-research/principal-investigators/chris-topp/resources) |
| *Setaria viridis, Setaria italica* | ~79,200          | 1                | VIS, NIR, PSII    | Shoot       | Growth: Water-limited          | [Fahlgren, Feldman, Gehan et al. 2015](https://doi.org/10.1016/j.molp.2015.06.005) | [Link](https://plantcv.danforthcenter.org/pages/data-sets/2013/setaria_burnin2.html) |
| *Setaria viridis, Setaria italica* | ~151,000         | 1                | VIS, NIR, PSII    | Shoot       | Growth: Water-limited          | [Feldman et al. 2017](https://doi.org/10.1101/083865)        | [Link](https://plantcv.danforthcenter.org/pages/data-sets/setaria_height.html) |
| *Sorghum bicolor*                  | 96,867           | 1                | VIS, NIR          | Shoot       | Growth: Nitrogen/Water-limited | [Veley et al. 2017](https://doi.org/10.1101/132787)          | [Link](https://plantcv.danforthcenter.org/pages/data-sets/sorghum_abiotic_stress.html) |
| *Sorghum bicolor*                  | 24,000           | 1                | VIS               | Shoot       | Growth: Nitrogen-limited       | [Berry et al. 2018](https://doi.org/10.1101/354274)          | [Link](https://plantcv.danforthcenter.org/pages/data-sets/sorghum_color_correction.html) |

### Download instructions

Follow the link to a specific dataset for further information about the specific ways the dataset is available.

Datasets available through HTTP (including Figshare, Zenodo, Dryad, etc.) can be downloaded directly using a web browser or with a command-line download utility such as `wget` or `curl`.

Datasets available through [CyVerse](http://www.cyverse.org/) can be accessed through the methods described above for HTTP through the [CyVerse Data Commons](http://datacommons.cyverse.org/browse/iplant/home/shared/danforth_center) or via the CyVerse Data Store (account required) via the path `/iplant/home/shared/danforth_center/`.

Datasets available through [Globus Connect](https://www.globus.org/) can be accessed by signing up for a Globus account and accessing the Danforth Center Data Science Endpoint following the instructions at https://datasci.danforthcenter.org/globus.

### 26. Beans

下载地址: https://github.com/AI-Lab-Makerere/ibean/

数据集简要说明: 

它由3个类组成：2个疾病类和健康类。 疾病包括角状叶斑病和豆锈病。

- **Splits**:

| Split          | Examples |
| :------------- | -------: |
| `'test'`       |      128 |
| `'train'`      |    1,034 |
| `'validation'` |      133 |

```
FeaturesDict({
    'image': Image(shape=(500, 500, 3), dtype=tf.uint8),
    'label': ClassLabel(shape=(), dtype=tf.int64, num_classes=3),
})
```

分类任务：

*图片示例*：

![image-20211205131051056](https://s2.loli.net/2021/12/06/rihkJ2Wjc8SYFTM.png)

### 27. **Soybean (Large) Data Set**

下载地址: https://archive.ics.uci.edu/ml/datasets/Soybean+%28Large%29

数据集简要说明: 

有 19 个类，最后四个类的数据不合理，因为样本很少。 有 35 个分类属性，一些是名义属性，一些是有序属性。 值“dna”表示不适用。属性值用数字编码，第一个值编码为“0”，第二个值编码为“1”，依此类推。未知值编码为“？ ''。

- 分类任务：

```
-- 19 Classes
diaporthe-stem-canker, charcoal-rot, rhizoctonia-root-rot,
phytophthora-rot, brown-stem-rot, powdery-mildew,
downy-mildew, brown-spot, bacterial-blight,
bacterial-pustule, purple-seed-stain, anthracnose,
phyllosticta-leaf-spot, alternarialeaf-spot,
frog-eye-leaf-spot, diaporthe-pod-&-stem-blight,
cyst-nematode, 2-4-d-injury, herbicide-injury.

1. date: april,may,june,july,august,september,october,?.
2. plant-stand: normal,lt-normal,?.
3. precip: lt-norm,norm,gt-norm,?.
4. temp: lt-norm,norm,gt-norm,?.
5. hail: yes,no,?.
6. crop-hist: diff-lst-year,same-lst-yr,same-lst-two-yrs,
same-lst-sev-yrs,?.
7. area-damaged: scattered,low-areas,upper-areas,whole-field,?.
8. severity: minor,pot-severe,severe,?.
9. seed-tmt: none,fungicide,other,?.
10. germination: 90-100%,80-89%,lt-80%,?.
11. plant-growth: norm,abnorm,?.
12. leaves: norm,abnorm.
13. leafspots-halo: absent,yellow-halos,no-yellow-halos,?.
14. leafspots-marg: w-s-marg,no-w-s-marg,dna,?.
15. leafspot-size: lt-1/8,gt-1/8,dna,?.
16. leaf-shread: absent,present,?.
17. leaf-malf: absent,present,?.
18. leaf-mild: absent,upper-surf,lower-surf,?.
19. stem: norm,abnorm,?.
20. lodging: yes,no,?.
21. stem-cankers: absent,below-soil,above-soil,above-sec-nde,?.
22. canker-lesion: dna,brown,dk-brown-blk,tan,?.
23. fruiting-bodies: absent,present,?.
24. external decay: absent,firm-and-dry,watery,?.
25. mycelium: absent,present,?.
26. int-discolor: none,brown,black,?.
27. sclerotia: absent,present,?.
28. fruit-pods: norm,diseased,few-present,dna,?.
29. fruit spots: absent,colored,brown-w/blk-specks,distort,dna,?.
30. seed: norm,abnorm,?.
31. mold-growth: absent,present,?.
32. seed-discolor: absent,present,?.
33. seed-size: norm,lt-norm,?.
34. shriveling: absent,present,?.
35. roots: norm,rotted,galls-cysts,?.
```

### 28. **Plant Pathology 2020 - FGVC7**

下载地址: https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data

数据集简要说明: 

分类任务：健康的叶子、感染苹果锈病的叶子、有苹果黑星病的叶子以及患有不止一种病害的叶子。约3600张图片。

## Files

**train.csv**

- `image_id`: the foreign key
- combinations: one of the target labels
- healthy: one of the target labels
- rust: one of the target labels
- scab: one of the target labels

**images**

A folder containing the train and test images, in jpg format.

**test.csv**

- `image_id`: the foreign key

**sample_submission.csv**

- `image_id`: the foreign key
- combinations: one of the target labels
- healthy: one of the target labels
- rust: one of the target labels
- scab: one of the target labels







