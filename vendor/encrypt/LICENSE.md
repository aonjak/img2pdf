# Licenses for vendored files in `vendor/encrypt/`

These files provide AES-256 PDF encryption fully in the browser (offline).

## qpdf.js / qpdf.wasm

Source: **@neslinesli93/qpdf-wasm** v0.3.0 — https://github.com/neslinesli93/qpdf-wasm
Wrapper license: **ISC**.

The WebAssembly binary (`qpdf.wasm`) embeds the following upstream projects:

- **qpdf** — the PDF transformation/encryption engine. License: **Apache-2.0**
  (https://github.com/qpdf/qpdf). qpdf implements the PDF standard security
  handler, including 256-bit AES (V5/R6, AESV3).
- **Emscripten** runtime glue (`qpdf.js`). License: **MIT / University of
  Illinois/NCSA** (Emscripten dual license).
- Bundled C libraries used by qpdf: **zlib** (zlib license) and **libjpeg**
  (IJG license), as compiled into the wasm by the qpdf-wasm build.

---

### ISC License (qpdf-wasm wrapper)

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH
REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT,
INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM
LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR
OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR
PERFORMANCE OF THIS SOFTWARE.

---

For the full text of the Apache-2.0 license (qpdf), see
https://www.apache.org/licenses/LICENSE-2.0
