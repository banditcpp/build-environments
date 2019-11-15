FROM debian:bullseye-slim
RUN apt-get -y update && \
    apt-get -y install make \
                       cmake \
                       g++-7 \
                       g++-8 \
                       g++-9 \
                       clang-6.0 \
                       clang-7 \
                       clang-8 \
                       clang-9 && \
    apt-get -y clean
