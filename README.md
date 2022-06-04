# Creación de una Pagina Web con "App Services"

![Microsoft Azure App Services](https://github.com/DagonNR/Uso-de-App-Services-Pagina-web/blob/main/images/Microsoft-Azure-App-Services.png)

---

## Requisitos
- Cuenta en [Microsoft Azure](https://portal.azure.com)
- Un dispositivo, por ejemplo una computadora
- Acceso a internet

---

## Importante
- En este caso creamos un "App Service" con plan "Free", por lo que no tuvo ningún costo, pero el uso de la web esta limitado a 60 minutos al día, pero si utilizas un plan con costo, este se realiza cada hora, por lo que si no se va a utilizar, es importante detenerla.

---

## Pasos a seguir
- Entramos en [Microsoft Azure](https://portal.azure.com), y buscamos "App Services", y creamos una, después llenamos los datos, en este caso usaremos Linux como sistema operativo y PHP 8.0.
![P1](https://github.com/DagonNR/Uso-de-App-Services-Pagina-web/blob/main/images/P1.png)


- Después mediante "Github", vamos a sincronizar los archivos que tenemos, de nuestra pagina web.
![P2](https://github.com/DagonNR/Uso-de-App-Services-Pagina-web/blob/main/images/P2.png)

- Entramos en la App Service que creamos, y nos vamos al apartado de "Centro de implementación", y en este caso lo haremos mediante "Github", dentro de Azure nos pedira iniciar sesión con nuestr cuenta de "Github" y escogeremos el repositorio donde antes subimos los archivos de nuestra pagina web.

- Si queremos ver como va el proceso de implementación de la pagina web, se puede hacer desde "Github", en el repositorio correspondiente, en el apartado de "Actions".

- Al terminar el proceso, nos arrojara un link, el cual si todo salio bien, al clicarlo, nos redireccionará a nuestra pagina web.
![P3](https://github.com/DagonNR/Uso-de-App-Services-Pagina-web/blob/main/images/P3.png)

- En este caso quedo así, si te aparece que el sitio es "No seguro", no te asustes, dentro de unos minutos cambiara a "Seguro".
![P4](https://github.com/DagonNR/Uso-de-App-Services-Pagina-web/blob/main/images/P4.png)
