Linux-On-Virtex-II-Pro
======================

Porting Linux Kernel on Legacy Virtex II Pro Board


Espanol: 
Este proyecto tiene intenciones meramente academicas para mostrar el flujo de trabajo para portar el Kernel Linux 
a un board FPGA legado Virtex II Pro. Este directorio de archivos se estructura de la sigueinte forma:

<VirtexIIP>
  hx
    -system.mhs
    -system.mss
    -system.xps
  lx
    -makefile
    -.config
    arch
      powerpc
        boot
        -config
        platforms
  sw
    rootfs
    my_apps
    powerpc-405-linux-gnu
  ace 