# Seguimiento #2 Parte1

- Tiene como objetivo recuperar la contraseña del usuario root.

 A contuación se verá el proceso de lo realizado.
 
 Se presiona cualquier tecla, esto con el fin de detener el arranque (establecerse en el GRUB).
 
 ![root1](https://user-images.githubusercontent.com/101071837/169875028-66c1803e-ee19-4c3d-bbe6-751e37c8651b.PNG)

Despues de esto se presiona la tecla "e", cambiamos la sentencia "rhgb quiet" por "rd break".

![root2](https://user-images.githubusercontent.com/101071837/169875512-6b8591bb-640b-4d54-be97-fa15c409d91e.PNG)

Posteriormente a la ejecución de esto se procede a escribir y ejecutar los siguiente comando en orden.

    mount
    mount -o rw. remount /sysroot/
    mount
    chroot /sysroot/
    passwd
    touch /.autorelabel
    exit
    exit
    
  ![root5](https://user-images.githubusercontent.com/101071837/169876347-b04e154d-9f60-46a7-b70f-0f819a6c2c28.PNG)

![root6](https://user-images.githubusercontent.com/101071837/169876435-1fca7051-cbe8-4173-86df-7d2ea0942a1b.PNG)

Por último se verá en pantalla.

![root7](https://user-images.githubusercontent.com/101071837/169876598-29ae2187-0425-4701-ab70-c7d55ba5152a.PNG)

Finalmente, una vez iniciado el SO revisaremos nuestro usuario.

![root8](https://user-images.githubusercontent.com/101071837/169876690-8471e6f7-7d93-4e3c-9309-57d61a55c187.PNG)

# Seguimiento #2 Parte2

- Su objetivo es realizar el movimiento y cambio de nombre de archivos y directorios.

Se agregó nuevos directorios al proyecto del seguimiento 1 y se cambió el nombre de algunos, tales como:

Bisabuela,Bisabuelo,Nieta,Nieto,Bisnieta,Bisnieto.

![familia2](https://user-images.githubusercontent.com/101071837/169879840-d794229b-6f7d-4ebe-96f3-ad7a3efaff28.PNG)

Despues de esto se movio el archivo de los nombres a su contraparte.

![familia4](https://user-images.githubusercontent.com/101071837/169880172-77b60000-21c1-40d5-9ae0-d5a4fa39b38b.PNG)

Por ultimo el resultado es:

![familia5](https://user-images.githubusercontent.com/101071837/169880202-86af49b9-9c52-452f-a0ae-b493c782af1b.PNG)







 
 
