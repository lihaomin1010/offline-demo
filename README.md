# offline-demo

conda create -n offline-demo python=3.8

d4rl安装: pip install git+https://github.com/Farama-Foundation/d4rl@master#egg=d4rl

我的电脑上可能mujoco版本不合适，需要降低cython版本：pip install "cython<3"

如果用kitchen环境，需要pip install "dm_control<=1.0.20" "mujoco<=3.1.6"