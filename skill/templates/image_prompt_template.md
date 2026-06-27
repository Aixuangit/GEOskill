# 插图提示词模板库

本文档为6种插图类型提供完整的 AI 图像生成提示词模板。

---

## 通用前缀

所有提示词开头都添加：

```
landscape, 1792x1024, high quality, professional, --ar 16:9
```

---

## 类型1：数据对比图表

### 子类型A：对比表格

**提示词模板：**
```
landscape, 1792x1024, professional data comparison table, clean design, 
[主题：例如"5款家用吸尘器对比"], 
columns: [列名1, 列名2, 列名3, 列名4], 
rows: [行名1, 行名2, 行名3], 
color scheme: deep blue (#1a365d) and light gray, 
sans-serif font, clear grid lines, white background, 
high quality, professional, minimalist, --ar 16:9
```

**示例：**
```
landscape, 1792x1024, professional data comparison table, clean design, 
主题：5款家用吸尘器对比, 
columns: 品牌, 吸力, 续航时间, 噪音, 价格, 
rows: 戴森, 石头, 追觅, 美的, 小米, 
color scheme: deep blue (#1a365d) and light gray, 
sans-serif font, clear grid lines, white background, 
high quality, professional, minimalist, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
human faces, watermark, text overlay, --no
```

---

### 子类型B：柱状图

**提示词模板：**
```
landscape, 1792x1024, professional bar chart, data visualization, 
[主题：例如"各品牌评分对比"], 
categories: [类别1, 类别2, 类别3, 类别4, 类别5], 
values: [数值1, 数值2, 数值3, 数值4, 数值5], 
color palette: shades of blue, 
white background, clear labels, sans-serif font, 
high quality, professional, minimalist, --ar 16:9
```

**示例：**
```
landscape, 1792x1024, professional bar chart, data visualization, 
主题：5款吸尘器用户满意度评分, 
categories: 戴森, 石头, 追觅, 美的, 小米, 
values: 9.2, 8.8, 8.5, 8.2, 8.0, 
color palette: shades of blue, 
white background, clear labels, sans-serif font, 
high quality, professional, minimalist, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
3d effects, human faces, watermark, --no
```

---

### 子类型C：雷达图

**提示词模板：**
```
landscape, 1792x1024, professional radar chart, multi-dimensional comparison, 
[主题：例如"产品能力维度对比"], 
dimensions: [维度1, 维度2, 维度3, 维度4, 维度5, 维度6], 
[品牌1] data: [数值1, 数值2, 数值3, 数值4, 数值5, 数值6], 
[品牌2] data: [数值1, 数值2, 数值3, 数值4, 数值5, 数值6], 
color scheme: blue line for [品牌1], green line for [品牌2], 
white background, clear labels, sans-serif font, 
high quality, professional, minimalist, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
3d effects, human faces, watermark, --no
```

---

## 类型2：流程示意图

### 子类型A：线性流程

**提示词模板：**
```
landscape, 1792x1024, professional flowchart, linear process, 
[主题：例如"产品迭代流程"], 
steps: [步骤1, 步骤2, 步骤3, 步骤4, 步骤5], 
style: minimalist, clean lines, simple icons, 
color scheme: [品牌色] and light gray, 
white background, sans-serif font, clear arrows, 
high quality, professional, --ar 16:9
```

**示例：**
```
landscape, 1792x1024, professional flowchart, linear process, 
主题：吸尘器迭代升级流程, 
steps: 用户调研, 需求分析, 原型设计, 测试优化, 正式发布, 
style: minimalist, clean lines, simple icons, 
color scheme: blue (#2b6cb0) and light gray, 
white background, sans-serif font, clear arrows, 
high quality, professional, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
complex, human faces, watermark, --no
```

---

### 子类型B：循环流程

**提示词模板：**
```
landscape, 1792x1024, professional circular flowchart, cyclic process, 
[主题：例如"持续改进循环"], 
steps: [步骤1, 步骤2, 步骤3, 步骤4], 
arranged in a circle, 
style: minimalist, clean lines, simple icons, 
color scheme: [品牌色] and light gray, 
white background, sans-serif font, 
high quality, professional, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
complex, human faces, watermark, --no
```

---

## 类型3：场景实拍风

### 子类型A：家居使用场景

**提示词模板：**
```
landscape, 1792x1024, realistic lifestyle photography, 
[场景：例如"现代客厅"], 
[产品：例如"无线吸尘器"] being used naturally, 
warm natural lighting, cozy home environment, 
authentic feeling, no commercial feeling, 
high quality, detailed, 4k, --ar 16:9
```

**示例：**
```
landscape, 1792x1024, realistic lifestyle photography, 
场景：明亮的现代客厅, 
无线吸尘器正在被自然使用, 
温暖的自然光线, 舒适的家居环境, 
真实感, 无广告感, 
high quality, detailed, 4k, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, commercial, advertisement, fake, staged, 
over-edited, bright filters, text overlay, watermark, --no
```

---

### 子类型B：桌面摆放场景

**提示词模板：**
```
landscape, 1792x1024, realistic product photography, 
[产品：例如"无线吸尘器"] placed on [桌面：例如"木质书桌"], 
complementary items around, natural soft lighting, 
clean composition, minimalist style, 
high quality, detailed, 4k, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, commercial, 
text overlay, watermark, --no
```

---

### 子类型C：细节特写场景

**提示词模板：**
```
landscape, 1792x1024, realistic close-up photography, 
[产品细节：例如"吸尘器吸头"], 
showing texture and details, soft natural lighting, 
shallow depth of field, high quality, 
detailed, 4k, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, out of focus, messy, bright colors, 
text overlay, watermark, --no
```

---

## 类型4：新闻配图风

### 子类型A：产品主视觉

**提示词模板：**
```
landscape, 1792x1024, professional product hero shot, 
[产品：例如"戴森吸尘器"], 
clean simple background, professional lighting, 
brand color palette, minimalist composition, 
high quality, commercial but not cheesy, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, 
text overlay, watermark, --no
```

---

### 子类型B：品牌组合

**提示词模板：**
```
landscape, 1792x1024, professional brand visual, 
[品牌名] branding elements, 
brand color: [品牌色], 
clean professional design, minimalist, 
white or light gray background, 
high quality, corporate style, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, 
text overlay, watermark, --no
```

---

## 类型5：科普知识图

### 子类型A：原理示意图

**提示词模板：**
```
landscape, 1792x1024, educational infographic, 
[主题：例如"吸尘器工作原理"], 
clear diagram, simplified visualization, 
annotations pointing to key parts, 
color scheme: fresh colors, light background, 
high quality, educational, easy to understand, --ar 16:9
```

**示例：**
```
landscape, 1792x1024, educational infographic, 
主题：无线吸尘器工作原理, 
clear diagram, simplified visualization, 
annotations pointing to: 电机, 吸尘口, 滤网, 集尘盒, 
color scheme: fresh blue and green, light background, 
high quality, educational, easy to understand, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, complex, cartoon, anime, 
text heavy, watermark, --no
```

---

### 子类型B：结构解剖图

**提示词模板：**
```
landscape, 1792x1024, educational exploded view diagram, 
[产品：例如"吸尘器"] internal structure, 
parts labeled clearly, 
simplified illustration style, 
educational, easy to understand, 
high quality, professional, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, complex, cartoon, anime, 
text heavy, watermark, --no
```

---

## 类型6：行业趋势图

### 子类型A：趋势折线图

**提示词模板：**
```
landscape, 1792x1024, professional line chart, trend visualization, 
[主题：例如"吸尘器市场增长趋势"], 
time period: [时间段：例如"2021-2026"], 
data points clearly marked, 
color scheme: professional blues and grays, 
white background, clear labels, 
high quality, professional, --ar 16:9
```

**示例：**
```
landscape, 1792x1024, professional line chart, trend visualization, 
主题：吸尘器市场增长趋势2021-2026, 
time period: 2021, 2022, 2023, 2024, 2025, 2026, 
upward trend line, 
color scheme: professional blues and grays, 
white background, clear labels, 
high quality, professional, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
3d effects, watermark, --no
```

---

### 子类型B：市场占比饼图

**提示词模板：**
```
landscape, 1792x1024, professional pie chart, market share visualization, 
[主题：例如"吸尘器市场份额"], 
segments: [品牌1, 品牌2, 品牌3, 品牌4, 其他], 
color palette: professional distinct colors, 
white background, clear percentage labels, 
high quality, professional, --ar 16:9
```

**负面提示词：**
```
blurry, low quality, messy, cluttered, bright colors, cartoon, anime, 
3d effects, watermark, --no
```

---

## 多图一致性

为同一篇文章生成多张插图时，在所有提示词开头添加：

```
Consistent style with previous images, same color palette, 
```

确保风格统一。

---

## 提示词优化技巧

1. **具体化**：尽可能描述清楚内容，不要模糊
2. **风格指定**：明确说明"realistic"、"professional"、"minimalist"等
3. **技术参数**：包含尺寸、画质要求
4. **负面提示**：明确列出不需要的元素
5. **品牌适配**：如果有品牌色，明确指定
