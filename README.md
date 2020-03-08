## cuda-kali-linux
additional step installing nvidia gpu on kali linux

# Follow step bellow
* before you go, make sure your sources.list have line bellow:
```
deb http://http.kali.org/kali kali-rolling main non-free contrib
deb-src http://http.kali.org/kali kali-rolling main non-free contrib
```
* follow step in https://www.kali.org/docs//general-use/install-nvidia-drivers-on-kali-linux/
* before installing hashcat, install also suggested packages except mesa-opencl-icd
- suggested packages are beignet-opencl-icd and nvidia-opencl-icd
* done.
