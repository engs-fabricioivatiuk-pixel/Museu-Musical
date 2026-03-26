## Buscar biografias automáticas de compositores
Implementar integração com APIs (Wikipedia/Vagalume) para capturar dados biográficos automaticamente. O sistema deve receber o nome do compositor e retornar um resumo formatado, eliminando a necessidade de cadastro manual no banco de dados.
## Criar página de biografia e obras relacionadas
Desenvolver o layout da página para exibir o perfil do artista, integrando o texto biográfico a uma lista de suas principais composições. A interface deve ser responsiva e permitir a navegação direta entre a história do autor e suas músicas catalogadas no museu.
## Criação do banco de dados
Modelar e implementar o esquema de dados (SQL ou NoSQL) para armazenar compositores, obras e metadados. Configurar as tabelas/coleções com relacionamentos claros para garantir consultas rápidas entre as biografias e o acervo musical.
## Validação de Formulários
Implementar scripts (JS/Regex) para verificar campos de entrada antes do envio ao servidor. Garantir que e-mails, nomes e datas estejam no formato correto, exibindo mensagens de erro imediatas para o usuário e prevenindo dados inválidos no banco.
## API de exposições
Criar os endpoints (Rotas GET/POST) para gerenciar as coleções temporárias e permanentes do museu. A API deve permitir a listagem de obras por temática, data ou artista, entregando os dados em formato JSON para o front-end
## Definição do Público-Alvo
Identificar e documentar o perfil dos usuários (estudantes, músicos ou entusiastas) para guiar o design da interface. Analisar faixas etárias e interesses para adaptar a linguagem visual e o nível técnico das informações do museu.
## Sistemas de armazenamento
Escolher e configurar a tecnologia de persistência (ex: SQL para dados relacionais ou NoSQL para metadados flexíveis). Definir a estrutura de diretórios ou buckets (como S3) para armazenar arquivos binários de áudio, capas de álbuns e mídias do museu.
## Design Responsivo Base
Implementar o layout flexível (Grid/Flexbox) para garantir que a interface se adapte a celulares, tablets e desktops. Definir os breakpoints principais e o uso de unidades relativas para que o museu seja acessível em qualquer tamanho de tela.



