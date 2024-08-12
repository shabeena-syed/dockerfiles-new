ARG version 
FROM almalinux:${version:-8}
 #RUN cat /etc/*release
ARG COURSE=python
ARG TRAINER=shafi
ARG  DURATION=100
ENV DURATION= ${DURATION}
RUN echo "course is : ${COURSE} , trainer is : ${TRAINER} , duration is : ${DURATION}"
CMD [ "sleep", "100" ]