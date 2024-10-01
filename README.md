Update Log - SpringWareFPS
Versão 1.2.0 - 01 de Outubro, 2024
Melhorias e Refatorações:

Refatoração do Script: Transformação das variáveis globais em locais, reduzindo a poluição do escopo global e aumentando a segurança do código.
Organização das Configurações: Consolidação das configurações em uma tabela única (Settings), facilitando a manutenção e a legibilidade do script.
Encapsulamento de Funções: Introdução da função loadExternalScript para gerenciar o carregamento de scripts externos com tratamento de erros usando pcall, melhorando a robustez do sistema.
Comentários Detalhados: Inclusão de comentários em todo o código para explicar a funcionalidade de cada seção, facilitando futuras alterações e a compreensão do código.
Sistema de Notificações: Adição de mensagens de sucesso ao carregar scripts, controladas pela variável SendNotifications, proporcionando feedback visual para o usuário.
Tratamento de Erros: Aprimoramento do tratamento de erros ao carregar scripts via HttpGet, com mensagens detalhadas no console em caso de falha.
Correções:

Resolução de um problema em que configurações globais poderiam ser sobrescritas inadvertidamente por outros scripts no ambiente, garantindo maior integridade das configurações.
