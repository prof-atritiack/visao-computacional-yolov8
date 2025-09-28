# YOLOv8 - Detecção e Segmentação de Objetos

## Descrição
Este repositório reúne exemplos práticos e organizados do uso do **YOLOv8 (Ultralytics)** em tarefas de visão computacional.  
O material é voltado para fins educacionais e demonstra diferentes aplicações de detecção e segmentação:

1. **Primeiros Testes com YOLOv8**: carregamento do modelo e inferência inicial.  
2. **Segmentação em Imagens**: identificação e segmentação de objetos em imagens estáticas.  
3. **Detecção de Objetos em Vídeos**: processamento de vídeos com geração de saídas anotadas.  
4. **Segmentação em Vídeos**: aplicação do modelo para segmentação de objetos em movimento.  

O notebook inclui observações e boas práticas sobre carregamento de arquivos de teste, organização do repositório e uso da GPU no Google Colab.

---

## Estrutura do Repositório
```
visao-computacional-yolov8/
│
├── notebooks/
│   └── YOLOv8_Visao_Computacional_Final.ipynb
│
├── datasets/        
│   ├── imagens/     # imagens de teste utilizadas nos exemplos
│   ├── videos/      # vídeos de teste utilizados nos exemplos
│
└── README.md
```

---

## Como usar

1. **Clonar este repositório**
   ```bash
   git clone https://github.com/prof-atritiack/visao-computacional-yolov8.git
   cd visao-computacional-yolov8
   ```

2. **Abrir o notebook em ambiente local**
   ```bash
   jupyter notebook notebooks/YOLOv8_Visao_Computacional_Final.ipynb
   ```

3. **Alternativamente, abrir o notebook no Google Colab**
   - Acesse o [Google Colab](https://colab.research.google.com/).  
   - Carregue o arquivo `YOLOv8_Visao_Computacional_Final.ipynb` da pasta `notebooks/`.  
   - Habilite a GPU em: **Ambiente de execução > Alterar tipo de ambiente de execução > Acelerador de hardware > GPU**.  

---

## Dependências Principais
- Python 3.9+  
- ultralytics  
- opencv-python  
- torch  
- matplotlib  

As dependências já estão listadas em uma célula de instalação no início do notebook.

---

## Referências e Fontes de Pesquisa
- [Ultralytics YOLOv8 - Documentação Oficial](https://docs.ultralytics.com/)  
- [Repositório Ultralytics no GitHub](https://github.com/ultralytics/ultralytics)  
- [Documentação OpenCV](https://docs.opencv.org/)  
- Conteúdos da IA Expert Academy  
- Organização do material com apoio do ChatGPT  

---

## Sobre o repositório
Este repositório foi criado como material de apoio didático para aulas de **Visão Computacional**.  
Ele integra diferentes exemplos de uso do YOLOv8 em imagens e vídeos, com foco em **aprendizado progressivo** e **prática hands-on**.
