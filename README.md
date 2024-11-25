# **Localização e Marcadores**

Este é um aplicativo mobile desenvolvido com React Native, projetado para permitir que os usuários interajam com um mapa, adicionem marcadores personalizados, editem e removam esses marcadores. O projeto inclui gerenciamento de estado e armazenamento persistente dos dados localmente no dispositivo usando AsyncStorage.

---

## **Principais Recursos**

- Exibição de mapa utilizando a biblioteca `react-native-maps`.
- Adição de marcadores com informações detalhadas, como título, descrição e coordenadas (latitude e longitude).
- Edição direta de marcadores no mapa.
- Remoção de marcadores específicos.
- Persistência de dados local com AsyncStorage.
- Localização atual do dispositivo utilizando `expo-location`.
- Interface moderna criada com `react-native-paper` para AppBar e botões.

---

## **Instalação**

1. **Clone o repositório**:

```bash
   git clone git@github.com:BillyTKDLM/Mapa.git
   cd Mapa
```


2. **Instale as dependências do projeto**:
Certifique-se de ter o Node.js e o Expo CLI previamente instalados.

```bash
   npm install
```

3. Inicie o projeto:
```bash
   expo start
```


---

## **Configuração**

Certifique-se de instalar e configurar corretamente as bibliotecas necessárias:

### **Dependências Essenciais**
- **React Native e Expo**
- Framework para desenvolvimento mobile:
 ```
 npm install react-native react-native-maps expo
 ```
- **Gerenciamento de localização**:
 ```
 npm install expo-location
 ```
- **Armazenamento de dados persistente**:
 ```
 npm install @react-native-async-storage/async-storage
 ```
- **Interface de usuário e ícones**:
 ```
 npm install react-native-paper @expo/vector-icons
 ```
- **Navegação entre telas**:
 ```
 npm install @react-navigation/native react-native-screens react-native-gesture-handler react-native-safe-area-context react-native-reanimated react-native-get-random-values react-native-vector-icons
 ```

---

## **Funcionalidades**

### **1. Tela Inicial**
- Lista todos os marcadores salvos com detalhes como título, descrição, latitude e longitude.
- Botão flutuante para adicionar novos marcadores.
- AppBar com opção de logout.

### **2. Tela do Mapa**
- Apresenta um mapa interativo com a localização atual do usuário.
- Funcionalidades disponíveis:
- **Adicionar:** Pressione o mapa para abrir um modal e inserir título e descrição.
- **Editar:** Toque em um marcador para abrir o modal e atualizar as informações.
- **Excluir:** Remova o marcador pela lista ou no modal de edição.
- **Mover:** Reposicione o marcador arrastando-o no mapa.

### **3. Persistência de Dados**
- Os marcadores são salvos localmente no dispositivo utilizando AsyncStorage, garantindo acesso às informações mesmo após o fechamento do aplicativo.

---

## **Guia de Uso**

### **Adicionar um Marcador**
1. Toque no botão “+” na tela inicial.
2. No mapa, pressione no local desejado para abrir o modal.
3. Insira o título e a descrição e clique em “Salvar”.

### **Editar um Marcador**
1. Toque em um marcador já existente no mapa.
2. Atualize as informações no modal e clique em “Salvar”.

### **Excluir um Marcador**
1. Use o botão de exclusão ao lado do marcador na lista ou no modal de edição.

---

## **Dependências Utilizadas**

- React Native
- Expo
- `react-native-maps`
- `expo-location`
- `react-native-paper`
- AsyncStorage
