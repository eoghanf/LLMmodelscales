
# Datasets

|                                                                                                                                                                                         | Tokens   | Size | Date       | Code/Text       | Creator           | License    | Notes                                                                                                              |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------|------|------------|-----------------|-------------------|------------|--------------------------------------------------------------------------------------------------------------------|
| CulturaX [link](https://arxiv.org/pdf/2309.09400.pdf)                                                                                                                                   | 6300 GT  | 27 TB | Sept 2023  | Multlingual     | Together Computer | Custom     |                                                                                                                    |
| Dolma  [link](https://blog.allenai.org/dolma-3-trillion-tokens-open-llm-corpus-9a0ff4b8da64)                                                                                            | 3080 GT  |    | Aug 2023   | English         | Allen AI          | Custom     |
| Falcon RefinedWeb  [link](https://arxiv.org/pdf/2306.01116.pdf)                                                                                                                         | ~5000 GT |    | Jun 2023   | English         | Falcon            | Not Public |                                                                                                                    |  
| Falcon RWeb extract                                                                                                                                                                     | 600 GT   |    | Jun 2023   | English         | Falcon            |            |
| Llama 2  [link](https://ai.meta.com/research/publications/llama-2-open-foundation-and-fine-tuned-chat-models/)                                                                          | 2000 GT  |    | Jul 2023   | Code + Text     | Facebook          | Not Public | [link](https://www.cnbc.com/2023/05/16/googles-palm-2-uses-nearly-five-times-more-text-data-than-predecessor.html) |
| Palm 2                                                                                                                                                                                  | 3600 GT  |    | May 2023   | English + Code  | Google            | |                                                                                                                    |                  |                                                                                                                    |                                                                                                                   |                                                                                                                   |                                                                                                                    | RedPajama  [link](https://together.ai/blog/redpajama)                                                                       | 1210 GT  |    | April 2023 |                 | Underlying Licenses                                       | "Cleanroom" replication of Llama | 
| Llama  [link](https://research.facebook.com/file/1574548786327032/LLaMA--Open-and-Efficient-Foundation-Language-Models.pdf)                                                             | 1400 GT  | 4.7 TB | Feb 2023   | Code + Text     |                   |            | English Text only                                                                                                  |
| The Stack                                                                                                                                                                               | 430 GT   | 3 TB | Nov 2022   | Code            |                   |            | All langs, Permissive license                                                                                      |
| Stack dedup Python                                                                                                                                                                      | 26 GT    | 80 GB | Nov 2022   | Code + English  |                   |            | Python only                                                                                                        |
| PaLM  [link](https://ai.google/static/documents/palm2techreport.pdf?_gl=1*jep511*_up*MQ..*_ga*MzQwMDY2MDE1LjE2OTU0ODM0Mjk.*_ga_KFG60X3H7K*MTY5NTQ4MzQyOS4xLjAuMTY5NTQ4MzQyOS4wLjAuMA..) | 780 GT   |    | Oct 2022   | Code + Text     |                   |            | 50% tokens "social media convs"                                                                                    |
| GPT-3.5 dataset                                                                                                                                                                         |          |    | Nov 2022   | Code + Text     |                   |            | Undisclosed                                                                                                        |
| GPT-3 dataset                                                                                                                                                                           | 300 GT   |    | Mar 2022   | Code + Text     |                   |            | Undisclosed                                                                                                        | 
| MassiveText                                                                                                                                                                             | 2350 GT  | 10.5 TB | Dec 2021   | Text            |                   |            | "We do not attempt to filter out low quality" English only                                                         |
| The Pile                                                                                                                                                                                | ~340 GT  | 825 GB | Dec 2020   | Text            |                   |            | Components below                                                                                                   |
| OpenWebText 2  [link](https://github.com/jcpeterson/openwebtext)                                                                                                                        |          | 66 GB | Jun 2020   | Text            |                   |            |                                                                                                                    |                 |  
| OpenWebText  [link](https://github.com/jcpeterson/openwebtext)                                                                                                                          |          | 40 GB | Unk 2019   | Text            |                   |            | Repl of WebText                                                                                                    | 
| WebText (GPT-2)                                                                                                                                                                         |          | 40 GB | Feb 2019   | Text            |                   |            | Outbound Reddit links                                                                                              |

(Note June 2023 Common Crawl is 390 TB)
The Pile - selected components

| Component | Raw Size (GB) |
| --- |---------------|
| Pile-CC | 227.1         |
| PubMed Central | 90.3          |
| Books3 | 101.0         |
| OpenWebText 2 | 62.8          |
| ArXiv | 56.2          |
| GitHub | 95.2          |
| FreeLaw | 51.2          |
| StackExchange | 32.2          |
| USPTO Backgrounds | 22.9          |
| Gutenberg | 10.9          |
| OpenSubtitles | 13.0          |
| Wikipedia (en) | 6.4           |

# Questions

* Why is the Stack so big? Why so much bigger than the GitHub component of the Pile?


