# Photoshop插件LLAI-PSAPI，适用版本23.0以上  
操作教程查看👉：https://my.feishu.cn/wiki/IL63w8z6mizaQdkNfTEcB3lanqd?from=from_copylink

## 低价API
低价API tab 用于调用插件内置的低价图像接口，支持 `gpt-image-2`、Gemini 图像模型等。可进行文生图、图生图，支持从 Photoshop 获取选区、获取全图，或添加本地参考图，最多可添加多张参考图。生成时可选择比例、分辨率，并支持结果预览、停止任务、结果回输和一键插入图层。图生图模式下可精确放置到原选区位置和尺寸。

## RunningHub
RunningHub tab 用于运行 RunningHub 工作流。填写 API Key 和 Workflow ID 后，可加载工作流 JSON，插件会自动识别 Prompt、图片输入节点和可修改参数。支持保存/加载/删除工作流预设，适合常用工作流快速复用。可从选区、全图或本地图片添加输入图，运行后支持多结果预览、切换结果图、插入图层、结果回输和精确放置。

## ComfyUI
ComfyUI tab 用于连接本地 ComfyUI。可填写本地地址并测试连接，加载 ComfyUI 的 API 格式工作流 JSON 后，插件会自动解析可编辑参数、Prompt 和图片输入节点。支持保存本地工作流预设，支持从 Photoshop 选区、全图或本地图片作为输入，运行后可预览生成结果、多图结果切换，并将图片插入 Photoshop 图层。

## 官方API
官方API tab 用于调用官方或中转图像接口，支持选择 RunningHub、OpenAI 官方、Gemini 官方或自定义中转站。可选择对应模型进行文生图、图生图，支持多参考图、选区/全图获取、比例与分辨率设置、结果预览、停止任务、结果回输和插入图层。适合需要使用官方 Key 或自有中转服务的用户。