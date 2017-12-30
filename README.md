# react-graphcool-image

## Why
- using the api of graphcool image help you get the proper size image for your application https://github.com/graphcool/serverless-image-proxy
- get the proper size for crop and contain image
- using this will show the smaller image that had been loaded before as a preview automatically

## Install
```bash
npm install react-graphcool-image -S
```

## Using

### React
```jsx
import GraphCoolImage from 'react-graphcool-image'

<GraphCoolImage file={{ secret: string, url: string }} width={number} height={number} />
```

### React Native
```jsx
import GraphCoolImage from 'react-graphcool-image/native'

<GraphCoolImage file={{ secret: string, url: string }} width={number} height={number} />
```

### Use with Image Progress
```jsx
import GraphCoolImage from 'react-graphcool-image/native'

<GraphCoolImage imageComponent={ImageProgress} progressProps={{
  useNativeDriver: true,
  animated: false,
  width: Math.round(width * 0.8),
  color: 'rgba(255, 255, 255, 0.8)',
  unfilledColor: 'rgba(200, 200, 200, 0)'
 }} />
```
