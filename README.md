# PII-Detection-and-Masking-in-Large-Language-Models
Built SmartPHIMasker, a real-time PHI masking pipeline using Microsoft Presidio, SpaCy NER, regex, and custom recognizers to detect and mask 15 HIPAA identifiers before LLM processing. Tested on 12 clinical scenarios across GPT-4o-mini, Mistral 7B, and FLAN-T5, achieving 100% precision/recall, &lt;0.3s latency, and zero PHI leakage.
