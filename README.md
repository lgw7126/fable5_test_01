# fable5_test_01

Interactive WebGL landing page — "Ankward Corp." moss-growing hero.

Move your cursor over the crossed branches to grow moss; scroll to dolly the
camera. Built with Three.js (vendored in `vendor/`), shell-textured fur
shaders for the moss, and a paintable canvas mask driven by raycasting.

## Run

```sh
python3 -m http.server 8000
# open http://localhost:8000/index.html
```

(Any static file server works; ES modules require http://, not file://.)
