# 4thGenCompilerUsingLLM
HingLang is an innovative 4th-generation compiler that blends the deterministic precision of traditional compilers with the adaptability of Large Language Models (LLMs). This project integrates Meta’s LLaMA (3.2B parameters) to dynamically interpret ambiguous inputs, generate code, and provide adaptive feedback.

## **HingLang Syntax Examples**  

### **Variable Assignment**
```hinglish
lo A = 10  # Assigns value 10 to A

Conditional Statements:
agar A > 5 {
    do "A is greater than 5"
} warna {
    do "A is 5 or less"
}

Loops:
jabtak A < 10 {
    do A
    lo A = A + 1
}

Functions:
fun add {
    lo result = A + B
    wapas result
}
endfun

Installation and Setup
Prerequisites
Python 3.8+
pip
Gradio
Transformers (Hugging Face)
PyTorch

Installation Steps:
git clone https://github.com/yourusername/HingLang.git
cd HingLang
pip install -r requirements.txt
