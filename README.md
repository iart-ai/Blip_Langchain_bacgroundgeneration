# Blip_Langchain_bacgroundgeneration
通过Blip将图片中的信息转换成文字，再将文字描述输入Langchain中，通过prompt指导langchain生成背景

##  BLIP: Inference Demo

### Image Captioning
Blip读入图片，可以输入图片路径或者图片url

## Use Langchain generate background
使用Langchain读入方法 `generate_caption`生成的对图片的描述，再使用 prompt `What is top 10 background for {description}?`生成背景。
