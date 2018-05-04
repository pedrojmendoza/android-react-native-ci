# Android/React Native CI

## Continous Integration (CI) for React Native apps on Android
An image for building Android apps based on React Native. This Docker image contains the Android SDK and most common packages necessary for building Android apps as well as Node in a CI tool. Based on [javiersantos/android-ci](https://github.com/javiersantos/android-ci/).

## CMDs
1. ```docker build -t android-react-native-ci:latest .```
2. ```docker login```
3. ```docker tag android-react-native-ci menpedro/android-react-native-ci:latest```
4. ```docker push menpedro/android-react-native-ci:latest```
