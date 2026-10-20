### What's changed in v0.13.9

* chore(deps): update helm release kube-prometheus-stack to v92.9.0 (#50) (by @renovate[bot])

  Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com>

* chore(deps): update helm release kube-prometheus-stack to v92.10.1 (#51) (by @renovate[bot])

  Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com>

* fix(deps): update helm release kube-prometheus-stack to v92.11.0 (#52) (by @renovate[bot])

  XR-rendered chart (functions/render/200-kube-prometheus-stack.yaml.gotmpl) -> fix to cut a release.
  92.11.0: additionalServiceMonitors/PodMonitors accept list or map (default [] -> null, same falsy behavior); we set neither. appVersion unchanged (operator v0.94.1), subcharts unchanged (grafana 14.0.1).
  Also releases the already-merged 92.10.1 (grafana subchart 14 = values schema only; our grafana values pass in e2e).
  PR CI: e2e/test (deploys ObserveStack w/ kps, Ready), test, validate x5, publish all green.

  Co-authored-by: renovate[bot] <29139614+renovate[bot]@users.noreply.github.com>


See full diff: [v0.13.8...v0.13.9](https://github.com/hops-ops/observe-stack/compare/v0.13.8...v0.13.9)
