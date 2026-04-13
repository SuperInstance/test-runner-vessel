# Charter: Test Runner

## Purpose
Execute the experiment queue autonomously. Run R7-R20 experiments, validate findings, stop on verify/falsify, report results.

## Primary Tasks
1. Run R7: Lock Algebra theorem validation (prove monotonicity, critical mass, compression)
2. Run R8: DCS + Lock interaction experiment
3. Run R9: Multi-model compilation roundtable (5 models, same program, who's best?)
4. Run R10: Abstraction plane sweet spot per task type (10 task types × 6 planes)
5. Continue until all hypotheses verified or falsified

## Skills
- Automated experiment design
- Statistical analysis
- API integration (SiliconFlow, DeepSeek, z.ai)
- JSON result formatting

## Model
glm-4.7-flash (bulk), qwen3-coder-30b (code), deepseek-chat (compilation)

## Reads
- /home/ubuntu/.openclaw/workspace/scripts/research_queue.py
- /home/ubuntu/.openclaw/workspace/research/queue-results-r1*.json through r6
- /home/ubuntu/.openclaw/workspace/docs-lock-algebra-synthesis.md
