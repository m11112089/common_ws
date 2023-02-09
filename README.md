# common_ws

安裝所有依賴

> $ rosdep install --from-paths src --ignore-src -r -y

啟動Topology_map Actoion Server

> $ rosrun forklift_server Topology_map_server.py

啟動PBVS Actoion Server

> $ rosrun forklift_server PBVS_server.py

啟動控制節點 Action Client

> $ rosrun forklift_server ctrl_server.py


install realsense SDk
https://github.com/IntelRealSense/librealsense/blob/master/doc/distribution_linux.md
