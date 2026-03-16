# SilkRoadNLP 2026 — Proceedings

**First Workshop on NLP and LLMs for the Iranian Language Family**
Co-located with [EACL 2026](https://2026.eacl.org/) · Rabat, Morocco · March 2026

---

This repository hosts the accepted papers of the **SilkRoadNLP 2026** workshop, dedicated to advancing NLP research across the Iranian language family — including Persian, Kurdish, Pashto, Balochi, Luri, Ossetian, Tajik, Shughni, and related languages.

> For more information, visit [silkroadnlp.org](https://silkroadnlp.org)

---

## Accepted Papers

| # | Title | Authors | Resources | Poster |
|---|-------|---------|-----------|--------|
| 2 | [Unmasking the Factual-Conceptual Gap in Persian Language Models](proceedings/2.pdf) | Alireza Sakhaeirad, Ali Ma'manpoosh, Arshia Hemmat | [![HuggingFace](https://img.shields.io/badge/🤗-Dataset-yellow)](https://huggingface.co/datasets/divanbench/divanbench) | — |
| 3 | [Benchmarking Offensive Language Detection in Persian and Pashto](proceedings/3.pdf) | Zahra Bokaei, Bonnie Webber, Walid Magdy | — | — |
| 4 | [Do Large Language Models Understand Double Mismatches? Evidence from Farsi](proceedings/4.pdf) | Maryam Mohammadi | — | — |
| 5 | [TajPersLexon: A Tajik–Persian Lexical Resource and Hybrid Model for Cross-Script Low-Resource NLP](proceedings/5.pdf) | Mullosharaf Kurbonovich Arabov | — | — |
| 6 | [A Computational Approach to Language Contact — A Case Study of Persian](proceedings/6.pdf) | Ali Basirat, Danial Namazifard, Navid Baradaran Hemmati | — | — |
| 7 | [Online Polarization Detection in Persian (Farsi) Social Media](proceedings/7.pdf) | Saeedeh Davoudi, Nazli Goharian | [![GitHub](https://img.shields.io/badge/GitHub-Code-black?logo=github)](https://github.com/dsaeedeh/Polarization_Detection) | — |
| 8 | [ParsCORE: The Persian Corpus of Online Registers](proceedings/8.pdf) | Alireza Razzaghi, Erik Henriksson, Veronika Laippala | `Dataset & Code on GitHub (link TBD)` | — |
| 10 | [PMWP: A Benchmark for Math Word Problem Solving in Persian](proceedings/10.pdf) | Marzieh Abdolmaleki, Mehrnoush Shamsfard, Veronique Hoste, Els Lefever | [![GitHub](https://img.shields.io/badge/GitHub-Dataset-black?logo=github)](https://github.com/marzieh-abdolmaleki/PMWP) | — |
| 11 | [APARSIN: A Multi-Variety Sentiment and Translation Benchmark for Iranic Languages](proceedings/11.pdf) | Sadegh Jafari, Tara Azin, Farhad Roodi, Zahra Dehghani Tafti, Mehrdad Ghadrdan, Elham Vatankhahan Esfahani, Aylin Naebzadeh, Mohammadhadi Shahhosseini, Ghafoor Khan, Kazem Forghani, Danial Namazi, Seyed Mohammad Hossein Hashemi, Farhan Farsi, Mohammad Osoolian, Maede Mohammadi, Mohammad Erfan Zare, Muhammad Hasnain Khan, Muhammad Hussain, Nooreen Zaki, Joma Mohammadi, Shayan Bali, Mohammad Javad Ranjbar, Els Lefever, Veronique Hoste | [![GitHub](https://img.shields.io/badge/GitHub-Benchmark-black?logo=github)](https://github.com/SilkRoadAparsin) | — |
| 12 | [One Language, Three of Its Voices: Evaluating Multilingual LLMs Across Persian, Dari, and Tajiki on Translation and Understanding Tasks](proceedings/12.pdf) | Noor Mairukh Khan Arnob, Abu Bakar Siddique Mahi | — | — |
| 13 | [PersianPunc: A Large-Scale Dataset and BERT-Based Approach for Persian Punctuation Restoration](proceedings/13.pdf) | Mohammad Javad Ranjbar Kalahroodi, Heshaam Faili, Azadeh Shakery | `Dataset & Model publicly available (link TBD)` | — |
| 15 | [Shughni Machine Translation Enhanced by Donor Languages](proceedings/15.pdf) | Dmitry Novokshanov, Innokentiy S. Humonen, Ilya Makarov | [![HuggingFace](https://img.shields.io/badge/🤗-Demo-yellow)](https://huggingface.co/spaces/Novokshanov/Shughni-Translator) | — |
| 16 | [Segmentation Strategy Matters: Benchmarking Whisper on Persian YouTube Content](proceedings/16.pdf) | Reihaneh Iranmanesh, Rojin Ziaei, Joe Garman | [![GitHub](https://img.shields.io/badge/GitHub-Dataset_&_Code-black?logo=github)](https://github.com/ri164-bolleit/persian-youtube-whisper-benchmark) | — |
| 18 | [Multi-modal Neural Machine Translation for Low-Resource Classical Persian Poetry: A Culture-Aware Evaluation](proceedings/18.pdf) | Soheila Ansari, Mounir Boukadoum, Fatiha Sadat | [![GitHub](https://img.shields.io/badge/GitHub-Corpus-black?logo=github)](https://github.com/amnghd/Persian_poems_corpus/tree/master) | — |

---

## Paper Abstracts

<details>
<summary><strong>Paper 2 — Unmasking the Factual-Conceptual Gap in Persian Language Models</strong></summary>

We introduce **DivanBench**, a manually curated benchmark of 315 questions across three task types — factual retrieval, paired scenario verification, and situational reasoning — designed to probe cultural and conceptual knowledge in Persian LLMs. Our evaluation reveals a consistent "acquiescence trap" where models default to agreement, and highlights gaps between factual recall and deeper conceptual reasoning.

📦 Dataset: [huggingface.co/datasets/divanbench/divanbench](https://huggingface.co/datasets/divanbench/divanbench)
</details>

<details>
<summary><strong>Paper 3 — Benchmarking Offensive Language Detection in Persian and Pashto</strong></summary>

This paper provides a systematic benchmark of offensive language detection across Persian and Pashto, evaluating a range of transformer-based models including multilingual and language-specific variants. It examines cross-lingual transfer, the impact of script similarity, and limitations of existing datasets.
</details>

<details>
<summary><strong>Paper 4 — Do Large Language Models Understand Double Mismatches? Evidence from Farsi</strong></summary>

This paper investigates whether LLMs can handle *double mismatch* constructions in Farsi — syntactic configurations where two grammatical features simultaneously deviate from their canonical agreement patterns. Results reveal systematic failures in current LLMs, pointing to gaps in morphosyntactic reasoning for morphologically rich languages.
</details>

<details>
<summary><strong>Paper 5 — TajPersLexon: A Tajik–Persian Lexical Resource and Hybrid Model for Cross-Script Low-Resource NLP</strong></summary>

We present **TajPersLexon**, a bilingual lexical resource of 40,112 Tajik–Persian word/phrase pairs bridging Cyrillic and Perso-Arabic scripts. A hybrid transliteration and alignment model is introduced to support cross-script NLP tasks for these closely related but orthographically distant language varieties.
</details>

<details>
<summary><strong>Paper 6 — A Computational Approach to Language Contact — A Case Study of Persian</strong></summary>

This paper proposes a computational framework for detecting and quantifying language contact effects in Persian, modeling lexical borrowing and phonological adaptation through diachronic corpus analysis. The methodology is validated against historical linguistic accounts of Arabic, French, and English influence on Persian.
</details>

<details>
<summary><strong>Paper 7 — Online Polarization Detection in Persian (Farsi) Social Media</strong></summary>

We investigate political polarization on Persian-language social media using NLP techniques. Fine-tuned transformer models are evaluated on the POLAR dataset, and the paper analyzes the impact of pre-training language specificity on polarization classification performance.

💻 Code: [github.com/dsaeedeh/Polarization_Detection](https://github.com/dsaeedeh/Polarization_Detection)
</details>

<details>
<summary><strong>Paper 8 — ParsCORE: The Persian Corpus of Online Registers</strong></summary>

**ParsCORE v0.1** is a corpus of 2,000 human-annotated Persian web documents spanning diverse online registers, developed within the Universal Register framework. Initial experiments on automatic register identification show performance comparable to high-resource languages, establishing a foundation for Persian web-language research.

💻 Dataset & Code: [GitHub](https://github.com/TurkuNLP/ParsCORE)
</details>

<details>
<summary><strong>Paper 10 — PMWP: A Benchmark for Math Word Problem Solving in Persian</strong></summary>

We introduce **PMWP**, the first dataset of 15,000 elementary-level Persian math word problems for training and evaluating mathematical reasoning in LLMs. Systematic evaluation shows Gemini-2.5-Flash achieves the highest accuracy (72.02%), while LoRA fine-tuning of open-weight models (LLaMA-3-8B, Qwen-2.5-7B) reaches over 91% exact equation match.

💻 Dataset: [github.com/marzieh-abdolmaleki/PMWP](https://github.com/marzieh-abdolmaleki/PMWP)
</details>

<details>
<summary><strong>Paper 11 — APARSIN: A Multi-Variety Sentiment and Translation Benchmark for Iranic Languages</strong></summary>

**APARSIN** is a large-scale benchmark covering 14 Iranic languages and dialects for sentiment analysis and machine translation. It provides standardized evaluation protocols and baselines using state-of-the-art LLMs, addressing the critical lack of multi-variety resources for the Iranian language family.

💻 Benchmark: [github.com/SilkRoadAparsin](https://github.com/SilkRoadAparsin)
</details>

<details>
<summary><strong>Paper 12 — One Language, Three of Its Voices: Evaluating Multilingual LLMs Across Persian, Dari, and Tajiki</strong></summary>

This paper evaluates multilingual LLMs on translation and understanding tasks across the three major varieties of Persian (Persian/Farsi, Dari, Tajiki), using a dataset of over 240,000 processed samples. Results highlight variety-specific performance gaps and the challenges of treating these as a single language.
</details>

<details>
<summary><strong>Paper 13 — PersianPunc: A Large-Scale Dataset and BERT-Based Approach for Persian Punctuation Restoration</strong></summary>

**PersianPunc** is a dataset of 17 million samples for Persian punctuation restoration, constructed by aggregating and filtering diverse textual resources. A fine-tuned ParsBERT model achieves 91.33% macro-F1, outperforming large generative models in efficiency and accuracy. The full dataset and fine-tuned model are publicly released.
</details>

<details>
<summary><strong>Paper 15 — Shughni Machine Translation Enhanced by Donor Languages</strong></summary>

This paper presents a machine translation system for **Shughni**, an endangered Iranian language of the Pamirs with fewer than 100,000 speakers and limited digital resources. By leveraging Russian and English as pivot/donor languages within an NLLB-200 framework, the system achieves significant improvements over baseline MT for this extremely low-resource language.

🤗 Demo: [huggingface.co/spaces/Novokshanov/Shughni-Translator](https://huggingface.co/spaces/Novokshanov/Shughni-Translator)
</details>

<details>
<summary><strong>Paper 16 — Segmentation Strategy Matters: Benchmarking Whisper on Persian YouTube Content</strong></summary>

We benchmark OpenAI's Whisper on 10 hours of Persian YouTube audio with gold-standard transcripts, systematically evaluating the impact of audio segmentation strategies on ASR performance. Results show that segmentation choices have a substantial effect on WER, with practical implications for Persian speech processing pipelines.

💻 Dataset & Code: [github.com/ri164-bolleit/persian-youtube-whisper-benchmark](https://github.com/ri164-bolleit/persian-youtube-whisper-benchmark)
</details>

<details>
<summary><strong>Paper 18 — Multi-modal Neural Machine Translation for Low-Resource Classical Persian Poetry</strong></summary>

We introduce the first multi-modal NMT system for translating classical Persian poetry (Masnavi-ye-Ma'navi), combining text with audio recitations. A new parallel Persian–English corpus of 26,571 aligned verse pairs with recitations is released, alongside a culture-specific evaluation framework for idiomatic and poetic translation quality.

💻 Corpus: [github.com/amnghd/Persian_poems_corpus](https://github.com/amnghd/Persian_poems_corpus/tree/master)
</details>

---

## Workshop Information

| | |
|---|---|
| **Full Name** | First Workshop on NLP and LLMs for the Iranian Language Family (SilkRoadNLP) |
| **Venue** | Co-located with EACL 2026, Rabat, Morocco |
| **Workshop Date** | March 28–29, 2026 |
| **Website** | [silkroadnlp.org](https://silkroadnlp.org) |
| **Languages Covered** | Persian · Dari · Tajiki · Kurdish · Pashto · Balochi · Luri · Ossetian · Shughni · and more |

---

## Important Dates (2025–2026)

| Milestone | Date |
|-----------|------|
| Call for Papers | October 20, 2025 |
| Direct Submission Deadline | January 8, 2026 |
| Notification of Acceptance | January 26, 2026 |
| Camera-ready Papers Due | February 3, 2026 |
| Workshop Date | March 28–29, 2026 |

---

## Citation

If you use these proceedings in your research, please cite the workshop:

```bibtex
@proceedings{silkroadnlp2026,
  title     = {Proceedings of the First Workshop on NLP and LLMs for the Iranian Language Family (SilkRoadNLP)},
  year      = {2026},
  address   = {Rabat, Morocco},
  publisher = {Association for Computational Linguistics},
  url       = {https://silkroadnlp.org}
}
```

---

<p align="center">
  <em>SilkRoadNLP 2026 — Bridging languages along the Silk Road</em>
</p>
