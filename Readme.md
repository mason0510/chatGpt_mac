打包步骤:
npm config set ELECTRON_MIRROR "https://cdn.npm.taobao.org/dist/electron/"
npx electron-packager .
npx electron-installer-dmg ./electron_mac-darwin-x64/electron_mac.app emp1

重新打包
npx electron-packager . --overwrite


