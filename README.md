# PSInformática - Portal Institucional 🚀

![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-blue?style=for-the-badge&logo=github)
![Jekyll](https://img.shields.io/badge/SSG-Jekyll-red?style=for-the-badge&logo=jekyll)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap%205-7952b3?style=for-the-badge&logo=bootstrap)

Este repositório contém o código-fonte oficial da **PSInformática**, empresa especializada em infraestrutura de redes, suporte técnico avançado e consultoria estratégica de TI, sediada em Guarabira/PB.

O projeto foi concebido com foco em **alta performance**, **SEO** e **experiência do usuário (UX)**, utilizando arquitetura de site estático para garantir segurança e velocidade de carregamento instantânea.

---

## 📄 Resumo do Projeto

O portal atua como o principal ponto de contato digital da empresa, permitindo a prospecção de clientes de forma automatizada e profissional.

* **Arquitetura:** Jamstack (JavaScript, APIs e Markup).
* **Performance:** Otimizado para Core Web Vitals do Google.
* **Funcionalidades:** Tabelas comparativas de planos, integração de suporte remoto em tempo real e formulários de contato seguros.

---

## 🛠️ Tecnologias & Integrações

| Tecnologia | Finalidade |
| :--- | :--- |
| **Jekyll** | Engine principal para geração de páginas estáticas. |
| **Liquid** | Lógica de templating para gestão dinâmica de variáveis. |
| **Bootstrap 5** | Grid system e componentes de interface responsiva. |
| **FormSubmit** | Backend-as-a-Service para processamento de leads. |
| **GitHub Actions** | Pipeline de CI/CD para deploy automatizado. |

---

## 📁 Arquitetura do Repositório

A estrutura segue o padrão de convenção do Jekyll, separando lógica de dados de apresentação visual:

```
├── _config.yml           # Configurações globais, variáveis de SEO e preços
├── _includes/            # Componentes modulares (Navbar, Footer, Modais)
├── _layouts/             # Templates estruturais das páginas
├── _data/                # (Opcional) Arquivos YAML com dados de clientes/planos
├── assets/               
│   ├── css/              # Estilos customizados e organizados por página
│   ├── js/               # Scripts de interação e animações
│   └── images/           # Assets visuais e favicons otimizados
├── index.html            # Landing Page com prova social e stats
├── planos.html           # Tabela comparativa e FAQ técnico
└── contato.html          # Gateway de comunicação via FormSubmit
```

## 🚀 Desenvolvimento Local

Para rodar o projeto e realizar testes em ambiente de desenvolvimento:

1. Pré-requisitos: Ter o Ruby e o Bundler instalados.

2. Clonar o repositório:

```
git clone https://github.com/psinformaticagba/psinformaticagba.github.io.git
```

3. Instalar dependências:

```
bundle install
```

4. Subir o servidor local:

```
bundle exec jekyll serve
```

5. Acessar: http://localhost:4000