### What's changed in v0.13.8

* chore(deps): update helm release kube-prometheus-stack to v92.7.0 (#48) (by @renovate[bot])

  Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com>

* fix(deps): update helm release kube-prometheus-stack to v92.8.0 (#49) (by @renovate[bot])

  Grafana subchart 13.6.0 -> 13.7.0 (adds optional imageRenderer.readinessProbe; imageRenderer not enabled by us). Cuts the release that also carries the 92.7.0 bump automerged as chore in #48. validate/test/e2e green.


See full diff: [v0.13.7...v0.13.8](https://github.com/hops-ops/observe-stack/compare/v0.13.7...v0.13.8)
