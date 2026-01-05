# LLM-Debugging-Data

This repository contains raw data for evaluating LLM debugging capabilities across different models. <br>
The data is 169 single-line bugs of Defects4J(v3.0.1)

## Models Tested

### Ko-LLMs
- ax: `A.X-4.0-Light`
- solar: `SOLAR-10.7B-Instruct-v1.0`
- exaone: `EXAONE-3.0-7.8B-Instruct`
- midm: `Midm-2.0-Mini-Instruct`
- kanana: `kanana-1.5-8b-instruct-2505`
- hyperclovax: `hyperclovax/HyperCLOVAX-SEED-Text-Instruct-1.5B`

### Global Open-Source LLMs
- qwen: `Qwen3-4B-Instruct-2507`
- codellama: `CodeLlama-7b-Instruct-hf`

### Commercial LLMs (GPT)
- gpt-3.5: `gpt-3.5-turbo`
- gpt-4.1: `gpt-4.1-nano`

## Dataset Files

- `FL_EN.csv` - Fault Localization dataset (English)
- `FL_KR.csv` - Fault Localization dataset (Korean)
- `APR_EN.csv` - Automated Program Repair dataset (English)
- `APR_KR.csv` - Automated Program Repair dataset (Korean)
