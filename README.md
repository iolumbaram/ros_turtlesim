# ros_turtlesim

1219  catkin_make
 1220  cd jh
 1221  cd src/turtlebot_hardware/src
 1222  rosrun turtlebot_hardware simulated_odom.py 
 1223  roscore
 1224  rostopic list
 1225  rostopic echo /tf
 1226  rosrun tf tf_echo /world /turtle1
 1227  cd jh/src
 1228  ls
 1229  rosrun tf tf_monitor
 1230  cd ..
 1231  catkin_make
 1232  cd src
 1233  catkin_create_pkg ros_tutorials tf roscpp rospy turtlesim
 1234  cd ..
 1235  catkin_make
 1236  source ./devel/setup.bash
 1237  roscd turtlebot_hardware
 1238  cd ..
 1239  cd ros_tutorials/
 1240  mkdir nodes
 1241  cd nodes/
 1242  sudo gedit turtle_tf_broadcaster.py
 1243  ls
 1244  chmod +x nodes/turtle_tf_broadcaster.py
 1245  chmod +x turtle_tf_broadcaster.py 
 1246  sudo chmod +x turtle_tf_broadcaster.py 
 1247  cd ..
 1248  mkdir launch
 1249  cd launch/
 1250  sudo gedit turtle_demo_tf.launch
 1251  sudo chmod +x turtle_demo_tf.launch 
 1252  ls
 1253  roslaunch ros_tutorials turtle_demo_tf.launch 
 1254  rosrun ros_tutorials turtle_tf_broadcaster.py 
 1255  roscd ros_tutorials/nodes/
 1256  ls
 1257  sudo gedit turtle_tf_broadcaster.py 
 1258  cd ../..
 1259  cd ..
 1260  catkin_make
 1261  rosrun ros_tutorials turtle_tf_broadcaster.py 
 1262  cd src/ros_tutorials/nodes/
 1263  sudo gedit turtle_tf_broadcaster.py 
 1264  cd ..
 1265  ls
 1266  cd src
 1267  ls
 1268  cd nodes/
 1269  rosrun ros_tutorials turtle_tf_broadcaster.py 
 1270  cd ..
 1271  sudo gedit tsim_tf_broadcaster.cpp
 1272  cd ..
 1273  ls
 1274  cd ../..
 1275  catkin_make
 1276  rosrun ros_tutorials tsim_tf_broadcaster 
 1277  cd src/ros_tutorials/src/
 1278  ls
 1279  sudo gedit tsim_tf_demo.launch
 1280  roslaunch ros_tutorials tsim_tf_demo.launch 
 1281  cd ../..
 1282  cd ..
 1283  catkin_make
 1284  roslaunch ros_tutorials tsim_tf_demo.launch 
 1285  catkin_make
 1286  roslaunch ros_tutorials tsim_tf_demo.launch 
 1287  catkin_make
 1288  roslaunch ros_tutorials tsim_tf_demo.launch 
 1289  catkin_make
 1290  roslaunch ros_tutorials tsim_tf_demo.launch 
 1291  catkin_make
 1292  roslaunch ros_tutorials tsim_tf_demo.launch 
 1293  catkin_make
 1294  roslaunch ros_tutorials tsim_tf_demo.launch 
 1295  catkin_make
 1296  roslaunch ros_tutorials tsim_tf_demo.launch 
 1297  catkin_make
 1298  roslaunch ros_tutorials tsim_tf_demo.launch 
 1299  rosrun ros_tutorials turtle_tf_broadcaster.py 
 1300  history
 1301  catkin_make
 1302  rosrun ros_tutorials turtle_tf_broadcaster.py 
 1303  catkin_make
 1304  rosrun ros_tutorials turtle_tf_broadcaster.py 
 1305  catkin_make
 1306  cd src/ros_tutorials/src
 1307  chmod +x gotogoal.py 
 1308  cd ../..
 1309  cd ..
 1310  catkin_make
 1311  rosrun ros_tutorials gotogoal.py 
 1312  roscore
 1313  rostopic list
 1314  clear
 1315  rostopic list
 1316  rosnode list
 1317  rosrun rqt_tf_tree rqt_tf_tree 
 1318  rosrun turtlesim turtlesim_node 
 1319  cd jh/
 1320  catkin_make
 1321  cd src/ros_tutorials/src
 1322  ls
 1323  chmod +x gosquare.py 
 1324  rosrun ros_tutorials gosquare.py 
 1325  chmod +x simsquare.py 
 1326  rosrun ros_tutorials simsquare.py 
 1327  rostopic echo /cmd_vel
