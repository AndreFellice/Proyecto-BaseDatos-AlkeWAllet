# Proyecto de Base de Datos: AlkeWallet



## Introducción
El proyecto de base de datos AlkeWallet se centra en el diseño e implementación de una base de datos para una aplicación de billetera digital llamada AlkeWallet. Esta aplicación permite a los usuarios gestionar sus fondos y realizar transacciones en diferentes monedas de manera eficiente y segura. La base de datos proporciona la estructura necesaria para almacenar la información de los usuarios, las transacciones y las divisas, así como para gestionar las relaciones entre estas entidades.

## Objetivos del Proyecto
1. Diseñar un esquema de base de datos relacional que cumpla con los requisitos de almacenamiento y gestión de datos de la aplicación AlkeWallet.
2. Implementar el esquema de base de datos en un sistema de gestión de base de datos (SGBD) MySQL para garantizar la integridad y la consistencia de los datos.
3. Desarrollar consultas SQL eficientes para realizar operaciones de recuperación, inserción, actualización y eliminación de datos en la base de datos.
4. Proporcionar una interfaz de usuario intuitiva y segura para que los usuarios puedan interactuar con la aplicación AlkeWallet y realizar transacciones de manera conveniente.

## Componentes Principales
1. **Entidades:**
   - Usuario: Almacena la información personal de los usuarios, como nombre, correo electrónico, contraseña y saldo.
   - Moneda: Representa las diferentes monedas admitidas por la aplicación, con su nombre y símbolo.
   - Transacción: Registra las transacciones realizadas entre los usuarios, incluyendo el importe, la fecha y la divisa utilizada.
   - Billetera: Asocia a cada usuario con las monedas que posee en su billetera digital.

2. **Relaciones:**
   - Realiza: Conecta a los usuarios con las transacciones que han realizado.
   - Contiene: Relaciona las transacciones con los productos involucrados en cada una.
   - Pertenece: Asocia a cada producto con su categoría correspondiente.

## Beneficios del Proyecto
1. **Eficiencia:** Permite a los usuarios realizar transacciones financieras de manera rápida y eficiente en diferentes monedas.
2. **Seguridad:** Garantiza la seguridad de los datos de los usuarios y las transacciones mediante técnicas de cifrado y autenticación.
3. **Escalabilidad:** Facilita la gestión de un gran volumen de usuarios y transacciones a medida que la aplicación crece.
4. **Experiencia del Usuario:** Ofrece una interfaz intuitiva y amigable que mejora la experiencia del usuario al utilizar la aplicación AlkeWallet.

## Enlace al Diagrama de Base de Datos
🔍[Ver Diagrama AlkeWallet](https://github.com/AndreFellice/Proyecto-BaseDatos-AlkeWAllet/blob/main/Diagrama%20BAsedatosAlkeWallet.pdf)

