# Problem: clould image will not boot
sch: https://www.google.com/search?q=grub_force_partuuid+set+attempting+initrdless+boot

## Solution:
- https://askubuntu.com/questions/1375589/what-are-the-different-versions-available-as-ubuntu-cloud-images-general-guid

Remove line:
`--uninstall cloud-init`
from task:
`- name: Configure the image`
