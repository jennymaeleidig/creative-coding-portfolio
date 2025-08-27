# For AT-5813-997 - Creative Coding Techniques

## Info

- https://jenny-leidig-creative-coding.neocities.org/
- Deploys to Neocities on merge / commit to main
- run local dev server for testing

```shell
cd ./public && python3 -m http.server 8000
```

- update submodules
  - first time setup

```shell
git submodule update --init --recursive
```

- subsequent updates

```shell
git submodule update --recursive --remote
```

- embed processing sketch

```html
<!-- https://cs.colgate.edu/~efourquet/bec_mitchell/onlinepdes.html -->
<div class="processing-container">
  <script src="../processing.js"></script>
  <canvas id="processing-canvas"></canvas>
</div>
```
