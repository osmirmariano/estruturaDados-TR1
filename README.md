# estruturaDadosI-TR1
Implementação de uma aplicação que gerencia embarcações 
# Porto
- Fila de contêiners

# Contêiners: 
- int id;
- int destino;
- string origem;

# Embarcação
- Navio que carregará os contêiners

# Embarcação
- string nome;
- arry list destinos;
- array list conteiners; (uma lista para cda destino)
- string status; (aportou, navegando ou em espera)

#Fila de Contêiners (implmentação de forma dinâmica)
* Um contêiner, ao chegar ao porto, será enfilerado se é compatível com os destinos disponíveis;

* Ao chegar uma embarcação, os contêiners são removidos da fila de acordo com seu destino, e são colocados  na embarcação, até o número máximo de 10 contêiners pr embarcação;

# Status da Embarcação
- Aportou: está vazia e será carregada;
- Navegando: está cheia ou não há mais contêiners para seus destinos;
- Em espera: não há nenhum contêiner para deus destino

# Os dados de embaracações e destinos podem vim de um arquivo

# Menu
- Chegou Conteiner
- Chega Embarcação
- Verificar embarcação em espera
- Mostrar
