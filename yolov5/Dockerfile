FROM ultralytics/yolov5
ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update && apt-get install htop -y --no-install-recommends \
&& apt-get install nfs-common -y --no-install-recommends \
&& apt-get install netbase -y --no-install-recommends --allow-unauthenticated \
&& apt-get install locales -y --no-install-recommends --allow-unauthenticated

RUN locale-gen en_US.UTF-8

ENV LANG en_US.UTF-8
ENV LANGUAGE en_US:en
ENV LC_ALL en_US.UTF-8