ARG VERSION
FROM almalinux:${VERSION:-9}
ARG COURSE="DOCKER" \
    LEARNER="JASWANTH"
ENV COURSE=${COURSE} 
# TO access ARG variable value in the container, we need to set it as ENV variable. 
RUN echo "Course: ${COURSE}, Learner: ${LEARNER}, Version: ${VERSION}"
CMD ["sleep", "1000"]