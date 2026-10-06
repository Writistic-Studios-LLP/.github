<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20&height=190&section=header&text=Writistic%20Studios&fontSize=56&fontColor=ffffff&animation=fadeIn&desc=An%20open%2C%20free%20alternative%20to%20gacha%20mechanics&descSize=20" alt="Writistic Studios" />

![MIT](https://img.shields.io/badge/licence-MIT-22d3ee?style=for-the-badge) ![Open source](https://img.shields.io/badge/open-source-34d399?style=for-the-badge) ![Anti-gacha](https://img.shields.io/badge/anti--gacha-by%20design-f43f5e?style=for-the-badge) ![Paper](https://img.shields.io/badge/paper-V5.0-a78bfa?style=for-the-badge)

**Game design and tools by Pratham Prateek Mohanty**

</div>

## 🌸 Blossom Bifurcation Mechanism

Players pay for **regret-free convenience**, never for luck. A story branches at key points, and a player can pay to rewind (**Fate Reversal**) and take a different path. A small trained model watches for players probing the hidden pattern and adapts randomization, so casual players get consistency and probers get chaos.

```mermaid
flowchart LR
  A[Story branches] --> B[Fate Reversal<br/>pay to rewind]
  B --> C[Behaviour features]
  C --> D[ML threat score 0-1]
  D --> E[Adaptive randomization<br/>20% to 100%]
```

| What | Where |
|---|---|
| 🎮 Live demo | https://huggingface.co/spaces/writistic-studios/Blossom-Bifurcation-Demo |
| 💻 Code, API, six developer guides | [Blossom-Bifurcation-Threat-Model](https://github.com/Writistic-Studios-LLP/Blossom-Bifurcation-Threat-Model) |
| 🧠 Model | https://huggingface.co/writistic-studios/Blossom-Bifurcation-Threat-Model |
| 📊 Dataset (30,000 simulated sessions) | https://huggingface.co/datasets/writistic-studios/Blossom-Bifurcation-Simulated-Sessions |
| ⚡ Hosted API | https://bbm-threat-api.vercel.app |
| 📄 Research paper V5.0 | https://doi.org/10.5281/zenodo.23180849 |

> Honest status: the model is a prototype trained on simulated players, since no real player logs exist yet. Retrain on real beta data before relying on it.
