# ARJS Thing

Projeto responsável por gerar a realidade aumentada no aplicativo my_wallet.

### Como contribuir

- **Adicionando novos modelos**
Todos os modelos devem estar presentes na pasta `assets/3D models/` utilizando 1 pasta para cada modelo. 
Exemplo: `assets/3D models/personagem-legal/*assets do modelo personagem-legal*`
Os modelos devem estar em formato `.gltf` utilizando o mesmo nome da pasta mãe e ao lado de uma pasta chamada `textures` que contem as texturas do modelo.
Exemplo: 
    ````bash
    /assets/3D models/personagem-legal/personagem-legal.gltf
    /assets/3D models/personagem-legal/textures/*
    ````
    Sempre dando preferencia a modelos que não veêm com as texturas no proprio gltf.