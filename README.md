# APPDIA-Discourse-aware-Style-Transfer-for-Offensive-Content
Data and code for APPDIA: A Discourse-aware Transformer-based Style Transfer Model for Offensive Social Media Conversations (COLING 2022)

# Data
The data consists of ~2K offensive reddit comments and corresponding style-transferred inoffensive text rewritten by human annotators. The data is also tagged automatically with RST and PDTB discourse relations. Please refer to the paper for more details.

The directory "data/discourse-augmented-data/" contains the splits for discourse-augmented data

The directiory "data/original-annotated-data/" contains the splits for human annotations without discourse relations

# Code
"code/baseline-DialoGPT.py" contains the code for fine-tuning a DialoGPT on data/original-annotated-data.

"code/discourse-aware-DialoGPT.py" contains the code for fine-tuning discourse-aware DialoGPT (details can be found in the paper) on data/discourse-augmented-data/
