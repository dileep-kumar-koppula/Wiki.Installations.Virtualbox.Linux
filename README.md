# Installing `VirtualBox` on Linux

## 

1. Package list update

  ```bash
  sudo apt update
  ```

2. Add the Oracle VirtualBox repository

  ```bash
  wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O- | sudo apt-key add -
  wget -q https://www.virtualbox.org/download/oracle_vbox_2016.asc -O /etc/apt/trusted.gpg.d/virtualbox.asc
  ```

3. Update the package lists again

  ```bash
  sudo apt update
  ```

4. Install VirtualBox

  ```bash
  sudo apt install virtualbox-7.1 -y
  ```
