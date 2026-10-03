ARG version
FROM almalinux:${version:-9} 
ARG course= "docker" \
    trainer= "manikumar" \
    duration= "10 hrs"
ENV course =${course} \
    trainer=${trainer} \
    duration =${duration}
RUN echo "Course is: ${course}, Duration is: ${duration}, Trainer is: ${trainer}, Version is: ${version}"

