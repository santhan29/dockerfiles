ARG version
FROM almalinux:${version:-9}  
ARG course="devops with aws" \
    duration="120days"
ENV duration=$duration
RUN echo "course: $course, duration: $duration, version: $version"  
CMD ["sleep", "200"] 