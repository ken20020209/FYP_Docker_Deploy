# FYP_Docker_Deploy
The repository use to deploy web , ros server , api server
start: docker compose up


<!-- for demo -->
git clone https://github.com/ken20020209/FYP_Robot.git -b test_without_robot;source install/setup.bash;cd FYP_Robot/;colcon build/;source install/setup.bash;
export name=dog_s2_0;python3 startConnector.py;
export name=dog_s2_1;python3 startConnector.py;
export name=dog_s2_2;python3 startConnector.py;
