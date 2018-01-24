# amaz0n

#      
      # curl -LOk  https://raw.githubusercontent.com/hyassine53/oshit/master/ezy.sh  && chmod +x ezy.sh && ./ezy.sh
# Swap
     mkdir -v /var/cache/swap && cd /var/cache/swap && dd if=/dev/zero of=swapfile bs=1K count=4M && chmod 600 swapfile &&  mkswap swapfile && swapon swapfile && echo "/var/cache/swap/swapfile none swap sw 0 0" | sudo tee -a /etc/fstab && swapoff swapfile &&  swapon -va
