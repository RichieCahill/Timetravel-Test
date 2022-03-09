# Timetravel-Test
I'm making this because i'm curious how git hum will handel me changing the date

sudo systemctl disable systemd-timesyncd.service
sudo date -s "" 
sudo systemctl enable systemd-timesyncd.service 
