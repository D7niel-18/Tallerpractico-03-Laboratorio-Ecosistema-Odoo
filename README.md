# Tallerpractico-03-Laboratorio-Ecosistema-Odoo
- Profesor: Willman Acosta
- Actividad: Taller Practico 03 - Laboratorio Ecosistema Odoo
## Descripción  
En este proyecto realizo una práctica con Odoo donde trabajo la integración de módulos, la creación de informes y la exportación de datos.

El objetivo es entender cómo funciona un ERP por dentro, cómo se conectan los módulos y cómo se manejan los datos usando XML, CSV y herramientas propias de Odoo.

## Objetivo  
Con esta práctica he aprendido a:

- Instalar y usar módulos en Odoo  
- Importar datos desde un CSV  
- Entender cómo se relacionan los datos en la base de datos  
- Exportar datos CSV para usarlos en otros programas

## Contenido del repositorio  
- clientes_mock.csv
- README.md

## Herramientas utilizadas  
- Visual Studio Code  
- Docker  
- Odoo  
- PostgreSQL  
- XML y CSV  

## Fases realizadas  

### Fase 1: 
Primero instalé los módulos de Inventario y Facturación.
<img width="467" height="279" alt="2" src="https://github.com/user-attachments/assets/bd65213d-e884-459a-8a2a-87b3bf880107" />

Después importé clientes desde un archivo CSV (clientes_mock.csv).
<img width="469" height="318" alt="1" src="https://github.com/user-attachments/assets/82ceef44-aa0a-4d54-98cb-f3e733c46cfe" />

Una vez importados:
<img width="471" height="307" alt="3" src="https://github.com/user-attachments/assets/5ab5050d-920f-48f3-9149-299f9f5238cc" />

También hice un proceso completo:  

Cree un articulo y luego.Presupuesto → Pedido → Entrega → Generar una factura Factura  
<img width="469" height="325" alt="4" src="https://github.com/user-attachments/assets/171bdddd-f531-4209-a81f-77a7472f4e73" />
<img width="400" height="361" alt="5" src="https://github.com/user-attachments/assets/284ab3d4-b8ad-4c3c-b447-6351a9868734" />
### Fase 2: Informes  
No pude terminar el informe de Odoo añadiendo un aviso legal y texto de protección de datos usando XML.

### Fase 3: Exportación  
En esta fase fui a Facturación → Clientes → Clientes
<img width="766" height="596" alt="1" src="https://github.com/user-attachments/assets/d5992126-5e23-4390-84de-7c8ce0251454" />

Luego fui a exportar y en tipo de exportacion le di a "Exportar datos compatibles con importación" con formato CSV y añadir Pais (country_id).
<img width="693" height="577" alt="2" src="https://github.com/user-attachments/assets/ffcf2101-e324-4340-82a5-458a3e3193a7" />

Termine de exportar y consegui el archivo .CSV
<img width="1000" height="225" alt="3" src="https://github.com/user-attachments/assets/b3247182-72d7-4118-9313-686209ed44c6" />
