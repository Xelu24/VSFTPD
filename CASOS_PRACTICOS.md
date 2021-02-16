## VSFTPD

# Versión VSFTPD

# Usuario Creados en la Instalación

# Servicio Asociado

![1](./imagenes/1.png  "1")

# Ficheros de configuración

/etc/vsftpd.conf

# Direcctivas Importantes

write_enable=YES Nos permite escribir
local_umask=022 Nos permite dar nuevos permisos
ftpd_banner Permite poner un banner al iniciar sesión.
chroot_enable=YES Activa el chroot, una medida de seguridad que sirve para enjaular los usuarios
chroot_list_enable=YES Habilita la chroot_list, es donde pondremos los usuarios que controlara chroot.
chroot_list_file=/etc/vsftpd.chroot_list Esta direcctiva indica la ruta del chroot_list, hay que crearlo ya que no existe por defecto
