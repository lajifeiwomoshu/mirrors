FROM aquasec/trivy
MAINTAINER lajifeiwomoshu@aliyun.com
WORKDIR /tmp
RUN trivy image --download-java-db-only && trivy image --download-db-only
ENTRYPOINT ["/bin/sh","-c","sleep 3600"]

