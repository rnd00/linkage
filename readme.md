# Linkage
---

Nothing was set in stone, this here is another `attempt-to-learn` again

## Ideas to work on

- GRPC
- API Gateway kind of thing which will be the center of everything
- All the other microservice is being connected with GRPC
- Microservice directory should be at the root (e.g. linkage)
- Dockerfile for each microservice
  - Multi-step build
  - Distroless container images (github -> [GoogleContainerTools/distroless](https://github.com/GoogleContainerTools/distroless))
- Common packages should be at the root (e.g. logger)
- Something of a worker-queue system with channels and concurrency (probably it can be applicable to some common packages so that it can work independently)
  - Might have some problem with time (attempt on function call, and log write/print call might be different by microseconds?)