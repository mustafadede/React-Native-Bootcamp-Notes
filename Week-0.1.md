# React Native deployment

Proje kurulumu :

1. Terminal kısmına `npx react-native init [proje-adi]` yazarak React Native projesi başlatabilirsiniz.

İpuçları :

- NPM cache temizleme : `npm cache clean --force`
- NPM cache temizleme doğrulama : `npm cache verify`
- NPM install dediğimizde sürüm çakışması için : `npm install --legacy-peer-deps`

Sorunlar :

- npx kurulumu için : `sudo npm i -g npx`
- Ruby version seçme :
  - `rvm install 2.7.5`
  - `rvm list`
  - `rvm use 2.7.5`
- RVM indirmek için : [Tıkla](https://rvm.io/rvm/install)
