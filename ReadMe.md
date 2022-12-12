https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_wasm

루트 경로 : wasm-pack build --target bundler
pkg : npm link
site : npm link hello-wasm
npm install
npm run serve
이때 index.html 은 site경로에 작성되어야 한다 (예제에선 wasm-pack build --target web 예제에서 사용된 root directory에 작성된 index.html의 내용만 교체하라고 나와있음)