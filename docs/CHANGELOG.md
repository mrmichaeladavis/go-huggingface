# `go-huggingface` Changelog

## v0.1.2

* If verbosity is 0, it won't print progress.
* Added support for custom end-points. Default being "https://huggingface.co" or the environment variable
  `$HF_ENDPOINT` if defined.

## v0.1.1

* Fixed URL resolution of non-model repos.
* Fixed sentencepiece Tokenizer and tokenizer API string methods (using `enumer`).
* Added dataset example. 
* Added usage with Rust tokenizer.
* Improved README.md
* Added SentencePiece proto support -- to be used in future conversion of SentencePiece models.
* Improved documentation.

## v0.1.0

* package `hub`: inspect and download files from arbitrary repos. Very functional.
* package `tokenizers`:
	* Interfaces, types and constants.
	* Gemma tokenizer implementation.
	* Not any other tokenizer implemented yet.
* Examples in `README.md`.