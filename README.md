This is a GitHub Pages repo hosting web demos of various [tlaplus-community](https://github.com/tlaplus-community) projects.
You can visit it at https://tlaplus-community.github.io.
Currently, it hosts web demos for the following projects:
* [tree-sitter-tlaplus](https://github.com/tlaplus-community/tree-sitter-tlaplus) at https://tlaplus-community.github.io/tree-sitter-tlaplus

## Running Locally

If you try to run these demos locally by simply cloning the repo then opening one of the `index.html` files in the browser, you will run afoul of [this error](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS/Errors/CORSRequestNotHttp) (seen in your browser's developer console).
You can read the reasons for it, but the upshot is you have to [set up a local http server](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server).
This will likely be as simple as navigating to the repo directory and running `python -m http.server` then navigating to `http://localhost:8000` in your browser.
