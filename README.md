# DR. WELL

**Dynamic Reasoning and Learning with a Symbolic World Model for Embodied Multi-Agent Cooperation**

> **Heads up!** We're currently cleaning up this codebase to make it more polished and easier to work with. Right now, you're looking at the raw, unfiltered version—it works, but it might be a bit messy in places. Feel free to explore and experiment, just keep in mind things are still being refined. Use at your own risk, and thanks for your patience!

## Overview

This repository provides the implementation of **DR. WELL**, a decentralized neurosymbolic framework for cooperative multi-agent reasoning and execution. The system combines structured communication, symbolic planning, and a dynamic world model that evolves through experience.

DR. WELL enables embodied LLM-based agents to coordinate on shared tasks without exchanging full plans. Cooperation is achieved through symbolic actions, a compact task vocabulary, and an iterative cycle of negotiation, planning, execution, and refinement.

**Paper:** [*DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration*](https://narjesno.github.io/DR.WELL/)

These agents operate in the **CUBE** environment. Learn more about [CUBE: Collaborative Multi-Agent Block-Pushing Environment for Collective Planning with LLM Agents](https://happyeureka.github.io/cube/).

## Citation

If you find this work useful, please cite:

```bibtex
@inproceedings{nourzad2025drwell,
  title     = {DR. WELL: Dynamic Reasoning and Learning with Symbolic World Model for Embodied LLM-Based Multi-Agent Collaboration},
  author    = {Nourzad, Narjes and Yang, Hanqing and Chen, Shiyu and Joe-Wong, Carlee},
  booktitle = {Workshop on Bridging Language, Agent, and World Models for Reasoning and Planning},
  year      = {2025}
}
```

If you like the environment, please also check out our CUBE paper:

```bibtex
@inproceedings{yangcube,
  title     = {CUBE: Collaborative Multi-Agent Block-Pushing Environment for Collective Planning with LLM Agents},
  author    = {Yang, Hanqing and Nourzad, Narjes and Chen, Shiyu and Joe-Wong, Carlee},
  booktitle = {Workshop on Scaling Environments for Agents},
  year      = {2025}
}
```