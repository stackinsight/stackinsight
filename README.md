## StackInsight

We measure what slow code actually costs, then build tools that catch it.

StackInsight is an independent software business in Sydney, Australia, focused on performance in JavaScript and TypeScript codebases.

### Product: Code Evolution Lab

[Code Evolution Lab](https://codeevolutionlab.com) is static analysis for performance problems with measurable cost, not style nits. Every detector is backed by a published study.

- 11 detectors: N+1 queries, missing indexes, blocking I/O, inefficient loops, memory leaks, resource leaks, bundle bloat, DOM layout thrashing, unbounded payloads, ReDoS, and caching opportunities
- CLI and GitHub Action for local scans, baselines, and regression checks in CI
- Web dashboard for scanning repositories and reviewing suggested fixes
- Replayable benchmarks, so you can check the evidence behind each rule yourself

```bash
npx code-evolution-lab analyze .
```

Free tier available. Pro is $7/month or $60/year.

- Website: https://codeevolutionlab.com
- Docs: https://codeevolutionlab.com/docs
- Source: https://github.com/liangk/code-evolution-lab

### Research

Each detector starts as an empirical study: scan hundreds of public repositories with custom AST analysis, benchmark the pattern against its fix, and publish the method and data in the open.

- Studies: https://stackinsight.dev
- Code and data: https://github.com/liangk/empirical-study

### Contact

contact@stackinsight.dev
