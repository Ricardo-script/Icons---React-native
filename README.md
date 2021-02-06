# Icons - React Native com Expo
![Logo of the project](https://miro.medium.com/max/3600/0*MBpEPaylvGhvHlTb)
_______________________________________________________________________________
Documentação: https://docs.expo.io/guides/icons/#expovector-icons
#### Biblioteca de Icones:
```sh
https://icons.expo.fyi/
```
#### Exemplo de como utilizar:
import * as React from 'react';
import { View, StyleSheet } from 'react-native';
import { Ionicons } from '@expo/vector-icons';

export default function App() {
  return (
    <View style={styles.container}>
	<Ionicons name="md-checkmark-circle" size={32} color="green" />
    </View>
  );
}   
_______________________________________________________________________________
