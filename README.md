# comfyui_zerotohero
Updated comfyui workflow construction method,brothers who want to learn can have a look at the tutorial of my @hexiaoyu946  homepage, the following document will also update the knowledge points at any time.
Where can I study?
AI generated images are still controversial at this stage, I will only update the software tutorial of ComfyUI in the Short Video Platform, brothers and sisters who want to learn can have a look at the tutorial of my @He Xiaoyu colleague homepage, the following document will also update the knowledge points involved in the video at any time.
At the same time, I will every Saturday night 20:00-22:00 LIVE demonstrate some workflow construction methods, LIVE construction part of the workflow will be updated in the workflow table , brothers and sisters who want to play together are welcome to communicate between LIVE, of course, if there is free time on working day, we will also LIVE.
In addition, if the boss needs to customize the workflow, you can private message me to talk about your needs. At present, AI design, AI photography, AI picture book and other directions of workflow can be built.
Knowledge Base link: https://sli4b6l3vs.feishu.cn/docx/UORRdL8apoS0b3x1CLAc34gJnBe
Personal profile
Social media homepages
Self-proclaimed: the first AI design workflow builder on the entire network
Now: a wild operation designer
Once upon a time, I was a seasoned software player
Present on all major platforms with the same name, sharing AI design tutorials irregularly through LIVE. Thank you for your attention~
Douyin's personal homepage: Share ComfyUI tutorials and application scenarios
Bilibili personal homepage: Share PS, AI, PR, AE tutorials
RED personal homepage: Share the application scenarios of AI in work
Watermelon Video Personal Homepage: Synchronous Douyin high definition ComfyUI Landscape Tutorial
Personal details

Proposer of the concept of "AI version of Photoshop" , contracted author of People's Posts and Telecommunications Publishing House, contracted author of Electronic Industry Publishing House, author of "Photoshop CC 2018 Basic Tutorial", author of "Illustrator 2020 Practical Tutorial", author of "Illustator 2022 Practical Tutorial", wild operation designer with 5 years of design experience , senior software player with 5 years of time, Bilibili 45,000 fans UP master, Bilibili 700,000 + explosive content creators, Xigua Video 200,000 + explosive content creators, 2019 Bilibili insists on 365 days of content creation behavior art completion .
[图片]

Practical application scenarios
Category
Demonstration example
AI design

Operation poster, brand extension design, font design, packaging design, illustration

暂时无法在飞书文档外展示此内容
暂时无法在飞书文档外展示此内容
暂时无法在飞书文档外展示此内容
AI photography
E-commerce products, e-commerce clothing, wedding dresses, Hanfu, fantasy, children

[图片]
[图片]
[图片]
[图片]
[图片]
AI picture book
Short film storyboards, comics, children's picture books

[图片]
[图片]
[图片]
[图片]
[图片]
[图片]
Game CG
Game character concept art, game scene concept art

Architectural design
Interior design renderings, architectural design renderings, landscape design renderings

[图片]
[图片]
Industrial design
Industrial design renderings

I. Workflow sharing
The table below will continue to update the workflow I have built. You can load the workflow directly by dragging the image into the software In addition, if you have any new ComfyUI gameplay you want to learn, you can also express your needs in the comment section of this document. I will give corresponding feedback according to the situation after studying. Of course, there are inevitably two possibilities. One is that I have understood it, and I will make a tutorial to share it. The other is that I have not understood it, and I will reply in the comment section of this document.

Date
Workflow name
Sample drawing
Download link
2023.12.20
Chinese style illustration workflow
[图片]
[图片]
He Xiaoyu colleague's workflow 
2023.12.30
Spring/Summer Autumn/Winter Workflow
[图片]
[图片]
He Xiaoyu colleague's workflow 
2024.1.20
Real-time portrait generation
[图片]
[图片]
He Xiaoyu colleague's workflow 
2024.1.20
Real-time painting
[图片]
[图片]
He Xiaoyu colleague's workflow 
Software introduction and installation
1. Software Introduction
Comfyui is a Stable diffusion graphical User Interface (GUI) that uses node-based interaction logic. It far exceeds other Stable diffusion graphical User Interfaces in flexibility and playability, and can be used to generate text, images, audio, video, 3D models . However, due to hardware technology and the limitations of large-scale Model Training, image generation is mainly used at this stage. Its application range is wide, and the known applicable scenarios include AI design, AI photography, game CG, AI picture book, architectural design, industrial design and other fields. It is generally used to assist in the production of renderings. Demonstration examples (some of which are landing projects) have been attached to the top table.
[图片]
[图片]
2. Native installation
The native installation of ComfyUI mainly includes three steps: operating environment setup, software Compressed Packet download and decompression, and basic configuration . You can follow the steps below to complete the installation.
A. Python and git download
First of all, you need to set up a good Python environment, and also need to download the git application, mainly to ensure the normal operation of ComfyUI and grab the code of the plug-in from GitHub . After downloading the installation package, click install directly. When installing, just mindlessly " Next ".
Software name
Download link
python
  https://www.python.org/downloads/release/python-3106/
git
  https://git-scm.com/download/win
[图片]
[图片]
B. Download ComfyUI Compressed Packet
After installing Python and Git, go directly to GitHub and search for ComfyUI . Then find " Direct link to download " on the code repository page of the project and click on it. After the download is completed, create a new folder with an English name on your computer hard drive and extract the Compressed Packet to that folder.
Software name
Download link
ComfyUI
https://github.com/comfyanonymous/ComfyUI/releases/download/latest/ComfyUI_windows_portable_nvidia_cu121_or_cpu.7z
[图片]
[图片]

[图片]
C. Startup method and model sharing
After the decompression is completed, enter the folder and click on the " run_nvidia_gpu .bat " executable file to start ComfyUI. You can also create a shortcut to the bat file and put it on the desktop, and click to start it directly. In addition, if you want to share the SD WebUI model with the ComfyUI model, you can click on the " ComfyUI " folder, find the " extra_model_paths yaml.example " file, press F2 to delete " .example ", then open the renamed file with Notepad, and copy the SD WebUI path to the position in the figure. Similarly, some models with fine-tuning models and plugins can also be directly copied to the corresponding location to complete the sharing.
[图片]
[图片]
[图片]
3. Third-party installation package
Third-party installation packages are relatively more convenient for software and model management during installation. After downloading the installation package directly, you can install it on your computer. It is very friendly to colleagues who have no foundation. If you don't want to go back and forth, you can choose to install the third-party installation package. At present, there are two main ones I know, one is StabilityMatrix , and the other is Autumn Leaf Launcher .
a、StabilityMatrix
This plug-in can install mainstream SD User Interface with one click, such as ComfyUI, SD WebUI, Fooocus can be installed with one click, and you can also download and manage large models in this application.
Type
Download link
Software installation package
Software github download link
https://github.com/LykosAI/StabilityMatrix
暂时无法在飞书文档外展示此内容
Official website download link
 https://lykos.ai/

[图片]
[图片]

B. Autumn leaf starter
I have not used this thing. You can take a look at the installation video posted by Bilibili himself. The video link is attached below. After downloading SD WebUI according to the demonstration in his video, simply copy the "A Launcher " to the ComfyUI folder. That is to say, to use this installation package, you still need to download the Compressed Packet of ComfyUI and extract it to the computer. The specific steps have been written in the software installation section. You can check it up. If it is not very clear, you can search for the installation tutorial on the Internet
Software name
Download link
Autumn leaf starter
https://www.bilibili.com/video/BV1iM4y1y7oA/?share_source=copy_web&vd_source=a10cbc347d1729cc8d8d1584b147cfcc
[图片]
III. Plugin installation
Generally speaking, you only need to search for the corresponding plug-in keywords in GitHub to complete the installation. You can use manual installation, command line installation, manager installation three ways, but it is recommended to use manual download after use, because there is a high probability of installation failure using command line and manager. Of course, if you use the Autumn Leaf launcher, you can download the plug-in directly in the launcher.
1. Installation method
A. Manual download
Similar to the installation of the software itself, the plugin also needs to go to GitHub to search for the corresponding plugin keywords to complete the installation. Taking controlnet as an example, click " code " on the code repository page of its project, click " download zip " in the pop-up window, unzip it directly after downloading, and copy the extracted folder to the path of ComfyUI_windows_portable\ ComfyUI\ custom_nodes to complete the installation. If you want to update the plugin, repeat the above operation and replace the old version.
[图片]
[图片]
B. git clone command download
Select ComfyUI_windows_portable\ ComfyUI\ custom_nodes file path in the Explorer, then enter cmd and press Enter. Enter "git clone + plugin github link" at the end point of the command line to grab the plugin to the local folder. However, it is also easy to download failure, so try more.
[图片]
[图片]
C. Download manager
Manager is a plugin used by ComfyUI to manage plugins. After installing this plugin, the "manager" button will appear in the control bar of ComfyUI. Click the button "install custom nodes" in the pop-up window, search for the keyword of the plugin in the pop-up window, and then click "install". However, it is generally easy to fail to install.
[图片]
[图片]
[图片]

2. Recommended basic plugins
Due to the fact that most of ComfyUI's plugins are developed by users themselves, there are a variety of plugins available. Here, only a few very basic and essential plugins can be listed. The download link is attached to the table, just click to download it.
Plugin name
Plugin introduction page screenshot
Remarks
Download link
ComfyUI Manager
[图片]
Plugin management plugin
https://github.com/ltdrdata/ComfyUI-Manager
ComfyUI Workspace Manager


[图片]
[图片]
[图片]
[图片]
[图片]
Plugin for work flow management. According to the official documentation of the project, the function of installing large models with one click will be updated later
https://github.com/11cafe/comfyui-workspace-manager
ComfyUI Browser


[图片]
Browse the plugin for generating graphs. There is overlap with the previous plugin. If the subsequent comfyspace iteration is complete, you can directly use comfyspace
https://github.com/talesofai/comfyui-browser
3. Latest plug-in search method
Search ComfyUI on GitHub , then select sort by recent updates at the top of the search results, then the plugins that have been updated recently will be sorted from near to far according to the update time, so you can always check these sorts and find many new plugins.
[图片]


IV. Model configuration and download

Model download can go to civitai and huggingface to search for the English name of the model to complete the download. Generally speaking, if you want to download the official model, you usually use huggingface to download. If you want to download a variety of models, you can use civitai to download.
1. Model overview and classification
Stable diffusion models are mainly divided into four types: large model, VAE model, CLIP model, and fine-tuning model. Generally speaking, the large model/checkepoint model and Lora model play a decisive role in the drawing effect
A. Type of model
Model type
Overview
VAE model
Variational Autoencoder
Variational autoencoder is a text, image, and audio generative model. Large models generally come with VAE models, and special cases require separate loading
CLIP model
Contrastive Language-Image Pretraining
Image-text comparison pre-trained model is a bridge between text and image

Large model/bottom model
Checkpoint models, such as SD1.5, SDXL, SSD, etc., generally have generalization and versatility
Fine tuning model/fune tuning
Models like lora, embedding, and hypernetwork all belong to fine-tuning models and need to be used in conjunction with large models
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

B. Version of the model
Version type
Overview
pruned
Pruning removes redundant nerve cells or links, simplifying neural networks. Runs fast and models are smaller.
ema
Smooth the oscillation and fluctuation of the model, improve robustness and generalization, and ensure the stability of the graph style
fp16/fp32
Less precision/more precision
[图片]
[图片]
[图片]
C. Model extension
Extension type
Overview
.safetensors
Safetensor, a format for storing model parameters and weights for large models, with good data security
.cpkt
Pickletensor, a format for storing model parameters and weights for large models
.pth
Usually only plug-in models will use this extension, such as controlnet
.bin
Usually only plug-in models will use this extension, such as ipadapter
.oonx

difference between safetensor and pickle tensor?
[图片]
2. Model configuration
After downloading the model, you need to put the model into the designated folder of ComfyUI to take effect. Essentially, it is the same as using Stable diffusion WebUI. Remember not to confuse the basic model with the plug-in model. The plug-in model is placed in the folder of the basic model. It does not work.
A. Configuration of the base model
Model category
Placed file path
Large model/checkpoint
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
Amplification model/upscale_model
ComfyUI_windows_portable\ComfyUI\models\upscale_models

[图片]
B. Configuration of plug-in model
Plugin category
Placed file path
controlnet
 ComfyUI_windows_portable\ComfyUI\models\controlnet
ipadapter
ComfyUI_windows_portable\ComfyUI\custom_nodes\ComfyUI_IPAdapter_plus_main\models
[图片]
3. Download civitai
Civitai is mainly used to download user-trained checkpoint, Lora, embedding and other models, with high playability. You can enter the English name of the model to search after entering the website, and click the download button under the model introduction to download.
[图片]
SD1.5 large model recommendation
Here are some SD1.5 models with high download volume on civitai , and I use some SD1.5 models with relatively good picture effect, which can be downloaded according to their own needs
Supported models
Model introduction page screenshot
Download link
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
B. SD1.5 Lora recommendation
Supported models
Model introduction page screenshot
Download link
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
C. SD1.5 Embedding Recommendation

(embedding:easynegative:1),(embedding:negative_hand:1),(embedding:bad_prompt_version2:1),(embedding:ng_deepnegative_v1_75t:1)
Supported models
Model introduction page screenshot
Download link
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
D. SDXL model recommendation
Here are some SDXL models with high download volume on civitai , and I use some SDXL models with relatively good picture effect, which can be downloaded according to their own needs
Supported models
Model introduction page screenshot
Download link
NewRealityXL

[图片]
https://civitai.com/models/161068/newrealityxl-photographic-all-in-one
dreamshaper-xl

[图片]
https://civitai.com/models/112902/dreamshaper-xl

XXMix_9realisticSDXL
[图片]
https://civitai.com/models/124421?modelVersionId=163192
4. Download huggingface
Huggingface is mainly used to download some basic large models and lora released by the official, as well as some models required for plugins. You can also enter keywords here to download
A, SD1.5 model download
Go to huggingface enter the keyword stable-diffusion-v1-5 , enter the model introduction page, click the second tab, download the accuracy of fp16, of course, if there is a large hard disk space, download the above 14GB is also no problem
Model name
Download link
SD1.5
https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main
[图片]
B. SDXL model download
Go to huggingface and enter the keyword stable-diffusion-xl . After entering the model introduction page, click the second tab and download SDXL 1.0
Model name
Download link
SDXL
https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0/tree/main
[图片]
C. SDXL_Turbo model download
Go to huggingface and enter the keyword sdxl-turbo , enter the model introduction page, click the second tab, download the accuracy of fp16, of course, if there is a large hard disk space, download the above 14GB is also no problem
Model name
Download link
SDXL_Turbo 
https://huggingface.co/stabilityai/sdxl-turbo/tree/main
[图片]
D. LCM model download
Go to huggingface and enter the keyword LCM . After entering the model introduction page, click the second tab to download the file with the extension safetensors, which is the LCM model. Below are three SD versions of the LCM model download links. Click directly to jump to the corresponding page for download.
Supported models
Download link
Support SD1.5 LCM model download
https://huggingface.co/latent-consistency/lcm-lora-sdv1-5/tree/main
LCM model download with SDXL support
https://huggingface.co/latent-consistency/lcm-lora-sdxl/tree/main
LCM model download with SSD (SDXL_Distilled) support
https://huggingface.co/latent-consistency/lcm-lora-ssd-1b/tree/main
[图片]









