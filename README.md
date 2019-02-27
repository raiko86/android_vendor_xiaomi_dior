# android_vendor_xiaomi_dior
<h3>LineageOS 14.1 Stabile - Xiaomi Redmi Note 4G (dior)</h3><br><br>
Add those lines to ".repo/local_manifests/roomservice.xml" and sync
<br><br>
  &lt;project name=&quot;raiko86/android_device_xiaomi_dior&quot; path=&quot;device/xiaomi/dior&quot; remote=&quot;github&quot; /&gt;<br>
  &lt;project name=&quot;raiko86/android_vendor_xiaomi_dior&quot; path=&quot;vendor/xiaomi/dior&quot; remote=&quot;github&quot; /&gt;<br>
  &lt;project name=&quot;raiko86/android_kernel_xiaomi_dior&quot; path=&quot;kernel/xiaomi/dior&quot; remote=&quot;github&quot; /&gt;<br>
  &lt;project name=&quot;LineageOS/android_device_qcom_common&quot; path=&quot;device/qcom/common&quot; remote=&quot;github&quot; 
/&gt;<br>
  &lt;project name=&quot;LineageOS/android_packages_resources_devicesettings&quot; path=&quot;packages/resources/devicesettings&quot; remote=&quot;github&quot; /&gt;
