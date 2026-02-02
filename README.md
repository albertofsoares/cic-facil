CIC Fácil - Apoio Acadêmico 🎓

O CIC Fácil é uma plataforma leve e intuitiva desenvolvida para centralizar materiais de apoio, resumos e guias práticos para estudantes de Ciência da Computação (ênfase Anhanguera). O projeto foca em acessibilidade, organização de conteúdo e facilidade de manutenção.

!

🚀 Funcionalidades Principais

Sistema de Busca em Tempo Real: Encontre assuntos específicos instantaneamente através de palavras-chave.

Categorização Inteligente: Filtros por matéria (Sistema Operacional, Gestão de Projetos, Arquitetura, etc).

Modo Escuro (Dark Mode): Interface adaptável para longas sessões de estudo, com persistência de tema.

Checklist de Progresso: Marque os conteúdos já estudados para manter o controle do seu avanço.

Edição Facilitada: Arquitetura que permite adicionar novos conteúdos diretamente no HTML de forma natural, sem lidar com complexidades de código.

UX Otimizada: Modal de leitura com controles fixos e fechamento inteligente para facilitar a leitura de textos longos.

🛠️ Tecnologias Utilizadas

HTML5: Estruturação semântica de conteúdo.

Tailwind CSS: Estilização moderna, responsiva e otimizada.

JavaScript (Vanilla): Lógica de busca, filtros, gerenciamento de estado local e manipulação do DOM.

Google Fonts & Lucide Icons: Identidade visual limpa e profissional.

📁 Estrutura do Projeto

O projeto foi refatorado para ser Single-File (um único arquivo), facilitando o deploy e a edição:

Configurações: Objeto JS no topo do arquivo para metadados e estrutura dos cards.

Templates: Conteúdo textual escrito de forma livre em tags <template> para edição sem complicações.

Lógica: Motor JS que integra busca, filtros e modais.

⚙️ Como usar

Clone o repositório:

git clone [https://github.com/seu-usuario/cic-facil.git](https://github.com/seu-usuario/cic-facil.git)


Abra o arquivo index.html em qualquer navegador moderno.

Para adicionar novos conteúdos, basta inserir um novo objeto no array posts e o respectivo texto dentro de um <template id="post-conteudo-X">.

📈 Evolução do Projeto

O desenvolvimento seguiu as seguintes etapas (confira o log_projeto.md para detalhes):

Fundação: Estrutura base e filtros.

UI/UX: Implementação de Dark Mode e design "Glassmorphism".

Acessibilidade: Ajustes de contraste e controles de navegação fixos.

Refatoração: Mudança para sistema de templates visando facilitar a inserção de textos acadêmicos.

Desenvolvido para facilitar a jornada acadêmica em Ciência da Computação. 💻✨
