# Repositório de Bia

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Status](https://img.shields.io/badge/status-em%20andamento-yellow?style=for-the-badge)

> **Atividade do Emerson** — prática de controle de versão, colaboração e documentação com Git, GitHub e Markdown.

---

## Sobre o projeto

Este repositório foi criado para a **atividade do professor Emerson** e reúne, na prática, o que foi estudado nas aulas de Git e GitHub:

- como funciona o **controle de versão** e por que ele evita arquivos como `projeto_final2_final_corrigido`;
- a diferença entre **Git** (ferramenta local) e **GitHub** (plataforma na nuvem);
- como **criar, versionar e publicar** um projeto;
- como **documentar** esse projeto em um `README.md` escrito em **Markdown**.

O objetivo deste arquivo é ser o *cartão de visitas* do repositório: quem chegar aqui deve entender, em poucos minutos, o que foi feito, com quais ferramentas e como reproduzir os passos.

---

## O conteúdo

| # | Etapa | Tema | Resumo |
|:---:|:---:|---|---|
| 1 | Aula 1 | O que é Git e GitHub | Controle de versão, diferença entre Git e GitHub, repositório local × remoto. |
| 2 | Etapa 2 | Instalação e configuração | Instalar o Git, conferir com `git --version` e configurar `user.name` e `user.email`. |
| 3 | Etapa 3 | Primeiro repositório | `git init`, `git status`, criar o `README.md`, `git add`, primeiro `commit` e `git log`. |
| 4 | — | README.md e Markdown | Estrutura de um bom README e a sintaxe básica de Markdown. |
| 5 | Etapa 4 | Trabalhando com alterações | Ver o que mudou, comparar diferenças e colocar arquivos no staging com `git add`. |
| 6 | Etapa 5 | Repositório remoto | Criar o repositório no GitHub e publicar o projeto que estava só na máquina. |
| 7 | Etapa 6 | Clone, pull e push | Baixar o projeto do GitHub e sincronizar as alterações nos dois sentidos. |
| 8 | Etapa 7 | Branches | Criar, listar e trocar de branch para evoluir sem quebrar a `main`. |
| 9 | Etapa 8 | Merge | Juntar as branches e integrar as alterações com segurança. |
| 10 | Etapa 9 | Conflitos | Identificar, resolver e concluir um merge que deu conflito. |
| 11 | Etapa 10 | `.gitignore` | Controlar o que entra (e o que não entra) no repositório. |
| 12 | Etapa 11 | GitHub na prática | Criar o repo na web, clonar, alterar, `commit`, `push` e abrir Pull Request. |
| 13 | Etapa 12 | Trabalho em equipe | Colaboradores, code review, aprovação e merge do PR. |
| 14 | Extra | Corrigir o último commit | `git commit --amend` e `git push --force-with-lease`. |
| 15 | Extra | Fork | Copiar o repositório de outra pessoa e contribuir sem afetar o original. |

---

## Tecnologias e ferramentas

- [Git](https://git-scm.com/) — sistema de controle de versão distribuído
- [GitHub](https://github.com/) — hospedagem de repositórios e colaboração
- [Markdown](https://www.markdownguide.org/) — linguagem de marcação usada neste README
- [Visual Studio Code](https://code.visualstudio.com/) — editor de código

---

## Pré-requisitos

Antes de reproduzir os passos deste repositório, você precisa de:

1. **Git instalado** — baixe em <https://git-scm.com/downloads> e confirmar com:

   ```bash
   git --version
   ```

2. **Uma conta no GitHub** — crie gratuitamente em <https://github.com>.
3. **Git configurado** com seu nome e e-mail:

   ```bash
   git config --global user.name "Seu Nome"
   git config --global user.email "seu@email.com"
   ```

---

## Como executar

### 1. Clonar o repositório

```bash
git clone https://github.com/beatrizgarduzi/Reposit-rio-de-Bia.git
cd Reposit-rio-de-Bia
```

### 2. Verificar a situação do projeto

```bash
git status    # mostra o estado dos arquivos
git log       # mostra o histórico de commits
```

### 3. Registrar uma alteração

```bash
git add .                              # adiciona as alterações à área de staging
git commit -m "Atualiza o README.md"   # registra a alteração no histórico
git push origin main                   # envia para o GitHub
```

---

## Comandos essenciais

| Comando | Para que serve |
|---|---|
| `git init` | Inicializa um repositório Git na pasta |
| `git status` | Mostra o estado atual dos arquivos |
| `git add <arquivo>` | Prepara o arquivo para o commit |
| `git commit -m "mensagem"` | Salva uma versão no histórico |
| `git log --oneline` | Lista o histórico de commits de forma resumida |
| `git branch` | Lista as branches do projeto |
| `git checkout -b nome` | Cria e troca para uma nova branch |
| `git push origin main` | Envia os commits para o GitHub |
| `git pull origin main` | Atualiza o repositório local com as novidades do GitHub |

---

## Estrutura do repositório

```text
Reposit-rio-de-Bia/
├── README.md      # documentação do projeto (este arquivo)
├── LICENSE        # licença MIT do projeto
└── .git/          # pasta criada automaticamente pelo Git (controle de versão)
```

---

## Boas práticas que estou aplicando

- [x] Escrever um README claro, com título, descrição e instruções
- [x] Fazer commits pequenos e com mensagens descritivas
- [x] Manter o repositório organizado e sempre atualizado
- [x] Usar Markdown para deixar a documentação legível no GitHub
- [ ] Criar uma branch para cada nova funcionalidade *(próximo passo)*
- [ ] Abrir um Pull Request para revisar as alterações *(próximo passo)*

---

## Contribuição

Sugestões e correções são bem-vindas. Para contribuir:

1. Faça um **fork** do projeto;
2. Crie uma branch com a sua melhoria: `git checkout -b minha-melhoria`;
3. Faça o commit: `git commit -m "minha melhoria"`;
4. Envie para o seu fork: `git push origin minha-melhoria`;
5. Abra um **Pull Request** descrevendo a mudança.

---

## Autora

**Beatriz Garduzi**

- GitHub: [@beatrizgarduzi](https://github.com/beatrizgarduzi)
- Repositório: [Reposit-rio-de-Bia](https://github.com/beatrizgarduzi/Reposit-rio-de-Bia)

---

## Licença

Este projeto está sob a licença **MIT** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## Referências

- [Git — documentação oficial](https://git-scm.com/doc)
- [GitHub Docs](https://docs.github.com/pt)
- [Markdown Guide](https://www.markdownguide.org/) — guia usado para escrever este README

---

<p align="center">
  <em>Documente hoje, colabore amanhã. 🚀</em>
</p>
