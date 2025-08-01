# Staysplore - Plataforma de Viagens

## Descrição
O Staysplore é uma plataforma completa de planejamento de viagens que permite aos usuários encontrar hotéis, explorar atrações turísticas e criar roteiros personalizados.

## Páginas Implementadas (10 telas)

### 1. **Página Inicial** (`index.html`)
- Hero section com busca de destinos
- Seção de destinos populares
- Seção "Planeje sua viagem"
- Menu de navegação completo
- Footer com informações da empresa

### 2. **Login** (`sign-in/login.html`)
- Formulário de login com validação
- Links para redes sociais
- Navegação para cadastro

### 3. **Cadastro** (`sign-up/register.html`)
- Formulário de cadastro com validação
- Campos: email, senha, confirmação de senha
- Integração com redes sociais

### 4. **Busca de Hotéis** (`hotels/hotels.html`)
- Lista de hotéis disponíveis
- Filtros de busca
- Cards com informações dos hotéis
- Tabela de preços e avaliações

### 5. **Atrações Turísticas** (`atracoes.html`)
- Formulário de busca de atrações (5+ campos)
- Lista de atrações populares
- Tabela de horários de funcionamento
- Validação JavaScript implementada

### 6. **Roteiros** (`roteiros.html`)
- Formulário de criação de roteiros (8+ campos)
- Lista de roteiros populares
- Tabela de roteiros do usuário
- Validação JavaScript implementada

### 7. **Contato** (`contato.html`)
- Formulário de contato (6+ campos)
- Informações da empresa
- Tabela de horários de funcionamento
- FAQ interativo
- Validação JavaScript implementada

### 8. **Sobre Nós** (`sobre.html`)
- Informações da empresa
- Missão e visão
- Equipe com fotos
- Timeline da empresa
- Estatísticas

### 9. **Perfil do Usuário** (`perfil.html`)
- Formulário de edição de dados pessoais (10+ campos)
- Histórico de viagens em tabela
- Preferências de viagem
- Validação JavaScript implementada

### 10. **Reserva de Hotel** (`reserva.html`)
- Formulário de reserva (8+ campos)
- Detalhes do hotel
- Resumo de preços
- Políticas de reserva
- Validação JavaScript implementada

## Elementos Implementados

### ✅ Títulos (H1 a H6)
- Todas as páginas utilizam hierarquia adequada de títulos

### ✅ Parágrafos
- Textos descritivos em todas as seções

### ✅ Imagens
- Logo da empresa
- Imagens de hotéis e destinos
- Fotos da equipe
- Placeholders para mapas

### ✅ Listas (ordenadas e não ordenadas)
- Menus de navegação
- Lista de atrações
- Lista de comodidades
- Lista de preferências

### ✅ Tags Semânticas
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- `<div>` para estruturação
- Uso adequado de `<form>`, `<table>`, `<ul>`, `<ol>`

### ✅ Tabelas
- Horários de funcionamento
- Histórico de viagens
- Resumo de preços
- Políticas de reserva

### ✅ Formulários (mínimo 1 com 5+ campos)
- **Formulário de Atrações**: 5 campos (destino, categoria, preço, data, pessoas)
- **Formulário de Roteiros**: 8 campos (nome, destino, datas, viajantes, orçamento, interesses, hospedagem, descrição)
- **Formulário de Contato**: 6 campos (nome, sobrenome, email, telefone, assunto, mensagem)
- **Formulário de Perfil**: 10 campos (dados pessoais completos)
- **Formulário de Reserva**: 8 campos (datas, hóspedes, tipo de quarto, dados pessoais)

### ✅ Validação JavaScript
- **Validação de campos vazios** em todos os formulários
- **Validação de email** com regex
- **Validação de datas** (check-in < check-out)
- **Validação de números** (quantidade de pessoas, orçamento)
- **Mensagens de erro** personalizadas
- **Feedback visual** para o usuário

## Menu de Navegação
- Header consistente em todas as páginas
- Links para: Início, Hotéis, Atrações, Roteiros
- Botões de Login e Cadastro
- Footer com links para todas as seções

## Responsividade
- Design responsivo para desktop, tablet e mobile
- Media queries implementadas
- Layout adaptativo

## Tecnologias Utilizadas
- HTML5 semântico
- CSS3 com Flexbox e Grid
- JavaScript para validações
- Imagens do Unsplash para demonstração

## Como Executar
1. Clone o repositório
2. Abra o arquivo `index.html` em um navegador
3. Navegue pelas páginas através dos menus

## Estrutura de Arquivos
```
staysplore/
├── index.html
├── atracoes.html
├── roteiros.html
├── contato.html
├── sobre.html
├── perfil.html
├── reserva.html
├── styles.css
├── README.md
├── images/
│   ├── LOGO.png
│   ├── home-banner.png
│   └── ...
├── sign-in/
│   ├── login.html
│   └── login.css
├── sign-up/
│   ├── register.html
│   └── register.css
└── hotels/
    ├── hotels.html
    └── hotels.css
```

## Requisitos Atendidos ✅
- [x] Mínimo 10 telas implementadas
- [x] Menu de navegação entre todas as telas
- [x] Títulos (H1 a H6) em todas as páginas
- [x] Parágrafos com conteúdo relevante
- [x] Imagens em todas as seções
- [x] Listas ordenadas e não ordenadas
- [x] Tags semânticas (div, footer, nav, etc.)
- [x] Tabelas com dados estruturados
- [x] Mínimo 1 formulário com 5+ campos (5 formulários implementados)
- [x] Validação JavaScript em todos os formulários
- [x] Design responsivo e moderno
- [x] Navegação consistente entre páginas
