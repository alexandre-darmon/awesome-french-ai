# Awesome French AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated map of the French artificial intelligence ecosystem — labs, models, tools, startups, research, and the people building it.
>
> *Une cartographie de l'écosystème de l'intelligence artificielle française.*

France has become Europe's largest AI startup ecosystem — 1,100+ AI startups according to the [France Digitale × Sopra Steria 2026 mapping](https://francedigitale.org/publications/mapping-startups-ia-2026) — with frontier labs shipping open-weight models, and a research tradition that trained a large share of the field's current leaders. This list maps that ecosystem for builders, researchers, and anyone trying to understand who's who.

**Scope:** actors that build AI (labs, models, tools, AI-native companies) — not general tech companies that merely use it. One line per entry. Curated, not exhaustive.

## Contents

- [Labs & Frontier Models](#labs--frontier-models)
- [Open-Source Models & Libraries](#open-source-models--libraries)
- [AI-Native Startups](#ai-native-startups)
  - [Enterprise AI & Developer Tools](#enterprise-ai--developer-tools)
  - [Health & Life Sciences](#health--life-sciences)
  - [Vertical AI](#vertical-ai)
- [Research & Academia](#research--academia)
- [Infrastructure & Compute](#infrastructure--compute)
- [Investors](#investors)
- [Communities & Events](#communities--events)
- [People to Follow](#people-to-follow)
- [Contributing](#contributing)

## Labs & Frontier Models

- [Mistral AI](https://mistral.ai) — Paris-based frontier lab founded in 2023 by Arthur Mensch, Guillaume Lample, and Timothée Lacroix. Open-weight and proprietary models (Mistral Large/Medium/Small, Codestral, Pixtral, Voxtral, Mistral OCR), the Le Chat assistant, and the Vibe coding agent. Raised a €3B Series D at a €21B+ valuation in September 2026, led by Samsung. Europe's flagship AI lab.
- [Hugging Face](https://huggingface.co) — The "GitHub of machine learning," co-founded by French entrepreneurs Clément Delangue, Julien Chaumond, and Thomas Wolf. Hosts 1M+ models; the central hub of open-source AI.
- [AMI Labs](https://amilabs.xyz) — Advanced Machine Intelligence, founded late 2025 by Yann LeCun after leaving Meta. Builds JEPA-based world models that learn from real-world sensory data, not text. CEO: Alexandre LeBrun. Raised a $1.03B seed at a $3.5B pre-money valuation (March 2026) — the largest seed in European history. HQ Paris, with hubs in New York, Montreal, and Singapore.
- [H Company](https://hcompany.ai) — Founded 2023 in Paris. Builds computer-use agents that operate software interfaces like a human (Runner H, Holo open-weight models, Holo Tab). Raised a $220M seed in 2024. CEO: Gautier Cloix (ex-Palantir France) since 2025.
- [Kyutai](https://kyutai.org) — Non-profit open-science lab backed by Xavier Niel, Rodolphe Saadé, and Eric Schmidt (€300M). Released Moshi, the first real-time full-duplex speech dialogue model, and Hibiki for simultaneous speech translation.
- [Gradium](https://gradium.ai) — Kyutai spin-off founded in 2025 by Neil Zeghidour, Laurent Mazaré, Alexandre Défossez, and Olivier Teboul. Real-time, ultra-low-latency audio language models (speech-to-text, text-to-speech, voice cloning). Seed extended past $100M in 2026, with Nvidia joining.
- [Genesis AI](https://genesis.ai) — Physical AI lab founded in late 2024 by Zhou Xian and Théophile Gervet (ex-Mistral), with offices in Paris and Silicon Valley. Builds a universal robotics foundation model (GENE-26.5) trained on simulation and human-hand data. $105M seed co-led by Eclipse and Khosla Ventures.
- [Bioptimus](https://www.bioptimus.com) — Paris lab building foundation models for biology: H-Optimus (pathology) and M-Optimus, a multimodal "world model" combining pathology, spatial transcriptomics, and genomics. $76M raised.
- [LightOn](https://lighton.ai) — Founded 2016. Enterprise on-prem generative AI (Paradigm platform). First European GenAI company to IPO (Euronext Growth Paris: ALTAI, 2024).
- [Pleias](https://pleias.fr) — French-German lab training fully open LLMs for document processing. Coordinated Common Corpus, the largest fully open multilingual pretraining dataset (~2T tokens).

## Open-Source Models & Libraries

- [Mistral models](https://huggingface.co/mistralai) — Open-weight family (Mistral 7B, Mixtral, Codestral, Pixtral) under permissive licenses. Among the most downloaded open LLMs worldwide.
- [Moshi](https://github.com/kyutai-labs/moshi) — Kyutai's speech-text foundation model and full-duplex dialogue framework, with the Mimi streaming neural audio codec. Apache / CC-BY.
- [Hibiki](https://github.com/kyutai-labs/hibiki) — Kyutai's model for simultaneous, on-device speech-to-speech translation.
- [Holo](https://huggingface.co/Hcompany) — H Company's open-weight computer-use models (Holo1, Holo1.5, Holo2) for agents that navigate GUIs.
- [H-Optimus](https://huggingface.co/bioptimus) — Bioptimus's 1.1B-parameter pathology foundation models, used by a majority of the top 20 pharma companies.
- [scikit-learn](https://scikit-learn.org) — The reference Python machine learning library, born at Inria and still largely maintained from France.
- [CamemBERT](https://camembert-model.fr) — The reference French language model (RoBERTa-based), from Inria's ALMAnaCH team. 4M+ downloads/month; CamemBERT 2.0 released to address concept drift.
- [PyLate](https://github.com/lightonai/pylate) — LightOn's library for training and serving ColBERT / late-interaction retrieval models, built on Sentence Transformers.
- [Giskard](https://github.com/Giskard-AI/giskard-oss) — Open-source library for testing and red-teaming LLMs, RAG systems, and agents (hallucinations, prompt injection, bias). Apache 2.0.
- [Common Corpus](https://huggingface.co/datasets/PleIAs/common_corpus) — Pleias's 2T+ token fully open, permissively licensed multilingual dataset for LLM pretraining.

## AI-Native Startups

### Enterprise AI & Developer Tools

- [Dust](https://dust.tt) — Founded 2022. Platform to build and govern enterprise AI agents connected to internal data and multiple LLMs.
- [Adaptive ML](https://www.adaptive-ml.com) — Founded 2023 by the team behind the Falcon open LLMs (ex-LightOn, Hugging Face). Reinforcement-learning platform to tune and operate open models for enterprise use. Paris and New York.
- [Linkup](https://www.linkup.so) — Founded 2024. Web search API built for LLMs and AI agents, with licensed publisher content. $10M seed led by Gradient (2026).
- [Giskard](https://www.giskard.ai) — Founded 2021. Testing, red-teaming, and evaluation platform for LLM agents; created the Phare benchmark with Google DeepMind as research partner.
- [Photoroom](https://photoroom.com) — Founded 2019 (Y Combinator). GenAI image editing for e-commerce; profitable, with tens of millions of users.

### Health & Life Sciences

- [Nabla](https://nabla.com) — Clinical AI assistant that drafts medical notes from consultations. First partner of AMI Labs.
- [Owkin](https://www.owkin.com) — AI for biotech and drug discovery, combining federated learning with medical research.
- [Gleamer](https://www.gleamer.ai) — Founded 2017. AI copilot for radiology (bone trauma, chest, oncology CT), FDA-cleared and CE-marked.
- [Aqemia](https://www.aqemia.com) — Drug discovery combining generative AI with physics-based modeling; partnerships with Sanofi and Servier.
- [Iktos](https://iktos.ai) — Generative AI and robotic synthesis platform for medicinal chemistry and drug design.

### Vertical AI

- [Doctrine](https://www.doctrine.fr) — Legal intelligence platform; AI-powered search across French case law and legal data.
- [Alan](https://alan.com) — Health insurance built around an AI-driven member experience.
- [Animaj](https://www.animaj.com) — AI-native kids' media company (Pocoyo, Maya the Bee) with a proprietary animation pipeline. $85M raised (2025); backed by Google's AI Futures Fund.
- [Alta Ares](https://www.altaares.com) — Founded 2024. AI-powered air defence: computer-vision guidance (Pixel Lock) and drone/missile interceptors. €50M Series A led by Air Street Capital (2026).
- [objekto.io](https://objekto.io/en) — Founded 2026, Paris. AI that designs multi-part, print-ready 3D models as parametric CAD from a few words, a photo or a sketch, then has them made by an industrial 3D-printing workshop.

## Research & Academia

- [Inria](https://www.inria.fr) — National institute for research in computer science. Birthplace of scikit-learn; its ALMAnaCH team produced CamemBERT and major French NLP resources.
- [CNRS](https://www.cnrs.fr) — National scientific research center; deep involvement in AI and ML research across labs.
- [École Polytechnique](https://www.polytechnique.edu) — Trained the founders of Mistral and Hugging Face, among many other AI leaders.
- [ENS (École Normale Supérieure)](https://www.ens.psl.eu) — Core training ground for French ML researchers.
- [PRAIRIE / PR[AI]RIE-PSAI](https://prairie-institute.fr) — Interdisciplinary AI research institute clustering top Paris-area labs.

## Infrastructure & Compute

- [Scaleway](https://www.scaleway.com/en/ai-supercomputers/) — French cloud provider offering GPU clusters and AI supercomputing (Jeremie / Nvidia H100).
- [OVHcloud](https://www.ovhcloud.com) — European sovereign cloud with managed AI and GPU instances.

## Investors

- [Bpifrance](https://www.bpifrance.fr) — Public investment bank; committed up to €10B to the French AI ecosystem by 2029. Shareholder in Mistral, H, Genesis AI, Animaj, and others.
- [Cathay Innovation](https://www.cathayinnovation.com) — Paris-headquartered global VC; co-led AMI Labs' seed and led Bioptimus's latest round.
- [Eurazeo](https://www.eurazeo.com) — Paris-based investment firm; co-led Gradium's seed and backed Aqemia.
- [Elaia](https://www.elaia.com) — Deep-tech VC, early backer of European AI startups (Giskard, Gleamer, Aqemia, Linkup).
- [Frst](https://www.frst.vc) — Early-stage French VC active in AI.
- [Kima Ventures](https://www.kimaventures.com) — Xavier Niel's prolific seed fund.

## Communities & Events

- [AI Action Summit](https://www.elysee.fr/en/sommet-pour-l-action-sur-l-ia) — Global heads-of-state AI summit hosted by France (Paris, 2025).
- [AI Now Summit 2026](https://mistral.ai/news/ai-now-summit-2026/) — Mistral AI's flagship enterprise summit (Paris, May 2026). Key announcements: industrial AI partnerships with Airbus, BMW, and ASML; Vibe agent launch; Les Ulis data center.
- [Station F](https://stationf.co) — The world's largest startup campus; home to AI programs and labs (Paris).
- [VivaTech](https://vivatech.com) — Europe's largest tech conference, held annually in Paris.
- [Paris ML Meetup](https://www.meetup.com/paris-machine-learning-applications-group/) — Long-running machine learning community meetup.

## People to Follow

### Founders & Executives

- [Arthur Mensch](https://www.linkedin.com/in/arthur-mensch/) — Co-founder & CEO, Mistral AI. Ex-DeepMind.
- [Guillaume Lample](https://x.com/GuillaumeLample) — Co-founder & Chief Scientist, Mistral AI. Ex-Meta (LLaMA).
- [Timothée Lacroix](https://mistral.ai) — Co-founder & CTO, Mistral AI. Ex-Meta (LLaMA).
- [Clément Delangue](https://x.com/ClementDelangue) — Co-founder & CEO, Hugging Face.
- [Thomas Wolf](https://x.com/Thom_Wolf) — Co-founder & Chief Science Officer, Hugging Face.
- [Alexandre LeBrun](https://x.com/lxbrun) — CEO, AMI Labs; founder and chairman of Nabla. Ex-Meta FAIR.
- [Gautier Cloix](https://hcompany.ai/team) — CEO, H Company. Founded and led Palantir's French office.
- [Neil Zeghidour](https://gradium.ai) — Co-founder & CEO, Gradium; Kyutai co-founder. Ex-Google DeepMind, co-author of SoundStream.
- [Julien Launay](https://www.linkedin.com/in/julienlaunay/) — Co-founder & CEO, Adaptive ML. Previously led work on the Falcon open LLMs.
- [Théophile Gervet](https://genesis.ai) — Co-founder, Genesis AI. Former research scientist at Mistral AI.
- [Stanislas Polu](https://x.com/spolu) — Co-founder, Dust. Ex-OpenAI.
- [Thomas Clozel](https://www.owkin.com) — Co-founder & CEO, Owkin.
- [Sixte de Vauplane](https://www.animaj.com/about-us) — Co-founder & CEO, Animaj.

### Researchers

- [Yann LeCun](https://x.com/ylecun) — Deep learning pioneer and Turing Award laureate; executive chairman of AMI Labs and NYU professor.
- [Patrick Pérez](https://ptrckprz.github.io/) — CEO, Kyutai. Ex-Valeo.ai, Inria, Microsoft Research.
- [Hervé Jégou](https://kyutai.org) — Co-founder, Kyutai. Former research director at Meta FAIR.
- [Gaël Varoquaux](https://gael-varoquaux.info) — Inria research director; co-founder of scikit-learn.
- [Pierre-Carl Langlais](https://vintagedata.org/) — Co-founder & CTO, Pleias; open-data and synthetic-pretraining researcher.

## Contributing

Contributions are welcome. To add or update an entry:

1. Fork the repo and edit `README.md`.
2. Keep the format: `[Name](url) — one-line description`.
3. Add only actors that **build** AI in France (labs, models, tools, AI-native companies, research, investors, communities, or people directly shaping the ecosystem).
4. Keep descriptions factual and concise — no marketing language.
5. Open a pull request explaining why the entry belongs here.

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting.

---

*This list reflects a September 2026 snapshot of a fast-moving ecosystem. Roles, valuations, and product names change — verify before citing. Maintained by [Alexandre Darmon](https://www.alexdarmon.net).*

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainer has waived all copyright and related rights to this work.
