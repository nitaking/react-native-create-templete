# react-native-create-templete

## Components
```jsx
// @flow
import React, { Component } from 'react';
import { View, Text, TouchableOpacity } from 'react-native';
import styles from './styles';

type Props = {

};

export default class MyComponent extends Component<Props> {
  static defaultProps = {
  };

  render() {
    return (
      <View style={styles.container}>
      </View>
    );
  }
}

```

## Stateless Functional Components
```jsx
// @flow
import React, { Component } from 'react';
import { View } from 'react-native';
import styles from './styles';

type Props = {

};

const component = (props:Props) => {
	const { value } = props;
  
    return (
      <View style={styles.container}>
      </View>
    );
}

```

## Styles
```jsx
// @flow
import React, { Component } from 'react';

type Props = {

};

const component = (props:Props) => {
	const { value } = props;
  
    return (
      <View style={styles.container}>
      </View>
    );
}

```
