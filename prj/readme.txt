yarn add -D @tauri-apps/cli
cargo install tauri-cli --locked --version "^1.0.0-rc"
yarn add @tauri-apps/api
# OR
npm install @tauri-apps/api

yarn tauri init

tauri info
 
prj need add  

在package.json里scripts 添加
"scripts": {
    "tauri": "tauri",
}

