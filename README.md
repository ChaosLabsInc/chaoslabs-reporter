# chaoslabs-reporter

A tiny status reporter for lab deployments. Reports deployment
telemetry to the configured collector endpoint.

## Setup

```
pip install git+https://github.com/ChaosLabsInc/chaoslabs-reporter.git
```

## Run

```
python -m chaoslabs_reporter.demo
```

Requires the `CHAOSLABS_RUNTIME_TOKEN` environment credential
(provisioned separately — do not print it).
