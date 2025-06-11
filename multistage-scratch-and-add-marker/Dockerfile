FROM busybox AS builder

RUN mkdir /potato-salad

RUN mkdir /snap

FROM scratch

COPY --from=builder /potato-salad /potato-salad

COPY --from=builder /snap /snap


