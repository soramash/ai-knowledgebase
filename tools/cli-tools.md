# CLI Tools

AIを利用・開発するためのCLIツール、ローカル環境構築ツールのリンク集。

## Local LLM

* [Ollama](https://ollama.com/) - ローカルでLLMを簡単に実行できるツール。`ollama run`の1コマンドでモデルのダウンロードから推論まで完結し、OpenAI互換APIも提供する。ローカル検証やオフライン環境での利用に手軽。 #local-llm #cli #ollama
* [vLLM](https://docs.vllm.ai/) - PagedAttentionによる高スループットなLLM推論・サービングエンジン。OpenAI互換APIサーバーを備え、本番環境での大規模サービングやGPUの効率的な利用に向く。 #local-llm #serving #gpu
* [llama.cpp](https://github.com/ggml-org/llama.cpp) - C/C++実装のLLM推論エンジン。GGUF形式の量子化モデルをCPU/GPUで動かせ、Apple Silicon等のローカル環境でも軽量に動作する。多くのローカルLLMツールの基盤。 #local-llm #cli #gguf
* [LM Studio](https://lmstudio.ai/) - GUIでローカルLLMを管理・実行できるデスクトップアプリ。モデルの検索・ダウンロードやチャット、OpenAI互換のローカルサーバー起動が可能で、非エンジニアでも扱いやすい。 #local-llm #gui #llm
