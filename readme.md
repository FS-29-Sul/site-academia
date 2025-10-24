# 🧑‍💻 Guia de Boas Práticas para Trabalho em Grupo no GitHub

Este documento define o padrão de colaboração e boas práticas que o grupo deve seguir para garantir **organização**, **consistência** e **qualidade** no desenvolvimento do projeto.

---

## 📁 Estrutura e Organização do Projeto

- Mantenha uma estrutura de pastas **limpa e padronizada**.
- Evite arquivos soltos na raiz do projeto (exceto os essenciais como `README.md`).
- Use nomes **autoexplicativos e em inglês** para pastas e arquivos (ex: `assets/`, `index.html`).

---

## 🌿 Fluxo de Trabalho (Git Flow)

### 1. Branches

Siga o padrão de branches:

| Tipo | Nome | Descrição |
|------|------|------------|
| `main` | Principal | Contém a versão estável e pronta para produção. |
| `develop` | Desenvolvimento |Onde novas features são integradas e testadas juntas. 
| `stage` | Homologação | Simula o ambiente de produção antes do deploy real.
| `feat/` | Ex: `feature/login-page` | Usada para criar novas funcionalidades. |
| `fix/` | Ex: `fix/validation-error` | Usada para corrigir bugs. |

⚠️ **Nunca** faça commits diretamente na `main, develop ou stage`.  
Todo código deve passar por uma **branch de feature** e depois ser integrado via **Pull Request (PR)**.

---

## 💬 Commits

Use mensagens de commit **claras e padronizadas**.  
Siga o padrão abaixo:


### Tipos comuns:
- `feat`: nova funcionalidade
- `fix`: correção de bug
- `chore`: manutenção, configs, dependências
- `docs`: alterações em documentação
- `refactor`: refatoração de código
- `style`: ajustes de formatação
- `test`: criação/ajuste de testes

### Exemplo:

---

# 🔄 Pull Requests (PR)

## 🔄 Guia de Como Abrir um Pull Request (PR)

Este é um guia que explica, passo a passo, **como abrir um Pull Request (PR)** no GitHub seguindo as boas práticas do time.  
O objetivo é manter o código **organizado, revisável e sem conflitos**.

---

## 🧭 O que é um Pull Request?

Um **Pull Request (PR)** é uma solicitação para que o seu código seja **revisado e integrado** à branch principal do projeto (geralmente `develop` ou `stage`).  
Ele serve para:
- Garantir que o código foi testado antes de entrar no projeto.
- Permitir revisões por outros membros.
- Manter o histórico de desenvolvimento limpo e rastreável.

---

## 🚀 Fluxo resumido

```text
feature/*  →  develop  →  stage  →  main
```

---

## 🧩 Código Padronizado

- Use o mesmo **estilo de código** em todo o projeto (indentação, aspas, ponto e vírgula, etc.).
- Nomes de classes devem ser **autoexplicativos e coerentes**.
- Evite código duplicado e comentários desnecessários.

---

## 📋 Convenções Gerais

✅ Faça:
- Atualize o projeto localmente antes de iniciar uma nova feature (`git pull origin develop`).
- Crie branches curtas e focadas em uma única tarefa.
- Comunique-se com o grupo sobre mudanças grandes.

🚫 Evite:
- enivar código sem testar e verificar se atente aos requisitos.
- Alterar a branch `main` diretamente.
- Subir commits com mensagens genéricas como “update”, “mudanças”, “teste”.

---

## 🧾 Checklist para Entregas

Antes da entrega final:
- [ ] Todas as funcionalidades testadas e funcionando.
- [ ] Código limpo e padronizado.

---

## 🤝 Comunicação e Organização

- Defina **responsáveis por cada módulo** do projeto.
- Atualize o time sobre progresso e possíveis bloqueios.

---

## ✨ Dica Final

Trabalhar em grupo exige:
> **Respeito, organização e colaboração.**  
> A qualidade do projeto depende do esforço coletivo e da comunicação entre os membros.

---

**📌 Mantido por:**  
FS24 – *[Site academia]*  
