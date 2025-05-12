# 🧠 AI Blog Generator

This is a Streamlit web application that generates blog content using the **LLaMA 2** language model via `CTransformers`. The blog is tailored to specific audiences such as **Researchers**, **Data Scientists**, or **Common People** based on a user-defined topic and word count.

## 🚀 Features

- Generate high-quality blog content with LLaMA 2
- Customize blog length (word count)
- Target specific audiences
- User-friendly interface powered by Streamlit

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **CTransformers**
- **LLaMA 2** (`llama-2-7b-chat.ggmlv3.q8_0.bin` model)

## 📦 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/ms-prakash27/blog_generation.git
   cd blog_generation
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

5. Make sure the LLaMA model file (`llama-2-7b-chat.ggmlv3.q8_0.bin`) is in the correct `models/` folder.

## 📄 Example Usage

- **Topic:** Climate Change  
- **Word Count:** 150  
- **Audience:** Researchers  
➡️ **Output:** A concise, scientific blog post tailored to researchers.

## 📌 Notes

- You may need to download the LLaMA 2 GGML model manually due to its size and license restrictions.
- Ensure proper hardware (RAM/CPU) support when running large models locally.

## 📜 License

MIT License
