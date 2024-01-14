# flutter_example

Flutter を何となく触ってみる

##  コマンドメモ

- パッケージインストール
  `flutter pub get`

- iOS シミュレータ立ち上げ
  `open -a Simulator`

アプリケーションンボ起動
`flutter run`

```bash

# シミュレータ系

## iOSシミュレータの起動
open -a Simulator

## AndroidエミュレータAVD名一覧を取得
emulator -list-avds
~/Library/Android/sdk/emulator/emulator -netdelay none -netspeed full -avd {avd_name}
## wipe-data
~/Library/Android/sdk/emulator/emulator -avd {avd_name} -wipe-data


flutter pub get

flutter devices

flutter run -d {device_id}

```
