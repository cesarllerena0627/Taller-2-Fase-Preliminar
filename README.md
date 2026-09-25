# Arquitectura Empresarial -- Caso de Estudio Sincelejo Comercio Digital

Este repositorio contiene el desarrollo de una **Arquitectura Empresarial utilizando el framework TOGAF (ADM)** para el caso de estudio de **Sincelejo Comercio Digital S.A.S.**, una propuesta de transformación digital enfocada en pequeños comerciantes y micronegocios de Sincelejo.

El objetivo es diseñar una arquitectura que permita **organizar e integrar los procesos de negocio, datos, aplicaciones y tecnología** necesarios para apoyar la gestión comercial de los negocios locales.

---

# Caso de Estudio: Sincelejo Comercio Digital S.A.S.

## 1. Contexto

**Sincelejo Comercio Digital S.A.S.** es una propuesta de plataforma digital orientada a comerciantes independientes, pequeños negocios y micronegocios de Sincelejo.

Actualmente, muchos comerciantes utilizan diferentes herramientas para desarrollar sus actividades comerciales. Las redes sociales son utilizadas para promocionar productos, WhatsApp para recibir pedidos, las transferencias para realizar pagos y la comunicación directa para coordinar los domicilios.

El problema es que estas herramientas funcionan de manera separada, lo que puede generar dificultades para:

- Mantener actualizada la información de los productos.
- Controlar inventarios.
- Gestionar pedidos.
- Verificar pagos.
- Coordinar domicilios.
- Consolidar información de ventas y clientes.

Ante esta situación, se propone una plataforma que permita **integrar estas actividades en un solo flujo comercial**.

La solución busca conectar:

- Comerciantes.
- Consumidores.
- Domiciliarios.
- Servicios tecnológicos.
- Posibles aliados locales.

---

# 2. Desafíos Iniciales

El proyecto parte de diferentes situaciones que afectan la gestión de los pequeños comercios:

- Uso separado de redes sociales, WhatsApp y medios de pago.
- Procesos manuales para gestionar pedidos y domicilios.
- Dificultad para mantener actualizados los inventarios.
- Información de ventas y clientes dispersa.
- Dificultades para verificar los pagos.
- Falta de una herramienta que integre el flujo comercial.
- Necesidad de una solución sencilla para comerciantes que trabajan de manera independiente.

Estos desafíos muestran la necesidad de organizar los procesos y la información mediante una solución tecnológica integrada.

---

# 3. Objetivos del Proyecto de Arquitectura Empresarial

- Organizar e integrar los principales procesos comerciales de la plataforma.
- Alinear las necesidades del negocio con la solución tecnológica.
- Organizar la información de comerciantes, clientes, productos, pedidos, pagos, entregas y ventas.
- Definir las funciones principales de la plataforma.
- Establecer los recursos tecnológicos necesarios para soportar la solución.
- Mantener el desarrollo enfocado en las necesidades del MVP.
- Establecer principios y reglas para organizar las decisiones del proyecto.
- Facilitar el crecimiento futuro de la plataforma.

---

# 4. Flujo del Proceso de Negocio

El flujo principal de la solución busca integrar las actividades que actualmente se realizan mediante diferentes herramientas.

```mermaid
flowchart LR

A[Comerciante] --> B[Publicación de productos]
B --> C[Catálogo digital]

C --> D[Cliente]
D --> E[Realizar pedido]

E --> F[Gestión del pedido]
F --> G[Verificación del pago]

G --> H[Coordinación del domicilio]
H --> I[Domiciliario]

I --> J[Entrega del pedido]

F --> K[Registro de ventas]
K --> L[Análisis de información]
L --> A
