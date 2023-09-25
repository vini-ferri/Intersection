# Intersection
Um aplicativo para calcular a menor distância entre múltiplas rotas

# Funcionalidades Principais
- Google Maps em React: O projeto utiliza a biblioteca React para renderizar o mapa do Google Maps.
- Adicionar marcadores: É possível adicionar marcadores no mapa para indicar pontos de interesse ou localizações específicas.
- Zoom in e zoom out: A aplicação permite controlar o nível de zoom no mapa, permitindo uma visualização mais detalhada ou uma visão mais ampla.
- Controles básicos ocultados: Os controles padrão do Google Maps, como os botões de zoom e controle de rotação, podem ser ocultados para uma interface mais limpa e personalizada.
- Autocomplete nas localizações: É implementado um recurso de autocomplete para facilitar a busca de localizações. Os usuários podem digitar um endereço ou lugar, e a aplicação sugere opções à medida que o usuário digita.
- Serviço de direção: A aplicação utiliza o serviço de direção do Google Maps para calcular rotas entre dois pontos específicos.
- Renderização das direções: As rotas calculadas são exibidas no mapa, permitindo visualizar a direção a ser seguida.

## Iniciando o App

Para executar o aplicativo, siga as etapas abaixo:

1. Crie uma chave de API no Google Developers Console e certifique-se de habilitar o acesso de terceiros à sua API, caso contrário, ocorrerá um erro de "development purposes only".
2. Adicione um arquivo `.env` ou `.env.local` na pasta raiz do projeto e especifique sua chave de API da seguinte forma: `REACT_APP_GOOGLE_MAPS_API_KEY=your_api_key_here`.
3. No diretório do projeto, execute o seguinte comando, dependendo do gerenciador de pacotes que você está usando:

Usando Yarn:

```
yarn install
yarn start
```

Ou usando npm

```
npm install
npm start
```
