ARG version=9
FROM almalinux:${version}
ENV course = "Devops" \
    trainer = "sivakumar" \
    duration = "120hrs" \
ARG USERNAME = Sivakumar
RUN echo "Hello user: ${USERNAME}, image version: ${version}" > /tmp/devops.txt
CMD ["sleep", "100"]