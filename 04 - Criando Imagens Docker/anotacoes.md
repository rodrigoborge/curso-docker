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

# Variáveis Docker
- FROM: qual imagem vai carregar? Linux, Ubunto, Alpine, Debian
- WORKDIR: especificacao de diretorio
- COPY/ADD: copia ou adiciona arquivos que fazem parte da aplicacao dentro da imagem
- RUN: comando para rodar a aplicacao/processo
- ENV: configuracoes do ambiente, o que precisa dentro do Linux para rodar a aplicacao
- EXPOSE: indica em qual porta vai rodar
- USER: quem é o usuario que executa a aplicacao
- CMD / ENTRYPOINT: roda comandos