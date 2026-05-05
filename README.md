# 🤖 Automação de Coleta de Dados com Python (RPA)

Script em Python para automatizar a coleta de dados em um sistema utilizando PyAutoGUI e salvar as informações em uma planilha Excel.

---

## 🚀 Funcionalidades

* Automação de navegação em sistema (cliques e digitação)
* Busca de dados a partir de códigos
* Extração de informações da tela
* Registro automático em planilha Excel
* Controle de status por linha (OK, ERRO, etc)

---

## 📂 Estrutura da planilha

| Coluna | Descrição          |
| ------ | ------------------ |
| B      | Código para busca  |
| C      | Nome coletado      |
| D      | Status da execução |

---

## ⚙️ Como usar

### 1. Clonar o repositório

```bash
git clone https://github.com/SEU-USUARIO/SEU-REPO.git
cd SEU-REPO
```

---

### 2. Instalar dependências

```bash
pip install -r requirements.txt
```

---

### 3. Executar o script

```bash
python main.py sua_planilha.xlsx
```

---

## 🧠 Como funciona

O script:

1. Lê os códigos da planilha Excel
2. Digita automaticamente no sistema
3. Navega pela interface usando coordenadas do mouse
4. Copia os dados exibidos na tela
5. Salva os resultados na planilha

---

## ⚠️ Atenção

Este projeto utiliza automação baseada em posição de tela.

* As coordenadas do mouse podem variar dependendo da resolução
* É necessário ajustar os pontos no código conforme o ambiente
* O sistema deve estar aberto na tela correta antes da execução

---

## 🛠 Tecnologias utilizadas

* Python
* PyAutoGUI
* Pyperclip
* OpenPyXL

---

## 📌 Observações

* O script depende do ambiente gráfico (não funciona em segundo plano)
* Pode exigir ajustes finos para diferentes máquinas
* Ideal para automatizar tarefas repetitivas em sistemas sem API

---

## 📄 Licença

MIT
