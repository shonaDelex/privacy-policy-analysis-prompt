# Repository: LLM Prompt for Privacy Policy Analysis  

## Overview  
This repository provides the prompt used in the study on the application of large language models (LLMs) to the analysis of privacy policy documents. The objective of the study was to examine whether LLMs can reliably identify **third-party entities** referenced in privacy policies, an essential aspect for enhancing user awareness of how their personal data may be shared.  

## Research Context  
Privacy policies are typically lengthy, vague, and difficult for users to parse in detail. Automated tools, such as LLMs, offer the potential to assist in extracting critical information from such documents.  
Our study investigates the ability of LLMs to detect third-party actors and evaluates their performance in terms of **recall, precision, and F1 scores**.  

**Findings:**  
- LLMs demonstrate **strong recall**, successfully identifying the majority of mentioned third parties.  
- However, **precision remains weak**, leading to frequent false positives and reduced F1 scores.  
- Overall, LLMs are **not yet sufficiently reliable** for fully automated analysis of privacy policies in a precise and independent manner.  
- Nevertheless, they hold promise as **preliminary aids** for supporting and expediting human assessment.  

## Contents  
- `prompt.txt`: The prompt used to instruct the LLM during the analysis of privacy policy documents.  


## License  
This repository is made available for academic and research purposes. Please ensure proper attribution when reusing or adapting the prompt.  
