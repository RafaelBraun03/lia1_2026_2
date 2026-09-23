## 🔍 Plataforma de Inferência YOLOv8n

Aplicação web para detecção de objetos em tempo real, utilizando um modelo YOLOv8n (ONNX) treinado para reconhecer 80 classes de objetos. Toda a inferência roda diretamente no navegador (client-side), sem necessidade de backend.

🔗 **Acesse a aplicação:** [Inferência global.app](https://object-pal-view.lovable.app/)

### ✨ Funcionalidades

- **Upload de imagem**: envie uma imagem e visualize as detecções desenhadas sobre ela, com a contagem de cada classe identificada.
- **Ajuste de confiança**: controle o threshold de confiança da inferência via slider ou digitando o valor manualmente.
- **Lista de classes**: consulte todas as 80 classes que o modelo é capaz de detectar.
- **Câmera ao vivo**: ative a câmera do dispositivo (webcam ou celular) e veja as detecções em tempo real, direto no navegador.

### 🛠️ Tecnologias

- YOLOv8n (ONNX)
- onnxruntime-web (inferência client-side via WASM/WebGPU)
