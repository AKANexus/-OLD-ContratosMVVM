# Gerador de Contratos — MVVM

**Projeto histórico — sem manutenção ativa.** Este repositório é preservado como registro de uma etapa anterior de desenvolvimento. Não há previsão de novas funcionalidades ou correções.

## Sobre o projeto

Aplicação desktop para montar contratos modulares em formato Word a partir de clientes e serviços cadastrados. O objetivo era reunir cláusulas, quantidades e valores em documentos adaptados a cada cliente.

## Escopo preservado

A aplicação organiza clientes, contratos-base e contratos associados, com geração de arquivos `.docx`. O código também contém integração com Bling e comandos relacionados a contas a receber; a documentação original descreve a consulta de dados de clientes em uma base Firebird 2.5 de terceiros.

## Tecnologias e organização

C#, WPF e .NET 5, com organização MVVM e Entity Framework Core 5. A configuração de persistência consultada utiliza SQLite, e a geração de documentos usa DocX 2.0.0, conforme o arquivo de projeto; `Services/ContratoDocService.cs` concentra a composição do Word.

## Estado e contexto de execução

A execução depende de Windows, banco e integrações configurados, além das imagens utilizadas nos documentos. O README anterior mencionava uso na Trilha Tecnologia; essa informação é preservada como contexto histórico, sem afirmar uso atual.

Esta documentação foi revisada a partir dos arquivos versionados. Não foram executados build, testes funcionais ou integrações durante a revisão; as versões citadas descrevem o projeto preservado, não uma recomendação de stack para novos sistemas.
