# WebUI一覧
## ローカル

基本的にローカルのリソースを用いて画像生成をするGUIツール  
各repoで特色が違う 

- [AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) → [解説](./stable-diffusion-webui/index.md)
- [invoke-ai/InvokeAI](https://github.com/invoke-ai/InvokeAI)  
- [Sygil-Dev/sygil-webui](https://github.com/Sygil-Dev/sygil-webui)  

## Docker
コンテナ技術などを用いて環境の共有を行うため、ユーザーの環境に起因するバグが少ない。  
しかし、WindowsではWSLなど仮想環境が必要などのデメリットもある。  
上級者向き

 - [AbdBarho/stable-diffusion-webui-docker](https://github.com/AbdBarho/stable-diffusion-webui-docker)
 - [ddPn08/Lsmith](https://github.com/ddPn08/Lsmith)

## Google Colaboratory
Google社製の[Google Colaboratory](https://colab.research.google.com)というクラウドリソースを活用したツール  
複雑な環境構築不要、ブラウザから実行可能、無料でも高性能(NVIDIA® Tesla® T4 GPU)と夢のようなツール  
しかし、利用時間などの制限もあるため、それらを考慮したくない方は[ローカル](#_1)のほうがよい  
お試し/入門者/性能不足の方向け

- [camenduru/stable-diffusion-webui-colab](https://github.com/camenduru/stable-diffusion-webui-colab)