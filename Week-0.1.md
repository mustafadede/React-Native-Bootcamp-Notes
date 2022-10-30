# React Native deployment

Proje kurulumu :

1. Terminal kısmına `npx react-native init [proje-adi]` yazarak React Native projesi başlatabilirsiniz.

İpuçları :

- NPM cache temizleme : `npm cache clean --force`
- NPM cache temizleme doğrulama : `npm cache verify`
- NPM install dediğimizde sürüm çakışması için : `npm install --legacy-peer-deps`
- Android Virtual device listeleme : `emulator -list-avds`
- İstediğimiz device'ı terminalde açmak için : `emulator @1`
- Kendi cihazınızı takıp terminalden çalıştırmak için :

  - `npm run android`
  - `react-native run android`
  - `npx react-native run-android`

- React Native Upgrade helper : [Tıkla](https://react-native-community.github.io/upgrade-helper/)

Sorunlar :

- npx kurulumu için : `sudo npm i -g npx`
- Ruby version seçme :
  - `rvm install 2.7.5`
  - `rvm list`
  - `rvm use 2.7.5`
- RVM indirmek için : [Tıkla](https://rvm.io/rvm/install)
