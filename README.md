# Automação de Downloads no eSocial com Python e Selenium

Automação em Python criada para simplificar e agilizar o download de arquivos no eSocial, utilizando Selenium para eliminar tarefas repetitivas e garantir maior eficiência e precisão no processo.

---

## 🎓 Contexto Profissional e Acadêmico

Este projeto foi desenvolvido a partir de uma necessidade real observada no ambiente profissional, onde tarefas repetitivas relacionadas ao download de arquivos no eSocial demandavam elevado tempo de execução e estavam sujeitas a erros humanos.

A automação foi utilizada como objeto de estudo na disciplina **Imersão Profissional: Inteligência Artificial**, com foco na análise de processos, registro profissional e proposição de evolução com o uso de Inteligência Artificial.

---

## 📊 Resultados Obtidos

- Redução do tempo de execução de aproximadamente **3–4 dias para 1–2 dias**
- Taxa de acerto aproximada de **99%**
- Padronização do processo e redução significativa de erros manuais
- Maior confiabilidade na execução das tarefas

---

## Sobre o Projeto

Este projeto foi criado para **simplificar e agilizar o processo de download** de arquivos no eSocial utilizando o Selenium. Ele foi configurado para navegar automaticamente pelo sistema, baixar e direcionar os arquivos de forma programática.

**⚠️ Observação:**  
O login é realizado manualmente, pois o eSocial possui mecanismos de detecção de automação. Após o login, o processo é executado automaticamente, eliminando a necessidade de intervenção repetitiva e garantindo maior eficiência e precisão, o que o torna ideal para tarefas rotineiras.

---

## ⚙️ Funcionalidades

- Realiza o login manualmente (usuário entra com suas credenciais, devido à detecção de automação do eSocial).
- Navega automaticamente até a seção de downloads.
- Faz o download dos arquivos de forma programática.
- Direciona os arquivos para a pasta pré-definida.
- Elimina a necessidade de repetição manual, garantindo mais agilidade e precisão.

---

## 💻 Tecnologias Utilizadas

- VS Code
- Python 3.13.9
- Selenium
- Undetected-chromedriver
- Openpyxl

---

## 🤖 Possíveis Evoluções com Inteligência Artificial

Como proposta de aprimoramento, o projeto pode evoluir com a aplicação de técnicas de Inteligência Artificial, permitindo:

- Identificação de padrões de erro
- Classificação automática de exceções
- Apoio à tomada de decisão
- Aprendizado a partir de dados históricos

Atualmente, o sistema opera de forma determinística, sendo a Inteligência Artificial uma evolução futura planejada.

---

## Instalações

Para rodar este script, certifique-se de que o Python e as bibliotecas necessárias estão instalados em sua máquina. Caso não tenha nada instalado, seguem abaixo os links e instruções.

### Instalação do VS Code

[📥 Download - VS Code](https://code.visualstudio.com/)

---

## Instalação do Python

[📥 Download - Python](https://www.python.org/downloads/)

**⚠️ Observação:**  
É necessário utilizar o Python na versão 3.10 ou superior. O projeto foi testado na versão 3.13.9.

---

## Instalação das bibliotecas

Abra o terminal e execute:

```
pip install Selenium
pip install undetected-chromedriver
pip install openpyxl
 ```

## Como executar

No diretório do projeto, execute:
```
python main.py
```

## Estrutura do Projeto
O projeto está organizado da seguinte forma:
```
├── Automação - esocial/
| ├── EFETIVO - EXEMPLO.xlsx    # Arquivo de dados de exemplo
| ├── LICENSE                   # Licença do projeto
| ├── main.py                   # Script principal
| ├── README.md                 # Documentação
| └── requirements.txt          # Dependências do projeto
```









