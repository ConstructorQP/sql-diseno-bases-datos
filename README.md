# Diseño de bases de datos con MySQL

Scripts SQL de la asignatura *Gestión de Bases de Datos* (ASIR). Recorren el diseño de una base de datos desde cero: esquemas, tablas, tipos de datos, restricciones y relaciones.

## Contenido

Los scripts están numerados en orden de aprendizaje:

| Script | Tema |
|---|---|
| `01` – `03` | Crear y borrar esquemas y bases de datos |
| `04` – `06` | Crear tablas (usuarios, clientes) y vaciar datos |
| `07` – `08` | Ejercicio de empresa y `ALTER TABLE` |
| `09` – `011` | Restricciones (`CONSTRAINT`), tipo `ENUM` y campos calculados |
| `012` – `013` | Claves foráneas e integridad referencial |
| `014` – `015` | Claves primarias compuestas y claves únicas |
| `RESTAURANTE_1.1.sql` | Proyecto completo: base de datos de un restaurante con clientes, pedidos y relaciones |
| `DEBERESGBD.sql` | Ejercicio de fabricantes y artículos |

## Tecnologías

MySQL / MariaDB · SQL (DDL y DML) · utf8mb4

## Cómo usarlo

Abre cualquier script en MySQL Workbench, DBeaver o la consola y ejecútalo:

```bash
mysql -u root -p < RESTAURANTE_1.1.sql
```

## Relacionado

Las consultas sobre estas bases de datos (`SELECT`, `JOIN`, subconsultas…) están en [sql-consultas](https://github.com/ConstructorQP/sql-consultas).
