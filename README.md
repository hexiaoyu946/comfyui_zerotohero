到哪里可以进行学习？
AI生成图像现阶段还存在争议性，我只会在短视频平台更新ComfyUI的软件教程，想学习的哥哥姐姐可以看看我@何小鱼同学主页的教程，下方文档也会随时更新视频中所涉及的知识要点。
同时我会在每周六晚上20:00-22:00直播演示一些工作流的搭建方法，直播搭建的部分工作流会更新在工作流的表格里，想一起玩的哥哥姐姐欢迎来直播间交流，当然如果工作日有空的话也会直播的。
另外如果有老板需要工作流定制，可以私信我详聊你的需求，目前AI设计、AI摄影、AI绘本等方向的工作流都可以搭建。
知识库链接：https://sli4b6l3vs.feishu.cn/docx/UORRdL8apoS0b3x1CLAc34gJnBe
暂时无法在飞书文档外展示此内容
个人简介
社交媒体主页
自诩是：全网第一位AI设计工作流搭建师
现在是：一只野生的运营设计师
曾经是：一名资深的软件玩家
全平台同名，不定期直播分享AI设计教程，感谢关注～
抖音个人主页：分享ComfyUI教程及应用场景
B站个人主页：分享PS、AI、PR、AE教程
小红书个人主页：分享AI在工作中的应用场景
西瓜视频个人主页：同步抖音高清ComfyUI横屏教程
个人详细介绍

"AI版photoshop"概念提出者，人民邮电出版社签约作者、电子工业出版社签约作者、《Photoshop CC 2018基础教程 》图书作者、《illustrator 2020实用教程 》图书作者、《illustator 2022实用教程》图书作者、5年设计经验的野生运营设计师、时长5年的资深软件玩家、B站4.5w粉UP主、B站70w+爆款内容创作者、西瓜视频20W+爆款内容创作者、2019年B站坚持365天内容创作行为艺术完成者。
[图片]

实际应用场景
类目
演示样例
AI设计

运营海报、品牌延展设计、字体设计、包装设计、插画

暂时无法在飞书文档外展示此内容
暂时无法在飞书文档外展示此内容
暂时无法在飞书文档外展示此内容
AI摄影
电商产品、电商服饰、婚纱、汉服、奇幻、儿童

[图片]
[图片]
[图片]
[图片]
[图片]
AI绘本
电影短剧分镜、漫画、儿童绘本

[图片]
[图片]
[图片]
[图片]
[图片]
[图片]
游戏CG
游戏角色原画、游戏场景原画

建筑设计
室内设计效果图、建筑设计效果图，景观设计效果图

[图片]
[图片]
工业设计
工业设计效果图

一、工作流分享
下方表格会持续更新我搭建好的工作流，图片直接拖动软件中就可以加载工作流。另外如果你有想学的一些ComfyUI新玩法也可以在本文档评论区说出你的需求，我会在研究之后根据情况给到相应反馈。当然难免会有两种可能，一种是我研究明白了，我会做教程分享出来；二是没有研究明白，那我会在本文档的评论区给到回复。

日期
工作流名称
样图
下载地址
2023.12.20
国风插画工作流
[图片]
[图片]
何小鱼同学的工作流 
2023.12.30
春夏秋冬工作流
[图片]
[图片]
何小鱼同学的工作流 
2024.1.20
实时人像生成
[图片]
[图片]
何小鱼同学的工作流 
2024.1.20
实时绘画
[图片]
[图片]
何小鱼同学的工作流 
二、软件简介及安装
1、软件简介
Comfyui是一个采用节点式交互逻辑的Stable diffusion图形用户界面（GUI），在灵活性和可玩性上远远超过其他Stable diffusion的图形用户界面，可以用其生成文本、图像、音频、视频、3D模型，但由于硬件技术及大模型训练的条件限制，现阶段主要以图像生成为主。其应用范围广泛，目前我已知的可应用场景包括AI设计、AI摄影、游戏CG、AI绘本、建筑设计、工业设计 等领域，一般用来辅助产出效果图，演示样例（部分为落地项目）已经附带在最上方表格了。
[图片]
[图片]
2、原生安装
ComfyUI的原生安装主要有运行环境搭建、软件压缩包下载及解压、基础配置三个步骤。可按以下步骤依次操作即可完成安装。
a、python和git下载
首先需要搭建好Python的环境，同时还需要下载git这个应用程序，主要是用来保证ComfyUI的正常运行以及从github上抓取插件的代码。下载好安装包后直接点安装，安装时直接无脑“下一步”即可。
软件名称
下载链接
python
  https://www.python.org/downloads/release/python-3106/
git
  https://git-scm.com/download/win
[图片]
[图片]
b、下载ComfyUI压缩包
安装完python和git之后，直接来到github搜索ComfyUI，接着在该项目的代码仓库页面找到“Direct link to download”并点击，下载完成之后直接在自己的电脑硬盘上新建一个名字为英文名的文件夹，并将压缩包解压到该文件夹。
软件名称
下载链接
ComfyUI
https://github.com/comfyanonymous/ComfyUI/releases/download/latest/ComfyUI_windows_portable_nvidia_cu121_or_cpu.7z
[图片]
[图片]

[图片]
c、启动方式及模型共用
解压完成后进入该文件夹，点“run_nvidia_gpu.bat”的执行文件即可启动ComfyUI，也可以把该bat文件创建一个快捷方式放到桌面，直接点击即可启动。另外如果想让SD WebUI的模型和ComfyUI的模型共用，可以点开“ComfyUI”文件夹，找到“extra_model_paths.yaml.example”的文件按F2把“.example”删除掉，接着用记事本打开重命名完成后的文件，将SD WebUI路径复制到图中的位置即可。同样一些微调模型和插件的模型也可直接把文件路径复制到相应的位置上也可完成共用。
[图片]
[图片]
[图片]
3、第三方安装包
第三方安装包在安装时相对来说在软件、模型的管理上会更加方便，直接下载好安装包后，安装在电脑就可以了，对于没有基础的同学非常友好，如果不想来回折腾，可以选择安装第三方的安装包。目前我已知的主要有两款一是StabilityMatrix，二是秋叶启动器。
a、StabilityMatrix
这个插件可以一键安装主流的SD的用户界面，像ComfyUI、SD WebUI、Fooocus都能一键安装，同时还可以在这个应用程序内进行大模型的下载和模型的管理。
类型
下载链接
软件安装包
软件github下载链接
https://github.com/LykosAI/StabilityMatrix
暂时无法在飞书文档外展示此内容
官网下载链接
 https://lykos.ai/

[图片]
[图片]

b、秋叶启动器
我并没有使用过他这个东西，可以看一下B站他本人发的安装视频，视频链接已经附带在下方了，按照他视频中的演示下载好SD WebUI后，直接把“A启动器”复制到ComfyUI的文件夹中就可以了。也就是说使用这个安装包还是需要去下载好comfyui的压缩包并解压到电脑上的，具体步骤已经在软件安装的部分写明了，可以往上翻查看一下。如果不是很清晰可以自行在网上查找一下安装教程
软件名称
下载链接
秋叶启动器
https://www.bilibili.com/video/BV1iM4y1y7oA/?share_source=copy_web&vd_source=a10cbc347d1729cc8d8d1584b147cfcc
[图片]
三、插件安装
一般而言只需要在github搜索相应的插件关键词即可完成安装。可以采用手动安装、命令行安装，manager安装三种方式，不过在使用过后推荐使用手动下载，因为使用命令行和manager都有有很大的概率安装失败，当然如果是使用了秋叶启动器的话直接在启动器里就可以进行插件的下载了。
1、安装方法
a、手动下载
与软件本体的安装相似，插件同样需要前往github搜索相应的插件的关键词才能完成安装。以controlnet为例，在其项目的代码仓库页面点击“code”，在弹出的小窗口中点“download zip ”，下载完成之后直接解压，并将解压得到该文件夹复制到ComfyUI_windows_portable\ComfyUI\custom_nodes这个路径下就完成了安装。如果想更新插件重复上述操作，替换掉老版本就行了。
[图片]
[图片]
b、git clone命令下载
在资源管理器中全选ComfyUI_windows_portable\ComfyUI\custom_nodes这个文件路径，接着输入cmd按回车，在命令行终端上输入“git clone + 插件github链接”即可对插件抓取到该本地文件夹中，但是也很容易下载失败，可以多尝试。
[图片]
[图片]
c、manager下载
manager是ComfyUI用来管理插件的插件，当安装好这个插件之后，在ComfyUI的控制栏中会出现“manager”的按钮，点击之后在弹出的窗口点“install custom nodes”的按钮，在弹出的窗口搜索插件的关键词，搜索到之后再点“install”就可以了，不过一般来说很容易就会安装失败。
[图片]
[图片]
[图片]

2、基础插件推荐
由于ComfyUI的插件大部分都是用户自行开发的，所以插件丰富，各式各样的都有，这里只能列举几个非常基础，可以说是必装的插件，下载链接已经附带在表格中了，点进去下载一下就行。
插件名称
插件简介页面截图
备注
下载链接
ComfyUI Manager
[图片]
插件管理的插件
https://github.com/ltdrdata/ComfyUI-Manager
ComfyUI Workspace Manager


[图片]
[图片]
[图片]
[图片]
[图片]
工作流管理的插件，根据项目的官方文档的说明，后续还会更新一键安装大模型的功能
https://github.com/11cafe/comfyui-workspace-manager
ComfyUI Browser


[图片]
浏览生成图的插件，与上一个插件有重叠之处，如果后续comfyspace迭代完全之后可以直接用comfyspace就可以了
https://github.com/talesofai/comfyui-browser
3、最新插件查找方法
在github搜索ComfyUI，接在搜索结果的顶部选择按照最近更新进行排序，那么最近有过更新的插件就会按照更新时间从近到远依次排序，那么随时查看这些排序就会发现很多新插件。
[图片]


四、模型的配置及下载

模型下载可以前往civitai和huggingface搜索模型的英文名完成下载，一般而言如果想下载官方的模型通常会使用huggingface进行下载，如果想下载多样化的模型可以使用civitai进行下载。
1、模型概述及分类
stable diffusion的模型主要分为大模型、VAE模型、CLIP模型，微调模型这四种，通常来说对出图效果起到决定性作用的是大模型/checkepoint模型和Lora模型
a、模型的类型
模型类型
概述
VAE模型
Variational Autoencoder
变分自动编码器,是一个文本、图像、音频生成模型，大模型一般自带VAE模型，特殊性情况需要单独加载
CLIP模型
Contrastive Language-Image Pretraining
图片文本对比预训练模型，是文本转图像之间的桥梁

大模型/底模型
checkpoint模型，如SD1.5、SDXL、SSD等，一般来说具有泛化性、通用性
微调模型/fune tuning
像lora、embedding、hypernetwork都属于微调模型，需要配合大模型使用
Understanding Variational Autoencoders (VAEs) 
[图片]
Learning Transferable Visual Models From Natural Language Supervision
[图片]
What are LoRA models and how to use them in AUTOMATIC1111
[图片]
What are hypernetworks and the ones you should know
[图片]
How does Stable Diffusion work?
[图片]
How to use embeddings in Stable Diffusion
[图片]

b、模型的版本
版本类型
概述
pruned
剪枝删除冗余的神经元或链接，简化神经网络。运行速度快，模型更小。
ema
平滑模型的震荡和波动，提高鲁棒性和泛化性，保证出图风格的稳定
fp16/fp32
精细度更小/精细度更大
[图片]
[图片]
[图片]
c、模型的扩展名
扩展名类型
概述
.safetensors
safetensor，一种用于存储大模型的模型参数和权重的格式，在数据的安全性上较好
.cpkt
pickletensor，一种用于存储大模型的模型参数和权重的格式
.pth
通常只有插件的模型会采用这种扩展名，如controlnet
.bin
通常只有插件的模型会采用这种扩展名，如ipadapter
.oonx

difference between safetensor and pickle tensor?
[图片]
2、模型的配置
下载完模型之后需要把模型放到ComfyUI的指定文件夹内才能生效，本质上跟使用Stable diffusion WebUI是一样的，记得基础模型和插件模型不要搞混了，插件模型放到基础模型的文件夹当中是不起作用的。
a、基础模型的配置
模型类别
放置的文件路径
大模型/checkpoint
ComfyUI_windows_portable\ComfyUI\models\checkpoints
lora
ComfyUI_windows_portable\ComfyUI\models\loras
embedding
ComfyUI_windows_portable\ComfyUI\models\embeddings
UNet
ComfyUI_windows_portable\ComfyUI\models\unet
VAE
ComfyUI_windows_portable\ComfyUI\models\vae
clip
ComfyUI_windows_portable\ComfyUI\models\clip
clip_vison
ComfyUI_windows_portable\ComfyUI\models\clip_vision
hypernetwork
ComfyUI_windows_portable\ComfyUI\models\hypernetworks
放大模型/upscale_model
ComfyUI_windows_portable\ComfyUI\models\upscale_models

[图片]
b、插件模型的配置
插件类别
放置的文件路径
controlnet
 ComfyUI_windows_portable\ComfyUI\models\controlnet
ipadapter
ComfyUI_windows_portable\ComfyUI\custom_nodes\ComfyUI_IPAdapter_plus_main\models
[图片]
3、civitai下载
civitai主要用于下载用户自行训练的checkpoint、Lora、embedding等模型，可玩性很高。可以进入网站之后输入模型的英文名进行搜索，在模型的简介下面点击下载按钮即可进行下载。
[图片]
a、SD1.5大模型推荐
下面是一些civitai上面下载量较高，同时我使用后出图效果相对较好的一些SD1.5模型，可以根据自己自身需求选择下载
支持的模型
模型简介页面截图
下载链接
dreamshaper   

[图片]
https://civitai.com/models/4384/dreamshaper

revAnimated

[图片]
https://civitai.com/models/7371/rev-animated
Counterfeit-V3.0

[图片]
https://civitai.com/models/4468/counterfeit-v30

GhostMix
[图片]
https://civitai.com/models/36520/ghostmix
Beautiful Realistic Asians

[图片]
https://civitai.com/models/25494/beautiful-realistic-asians

epiCPhotoGasm

[图片]
https://civitai.com/models/132632?modelVersionId=223670

realisticVision

[图片]

https://civitai.com/models/4201?modelVersionId=245598
b、SD1.5 Lora推荐
支持的模型
模型简介页面截图
下载链接
Studio Ghibli Style LoRA

[图片]
https://civitai.com/models/6526/studio-ghibli-style-lora
Red Dead Redemption Artstyle
[图片]
https://civitai.com/models/89532?modelVersionId=95311
Cyber World
[图片]
https://civitai.com/models/159317/cyber-world
Arcane Style LoRA
[图片]
https://civitai.com/models/7094/arcane-style-lora

Cartoon - Jenő Rejtő - Korcsmáros
[图片]
https://civitai.com/models/6815/cartoon-jeno-rejto-korcsmaros
c、SD1.5 Embedding推荐

(embedding:easynegative:1),(embedding:negative_hand:1),(embedding:bad_prompt_version2:1),(embedding:ng_deepnegative_v1_75t:1)
支持的模型
模型简介页面截图
下载链接
EasyNegative
[图片]
https://civitai.com/models/7808/easynegative
Deep Negative V1.x
[图片]

https://civitai.com/models/4629/deep-negative-v1x
negative_hand Negative Embedding
[图片]
https://civitai.com/models/56519/negativehand-negative-embedding
bad_prompt Negative Embedding

[图片]
https://civitai.com/models/55700/badprompt-negative-embedding
d、SDXL模型推荐
下面是一些civitai上面下载量较高，同时我使用后出图效果相对较好的一些SDXL模型，可以根据自己自身需求选择下载
支持的模型
模型简介页面截图
下载链接
NewRealityXL

[图片]
https://civitai.com/models/161068/newrealityxl-photographic-all-in-one
dreamshaper-xl

[图片]
https://civitai.com/models/112902/dreamshaper-xl

XXMix_9realisticSDXL
[图片]
https://civitai.com/models/124421?modelVersionId=163192
4、huggingface下载
huggingface主要用来下载官方发布的一些基础大模型和lora，以及一些插件所需的模型也可以到此输入关键词进行下载
a、SD1.5模型下载
前往huggingface输入关键词stable-diffusion-v1-5，进入模型简介页面后点第二个选项卡，下载精度为fp16的就可以，当然如果有较大的硬盘空间，下载上面14GB的也没问题
模型名称
下载链接
SD1.5
https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main
[图片]
b、SDXL模型下载
前往huggingface输入关键词stable-diffusion-xl，进入模型简介页面后点第二个选项卡，下载SDXL 1.0就可以
模型名称
下载链接
SDXL
https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main
[图片]
c、SDXL_Turbo模型下载
前往huggingface输入关键词sdxl-turbo，进入模型简介页面后点第二个选项卡，下载精度为fp16的就可以，当然如果有较大的硬盘空间，下载上面14GB的也没问题
模型名称
下载链接
SDXL_Turbo 
https://huggingface.co/stabilityai/sdxl-turbo/tree/main
[图片]
d、LCM模型下载
前往huggingface输入LCM这个关键词，进入模型简介页面后点第二个选项卡，下载扩展名为safetensors的文件即为LCM模型，下方整理了三种SD版本的LCM模型下载链接，直接点击即可跳转到相应的页面进行下载。
支持的模型
下载链接
支持SD1.5的LCM模型下载   
https://huggingface.co/latent-consistency/lcm-lora-sdv1-5/tree/main
支持SDXL的LCM模型下载   
https://huggingface.co/latent-consistency/lcm-lora-sdxl/tree/main
支持SSD（SDXL_Distilled）的LCM模型下载  
https://huggingface.co/latent-consistency/lcm-lora-ssd-1b/tree/main
[图片]









