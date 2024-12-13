## Ollama를 사용하여 Open Large Language Model을 수행하는 예제 코드입니다.
### Package 설치
```
python3.10 -m venv .venv
.venv\Scripts\activate.bat
pip3 install -r requirements.txt
```

### Chat 모드 예제
모델 다운로드 
```
ollama pull llama2
ollama pull llama3
ollama pull qwen2
```

embedding_langchain_ollama_llama3.ipynb : 입력 텍스트에 임베딩을 수행하여 수치 배열로 전환합니다.

langchain_chatollama_llama2.ipynb : llama2와 대화하는 예제 입니다.

embedding_ollama_qwen2.ipynb : qwen2 모델을 이용하여 임베딩을 수행하여 수치 배열로 전환합니다.

