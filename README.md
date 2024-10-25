Gerenciador de Lista de Compras

Este é um aplicativo de terminal em Python para gerenciar listas de compras. O programa permite adicionar, remover e visualizar itens em uma lista de compras, além de salvar e carregar listas salvas em arquivos .json.

1 - Funcionalidades

Adicionar itens: Inclua um item e sua quantidade na lista de compras.
Remover itens: Exclua um item específico da lista.
Visualizar a lista: Veja todos os itens e suas quantidades na lista.
Salvar e carregar listas: Salve uma lista de compras em um arquivo .json e carregue listas previamente salvas.
Gerenciamento de arquivos: Crie uma nova lista ou carregue listas existentes de um diretório.

2 - Estrutura do Código

Funções principais

adicionar_item(compras, item, quantidade): Adiciona um item com sua quantidade na lista de compras.
remover_item(compras, item): Remove um item da lista, se ele existir.
visualizar_compras(compras): Exibe todos os itens e quantidades.
salvar_compras(compras, nome_arquivo): Salva a lista atual em um arquivo JSON.
carregar_compras(nome_arquivo): Carrega uma lista de compras a partir de um arquivo JSON.
gerenciar_compras(compras, nome_arquivo=None): Menu para adicionar, remover, visualizar e salvar a lista de compras.
main(): Menu principal para criar ou carregar uma lista de compras.

3 - Pré-requisitos

Python 3.x
Biblioteca json (já inclusa no Python)

4 - Como Executar
Clone ou faça o download do repositório para sua máquina.

Navegue até o diretório onde o código está salvo.

Execute o arquivo:

Ao iniciar o programa, escolha uma das opções:
Criar uma nova lista de compras: inicia uma lista vazia.
Carregar uma lista existente: lista os arquivos JSON no diretório e permite carregar um deles.
Sair: fecha o programa.

Na interface de gerenciamento da lista, você pode:
Adicionar um item: insere o nome e a quantidade.
Remover um item: digita o nome do item para removê-lo.
Visualizar a lista: exibe a lista completa.
Salvar e sair: salva a lista no arquivo especificado.
Sair sem salvar: encerra o gerenciamento sem salvar as mudanças.

Exemplo de uso
Adicionar um item: Digite 1 e insira o nome e quantidade do item.
Salvar a lista: Digite 4 e forneça o nome do arquivo (ou um novo nome) para salvar.
Carregar uma lista existente: Selecione uma lista pelo número correspondente ao arquivo JSON.

5 - Observações
Certifique-se de que os arquivos .json são mantidos no mesmo diretório do script para carregamento correto. O código considera o sistema operacional para comandos de limpeza de tela (cls para Windows e clear para Unix/Linux).
