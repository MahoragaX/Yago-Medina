# Criador de Fichas de Criatura (Homebrew) para D&D 5e

Este é um projeto de uma ferramenta web desenvolvida para facilitar a criação, gestão e exportação de fichas de criaturas e NPCs para o sistema de D&D 5ª Edição. A aplicação foi criada como um projeto prático para aplicar e demonstrar conhecimentos em desenvolvimento web front-end.

## 🎯 Objetivo

O objetivo principal é fornecer uma interface intuitiva e automatizada para mestres de RPG, permitindo que criem conteúdo homebrew de forma rápida, com um visual fiel aos livros oficiais, e que possam salvar e reutilizar as suas criações facilmente.

## ✨ Funcionalidades Principais

* **Editor Completo:** Campos para todos os atributos, habilidades, ações, reações, etc.
* **Cálculos Automáticos:** Modificadores de habilidade, bónus de proficiência e percepção passiva são calculados em tempo real.
* **Biblioteca de Criaturas:** Salve, carregue, clone e exclua criaturas, com sistema de pesquisa e filtros por tags.
* **Biblioteca de Habilidades:** Crie bibliotecas reutilizáveis para ações, reações e habilidades especiais.
* **Importação com IA:** Utilize Inteligência Artificial para extrair os dados de uma criatura a partir de um ficheiro PDF e preencher a ficha automaticamente.
* **Exportação para HTML:** Exporte as fichas como ficheiros HTML independentes e estilizados.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído inteiramente com tecnologias front-end padrão, sem a necessidade de um back-end complexo.

* **HTML5:** Para a estrutura semântica de toda a aplicação.
* **CSS3 (com Tailwind CSS):** Para a estilização e criação de um layout responsivo e moderno.
* **JavaScript (ES6+):** Para toda a lógica da aplicação, manipulação do DOM, cálculos automáticos e interatividade.
* **Firebase (Firestore):** Utilizado como uma base de dados NoSQL na nuvem para salvar as criaturas e as bibliotecas de habilidades de forma persistente.
* **API do Google AI (Gemini):** Para a funcionalidade de análise e extração de dados de ficheiros PDF.
