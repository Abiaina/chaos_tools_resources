# chaos_tools_resources
References, chaos overview, tools and sample projects and experiments

## Chaos TLDR
- Define Steady State
- Hypothesize Steady State will remain in control and experimental group (H0 aka Null Hypothesis)
- Hypothesize Steady State will change in experimental (H1 or Ha aka Alternative Hypothesis)
- Introduce variables/changes/chaos based on real world events/previous outages (crash servers, bad network connection). Minimize blast radius.
- The more resilient steady state, the more confidence we have in the behavior of the system.
- Any variable that causes difference in steady state is a target for development to achive ^^ .

## Chaos Requirements
- Observability metrics for the experimental and control groups
- Chaos agent: Self, or specific SASS
- Ability to stop experiment and recover (Rollback, respawn resource, or run book with this specific experiment disaster recovery)
  
## Great Books & Articles
- [Oct 2025 Google Cloud Article](https://cloud.google.com/blog/products/devops-sre/getting-started-with-chaos-engineering)
- Chaos Engineering: System Resiliency in Practice
- Learning Chaos Engineering: Discovering and Overcoming System Weaknesses Through Experimentation
- [Google Boutique](https://github.com/GoogleCloudPlatform/microservices-demo) - sample app to run chaos experiments on (Note: some configs need to be adapted to work on minikube).
- [Minikube](https://minikube.sigs.k8s.io/docs/start/?arch=%2Fmacos%2Fx86-64%2Fstable%2Fbinary+download) - Create simple cluster to experiment on/deploy sample app on.

## Sample Chaos Experiemnt TODO

## Overview of configs for experiment and different chaos agents TODO
