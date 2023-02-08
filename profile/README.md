# Hello

This GitHub organization works as follows:

* We have our central repository [Supernova](https://github.com/obs-nebula/supernova)
  * We create new things here first, and then if make sense to create a new repository we can close the issue and continue on the created repository.
  * It's also a good place to create issues that affect multiple repositories.

* We are using Node [LTS](https://github.com/nodejs/release#release-schedule)

# About our repositories

* [check-traces](https://github.com/obs-nebula/check-traces) - The purpose of this repository is to ensure that a basic Express app's traces are correctly generated and successfully exported to the final destination which is Jaeger. So we can make safer modifications and experiments according to the evolution of the APIs of the OTEL-JS modules.
* [check-traces-manual](https://github.com/obs-nebula/check-traces-manual) - Same as `check-traces`, but manual.
* [desktop-electron](https://github.com/obs-nebula/desktop-electron) - A really basic Desktop Electron app that is part of the `function-five` demo to call the first function outside the cloud.
* [frontend-react](https://github.com/obs-nebula/frontend-react) - Repository containing a basic back-end and a front-end, used to apply OpenTelemetry-JS (Web) for trace generation.
* [function-five](https://github.com/obs-nebula/function-five) - Knative-functions demo (WIP)
* [gamma-ray](https://github.com/obs-nebula/gamma-ray) - Nothing done, reserved for future experiments.
* [hyperfoil-test](https://github.com/obs-nebula/hyperfoil-test) - Repository containing a demo that uses https://hyperfoil.io/ to compare the performance of some OpenTelemetry-JS plugins when applied to microservices
* [osview](https://github.com/obs-nebula/osview) - A basic CLI used as an experiment to apply the OpenTelemetry signals.
* [perf-quest](https://github.com/obs-nebula/perf-quest) - This repository is an experimental meta-work for [hyperfoil-test](https://github.com/obs-nebula/hyperfoil-test)
