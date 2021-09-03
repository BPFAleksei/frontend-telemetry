<!-- ABOUT THE PROJECT -->
## Acerca del proyecto
Proyecto de practica de telemetría del Frontend con Matomo. 
Es parte de mis practicas en el curso de DevOps de mundosE y la Universidad Nacional de Cordoba, Argentina.
La arquitectura es la siguiente:
![image](https://user-images.githubusercontent.com/32690411/132074149-0ec34226-7c66-4a03-84f0-3a4509cc58a5.png)

### Built With
El proyecto consta de un cluster en Kubernetes, con containers de MySQL como base de datos de Matomo, Matomo, y un frontend hecho en React el cual utiliza un JsonFy para fines de prueba en el front.

* [K3S](https://k3s.io/)
* [Matomo](https://matomo.org/)

<!-- GETTING STARTED -->
## Empezando

Este es un ejemplo de como realizar metricas en el frontend, con matomo.

### Pre Requisitos
Como prerequisito se debe tener instalado K3S.

<!-- USAGE EXAMPLES -->
## Uso
Teniendo el cluster desplegado se ingresa a la url de matomo
![image](https://user-images.githubusercontent.com/32690411/132074643-e0d8f107-c34d-4e10-829a-1ca2bf937dbd.png)

Luego al realizar visitas e interactuar con la aplicación de frontend podemos ver ya las metricas en matomo, de cantidad de usuarios, sistema desde donde han ingresado los usuarios, las ubicaciones, entre otras muchas metricas.


![image](https://user-images.githubusercontent.com/32690411/132074697-900d74ce-07ea-4869-afdb-d89cc57fe6e0.png)
![image](https://user-images.githubusercontent.com/32690411/132074701-ebd32ee8-94f8-4af5-894b-326fc2229381.png)
![image](https://user-images.githubusercontent.com/32690411/132074721-37e17962-a77f-4617-a5b6-9cbf4bea5b55.png)

<!-- CONTACT -->
## Contact

Mgtr. Aleksei Escobar - [@tsl_aleksei](https://twitter.com/tsl_aleksei) - aleksei.escobar@gmail.com

Project Link: [https://github.com/BPFAleksei/frontend-telemetry](https://github.com/BPFAleksei/frontend-telemetry)
