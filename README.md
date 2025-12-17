# 🌠 projeto-cosmos-web

**Experiência imersiva de anomalia cósmica interativa.**

Este projeto utiliza computação gráfica avançada para renderizar uma simulação estelar em tempo real. Através de **Custom Shaders (GLSL)**, 40.000 partículas são processadas diretamente na GPU, permitindo interatividade fluida e efeitos visuais de alta fidelidade.

🔗 **Acesse o projeto online:** [https://brunnodev50.github.io/projeto-cosmos-web/](https://brunnodev50.github.io/projeto-cosmos-web/)

---

## 🚀 Funcionalidades

* **Simulação de Partículas:** Movimentação orgânica baseada em *Simplex Noise 3D*.
* **Interatividade Total:** O núcleo reage à posição do mouse, criando distorções e pulsações dinâmicas.
* **Motor de Temas:** Troca instantânea entre 7 paletas de cores (Nebula, Sunset, Aurora, etc.).
* **Design Glassmorphism:** Interface moderna com desfoque de fundo (backdrop-filter) e controles responsivos.
* **Pós-processamento:** Efeitos de *Unreal Bloom* para simular emissão de luz e profundidade.

## 🛠️ Tecnologias Utilizadas

* **JavaScript (Three.js)** - Motor de renderização 3D.
* **GLSL (Shaders)** - Programação de vértices e fragmentos para alta performance.
* **HTML5 & CSS3** - Estrutura e estilização da interface HUD.
* **RGBELoader** - Para iluminação e ambientes baseados em imagens HDR.

## ⚙️ Como visualizar localmente

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/brunnodev50/projeto-cosmos-web.git](https://github.com/brunnodev50/projeto-cosmos-web.git)
    ```
2.  Abra a pasta do projeto.
3.  Execute através de um servidor local (ex: *Live Server* do VS Code) para garantir que os arquivos HDR e módulos JavaScript carreguem corretamente.

## 👤 Autor

**Brunno Henrique Vilas Boas** GitHub: [@brunnodev50](https://github.com/brunnodev50)

---
*Projeto desenvolvido para exploração de WebGL e arte generativa.*
