# Hinglish-to-Hindi Neural Translator

Hinglish-to-Hindi Neural Translator is a character-level translator implemented in PyTorch, specifically designed for translating Hinglish (romanized Hindi) to Hindi. This project employs a Transformer-based architecture that leverages attention mechanisms to provide accurate and context-aware translations.

## Key Features
- **Character-level Translation**: Translates Hinglish input to Hindi output with high accuracy.
- **Transformer-based Architecture**: Utilizes the power of Transformers for enhanced context understanding.
- **PyTorch Implementation**: Built with PyTorch for ease of use and extensibility.
- **Pre-trained Model**: Comes with a pre-trained model, trained on a Hinglish-Hindi dataset.
- **Ideal for Small to Medium-sized Tasks**: Suitable for individual or small project applications.

## How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/hinglish-to-hindi-neural-translator.git
cd hinglish-to-hindi-neural-translator
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Download Pre-trained Model
- Download the pre-trained model weights and save them in the `models/` directory.

### 4. Run the Translator
You can use the provided script or integrate the translator into your Python code.

#### Example
```python
from translator import Hinglish2HindiTranslator

# Instantiate the translator (set model_type_oneHot as needed)
translator = Hinglish2HindiTranslator(model_path='model/hinglish2hindi_epoch-50.pth.tar', model_type_oneHot=False)
translation = translator.translate("mera naam laksh kumar sisodiya hai")
print(f"Translation: {translation}")  # Expected output: मेरा नाम लक्ष कुमर सिसोदिया है
```

### Fine-tuning (Optional)
For specific datasets, fine-tune the model by adjusting the training script and providing your own data.

## Contributions
Contributions are welcome! Feel free to submit pull requests, report issues, or suggest improvements. All levels of contributions are appreciated, whether you are a beginner or an experienced developer.

## Disclaimer
This translator is intended for educational purposes and small to medium translation tasks. Performance on large-scale or domain-specific data may vary.

---
