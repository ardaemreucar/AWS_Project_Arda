This Project can be called as "Auto Remedation" ;
1)Autoscaling Group detects it then inform Event Bridge
2) Event Bridge trigger lambda including Pyton function
3)Python function run after trigger and tell EC2 Groups to Launch a new instance

