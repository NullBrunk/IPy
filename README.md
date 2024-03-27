<div align="center">

# IPy 
<img src="https://readme-typing-svg.demolab.com?font=Iosevka+Nerd+Font&weight=900&pause=1000&color=6791C9&background=0C0E0F00&center=true&vCenter=true&width=700&lines=GNU%2FLinux+network+configuration+tool+written+in+python">
<br/>  
  
![GitHub top language](https://img.shields.io/github/languages/top/NullBrunk/IPy?style=for-the-badge)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/NullBrunk/IPy?style=for-the-badge)
![repo size](https://img.shields.io/github/repo-size/NullBrunk/IPy?style=for-the-badge)

![image](https://github.com/NullBrunk/IPy/assets/125673909/fac4f41a-62c3-44b5-a056-91e8c3a172c1)

</div>

# 💻 Usage 

### Show mode
This mode allows you to display several informations about a given interface. You can pass the interface in CLI, or select it in a list of all your interfaces in interactive mode. 

![show_mode](https://github.com/NullBrunk/IPy/assets/125673909/a153077c-3768-4233-99cb-1570efd3d758)


### Config mode : IP
This mode allows you to UP, DOWN, ADD an ip, DEL an IP on a given interface. You can pass the interface in CLI, or select it in a list of all your interfaces in interactive mode 

![config_mode_ip](https://github.com/NullBrunk/IPy/assets/125673909/50fc80c2-4d92-46d3-876e-fdb17f904546)


### Config mode : ROUTE
This mode allows you to ADD or DEL a Route on a given interface. You can pass the interface in CLI, or select it in a list of all your interfaces in interactive mode 

![config_mode_route](https://github.com/NullBrunk/IPy/assets/125673909/874cba57-2453-400b-865a-1b232dfae5dc)


# 📖 Changelog

All notable changes to this project will be documented in this file.

```bash
# [1.0] - 27 mars 2024
- First commit
- Show IP of a specific interface
- Show all routes
- Configure an interface (UP, DOWN, ADD/DEL IP)
- Configure routes (ADD/DEL)
```
 
# ⚒️ Installation
```bash
git clone https://github.com/NullBrunk/IPy
cd IPy
pip3 install -r requirements.txt
chmod +x ipy
./ipy
```

