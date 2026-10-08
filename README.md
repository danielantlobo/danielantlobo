## Hey, I'm Daniel

I work on making AI run fast: GPU kernels, inference serving, and the hardware underneath.
MSc in Informatics Engineering (Advanced Computing & AI) at the University of Minho, Portugal.

### What I'm working on
- **S.M.A.R.T. Neuro** (MSc thesis): an LLM agent that coordinates expert models for brain tumour MRI analysis, running on local hardware. The part I care about most is making it fast enough for several clinicians at once: profiling, TensorRT, Triton Inference Server.
- Rebuilding my fundamentals from the ground up: neural networks, linear algebra, then ML systems. I'd rather understand why a kernel is slow than memorise how to make it fast.

### Things I've measured
- **ZPIC on NVIDIA A100** (CUDA, with a teammate): 27.4x speedup with warp-shuffle reductions and a fused particle kernel → [repo]
- **ZPIC on Fujitsu A64FX** (OpenMP, SVE): 76.3 s → 13.9 s by binding threads to the chip's NUMA layout → [repo]
- **llama.cpp on Arm vs x86**: time to first token, time per token and goodput across models, quantization levels and thread counts → [repo]

Every number links to the code and the steps to reproduce it.

### Toolbox
CUDA C++ · C · Python · PyTorch · TensorRT · Triton · OpenMP · MPI · SVE · Score-P · Slurm · Docker

### Outside the terminal
I hike, mostly the long climbs, play basketball, and save old people from collapsing buildings.
Kubrick is my favourite director: nothing in his frames is there by accident.
Currently reading Asimov's *Foundation*, a story about planning for the very long run.
