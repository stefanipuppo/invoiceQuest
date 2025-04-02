# 📊 Automação de Processamento de Faturas

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)

![MySQL](https://img.shields.io/badge/MySQL-8.0+-blue?logo=mysql)

![PDF Processing](https://img.shields.io/badge/Processamento_PDF-PDFPlumber-red)

Extração de dados de faturas em PDF e exportação para Excel + MySQL com tratamento robusto de erros.

## ✨ Funcionalidades

- **Extração de dados de PDFs**:
  - Números de faturas
  - Datas das faturas
  - Metadados dos arquivos
- **Exportação dupla**:
  - Arquivos Excel com timestamp
  - Armazenamento em banco MySQL
- **Resiliência a erros**:
  - Registro detalhado de erros
  - Continuação do processo após falhas

## 🛠️ Configuração

### Requisitos
```bash
pip install -r requirements.txt
openpyxl>=3.0.0
pdfplumber>=0.7.0
mysql-connector-python>=8.0.0

