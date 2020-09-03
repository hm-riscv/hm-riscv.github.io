---
title: Micro-architecture Traces
weight: 20
---

Teaching computer architecture requires accurate models to understand the
effects of techniques to accelerate instruction processing. While there are many
RISC-V open source processor cores that can be simulated, their usage is not
very accessible to many students.

To avoid looking through endless VCD files (signal traces) we are working on a
framework for micro-architectural tracing. The framework abstracts from
electrical signals and instead traces the events of the processor's
microarchitecture. You can find the project on
[Github](https://github.com/hm-riscv/microarchtrace).

The micro-architecture traces can be processed an visualized by
[pipeline-viewer](https://pypi.org/project/pipelineviewer/).
