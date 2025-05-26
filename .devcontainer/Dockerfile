FROM ros:humble-ros-core

ENV DEBIAN_FRONTEND=noninteractive

RUN apt-get update && apt-get install -y \
    curl git lsb-release locales \
    python3-colcon-common-extensions \
    python3-pip \
    python3-vcstool \
    build-essential \
    ros-humble-robot-state-publisher \
    ros-humble-tf2-ros \
    ros-humble-foxglove-bridge \
    ros-humble-xacro \
    ros-humble-rviz2 \
    ros-humble-joint-state-publisher-gui \
    && rm -rf /var/lib/apt/lists/*

SHELL ["/bin/bash", "-c"]
RUN echo "source /opt/ros/humble/setup.bash" >> ~/.bashrc
CMD [ "bash" ]