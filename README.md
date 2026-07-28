<h1 align="center">Farros Hilmi Syafei</h1>

<p align="center">
  Backend &amp; ML systems engineer · Surabaya, Indonesia<br>
  <em>I build systems that can be checked.</em>
</p>

<p align="center">
  <a href="https://farroshsyportfolio.vercel.app"><b>Portfolio</b></a> ·
  <a href="https://www.linkedin.com/in/farroshilmisyafei/">LinkedIn</a> ·
  <a href="https://www.kaggle.com/farroshs">Kaggle</a> ·
  <a href="mailto:farros.syafei@gmail.com">Email</a>
</p>

<p align="center"><b>Open to backend, data and applied-ML roles — remote or relocating.</b></p>

---

### 🔬 [hcie-system](https://github.com/farroshsy/hcie-system) — event-sourced adaptive tutoring system

Beats BKT on cold-start over 232k learners, and every decision replays exactly.

| cold-start AUC | scale | replay |
|:--|:--|:--|
| **0.6051** vs BKT 0.5963 | **1.98M** rows · **232,440** learners | **bit-identical** |

```console
$ make parity
BIT-IDENTICAL ✓  md5 3ab07694eabe0ad52c6378065cf23100
```
<sub>Published so you can check it rather than take my word for it.</sub>

`FastAPI` · `PostgreSQL` · `Kafka/Redpanda` · `CQRS` · `Next.js`

---

### 🪪 [computervision-api-system](https://github.com/farroshsy/computervision-api-system) — Indonesian document verification API

OCR + verification for KTP, SIM, STNK and KIR. Stateless: nothing is stored.

| SIM | KTP | KIR | STNK |
|:--:|:--:|:--:|:--:|
| **90%** | **87%** | **86%** | **83%** |

```bash
docker pull ghcr.io/farroshsy/computervision-api-system:latest
```
<sub>Returns <code>match</code>, <code>no_match</code> or <code>needs_review</code> — unreadable input goes to a human instead of being guessed at.</sub>

`Python` · `FastAPI` · `PaddleOCR` · `YOLO` · `Docker`

---

<details>
<summary><b>Currently building</b></summary>

<br>

| repo | what |
|:--|:--|
| [replay-backtest](https://github.com/farroshsy/replay-backtest) | a backtester where lookahead bias is structurally impossible |
| [ocr-benchmark-id](https://github.com/farroshsy/ocr-benchmark-id) | public benchmark for Indonesian document OCR |
| [polymarket-calibration](https://github.com/farroshsy/polymarket-calibration) | when a market says 70%, does it happen 70% of the time? |
| [dokumen-id](https://github.com/farroshsy/dokumen-id) | free NIK and plate tools that never send your data anywhere |

</details>
