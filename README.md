# loja-Rainha

a ideia é montar um ERP, de forma organizada em que gerenciamos uma loja, a ideia é seguir as instruções do usuário, criar inicialmente um CRUD completo, e aprimorar a partir disto.

Status atual:
Modelagem inicial definida, Estrutura base do backend em construção.

planejamento: implementação e aprimoramento do sistema financeiro 

separação de responsabilidades:

/modulo_exemplo

├── routes.py         ----(Onde o front bate)

├── controller.py     ----(Quem recebe o dado e responde)

├── services.py       ----(Onde você coloca a inteligência/regras)

├── models.py         ----(A "planta baixa" dos dados)

└── repository.py     ----(Quem salva e busca no banco)
