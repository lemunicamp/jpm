# Jornal do Professor de Matemática

## 📖 Sobre o Projeto

O **Jornal do Professor de Matemática** (JPM) é uma iniciativa do **Laboratório de Ensino de Matemática (LEM)** da Unicamp, com o objetivo de **compilar, produzir e divulgar recursos e projetos que contribuam para a vivência docente e a experiência de ensino de professores de matemática**.

O projeto se inspira no antigo **Jornal do Professor de Matemática**, produzido pelo próprio LEM há mais de 10 anos, além da **Revista do Professor de Matemática**, publicada pela SBM, e da **Revista Professor de Matemática Online**.

### 🎯 Público-Alvo
- Professores de matemática da educação básica e superior
- Licenciandos em matemática
- Pesquisadores da área de educação matemática

### 📅 Periodicidade
A periodicidade do jornal ainda não está definida, mas espera-se que seja **semanal**.

## 📂 Estrutura do Repositório

A organização dos arquivos no repositório segue a seguinte estrutura:

```
📂 /edicoes
 ├── 📂 2025
 │    ├── 📂 edicao-01
 │    │    ├── main.tex   # Arquivo LaTeX principal da edição
 │    │    ├── jpm.pdf    # PDF final da edição
 │    │    ├── figuras/   # Imagens e gráficos usados na edição
 │    │    ├── artigos/   # Artigos dessa edição
 │    ├── 📂 edicao-02
 │    └── ...
 │
📂 /jornal
 ├── jpm.cls     # Classe LaTeX do jornal
 ├── preambulo.tex # Arquivos base para formatação
 │
📂 /artigos
 ├── artigo-01.tex  # Arquivo LaTeX do artigo completo
 ├── artigo-02.tex  
 └── ...
 │
📂 /templates
 ├── template-artigo.tex  # Modelo para submissão de artigos
 │
📜 README.md  # Este arquivo
📜 LICENSE    # Licença GPL-3.0
```

## 🛠 Tecnologias e Ferramentas

- **LaTeX3** é a linguagem padrão para a formatação do jornal.
- O template para submissão de artigos estará disponível em [`/templates/template-artigo.tex`](templates/template-artigo.tex).
- Buscaremos minimizar o uso de pacotes externos, especificando apenas os estritamente necessários.

## 🤝 Como Contribuir

### 1️⃣ Contribuindo para o Repositório
Interessados podem contribuir por meio de **pull requests**. Sugestões de melhorias, correções e novas edições são bem-vindas.

### 2️⃣ Submetendo Artigos
Autores que desejam submeter artigos devem enviar suas propostas para **lem@unicamp.br**. O processo de submissão inclui:
1. Uso do template oficial disponível na pasta [`/templates`](templates/).
2. Revisão pelo **corpo editorial**, composto por estudantes de licenciatura do IMECC e pelo professor orientador do projeto.
3. Inclusão do artigo em uma edição do jornal, com sua versão completa disponível na pasta [`/artigos`](artigos/).

## 📜 Licença

Este projeto está licenciado sob a **GPL-3.0**. Os autores mantêm os direitos sobre seus textos.

## 📩 Contato

O **Jornal do Professor de Matemática** é organizado por estudantes de licenciatura em matemática da Unicamp, vinculados ao **Laboratório de Ensino de Matemática (LEM)**, sob orientação do **Professor Giuliano Zugliani**.

📧 **E-mail de contato:** lem@unicamp.br
