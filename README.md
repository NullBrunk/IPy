<div align="center">

# IPy 
<img src="https://readme-typing-svg.demolab.com?font=Iosevka+Nerd+Font&weight=900&pause=1000&color=6791C9&background=0C0E0F00&center=true&vCenter=true&width=700&lines=A+python+GNU%2FLinux+networking+configuration+tool">
<br/>  
  
![GitHub top language](https://img.shields.io/github/languages/top/NullBrunk/IPy?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/NullBrunk/IPy?style=for-the-badge)
![GitHub repo size](https://img.shields.io/github/repo-size/NullBrunk/IPy?style=for-the-badge)

![image](https://github.com/NullBrunk/IPy/assets/125673909/b7a577a4-76fb-485d-a33e-7e31c3642f6e)


</div>

# 💻 Usage 

### Show mode : IP
This mode allows you to display a variety of information related to a given interface. You can provide the interface via CLI or by interactively selecting it from a list.
![show_mode_ip](https://github.com/NullBrunk/IPy/assets/125673909/5da86a4c-cdb0-414c-8aa6-d873ca4e5cde)

### Show mode : ROUTE
This mode allows you to display the routes in a nice format
![image](https://github.com/NullBrunk/IPy/assets/125673909/ce1d2c97-02ec-4780-a132-d9c23efc34c2)


### Config mode : IP
This mode allows you to UP/DOWN the interface or ADD/DELL an ip (v4 or v6), on a given interface. You can provide the interface via CLI, or by interactively selecting it from a list.
![config_mode_ip](https://github.com/NullBrunk/IPy/assets/125673909/940bca59-5797-4fc9-a9c2-1843a10ba855)


### Config mode : ROUTE
This mode allows you to ADD/DEL a Route on a given interface. You can provide the interface via CLI, or by interactively selecting it from a list.
![route_mode](https://github.com/NullBrunk/IPy/assets/125673909/9ff3bd4b-42d8-4efc-a0c4-b5a4f1b976ea)


# 📖 Changelog

All notable changes to this project will be documented in this file.

```bash
# [1.0] - 27 mars 2024
- First commit
- Show IP (v4 and v6) of a specific interface
- Show all routes
- Configure an interface (UP, DOWN, ADD/DEL IP)
- Configure routes (ADD/DEL)

# [1.1] - 28 mars 2024
- Refactored ALL_INTERFACES + display_interface() with netifaces
- Added netifaces to the requirements
- General graphical improvement
- Refactored the log class
```
 
# ⚒️ Installation
```bash
git clone https://github.com/NullBrunk/IPy
cd IPy
pip3 install -r requirements.txt
chmod +x ipy
./ipy
```

