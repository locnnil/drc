FROM busybox AS builder

RUN mkdir /snap

FROM scratch

COPY --from=builder /snap /snap
