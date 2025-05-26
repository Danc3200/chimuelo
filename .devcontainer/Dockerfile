FROM ros:humble-ros-core

RUN apt-get update && apt-get install -y \
    ros-humble-robot-state-publisher \
    ros-humble-tf2-ros \
    ros-humble-foxglove-bridge \
    ros-humble-xacro \
    ros-humble-rviz2 \
    ros-humble-joint-state-publisher-gui \
    && rm -rf /var/lib/apt/lists/*