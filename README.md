hinglish-chatbot/
│
├── data/
│   ├── whatsapp.txt          # Exported WhatsApp chat
│   ├── discord.csv           # Exported Discord chat
│   ├── cleaned_chat.txt      # Optional intermediate cleaned dataset
│   └── normalized_chat.txt   # Normalized dataset for GPT-2 training
│
├── load_chats.py             # Functions to load chat exports
├── clean_and_normalize.py    # Cleaning and normalization functions
├── dictionary.py             # Dictionary mapping and back-transliteration
├── dataset.py                # PyTorch dataset class for GPT-2
├── train_model.py            # Fine-tuning script for GPT-2
├── chatbot.py                # CLI chat interface
├── requirements.txt          # Python dependencies
└── README.md                 # This file

for references:
https://chatgpt.com/share/68e11468-f100-800a-b1d3-f41de0a398a2
