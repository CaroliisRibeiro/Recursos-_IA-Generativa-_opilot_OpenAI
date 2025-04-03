# 🤖 Explorando os Recursos de IA Generativa com Copilot e OpenAI

Este repositório documenta a experiência prática de exploração de ferramentas de IA generativa, como **GitHub Copilot** e **OpenAI**, com foco na **extração de texto a partir de imagens** usando técnicas de OCR (Reconhecimento Óptico de Caracteres).

---

## 🗂 Estrutura do Projeto
📁 inputs/ → Imagens utilizadas no processo 📁 output/ → Arquivos com texto extraído das imagens 📄 readme.md → Documentação do processo

---

## 🧪 Passo a Passo do Processo

### 1. Coleta das Imagens (`inputs/`)

Foram coletadas imagens com textos variados — frases de avaliação de clientes, avisos e prints de tela. Essas imagens foram salvas na pasta `inputs`.

> 📌 Exemplo:

<p align="center">
  <img src="https://github.com/user-attachments/assets/732c1d19-0b73-4737-b1d8-cc327f4fc1e1" width="300"/>
  <img src="https://github.com/user-attachments/assets/0f14d07a-a2d7-4994-bc5b-f02869c71ef6" width="300"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e636c909-f791-4d11-9594-d408c7a4eb15" width="300"/>
  <img src="https://github.com/user-attachments/assets/426cfdb9-80de-40b0-8923-e989756be0b1" width="300"/>
</p>


### 2. Extração de Texto com IA (`output/`)

Utilizei um modelo de OCR baseado em IA (ex: **Azure AI Vision**, **Tesseract.js** ou **paddleocr**) para extrair o conteúdo textual das imagens.

Os textos extraídos foram salvos em arquivos `.txt`, um para cada imagem, na pasta `output/`.

#### 📄 Exemplo de saída:

> [validade do serviço.txt](https://github.com/user-attachments/files/19590553/validade.do.servico.txt)

> O serviço de atendimento ao cliente foi excelente e rápido.
> A entrega demorou mais do que o esperado.

---

> [study.txt](https://github.com/user-attachments/files/19590465/study.txt)
Study hard
> Learn physics
> Getadiploma
> Explore the world

---

> [warning signs.txt](https://github.com/user-attachments/files/19590515/warning.signs.txt)
> Customer Satisfaction
> How satisfied are you?
> ewe)
> Neutral Dissatisfied
> BEACH CLOSED
> No swimming
> allowedg warning signs

---

> [thanks.txt](https://github.com/user-attachments/files/19590531/thanks.txt)
> Thank You!

---

### 3. Prints do Processo

#### 🔍 Imagem de entrada
<p align="center">
  <img src="https://github.com/user-attachments/assets/0b5740e2-13c7-4eac-8676-73466a968e8f" width="700"/>
</p>


#### 📜 Texto extraído com IA
<p align="center">
  <img src="https://github.com/user-attachments/assets/e65fc7f2-550b-4d71-badc-13f6eda9f734" width="800"/>
</p>

----
>
Customer Satisfaction
How satisfied are you?
Satisfied
Neutral
Dissatisfied

---
>
BEACH CLOSED
WARNING
No swimming allowed

---

## 💡 Insights Obtidos

- A **qualidade da imagem** influencia diretamente na precisão do reconhecimento de texto.
- O uso de IA generativa permite transformar **dados não estruturados em informações úteis**.
- Recursos de IA como **Copilot** são extremamente úteis para acelerar tarefas repetitivas como limpeza de texto, organização de arquivos e criação de scripts automatizados.
- O processo é altamente escalável e pode ser integrado a sistemas maiores como: **chatbots, análises de sentimento, dashboards e CRMs**.

---

## 🛠️ Possibilidades Futuras

- Integrar com **Azure Cognitive Services** para análise de sentimento das frases extraídas.
- Aplicar **tradução automática** nos textos reconhecidos.
- Criar um painel de visualização com **Power BI** ou **Streamlit**.
- Usar **Copilot** para gerar relatórios automáticos com base nas saídas.

---

## 📘 Aprendizados

- Como funciona o OCR com IA e suas aplicações reais.
- Como estruturar um projeto simples e funcional de IA generativa.
- A importância de organizar os dados em pastas claras como `inputs` e `output`.
- Como documentar um projeto para criar um portfólio atrativo.

---

## 📎 Referências

- [Azure AI Vision](https://learn.microsoft.com/pt-br/azure/ai-services/computer-vision/overview-ocr)
- [Tesseract.js](https://github.com/naptha/tesseract.js)
- [OpenAI Docs](https://platform.openai.com/docs)
- [GitHub Copilot](https://github.com/features/copilot)



