# AV Development-Connected Autonomous Vehicle Installation  
USF Autonomous vehicle development notes, installation guide, and websites.
## minor bug report
[20/10/2023] bug: runtime_manager fail to start
Casue : Inapporiate closing of Autoware may lead to the broken of "param.yaml" in  /Autoware/ros/src/util/packages/runtime_manager/scripts.
Fix: delet the yaml file and restart/reconfigure autoware. 





For more timely update, please refer to https://github.com/Tom-ABCD-sxw
