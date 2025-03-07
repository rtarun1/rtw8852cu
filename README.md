# rtw8852cu

## FOR TP_LINK ARCHER 50UH

- To install in Linux

### Clone
```bash
git clone https://github.com/rtarun1/rtw8852cu
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