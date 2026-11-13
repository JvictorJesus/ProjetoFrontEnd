# 🎯 Projeto Front-End — Plataforma de Divulgação de Eventos & Iniciativas

Plataforma web voltada para a **divulgação de eventos** e **compartilhamento de iniciativas**.  
O visitante pode visualizar informações detalhadas, entrar em contato com os realizadores, fornecer feedback e (após login) publicar seus próprios eventos.

---

## 📌 Objetivo do Site

| Pergunta | Resposta |
|----------|----------|
| **Qual problema/necessidade atende?** | Falta de um espaço centralizado e simples para divulgar eventos acadêmicos, culturais e iniciativas sociais. |
| **O que o visitante deve conseguir fazer?** | Visualizar eventos em detalhes, entrar em contato com organizadores, dar feedback e publicar seus próprios eventos. |
| **Que tipo de conteúdo será oferecido?** | Publicações de eventos/iniciativas com descrição, imagens, data, local e informações de contato. |
| **Principal resultado esperado** | Facilitar a conexão entre organizadores e público interessado (estudantes, voluntários, patrocinadores, ONGs etc.). |

---

## 👥 Público-Alvo

- Estudantes e universitários  
- Patrocinadores  
- Vendedores / empreendedores  
- Voluntários  
- ONGs e coletivos  

---

## 🗺️ Sitemap

| Página | Descrição |
|--------|-----------|
| **Index** | Página inicial com informações essenciais da plataforma |
| **Projetos / Galeria** | Lista de publicações (eventos simulados inicialmente) |
| **Visualização** | Página detalhada de cada evento (3 exemplos: Evento 1, 2 e 3) |
| **Publicação** | Formulário para criar novo evento (requer login) |
| **Registro** | Cadastro de novo usuário |
| **Login** | Autenticação do usuário |
| **Perfil** | Edição de dados pessoais, foto, descrição e histórico de eventos |
| **Sobre** | História e informações da organização responsável |
| **Contato** | Formulário de contato e feedback |

### Menu de Navegação
- Início  
- Galeria (Eventos)  
- Sobre nós  
- Fale Conosco  
- Minha Conta  

---

## 🎨 Guia Visual Simplificado

| Elemento | Valor |
|----------|-------|
| **Cor principal** | `#e8e8e8` |
| **Cor secundária** | `#1e3a5f` |
| **Cor de destaque** | `#ffffff` |
| **Cor de fundo** | `#e8e8e8` |
| **Cor dos botões** | `#1e3a5f` |
| **Fonte principal** | Branca (`#ffffff`) sobre fundos escuros |

> **Dica:** Mantenha consistência visual em todas as páginas usando as variáveis CSS definidas em `css/style.css`.

---

## 📁 Estrutura de Arquivos

```
ProjetoFrontEnd/
├── index.html
├── sobre.html
├── contato.html
├── projetos.html
├── perfil.html
├── login.html
├── registro.html
├── novo-projeto.html
├── projetos/
│   ├── projeto1.html
│   ├── projeto2.html
│   └── projeto3.html
├── css/
│   └── style.css
├── imagens/
│   ├── projeto1.jpg
│   ├── projeto2.jpg
│   └── projeto3.jpg
├── docs/
│   └── ProjetoFrontEnd.docx
└── README.md
```

---

## 🚀 Como executar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   ```
2. Abra a pasta do projeto.
3. Abra o arquivo `index.html` diretamente no navegador  
   **ou** utilize um servidor local (recomendado):

   ```bash
   # Com Python
   python -m http.server 8000

   # Com Live Server (VS Code)
   # Clique com o botão direito em index.html → "Open with Live Server"
   ```

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — Estrutura semântica
- **CSS3** — Estilização e responsividade
- **JavaScript** (vanilla) — Interatividade básica (formulários, navegação, simulação de login)

> *Projeto desenvolvido como atividade acadêmica de Front-End. Não possui backend real — as publicações e autenticação são simuladas.*

---

## 📸 Páginas Principais (Wireframes de baixa fidelidade)

- [ ] Index  
- [ ] Projetos / Galeria  
- [ ] Contato  
- [ ] Login / Registro  
- [ ] Perfil  
- [ ] Página de detalhe do evento  

*(Adicione aqui prints reais das páginas quando estiverem prontas)*

---

## ☁️ Hospedagem (Referência)

Comparação realizada em **31/10/2026** (valores promocionais):

| Provedor     | Plano mais acessível | Destaque |
|--------------|----------------------|----------|
| **Hostinger** | Single (R$ 5,99)    | Melhor custo-benefício |
| **HostGator** | Plano P (R$ 10,09)  | Servidores no Brasil + IA |
| **WordPress.com** | Pessoal (R$ 8,50) | Experiência gerenciada |

> **Recomendação para o projeto:** Hostinger (plano Single ou Premium) por ser simples, barato e suficiente para um site estático.

---

## 👨‍💻 Autores / Grupo

- Nome 1  
- Nome 2  
- Nome 3  
- Nome 4  

*(Atualize com os nomes reais do grupo)*

---

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.  
Sinta-se livre para estudar, modificar e utilizar o código como base de aprendizado.

---

**Status do Projeto:** 🟡 Em desenvolvimento  
**Última atualização:** Novembro 2026
