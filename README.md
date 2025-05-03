# Configuracion-Red

## 1. Creamos dos máquinas virtuales

  - Usando la opción de clonación enlazada creamos dos máquinas a las cuales tenemos que modificar la MAC.

    ![Máquina A](./Configuracion-Red/1º.png)

  - En la misma configuración de red de VirtualBox, el segundo adaptador de las dos máquinas lo habilitamos y lo ponemos en red interna.

    ![Máquina A](./Configuracion-Red/2º.png)

## 2. Configuración de red `enp0s8` temporal

  **Máquina A:** `192.168.100.2`

  ![Máquina A](./Configuracion-Red/3º.png)

  **Máquina B:** `192.168.100.3`

  ![Máquina B](./Configuracion-Red/4º.png)

## 3. Comprobación de ping entre máquinas

  **Máquina A**

  ![Máquina A](./Configuracion-Red/5º.png)

  **Máquina B**

   ![Máquina B](./Configuracion-Red/6º.png)

## 4. Configuración de red permanente

  - Primeramente hacemos la copia del archivo `.yaml` para tener la plantilla.

    ![Máquina A](./Configuracion-Red/7º.png)

  - Editamos el archivo de configuración

    **Máquina A**

    ![Máquina A](./Configuracion-Red/8º.png)

  - La máquina B se hace a través de interfaz gráfica.

    ![Máquina B](./Configuracion-Red/9º.png)
        
