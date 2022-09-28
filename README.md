# Port-Windows-11-Poco-X3-pro

# English

We're not responsible for bricked devices, dead microSD cards, dead cats or dogs, nuclear wars or you getting fired because the alarm app didn't work.

## Important

This project is in a very early stage, all the files here have been contributed by other users, here you will find a guide with the working files we managed to get.

Some drivers in this project belong to gus33000 [here](https://github.com/WOA-Project/SurfaceDuo-Drivers) you can see his project.

Some drivers in this project belong to map220v [here](https://github.com/map220v/MiPad5-Drivers) you can see his project.

UEFI EDK2 image for Poco X3 Pro was taken from [here](https://forum.xda-developers.com/t/uefi-poco-x3-pro.4441163/).

The compiled Windows Pe for the snapdragon 855, 855+ and 860 [source](https://youtu.be/IKLjTv5ooZU)

## Project status

At the moment, we are trying to solve the issue "Too many primary partitions" that happens when trying to make the Win partition.

In theory, the error is because [GPT disks can't have more than 32 partitions](https://en.wikipedia.org/wiki/GUID_Partition_Table#Partition_entries_(LBA_2%E2%80%9333))  and Xiaomi filled those 32 partitions, so we will investigate if we can remove some of them.

A user already found the solution, you have to use [gptfdisk](https://unix.stackexchange.com/a/90224) , so the commands here are wrong, I hope to be able to correct them soon.

## Required Files

Coming soon...

# Español

# ¡Advertencia!
No nos hacemos responsables de dispositivos brickeados, micro SD muertas, guerras nucleares, mascotas muertas o que la app de alarma falle y te despidan del trabajo.

Esto es un proceso delicado, hágalo bajo su propio riesgo y sin saltarse pasos del tutorial

## Importante

Este proyecto por ahora está en una fase experimental muy temprana, todos los archivos han sido aportados por otros usuarios de la comunidad, aquí realmente tendrás una guía con la documentación que hemos sido capaces de reunir.

La mayoría de información fue proporcionada por usuarios del discord de Renegade Project.

Los drivers usados en este proyecto pertenecen a gus33000 en el port de la Surface Duo [aquí](https://github.com/WOA-Project/SurfaceDuo-Drivers) puedes ver su proyecto.

Los drivers usados en este proyecto pertenecen a map220v en el port de la Xiaomi Mi Pad 5 [aquí](https://github.com/map220v/MiPad5-Drivers) puedes ver su proyecto.

La imagen Uefi del Poco X3 Pro fue sacada de [aquí](https://forum.xda-developers.com/t/uefi-poco-x3-pro.4441163/), (Actualmente tiene un error que se está tratando de solucionar.)

Se está trabajando sobre [esta imagen uefi](https://github.com/halal-beef/MU-sm8150pkg-auto-complie/tree/main/Platforms/SurfaceDuoPkg/Device/xiaomi-vayu)

El Windows Pe compilado para el snapdragon 855, 855+ y 860 [lo obtuvimos aqui](https://youtu.be/IKLjTv5ooZU)

## Estado del proyecto

Ahora se está tratando de solucionar un error que impide al poco X3 pro arrancar Windows, falla incluso teniendo un Windows pe compatible con el 860

## Archivos necesarios

Próximamente...
