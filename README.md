Formulário de Cadastro com Validação e API de CEP
Este projeto é uma aplicação web frontend que consiste em um formulário de cadastro de usuário completo. Foi desenvolvido como parte de um trabalho prático para a disciplina "Framework para Desenvolvimento de Software", com o objetivo de aplicar conceitos fundamentais do desenvolvimento web moderno.

A aplicação inclui validação de campos em tempo real, estilização responsiva e integração com uma API externa para preenchimento automático de endereço.

🔗 Link para o Deploy (Vercel): [Insira o seu link da Vercel aqui]

✨ Funcionalidades
Formulário Responsivo: A interface se adapta perfeitamente a diferentes tamanhos de tela, de desktops a dispositivos móveis, graças ao framework Bootstrap 5.

Consumo de API Externa: Integração com a API ViaCEP para preencher automaticamente os campos de endereço (Rua, Bairro, Cidade, Estado) a partir do CEP digitado pelo usuário.

Validação de Campos (Client-Side):

Verificação de preenchimento para todos os campos obrigatórios.

Validação do formato do e-mail utilizando Expressões Regulares (Regex) para garantir que o dado inserido seja válido.

Feedback visual imediato para o usuário, destacando os campos com erros.

Estrutura em Arquivo Único: Para fins de simplicidade e portabilidade, todo o código (HTML, CSS e JavaScript) está contido em um único arquivo.

🛠️ Tecnologias Utilizadas
O projeto foi construído utilizando as seguintes tecnologias e ferramentas:

HTML5: Para a estruturação semântica do conteúdo.

CSS3: Para estilizações personalizadas.

Bootstrap 5: Framework CSS para a criação de um design moderno, responsivo e "mobile-first".

JavaScript: Linguagem de programação para adicionar interatividade e lógica à aplicação.

jQuery: Biblioteca JavaScript para simplificar a manipulação do DOM, tratamento de eventos e requisições AJAX.

ViaCEP API: Webservice gratuito para consulta de Códigos de Endereçamento Postal (CEP) no Brasil.

IDE NetBeans: Ambiente de desenvolvimento integrado utilizado para a criação e gerenciamento do projeto.

🚀 Como Executar o Projeto Localmente
Como este é um projeto frontend puro, não há necessidade de um servidor complexo ou de processos de build.

Clone o repositório (ou faça o download dos arquivos):

git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

Navegue até a pasta do projeto:

cd seu-repositorio

Abra o arquivo cadastro-usuario.html no seu navegador de preferência.

E pronto! A aplicação estará funcionando em sua máquina local.

🎯 Objetivo do Projeto
O principal objetivo deste trabalho foi demonstrar a aplicação prática de conceitos de desenvolvimento web, incluindo:

Criação de uma estrutura HTML5 semântica e bem organizada.

Estilização de um formulário complexo com o framework Bootstrap 5.

Manipulação de eventos e do DOM utilizando a biblioteca jQuery.

Implementação de lógica de validação de dados no lado do cliente.

Comunicação com uma API REST externa de forma assíncrona (AJAX) para buscar dados e melhorar a experiência do usuário.
