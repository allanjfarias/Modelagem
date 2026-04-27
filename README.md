# 📊 Projeto ENADE - Pipeline de Processamento e Análise

Este projeto tem como objetivo processar os microdados do ENADE, realizando etapas de limpeza, seleção de colunas, normalização e preparação para análise em banco de dados relacional e NoSQL.

---

## 📥 Download dos Dados

Os microdados do ENADE não estão versionados neste repositório devido ao seu grande tamanho.

Você pode baixar os dados diretamente neste link:

👉 **[Google Drive - Microdados ENADE](https://drive.google.com/file/d/14Vwg8i7UDx7cqjqQPvTX9iCAx1sWfgdt/view?usp=sharing)**

Após o download, extraia os arquivos na seguinte estrutura:

```text
/enade_raw/
            2017/ -> Edição
            2018/
            2019/

Cada edição contém:
            /LEIA-ME  -> dicionários de dados e manual da edição
            /DADOS    -> Arquivos .txt
```
---

## 🧪 Configuração do Ambiente (venv + Jupyter)

### 1. Criar ambiente virtual

```bash
python3 -m venv .venv
```

### 2. Ativar o ambiente

```bash
source .venv/bin/activate
```

### 3. Instalar dependências

```bash
pip install -r requirements.txt
```

---

## 🚀 Usando o Notebook

1. Abra o Jupyter:

```bash
jupyter notebook
```

2. Abra o arquivo `.ipynb`

3. No topo do notebook, vá em:

```
Kernel → Change Kernel → Python (venv)
```

✔ Pronto! Agora o notebook está usando o ambiente virtual correto.

---


## ⚠️ Observações

* Os dados brutos não estão no repositório por serem pesados
* O dataset deve ser baixado separadamente via Drive

---
