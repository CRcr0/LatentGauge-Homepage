# LatentGauge — project homepage

Public homepage for **LatentGauge: Planning-Geometry Attacks in a Measure-Preserving Blind Spot**.

Live site: <https://crcr0.github.io/LatentGauge-Homepage/>

- `index.html` is the whole site: one self-contained page with no build step and no external assets. English / 中文 toggle in the nav bar (`?lang=zh` also works).
- The witness lab recomputes the paper's canonical witness in the browser from the closed-form map (flip at τ* = 0.765739, D(T₁) = 0.004548694 < ε² = 0.0049).
- Interactive story: <https://crcr0.github.io/LatentGauge/> (repository `CRcr0/LatentGauge`).

To preview locally:

```bash
python3 -m http.server 8811 --directory .
```
