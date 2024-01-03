FROM aquasec/trivy
MAINTAINER lajifeiwomoshu@aliyun.com
RUN trivy image --download-java-db-only && trivy image --download-db-only
CMD /bin/sh sleep 3600

