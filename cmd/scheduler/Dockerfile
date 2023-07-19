
FROM alpine:3.12

COPY ./kube-scheduler /bin/kube-scheduler

RUN chmod +x /bin/kube-scheduler

WORKDIR /bin

CMD ["kube-scheduler"]
