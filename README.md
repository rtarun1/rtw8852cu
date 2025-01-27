# rtw8852cu

To install in Jetson

### Clone
```bash
git clone https://github.com/lwfinger/rtw8852cu
cd rtw8852cu
```

### Build
```bash
make
```

### Install
```bash
sudo make install
```

### Reload
```bash  
sudo modprobe -r 8852cu || true
sudo modprobe 8852cu
```