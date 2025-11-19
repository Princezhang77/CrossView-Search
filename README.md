# CrossView-Search：基于智能体及几何结构的跨视角图像位置识别
## 0.鸣谢
感谢 [**上海人工智能实验室书生浦语大模型**](https://internlm.openxlab.org.cn/) 的支持，感谢实训营提供的赞助和机会。

## 1.展示(点击进入)：

<div align="center">
     <a href="https://www.bilibili.com/video/BV1BcUmYtESj/?spm_id_from=333.1387.homepage.video_card.click" target="_blank">
          <img width="70%" src="https://github.com/user-attachments/assets/809616ce-0e28-44e6-b9ac-1cadae297234" alt="bilibili" />
     </a>
</div>

## 快速运行：
1. 创建 `.env` 文件（参考 `.env.example`）并配置以下 API 密钥：
   - `DASHSCOPE_API_KEY`：通义千问VL大模型API密钥
   - `BOCHA_API_KEY`：博查搜索API密钥
   - `AMAP_API_KEY`：高德地图API密钥
   - `SILICON_FLOW_API_KEY`：Silicon Flow API秘钥
2. 安装依赖：`pip install -r requirements.txt`
3. 运行服务：`python center/center.py`

## 2.介绍
**MultiAgent-Search**是基于InternLM书生浦语大模型实现的多智能体项目，在图寻地址方面为全球首创，旨在利用多**Agent**识别上海市松江大学城图像，识别过程很好地模拟了人类思考图像位置的过程，以进行图像寻址，如：上海工程技术大学松江校区-图书馆等，在图像寻址功能上超越了**ChatGPT4o**与**文心一言3.5**等大模型。
