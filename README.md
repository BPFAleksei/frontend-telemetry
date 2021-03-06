<!-- ABOUT THE PROJECT -->
## Acerca del proyecto
Proyecto de practica de telemetría del Frontend con Matomo. 
Es parte de mis practicas en el curso de DevOps de mundosE y la Universidad Nacional de Cordoba, Argentina.

Matomo es una alternativa a Google Analytics y es OpenSource

La arquitectura general del proyecto es la siguiente:
![image](https://user-images.githubusercontent.com/32690411/132074149-0ec34226-7c66-4a03-84f0-3a4509cc58a5.png)

### Construido Con
El proyecto consta de un cluster en Kubernetes, con containers de MySQL como base de datos de Matomo, Matomo, y un frontend hecho en React el cual utiliza un JsonFy para fines de prueba en el front.

* [K3S](https://k3s.io/)
* [Matomo](https://matomo.org/)

<!-- GETTING STARTED -->
## Empezando
Este es un ejemplo de como realizar metricas en el frontend, con matomo.

### Pre Requisitos
Como prerequisito se debe tener instalado K3S.
y se deben levantar todos los containers.

<!-- USAGE EXAMPLES -->
         
- Instalar k3s 
- Deploy Mysql 
- Deploy/Install Matomo 
- Deploy Nginx con App
- Agregar dominios Hosts
- Crear Reglas Ingress
- Test


Teniendo el cluster desplegado se ingresa a la url de matomo
![image](https://user-images.githubusercontent.com/32690411/132074643-e0d8f107-c34d-4e10-829a-1ca2bf937dbd.png)

Luego al realizar visitas e interactuar con la aplicación de frontend podemos ver ya las metricas en matomo, de cantidad de usuarios, sistema desde donde han ingresado los usuarios, las ubicaciones, entre otras muchas metricas.


![image](https://user-images.githubusercontent.com/32690411/132074697-900d74ce-07ea-4869-afdb-d89cc57fe6e0.png)
![image](https://user-images.githubusercontent.com/32690411/132074701-ebd32ee8-94f8-4af5-894b-326fc2229381.png)
![image](https://user-images.githubusercontent.com/32690411/132074721-37e17962-a77f-4617-a5b6-9cbf4bea5b55.png)
![image](https://user-images.githubusercontent.com/32690411/132075447-00ff94c6-1d15-448a-8928-2249374aa4b6.png)

<!-- CONTACT -->
## Contact

Mgtr. Aleksei Escobar - [@aleksei_tsl](https://twitter.com/aleksei_tsl) - aleksei.escobar@gmail.com

Project Link: [https://github.com/BPFAleksei/frontend-telemetry](https://github.com/BPFAleksei/frontend-telemetry)
