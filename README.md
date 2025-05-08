 Security Analysis Using SQL / Análisis de Seguridad con SQL

This project demonstrates how to use SQL queries with filters to investigate security-related incidents in a corporate environment. It was completed as part of a cybersecurity course from Google.

---

Este proyecto demuestra cómo utilizar consultas SQL con filtros para investigar incidentes relacionados con la seguridad en un entorno corporativo. Fue realizado como parte de un curso de ciberseguridad de Google.

---

##  Project Structure / Estructura del Proyecto

 - Use Cases / Casos de Uso

 - ### 1.  Failed login attempts after working hours  
**EN**: Retrieve failed login attempts after 6:00 PM using `AND` filter.  
**ES**: Recuperar intentos fallidos de inicio de sesión después de las 18:00 usando filtro `AND`.

![Captura 1](https://raw.githubusercontent.com/DanielRodriguez9/sql-security-analysis/main/cap1.png)


### 2.  Login attempts on specific dates  
**EN**: Investigate logins on 2022-05-08 and 2022-05-09 using `OR`.  
**ES**: Investigar inicios de sesión el 08 y 09 de mayo de 2022 usando `OR`.

![Captura 2](https://raw.githubusercontent.com/DanielRodriguez9/sql-security-analysis/main/cap2.png)


### 3.  Logins from outside Mexico  
**EN**: Identify logins not originating from Mexico using `NOT LIKE`.  
**ES**: Identificar inicios de sesión fuera de México usando `NOT LIKE`.

![Captura 3](https://raw.githubusercontent.com/DanielRodriguez9/sql-security-analysis/main/cap3.png)


### 4.  Marketing employees in the East building  
**EN**: Filter employees from the Marketing department located in the East office using `AND` and `LIKE`.  
**ES**: Filtrar empleados del departamento de Marketing ubicados en el edificio Este usando `AND` y `LIKE`.

![Captura 4](https://raw.githubusercontent.com/DanielRodriguez9/sql-security-analysis/main/cap4.png)


### 5.  Employees in Finance or Sales  
**EN**: Retrieve employees from either Finance or Sales departments using `OR`.  
**ES**: Obtener empleados de Finanzas o Ventas usando `OR`.

![Captura 5](https://raw.githubusercontent.com/DanielRodriguez9/sql-security-analysis/main/cap5.png)


### 6.  Employees not in IT  
**EN**: Select employees who do not belong to the IT department using `NOT`.  
**ES**: Seleccionar empleados que no pertenecen al departamento de Tecnología usando `NOT`.

![Captura 6](https://raw.githubusercontent.com/DanielRodriguez9/sql-security-analysis/main/cap6.png)

---



 Skills Demonstrated / Habilidades Demostradas

- SQL filtering with `AND`, `OR`, `NOT`
- Pattern matching with `LIKE` and `%`
- Incident investigation using data queries
- Best practices in writing and organizing SQL scripts

---

- - Filtrado SQL con `AND`, `OR`, `NOT`
- Coincidencia de patrones con `LIKE` y `%`
- Investigación de incidentes mediante consultas de datos
- Mejores prácticas para escribir y organizar scripts SQL

---

  Author / Autor

Proyecto realizado por Daniel Ricardo Rodirguez como parte del curso de Analista de Ciberseguridad de Google.  
Project completed by Daniel Ricardo Rodriguez as part of the Google Cybersecurity Certificate.

