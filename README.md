# ROS-Installation
Comprehensive tutorial on setting up a ROS development environment using VirtualBox and Ubuntu 20.04. This guide walks you through the process of creating a virtual machine, installing Ubuntu, and configuring ROS Noetic. Perfect for beginners and experienced robotics programmers alike.




# Step 1: Download and Install VirtualBox

1.Open your web browser and go to the [VirtualBox website] (https://www.virtualbox.org/).
![image](https://github.com/user-attachments/assets/676c91a2-d5f7-4ed7-ac41-c61314a887a9)

2. Click on "Download VirtualBox". 3. Select the version appropriate for your operating system (Windows, macOS, Linux). 4. After downloading, open the installation file and follow the on-screen instructions to install VirtualBox.

# Step 2: Download Ubuntu 20.04 

1.Open your web browser and go to the Ubuntu website.
![image](https://github.com/user-attachments/assets/d80ef772-9286-41af-8828-db1450d91a00)

2.Select "Ubuntu 20.04 LTS" and click on "Download".

# Step 3: Create a New Virtual Machine in VirtualBox

1.Open VirtualBox and click on "New" to create a new virtual machine.

![image](https://github.com/user-attachments/assets/bcc3f501-8f18-40e5-8652-cf79c2c015b4)

2.Name the machine and choose the type of operating system as "Linux" and the version as "Ubuntu (64-bit)".

![image](https://github.com/user-attachments/assets/c4dbec43-a9a0-47e0-a0bc-f5187f736807)

3.Set the memory size (RAM) (at least 2 GB is recommended)(to green).

![image](https://github.com/user-attachments/assets/40e03dc6-37ed-4279-abf2-ed5cf4ae88fa)

4. Set the size of the virtual hard disk (at least 25 GB is recommended) and click "Create".
   ![image](https://github.com/user-attachments/assets/7b374ee2-27e7-4e27-bb44-6ea0bd252ba4)


# Step 4: Install Ubuntu 20.04

1.After creating the virtual machine, select it from the list in VirtualBox and click "Start".
![image](https://github.com/user-attachments/assets/e64d4350-1ba6-4c2f-83f3-a11c383d8d99)

2.When prompted, choose the Ubuntu 20.04 ISO file you downloaded and click "Start".

![image](https://github.com/user-attachments/assets/97b277b9-2567-443c-854e-a2f7552a6bf0)
![image](https://github.com/user-attachments/assets/49fd432d-2f6d-412d-bf4c-676d7508d403)
![image](https://github.com/user-attachments/assets/8ca81335-fea1-42df-9408-1e91b3f41c6c)

3.Follow the on-screen instructions to install Ubuntu 20.04 on the virtual machine.

4.Start downlaoding
   
![image](https://github.com/user-attachments/assets/28c94fdc-7475-4c13-a68b-8f3dd6ed197f)

5.After finishing doanlaoding you should Restart
![image](https://github.com/user-attachments/assets/72dc520b-897c-4568-8ea9-6561052daa20)

6.Start using 
![image](https://github.com/user-attachments/assets/05b5e69a-57fd-443d-b855-20c22338391b)


#Step 5: Install ROS on Ubuntu 20.04

1.After installing Ubuntu, open a terminal window.
![image](https://github.com/user-attachments/assets/22c712b3-4be1-418b-9017-d78da16cb8d0)

2.Add the ROS repository to your system:
![image](https://github.com/user-attachments/assets/2b8916d1-f529-4f9a-bdf9-7ab90414cfcd)

sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'





















