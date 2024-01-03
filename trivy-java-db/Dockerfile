FROM ghcr.io/oras-project/oras:v1.1.0
WORKDIR /tmp
RUN oras pull ghcr.io/aquasecurity/trivy-db:2 && oras pull ghcr.io/aquasecurity/trivy-java-db:1
CMD /bin/sh

