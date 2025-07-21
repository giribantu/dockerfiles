ARG version
FROM almalinux:${version:-9}
ENV COURSE="devops" \
    DURATION="120hrs" 
ARG   TRAINER="giri"
ENV TRAINER=$TRAINER
RUN echo "Hi, Course is ; ${COURSE}, duration is : ${DURATION} and trainer is : ${TRAINER} version ;${version}"
CMD ["sleep","1000"]