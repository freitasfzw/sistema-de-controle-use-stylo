# 🧾 Sistema de Vendas Local - Use Stylo

Este projeto é um sistema simples de **controle de estoque e vendas** desenvolvido com **HTML, CSS e JavaScript puro**, ideal para uso **offline/local** em pequenas lojas, como a loja de roupas *Use Stylo*.

---

## 🎯 Funcionalidades

- ✅ Cadastro de produtos com nome, quantidade e preço  
- ✅ Registro de vendas com atualização automática no estoque  
- ✅ Histórico de vendas com filtro por data  
- ✅ Geração de relatório semanal, mensal e anual com gráficos  
- ✅ Exportação e importação de backup em JSON  
- ✅ Backup em nuvem com Firebase  
- ✅ Interface responsiva para desktop e dispositivos móveis  

---

## 🧱 Estrutura do Código

### 🔹 HTML
- 3 seções principais: **Estoque**, **Vendas** e **Histórico**
- Navegação por botões com exibição dinâmica de conteúdo
- Formulários simples e interativos

### 🔹 CSS
- Uso de **variáveis CSS** para padronizar cores
- Gradiente de fundo, botões estilizados, sombras e cantos arredondados
- Design **clean** e **moderno**
- Estilização do **footer** com links interativos
- **Responsivo** via media queries

### 🔹 JavaScript
- Lógica embarcada no próprio HTML (sem bibliotecas externas)
- Utiliza **localStorage** para salvar os dados localmente
- Funções para:
  - Adicionar, editar e excluir produtos
  - Registrar vendas com desconto percentual
  - Atualizar o estoque automaticamente
  - Filtrar vendas por data e gerar relatórios com gráficos
  - Exportar e importar backup de dados localmente ou pela nuvem (Firebase)

---

## ☁️ Integração com Firebase (Backup em Nuvem)

Além do backup local via `localStorage`, o sistema conta com **integração ao Firebase Realtime Database** para **salvar e restaurar os dados na nuvem**, de forma prática e segura.

### 🔄 Exportação e Importação em Nuvem

- **Exportar para a nuvem**: salva automaticamente os dados do estoque e das vendas no banco de dados em tempo real do Firebase com um clique.
- **Importar da nuvem**: recupera os dados salvos anteriormente na nuvem, restaurando o sistema mesmo que os dados locais tenham sido apagados.
- Ao importar, o sistema também **exibe a data do último backup feito** na nuvem, garantindo mais controle sobre os dados.

> ⚠️ É necessário conexão com a internet para usar essa funcionalidade.

---

## 📊 Relatórios com Gráficos Interativos

O sistema conta com gráficos animados gerados com **Chart.js**, exibindo o desempenho das vendas de forma visual:

- 📆 **Relatório semanal**: mostra os totais vendidos em cada dia da semana.
- 📅 **Relatório mensal**: total de vendas por mês ao longo do ano.
- 📈 **Relatório anual**: comparação dos totais vendidos por ano (se houver dados de anos anteriores).

Esses relatórios são acessados diretamente na aba **Histórico de Vendas**, e ajudam a visualizar o desempenho do negócio ao longo do tempo.

---

## 📦 Tecnologias Utilizadas

- HTML5  
- CSS3 (com variáveis e responsividade)  
- JavaScript (puro)  
- localStorage (armazenamento local no navegador)  
- Firebase Realtime Database  
- Chart.js (gráficos interativos)  

---

## 📱 Responsividade

Este sistema foi projetado para se adaptar a diferentes tamanhos de tela, garantindo uma boa experiência tanto em **computadores quanto em dispositivos móveis**.

---

## 🧑‍💻 Desenvolvido por

**Freitas Fzw**  
🔗 [github.com/freitasfzw](https://github.com/freitasfzw)

---

### ⚠️ Licença e Uso

Este projeto é de uso **exclusivamente pessoal** e **não pode ser redistribuído, copiado, comercializado ou disponibilizado por terceiros**, total ou parcialmente, sem autorização expressa do autor.

---
