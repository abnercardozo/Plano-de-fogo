# Plano-de-fogo
Automatização dos cálculos de plano de fogo usando Python e exportação para Excel.
# 💥 Projeto Plano de Fogo Automatizado com Python

Este projeto foi desenvolvido como exercício prático por um estudante de **Técnico em Mineração** e **programação iniciante**, com o objetivo de automatizar os cálculos técnicos do **Plano de Fogo** — etapa essencial em operações de desmonte de rochas em mineração.

## 📌 O que é o Plano de Fogo?

O plano de fogo define os parâmetros para perfuração, carregamento e detonação em frentes de lavra. Seu objetivo é fragmentar rochas com segurança, eficiência e controle de custos, evitando perdas ou danos indesejados.

---

## 🎯 Objetivo do Projeto

- Praticar lógica de programação com Python aplicando conhecimentos técnicos da mineração;
- Automatizar todos os cálculos do plano de fogo com entrada de dados interativa;
- Exportar os resultados diretamente para uma planilha Excel;
- Gerar relatórios reutilizáveis e prontos para análise.

---

## ⚙️ Funcionalidades

✔️ Entrada de parâmetros técnicos via terminal  
✔️ Conversão entre mm ↔ polegadas  
✔️ Cálculo automático de:
- Afastamento (A)
- Espaçamento (E)
- Subfuração (Sf)
- Profundidade total (Hf)
- Altura de carga (Hct)
- Razão de carregamento (RC)
- Custo por metro cúbico e por tonelada
- Custo total do desmonte

✔️ Exportação automática para `.xlsx` (Excel)  
✔️ Abertura automática da planilha com os resultados  

---

## 📽️ Demonstrações

- **Vídeo 1:** Execução do código com entrada manual dos dados.  
- **Vídeo 2:** Execução do mesmo código com os mesmos valores, agora com **exportação automática para Excel**.

📌 Os vídeos podem ser acessados nos destaques ou na postagem no [LinkedIn](https://www.linkedin.com).

---

## 🧠 Base técnica

Todas as fórmulas e parâmetros foram fornecidos por um professor durante a disciplina de Planejamento de Lavra em sala de aula. O código foi elaborado como exercício pessoal de automação técnica.

---

## 🛠️ Tecnologias Utilizadas

- Python 3.11+
- Pandas
- NumPy
- Math
- Excel (.xlsx)

---

## 🚀 Como Executar

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/plano-de-fogo-python.git
cd plano-de-fogo-python

# Criar ambiente virtual (opcional, recomendado)
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\\Scripts\\activate   # Windows

# Instalar dependências
pip install -r requirements.txt

# Executar
python main.py
