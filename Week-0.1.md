# React Native Start

**Not: Android kısımlarını ios ile değiştirebilirsiniz.**

<br>

Proje kurulumu :

1. Terminal kısmına `npx react-native init [proje-adi]` yazarak React Native projesi başlatabilirsiniz.

IOS için build alma :

1. ios klasörüne gelip terminalde aç dedikten sonra `pod install --repo-update` terminale kodu giriniz.

Kendi cihazınızda çalıştırmak için :

1. Telefonu kablo ile bağlayıp usb debugging modunu açın.

2. Terminalde cihazınızı görüntülemek için `adb devices`

3. Projenizi cihazınızda başlatmak için `npx react-native run-android --deviceId=yourDeviceId `

4. Projenizi daha sonra başlatmak için : `adb reverse tcp:8081 tcp:8081`

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

- NPM sürümlerini görme : `npm outdated`
- NPM içeriklerini güncelleme : `npm update`
- npm upgrade ve update arasındaki farklar : [Tıkla](https://stackoverflow.com/questions/12478679/npm-install-vs-update-whats-the-difference)
- Start dediğimizde npm sıkıtılarını çözmek için : `npm audit fix`
  Sorunlar :

- npx kurulumu için : `sudo npm i -g npx`
- Ruby version seçme :
  - `rvm install 2.7.5`
  - `rvm list`
  - `rvm use 2.7.5`
- RVM indirmek için : [Tıkla](https://rvm.io/rvm/install)
