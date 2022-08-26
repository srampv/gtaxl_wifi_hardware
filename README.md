# gtaxl_wifi_hardware
you need to add below xml to your manifest file under .repo/local_manifests/roomservice.xml
<project name="srampv/gtaxlwifi_device_tree.git" path="device/samsung/gtaxlwifi" remote="github" />
 <project name="srampv/gtaxlwifi_vendor_tree.git" path="vendor/samsung/gtaxlwifi" remote="github" />
  <project name="srampv/gtaxl_wifi_hardware.git" path="hardware/samsung" remote="github" />
  
  and then run below steps
  
  source build/envsetup.sh
  ~/bin/repo sysnc
  breakfast gtaxlwifi
  brunch gtaxlwifi
