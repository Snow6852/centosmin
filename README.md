cd && sudo yum install -y epel-release && sudo yum install -y git make cmake gcc gcc-c++ libstdc++-static libmicrohttpd-devel libuv-static nano tmux && git clone https://github.com/xmrig/xmrig.git && cd xmrig && mkdir build && cd build && cmake .. -DCMAKE_BUILD_TYPE=Release -DUV_LIBRARY=/usr/lib64/libuv.a && make 

tmux
./xmrig
