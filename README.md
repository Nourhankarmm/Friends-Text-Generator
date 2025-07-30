# 🎭 Friends Text Generator

This project uses RNN (LSTM/GRU) to generate TV script-style dialogue inspired by the **Friends** sitcom. Trained on actual transcripts, the model generates character lines in a realistic conversational flow.

## 🧠 Model Architecture
- Character-level RNN with Embedding + LSTM/GRU
- Trained on Friends show transcripts
- Text generation using temperature sampling

## 🚀 Example Output

**Prompt**: `Rachel: I can't believe you`  
**Generated**:  
`Rachel: I can't believe you did that!`  
`Joey: What? I just said hi!`  
`Monica: You always say hi like that...`

## 🛠️ Tools
- Python, TensorFlow/Keras
- Jupyter Notebook
- Numpy, Matplotlib

## 📂 Files
- `data/friends_transcript.txt`
- `train_rnn.py`
- `generate_text.py`
- `README.md`

## ✨ Future Improvements
- Switch to GPT-2 or LLM for better coherence
- Add speaker tags as features
- Deploy as a chatbot interface
