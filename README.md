📚 Trilha Inicial DevOps Jr
Este projeto tem como objetivo principal introduzir e praticar conceitos fundamentais de DevOps Jr através da implementação de um pipeline de CI/CD para uma aplicação web simples. Os principais objetivos são:

Estrutura do Projeto:
O projeto deve incluir a aplicação web, um Dockerfile para containerização, a configuração do GitHub Actions para CI/CD e um README.md detalhando o processo de configuração e execução do pipeline.

Objetivos:
Configurar um repositório no GitHub para a aplicação.
Implementar um pipeline de CI/CD usando GitHub Actions.
Automatizar os processos de build, testes e deploy da aplicação.
Documentar o processo de configuração e execução do pipeline.
Requisitos Funcionais:
Configuração do Repositório:

Criar um repositório público no GitHub para o projeto.
Adicionar um arquivo README.md com uma descrição do projeto.
Aplicação Web:

Utilizar uma aplicação web simples, como um projeto em Node.js, Python Flask ou qualquer outra tecnologia de sua escolha.
Incluir um arquivo Dockerfile para a aplicação.
Pipeline de CI/CD:

Configurar GitHub Actions para automatizar o build da aplicação.
Adicionar testes automatizados (unitários ou de integração).
Configurar o deploy automático da aplicação usando GitHub Actions.
Deploy:

Implementar o deploy em uma plataforma gratuita como Heroku, Netlify, Vercel ou GitHub Pages (para aplicações estáticas).
Estrutura do Projeto:
project-root/
│
├── .github/
│   ├── workflows/
│   │   ├── ci.yml
│   │   └── cd.yml
│
├── src/
│   ├── app/ (ou a estrutura da aplicação escolhida)
│
├── tests/
│   ├── test_app.py (ou a estrutura de testes apropriada)
│
├── Dockerfile
├── README.md
└── LICENSE
Entregáveis:
Repositório GitHub:
Repositório público com a aplicação e configuração do pipeline.
Pipeline de CI/CD:
Configuração do GitHub Actions para build, testes e deploy.
Documentação:
README.md com instruções para configurar, executar e visualizar o pipeline.
Dicas para Abordar o Projeto 🌟
Crie um Fork desse Repositório.
Criar do Zero: É fundamental que o projeto seja desenvolvido completamente do zero, demonstrando suas habilidades e criatividade desde o início.
Teste o Pipeline localmente antes de subir para o GitHub para garantir que está funcionando corretamente.
Critérios de Avaliação:
Configuração do Pipeline: O pipeline de CI/CD está configurado corretamente e automatiza os processos de build, testes e deploy?
Qualidade do Código: O código da aplicação e os arquivos de configuração estão bem estruturados e documentados?
Execução dos Testes: Os testes são executados automaticamente e verificam a funcionalidade da aplicação?
Deploy Automático: A aplicação é automaticamente implantada em uma plataforma de hospedagem?
Documentação: A documentação é clara e detalha o processo de configuração e execução do pipeline?
Não Queremos 🚫
Descobrir que o candidato não foi quem realizou o teste.
Ver commits grandes sem muita explicação nas mensagens no repositório.
Entregas padrão ou cópias de outros projetos. Buscamos originalidade e autenticidade em cada contribuição.
Prazo ⏳
A data máxima para entrega das trilhas foi removida, permitindo que as pessoas entreguem conforme sua disponibilidade. No entanto, ainda é necessário concluir a trilha com sucesso para ser inserido em uma equipe.

Checklist de Configuração do Ambiente de Trabalho
Ferramentas e Plataformas Utilizadas:

Repositório Git: GitHub
Integração Contínua/Entrega Contínua: GitHub Actions
Hospedagem: Heroku, Netlify, Vercel ou GitHub Pages
Configuração do Ambiente:

Criar Conta no GitHub: Se você ainda não tem uma conta, crie uma conta gratuita no GitHub.
Configurar GitHub Actions:
Crie workflows de CI/CD no diretório .github/workflows/ do repositório.
Deploy:
Configure uma conta na plataforma de hospedagem escolhida.
Integre o deploy com o workflow do GitHub Actions.
Instruções de Entrega: 📬
Após finalizar o projeto, publique-o em uma URL pública (por exemplo, Vercel, Netlify, GitHub Pages, etc.) e hospede o seu servidor na nuvem. Use serviços que ofereçam uso gratiuto por um período, como a AWS e preencha o Formulário:

Desafio da Inovação 🚀
Achou esse projeto inicial simples? Eleve ainda mais! Estamos em busca de mentes inovadoras que não apenas criem, mas que também desafiem os padrões. Como você pode transformar essa estrutura inicial em algo verdadeiramente extraordinário? Demonstre o poder da sua criatividade e o impacto das suas ideias inovadoras!
