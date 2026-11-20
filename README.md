# Egor Fyodorov

I'm a senior Python backend engineer working on asynchronous services, Kafka event processing, and document search. At CDNvideo, I designed and maintained a cache-invalidation service that handled 10,000 requests per second across 300+ CDN nodes.

## Open Source

### [trtvideo](https://github.com/egor-fedorov/trtvideo)

GPU-resident video upscaling with TensorRT. Frames stay on the GPU through decoding, preprocessing, inference, and encoding. In the RTX 4090 benchmark, SPAN at 720p → 1440p achieved 9.1% higher end-to-end throughput than TheAnimeScripter. [Benchmark results](https://github.com/egor-fedorov/trtvideo#measured-throughput-and-resource-use)

### [safetensors.mojo](https://github.com/egor-fedorov/safetensors.mojo)

An independent implementation of the Safetensors format in Mojo with memory-mapped reads, atomic writes, and byte-for-byte compatibility tests against the reference serializer. [Conda package](https://prefix.dev/channels/modular-community/packages/safetensors-mojo)

### [telegram-mcp](https://github.com/egor-fedorov/telegram-mcp)

A local Python MCP server for reading and searching Telegram. Subscriptions retain batches until the client acknowledges them, and file sends support idempotency.

### [whisper-transcribator](https://github.com/egor-fedorov/whisper-transcribator)

An offline C++17 command-line tool for transcribing audio and video with whisper.cpp and FFmpeg. It exports plain text, SRT, WebVTT, and JSON. [Prebuilt releases](https://github.com/egor-fedorov/whisper-transcribator/releases)

## Interests

Linux and operating systems · parallel programming · GPU computing · compilers · video processing · Web3

## Contact

[LinkedIn](https://www.linkedin.com/in/egor-fyodorov/) · [Email](mailto:egorfyodorovv@gmail.com) · [Telegram](https://t.me/egor_fyodorov)
