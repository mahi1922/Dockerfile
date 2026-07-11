ARG version
FROM almalinux:${version:-9}
ARG course="DevOps" \
    Goal="aws"
ENV course="${course}" \
    Goal="${Goal}"
RUN echo "cousre is ${course}, and goal is ${Goal}"
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/*
COPY qi/ /usr/share/nginx/html/
CMD ["nginx", "-g", "daemon off;" ]