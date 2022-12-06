## 打包步骤:
1.npm config set ELECTRON_MIRROR "https://cdn.npm.taobao.org/dist/electron/"
2.npx electron-packager .
3.npx electron-installer-dmg ./electron_mac-darwin-x64/electron_mac.app chat

4.重新打包
npx electron-packager . --overwrite


