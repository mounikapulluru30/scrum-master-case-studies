# 📊 Agile Metrics Examples

This folder provides a small fictional dataset and practical guidance for using metrics responsibly.

## Principles

1. Use metrics to improve the system, not rank people.
2. Look at trends rather than isolated numbers.
3. Combine quantitative signals with team context.
4. Never optimize velocity at the expense of quality.
5. Ask what decision the metric will help the team make.

## Metric Guide

| Metric | What it tells us | Useful question |
|---|---|---|
| Sprint Goal Achievement | Whether the intended outcome was achieved | Are we consistently achieving meaningful goals? |
| Carryover % | How much planned work remains unfinished | Why is work not finishing? |
| Velocity | Historical amount of work completed | What can we reasonably forecast? |
| Cycle Time | Time from work start to completion | Where is work waiting? |
| Lead Time | Time from request to delivery | How quickly does value move? |
| Throughput | Items completed over time | How much work flows through the system? |
| WIP | Work currently in progress | Are we starting too much? |
| Blocked Time | Time work is unable to progress | What impediments need attention? |
| Escaped Defects | Defects found after delivery | Are we building quality in? |
| Flow Efficiency | Active work vs total elapsed time | How much time is spent waiting? |

## Example Interpretation

A team might show:

- Velocity ↑
- Cycle time ↑
- WIP ↑
- Escaped defects ↑

This should **not** be interpreted as "the team is performing better because velocity increased."

It suggests the Scrum Master should inspect:

- work size,
- quality,
- WIP,
- bottlenecks,
- waiting time,
- Definition of Done,
- and whether the metric itself is being gamed.

## Sample Dataset

See [`sample-sprint-metrics.csv`](sample-sprint-metrics.csv).
