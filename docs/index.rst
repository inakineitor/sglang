SGLang Documentation
====================================

SGLang is a fast serving framework for large language models and vision language models.
It makes your interaction with models faster and more controllable by co-designing the backend runtime and frontend language.
The core features include:

- **Fast Backend Runtime**: Provides efficient serving with RadixAttention for prefix caching, jump-forward constrained decoding, continuous batching, token attention (paged attention), tensor parallelism, FlashInfer kernels, chunked prefill, and quantization (INT4/FP8/AWQ/GPTQ).
- **Flexible Frontend Language**: Offers an intuitive interface for programming LLM applications, including chained generation calls, advanced prompting, control flow, multi-modal inputs, parallelism, and external interactions.
- **Extensive Model Support**: Supports a wide range of generative models (Llama 3, Gemma 2, Mistral, QWen, DeepSeek, LLaVA, etc.) and embedding models (e5-mistral), with easy extensibility for integrating new models.
- **Active Community**: SGLang is open-source and backed by an active community with industry adoption.


.. toctree::
   :maxdepth: 1
   :caption: Getting Started

   start/install.md
   start/send_request.ipynb


.. toctree::
   :maxdepth: 1
   :caption: Backend Tutorial

   backend/openai_api_completions.ipynb
   backend/openai_api_vision.ipynb
   backend/openai_api_embeddings.ipynb
   backend/native_api.ipynb
   backend/backend.md


.. toctree::
   :maxdepth: 1
   :caption: Frontend Tutorial

   frontend/frontend.md


.. toctree::
   :maxdepth: 1
   :caption: References

   references/sampling_params.md
   references/hyperparameter_tuning.md
   references/model_support.md
   references/benchmark_and_profiling.md
   references/choices_methods.md
   references/custom_chat_template.md
   references/contributor_guide.md
   references/troubleshooting.md
   references/faq.md
   references/learn_more.md
