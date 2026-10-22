fluxo geral: menu → cadastrar → calcular → salvar no arquivo → listar.

Estrutura do projeto
planos_saude/
├── main.c          → menu principal e laço do programa
├── tipos.h         → structs (Cliente, Dependente, Data) e constantes
├── cliente.c/.h    → cadastrar, editar, remover
├── plano.c/.h      → calcular valor do plano
├── arquivo.c/.h    → carregar e salvar no arquivo
├── listagem.c/.h   → listagem geral, por plano, vencimentos do mês
├── utils.c/.h      → datas, idade, leitura segura, validações
└── clientes.dat    → arquivo de dados (gerado pelo programa)
