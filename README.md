### dsadawq3 — quantization notes (F-Labs)

I work on post-training INT4 quantization of LLMs (group-wise INT4, SRC, DV-SSQ, KV-BSS).

- **FQuant** — PTQ toolkit (quantize/dequantize + audit) — https://github.com/dsadawq3/FQuant
- **MiniCPM5-2B-Hadamard-GSQ** — 2.03GB, ~2.30x, 128K context — https://github.com/dsadawq3/MiniCPM5-2B-Hadamard-GSQ
- **Spark-X2.5-4B-Hadamard-GSQ** — 4.18GiB (-45.43%), Top-1 93.28% (111/119), KL 0.1095 — https://github.com/dsadawq3/Spark-X2.5-4B-Hadamard-GSQ

Models: https://huggingface.co/F-Labs | Related: QuaRot, SpinQuant, GPTQ, AWQ, ZeroQuant-V2, LoRC, LLM.int8(), SpQR.