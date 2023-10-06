# Docker Image
Image é onde está o sistema operacional e dentro dela é onde estão:
- todas as bibliotecas para rodar a aplicacao
- arquivos da aplicacao
- variaveis de ambiente

Contem tudo o que é necessario para a aplicacao funcionar.

# Containers
Possuem outra funcao
- ambiente isolado
- pode ser iniciado e parado start/stop
- é considerado como um processo que roda dentro de uma maquina

sendo assim, quando a imagem esta pronta é criado um container para rodar a imagem

### Exemplo
- a aplicacao fica pronta
- é convertida para uma imagem atraves do dockerfile
- é criado o container
- carrega a imagem para o container
- é rodada a aplicacao
