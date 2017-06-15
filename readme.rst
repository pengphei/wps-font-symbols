安装方法
=======================================

1. 拷贝字体到 *usr/share/fonts*
   
.. code-block:: shell
      
   cp -r ./wps-font-symbols /usr/share/fonts/
   
2. 权限配置
   
.. code-block:: shell
      
   cd /usr/share/fonts
      
   chmod 755 wps-font-symbols
      
   cd /usr/share/fonts/wps-font-symbols
      
   chmod 644 *
      
3. 生成字体缓存信息
   
.. code-block:: shell
      
   cd /usr/share/fonts/wps-font-symbols
      
   mkfontdir
      
   mkfontscale
      
   fc-cache
      
