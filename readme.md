hello here is the chart.

# 🚀 My 4090 Powerhouse Performance Chart

*(Sorted: Largest Parameters → Smallest | Your Setup: RTX 4090 | 32GB DDR5 RAM | Intel i7-13900K)*

# 🚀 My 4090 Powerhouse Performance Chart  

*(Sorted: Largest Parameters → Smallest | Your Setup: RTX 4090 | 32GB DDR5 RAM | Intel i7-13900K)*

| 🧠 Model Name                                | ⚙️ Params | 🔍 **Quant**      | 📏 Context Length | ⚡ Tokens/s   | 🔑 Fits in 24GB VRAM |
|----------------------------------------------|-----------|--------------------|--------------------|----------------|----------------------|
| `Qwen3-30B-A3B-Instruct` (Q8_0)              | **30B**   | `Q8_0`             | 32k                 | **17–25**     | ✅ Yes                |
| `Qwen3-Coder-30B-A3B-Instruct` (Q8_0)        | **30B**   | `Q8_0`             | 4k                  | **11**        | ⚠️ No (spillover? Nah!) |
| `Devstral-Small` (Q6_K)                     | **24B**   | `Q6_K`             | 14k                 | **45**        | ✅ Yes                |
| `Magistral-Small` (Q6_K)                    | **24B**   | `Q6_K`             | 14k                 | **40**        | ✅ Yes                |
| `ERNIE-4.5-21B-A3B-PT` (Q6_K)               | **21B**   | `Q6_K`             | 40k                 | **150–160**   | ✅ Yes                |
| `Qwen3-32B-Q4_K_M` (Q4_K_M)                 | **32B**   | `Q4_K_M`           | 9k                  | **16–32**     | ✅ Yes                |
| `DeepSeek-R1-Distill-Llama-Medical-Doctor`  | **8B**    | `F16`              | 36k                 | **50**        | ✅ Yes                |
| `deepseek-r1-0528-qwen3-8b` (Q8_0)          | **8B**    | `Q8_0`             | 80k                 | **50–77**     | ✅ Yes                |
| `Qwen3-4B-Thinking` (F16)                   | **4B**    | `F16`              | 68k                 | **77**        | ✅ Yes                |

---

### 💎 Why This Matters for YOU
| Your Obsession          | What You See                                                                 |
|-------------------------|----------------------------------------------------------------------------|
| **Spillovers?**         | `Qwen3-Coder-30B` uses **23.8GB VRAM** (spillovers = temporary GGML magic!)  |
| **Long context wins**   | ✅ `Qwen3-4B` hits **77 tokens/s** with **68k context** → *way* faster!      |
| **Your hardware shines**| 🔥 **150–160 t/s** for `ERNIE-4.5-21B` (40k context) on your 4090 👑       |

---

### 🏆 Your Best Pick Right Now
```bash
# Run this to get 150–160 tokens/second with ZERO spillovers:
llama.cpp --model ERNIE-4.5-21B-A3B-PT-Q6_K.gguf --ctx-size 40k

---

### 🏆 Your Best Pick Right Now
```bash
# Run this to get 150–160 tokens/second with ZERO spillovers:
llama.cpp --model ERNIE-4.5-21B-A3B-PT-Q6_K.gguf --ctx-size 40k
