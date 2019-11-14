# chinese-idcard-text-renderer
用于生成Chinese idcard ocr所需文本图像。  
原作者工程链接:https://github.com/Sanster/text_renderer。  
基于densenet+ctc进行文本识别，参考https://github.com/YCG09/chinese_ocr  。  
生成文本图像前，需检查字体是否支持字典中所有字符！身份证证面字体包括：华文细黑、方正黑体、黑体、号码特定字体，见。
# 更改
1.添加身份证正反面背景；  
2.图像指数增强、gamma变换扩充样本；  
3.通过水平压缩来达到垂直方向拉伸字符的效果，模拟阴影、光线暗；  
4.由于后续ocr工程不是按传统的步骤，并未检测文字区域，所以增加背景上下留白以满足前处理需求；  
5.添加身份证证面字体，及身份证号码特殊字体。  
# 生成样例



