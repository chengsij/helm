##Debugging Helm

[Helm Debugging](https://helm.sh/docs/chart_template_guide/debugging/#scrollpane)git 
- create chart
```bash
helm create helm
```

- generate template
```bash
helm template helm
```

## Tiller
tiller pod -n kube-system tiller-deploy
Helm connects to the tiller in the current k8s context

can list/install/remove when connected to the tiller