ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="devops"\
    TRAINER="sai"
ENV COURSE=${COURSE}
RUN echo "COURSE is ${COURSE}, TRAINER is: ${TRAINER}"
CMD ["sleep", "500"]
