#High-Performance Document Processing System
/Fast & Efficient PDF Processing with LLM-Based Answering

📖 Overview
This project is designed to rapidly process large PDF documents (100+ pages) using parallel processing, memory-efficient text extraction, and an LLM-based answering system. The system supports:

✅ Parallel PDF Processing (Async & Multiprocessing)
✅ Memory-Efficient Data Extraction (≤ 1GB RAM Usage)
✅ Accurate Table & Chart Handling (>95% Accuracy)
✅ Fast Processing (100-Page PDF in <30 Seconds)
✅ LLM-Based Question Answering from Extracted Text

🛠️ Features
📄 Extracts Text & Tables from PDFs
⚡ Processes PDFs Asynchronously for Speed
📊 Handles Complex Document Elements (Tables, Charts)
🤖 Uses LLM (Transformer-Based) for Answering
🔎 Optimized for Large Documents with Minimal Memory Use

📂 Project Structure
high_performance_doc_processing/
│── src/
│   ├── extract_text.py        # Extracts text & tables  
│   ├── preprocess.py          # Cleans and chunks extracted data  
│   ├── llm_inference.py       # Answers questions based on extracted text  
│   ├── async_processing.py    # Parallel async PDF processing  
│── benchmarks/
│   ├── performance_tests.py   # Benchmarking script  
│── data/                      # Sample PDFs for testing  
│── requirements.txt           # Dependencies  
│── README.md                  # This README file  
│── demo.mp4                   # Demo video (optional)  
│── main.py                    # Main script to run the system  

    
  
