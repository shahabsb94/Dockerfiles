ARG version
FROM almalinux:${version:-9}
ENV course="Devops" \
    trainer="shabu" \
    duration="120hrs"
#RUN echo "Hello ${trainer}" > /tmp/devops.txt
ARG USERNAME=syed
ENV USERNAME=$USERNAME
RUN echo "hello user: ${USERNAME}" > /tmp/devops.txt
CMD [ "sleep", "100" ]