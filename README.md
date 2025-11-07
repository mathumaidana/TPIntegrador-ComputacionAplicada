# Trabajo Práctico Integrador – Computación Aplicada
Universidad de Palermo — 2025

- Integrantes Grupo 6:
  - Marco Antonio Braithwaite Paredes
  - Lucas Cristaldo
  - Celina Galloni
  - Matheo Maidana

- Información relevante
  - Hostname: TPServer
  - Servicios: SSH por clave, Apache+PHP (DocumentRoot: /www_dir), MariaDB (db.sql importado).
  - Red: IP estática 192.168.1.7/24.
  - Almacenamiento: /www_dir (3 GB) y /backup_dir (6 GB) en /dev/sdc1 y /dev/sdc2 por UUID (fstab).
  - Nota /proc: copia en /root/particion.
  - Backups: /opt/scripts/backup_full.sh  
    - 00:00 → /var/logs  
    - 23:00 L-M-V → /www_dir
  - Entregables: tars y var.tar.gz.part.

- Link a VM
  - https://palermo-my.sharepoint.com/:u:/g/personal/mmaida9_up_edu_ar/EfKFBIC289VFrekj5qoS9hoBy3-gBrcD0fgMBuYrBeeaUw?e=BCw9q5
