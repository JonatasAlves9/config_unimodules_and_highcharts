# Gráficos no React Native com HighCharts

Iniciar projeto React Native

```bash
npx react-native init ReactNativeHighcharts
```

Em android adicionar arquivo [local.properties](http://local.properties) com o seguinte conteudo:

- in Windows `sdk.dir = C:\\Users\\USERNAME\\AppData\\Local\\Android\\sdk`
- in macOS `sdk.dir = /Users/USERNAME/Library/Android/sdk`
- in linux `sdk.dir = /home/USERNAME/Android/Sdk`

# Dependências para os gráficos

Necessário instalar: 

- @highcharts/highcharts-react-native
- react-native-unimodules
- react-native-webview

# Configurar o UniModules

Link da documentação:

[Installing react-native-unimodules - Expo Documentation](https://docs.expo.io/bare/installing-unimodules/)

Prestar bastante atenção que é necessário fazer uma modificação no import no arquivo main.application no **Android.**