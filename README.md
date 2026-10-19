# 🎥 YouTube Clone - Desafio CSS Grid Layout
Desafio da DIO - Um clone responsivo da interface principal do YouTube desenvolvido com **HTML5** e **CSS3**, focando na aplicação prática de **CSS Grid Layout** e **Flexbox**. Projeto desenvolvido como parte do desafio prático da [Digital Innovation One (DIO)](https://www.dio.me/).

---

## 📌 Sobre o Projeto

O objetivo deste projeto foi recriar a estrutura visual da página inicial do YouTube, aplicando conceitos modernos de layout web, organização de componentes HTML semânticos e responsividade para diferentes tamanhos de tela.

### 🛠️ Tecnologias Utilizadas

- **HTML5**: Estruturação semântica do conteúdo (`header`, `aside`, `main`, `section`, `article`, `nav`).
- **CSS3**:
  - **CSS Grid Layout**: Utilizado no layout geral da página, no cabeçalho e na grade de vídeos.
  - **Flexbox**: Utilizado na organização dos itens internos dos cards e botões.
  - **Media Queries**: Responsividade adaptada para desktop, tablet e dispositivos móveis.
- **Google Fonts**: Tipografia com a fonte *Roboto*.

---

## 📐 Estrutura do Layout

- **Cabeçalho (`.header`)**: Estruturado com `display: grid` dividindo a logo, a barra de pesquisa centralizada e os ícones de ação do utilizador.
- **Menu Lateral (`.sidebar`)**: Lista de navegação com ícones e rótulos textualizados, alinhados de forma consistente.
- **Grade de Vídeos (`.video-grid`)**: Organizada com `display: grid; grid-template-columns: repeat(4, 1fr);` para uma distribuição proporcional dos cartões de vídeo.
- **Cards de Vídeo (`.video-card`)**: Estrutura flexível contendo a miniatura, foto do canal, título e estatísticas de visualização.

---

## 📱 Responsividade

A página adapta-se dinamicamente conforme a largura da viewport:

- **> 1200px**: Grade com 4 colunas de vídeos.
- **900px - 1200px**: Grade ajustada para 3 colunas e menu lateral colapsado em ícones.
- **600px - 900px**: Grade com 2 colunas.
- **< 600px**: Grade em coluna única e menu lateral oculto para telas menores.

---

## 📸 Demonstração

🔗 [Clique aqui para visualizar o projeto online](https://riqueerculano.github.io/desafio-grid/)

## 🚀 Como Executar o Projeto
Clone este repositório:

```
git clone https://github.com/riqueerculano/desafio-grid.git
```
Navegue até a pasta do projeto:
```
cd desafio-flebox
```
Abra o arquivo ``index.html`` no seu navegador de preferência.

Feito por Henrique Erculano