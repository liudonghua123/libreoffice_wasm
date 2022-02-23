# libreoffice_wasm

This is web static files served on https://lab.allotropia.de/wasm/, just for personal fun.

Note you need to enable Cross-origin isolation for using SharedArrayBuffer, or you will got `ReferenceError: SharedArrayBuffer is not defined` Error!

![image](https://user-images.githubusercontent.com/2276718/155262987-1eb52ac7-84c3-427a-b206-26a8364442a7.png)

See https://developer.chrome.com/blog/enabling-shared-array-buffer/?utm_source=devtools#cross-origin-isolation for more details.

### How to run it

1. `git clone git@github.com:liudonghua123/libreoffice_wasm.git`
2. `cd libreoffice_wasm`
3. `npm install -g serve` # optional if you have installed already
4. `serve .`

### References

- https://www.oschina.net/news/183522/libreoffice-webassembly-port
- https://git.libreoffice.org/core/+/refs/heads/master/static/README.wasm.md
- https://fosdem.org/2022/schedule/event/lotech_lowa/attachments/slides/5218/export/events/attachments/lotech_lowa/slides/5218/fosdem_2022_wasm.pdf
- https://github.com/vercel/serve/issues/606

