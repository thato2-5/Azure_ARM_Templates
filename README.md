This repository represents a set of Azure services needed to successfully create a virtual machine.
Virtual Machine Specs:
                    -> SKU : Free B1 \n
                    -> Disk : Managed 30GB
                    -> Location : South Africa North
                    -> Authentication : Password
                    -> Type : Ubuntu Server

Comments:
Please update the parameters.json file to include your own runtime values.
The setup.sh file will customize the OS by installing and configuring python.
This VM was meant for replacing my App Service Plane (ASP) to serve flask applications.
