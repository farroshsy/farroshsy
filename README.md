<h1 align="center">Farros Hilmi Syafei</h1>

<p align="center">
  Software Engineer · Backend &amp; Applied AI · Surabaya, Indonesia<br>
  <em>I build systems that can be checked.</em>
</p>

<p align="center">
  <a href="https://farroshsyportfolio.vercel.app"><b>Portfolio</b></a> ·
  <a href="https://www.linkedin.com/in/farroshilmisyafei/">LinkedIn</a> ·
  <a href="https://www.kaggle.com/farroshs">Kaggle</a> ·
  <a href="mailto:farros.syafei@gmail.com">Email</a>
</p>

<p align="center"><b>Open to software engineering, backend and applied-AI roles · Surabaya or Jakarta</b><br>
<sub>I go wherever the problem needs: APIs and data systems, computer vision, adaptive learning, web and iOS.</sub></p>

---

### 🪪 [computervision-api-system](https://github.com/farroshsy/computervision-api-system): Indonesian document verification API

Built during my internship: OCR and computer vision that verify KTP, SIM, STNK and KIR for driver onboarding and dispatch. Stateless, so nothing is stored.

<p align="center"><img src="https://raw.githubusercontent.com/farroshsy/computervision-api-system/main/docs/img/demo.gif" width="640" alt="Demo: a SIM is read, checked against the claim and rejected as expired, with the reason"></p>
<p align="center"><sub>Synthetic cards only; every field and decision is a real API response.</sub></p>

| SIM | KTP | KIR | STNK |
|:--:|:--:|:--:|:--:|
| **90%** | **87%** | **86%** | **83%** |

<sub>Field accuracy per document type. Returns <code>match</code>, <code>no_match</code> or <code>needs_review</code>: unreadable input goes to a human instead of being guessed at.</sub>

`Python` · `FastAPI` · `PaddleOCR` · `YOLO` · `Docker`

---

### 🔬 [hcie-system](https://github.com/farroshsy/hcie-system): adaptive tutoring for a brand-new subject (thesis)

Personalizes practice from a student's first answer, with no history and no training, and every decision replays exactly.

| cold-start AUC | first attempt | replay |
|:--|:--|:--|
| **0.6051** · on par with BKT 0.5963 · 93 learners | **0.62–0.76** · BKT w/o history ≈ 0.50 | **bit-identical** |

```console
$ make parity
BIT-IDENTICAL ✓  md5 3ab07694eabe0ad52c6378065cf23100
```

`FastAPI` · `PostgreSQL` · `Kafka/Redpanda` · `CQRS` · `Next.js`

---

### More

| repo | what |
|:--|:--|
| [compass](https://github.com/farroshsy/compass) | iOS habit tracker: SwiftUI + widget, records signed in the Secure Enclave, 482 tests |
| [ocr-benchmark-id](https://github.com/farroshsy/ocr-benchmark-id) | public benchmark for Indonesian document OCR, scoring rules published before results |
| [dokumen-id](https://github.com/farroshsy/dokumen-id) · [dokumen-kit](https://github.com/farroshsy/dokumen-kit) | NIK tools that run entirely in the browser or on-device, so data never leaves you |
| [replay-backtest](https://github.com/farroshsy/replay-backtest) | a backtester where lookahead bias is structurally impossible |
| [farroshsyportfolio](https://github.com/farroshsy/farroshsyportfolio) | my portfolio site, Next.js 16 + a live OCR demo |
