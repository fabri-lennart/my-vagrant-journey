# Learning Vagrant Basics

<img 
  src="https://github.com/user-attachments/assets/bd68100f-303f-41f6-9149-c34f6cfd18d2" 
  alt="image"
  width="900"
/>

A hands-on repository to learn Vagrant fundamentals by creating and managing virtual machines. This is my personal journey as a Data Engineer learning DevOps basics through practical VM provisioning and configuration.

---

## 🎯 What This Repo Is About

This repository contains my practice with:
- Creating virtual machines with Vagrant
- Writing and modifying Vagrantfiles
- Basic VM configuration
- Understanding Vagrant commands
- Experimenting with VM settings

No complex setups, no advanced orchestration - just learning the fundamentals of Vagrant one step at a time.

---

## 🚀 Prerequisites

- **Vagrant 2.3+** 
- **VirtualBox 7.0+** (or another provider)
- Basic command line knowledge

### Installation

**macOS**
```bash
brew install vagrant
brew install virtualbox
```

**Linux (Ubuntu/Debian)**
```bash
wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install vagrant
```

**Windows**
- Download from [vagrantup.com](https://www.vagrantup.com/downloads)
- Download VirtualBox from [virtualbox.org](https://www.virtualbox.org/wiki/Downloads)

---

## 📖 What I'm Learning

### Basic Vagrant Operations
- `vagrant init` - Initialize a new Vagrantfile
- `vagrant up` - Start virtual machines
- `vagrant ssh` - Access VMs via SSH
- `vagrant halt` - Stop VMs
- `vagrant destroy` - Remove VMs
- `vagrant status` - Check VM status

### Vagrantfile Configuration
- Choosing different box images
- Setting VM memory and CPU
- Configuring network settings
- Port forwarding
- Synced folders
- Basic provisioning scripts

### VM Management
- Creating single VMs
- Running multiple VMs
- Modifying VM resources
- Testing different configurations
- Troubleshooting common issues

---

## 🔧 Essential Commands

```bash
# Start a VM
vagrant up

# Access the VM
vagrant ssh

# Stop the VM
vagrant halt

# Restart with new configuration
vagrant reload

# Remove the VM completely
vagrant destroy

# Check VM status
vagrant status

# Validate Vagrantfile syntax
vagrant validate
```

---

## 💡 Why Vagrant?

As a Data Engineer wanting to learn DevOps basics, Vagrant provides:

✅ **Reproducible environments** - Same setup every time  
✅ **Quick experimentation** - Create and destroy VMs easily  
✅ **No server costs** - Everything runs locally  
✅ **Real infrastructure practice** - Work with actual VMs  
✅ **Foundation for more** - Gateway to advanced DevOps tools  

---

## 📚 Learning Resources

- [Official Vagrant Documentation](https://www.vagrantup.com/docs)
- [Vagrant Box Catalog](https://app.vagrantup.com/boxes/search)
- [VirtualBox Documentation](https://www.virtualbox.org/manual/)

---

## 📝 Notes

This is a learning repository where I practice and experiment with Vagrant basics. Each configuration represents a step in understanding how to work with virtual machines and infrastructure as code.

**Status**: Actively learning 🚀

---

## 📄 License

MIT License - Free to use for learning purposes.

---

**Happy Learning!** ⭐
