<p align="center">
  <a href="https://github.com/marioaug/mipos-bester-showcase">
    <img src="/assets/logo.jpg" alt="Logo Bester" width="220">
  </a>
</p>

<h1 align="center">miPOS Bester</h1>

<p align="center">
  <strong>Sistema Integral de Punto de Venta y Gestión de Servicio Técnico</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-En%20Producción-0078D4?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white" alt="DigitalOcean">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

---

## 📖 Descripción

**miPOS Bester** es una solución profesional diseñada para optimizar negocios de tecnología. Permite un control exhaustivo de stock, seguimiento de reparaciones y balances de caja en tiempo real, todo bajo una infraestructura escalable en la nube.

El sistema transforma la gestión manual en un flujo digital seguro, eliminando errores humanos en la facturación y el servicio técnico.

## 🚀 Características Principales

* **💳 Punto de Venta (POS):** Facturación ágil con soporte para Efectivo, Tarjeta y QR integrado.
* **🔧 Servicio Técnico:** Gestión completa de reparaciones con estados (Pendiente, Diagnóstico, En Proceso, Entregado). **Bloqueo de entrega por deuda.**
* **📦 Inventario Inteligente:** Alertas de stock bajo, organización por categorías y validación de precios.
* **💰 Control de Caja:** Registro detallado de ingresos, egresos, caja chica y conciliación de tarjetas.
* **🔐 Seguridad:** Autenticación robusta, roles de usuario (Admin/Vendedor) y validación de datos estricta (Zod).

## 🛠️ Stack Tecnológico

El proyecto utiliza una arquitectura moderna y escalable:

<p align="left">
  <a href="https://reactjs.org/" target="_blank">
    <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React">
  </a>
  <a href="https://tailwindcss.com/" target="_blank">
    <img src="https://img.shields.io/badge/UI-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind">
  </a>

  <a href="https://nodejs.org/" target="_blank">
    <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="NodeJS">
  </a>
  <a href="https://expressjs.com/" target="_blank">
    <img src="https://img.shields.io/badge/Framework-Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express">
  </a>

  <a href="https://www.postgresql.org/" target="_blank">
    <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  </a>
  <a href="https://www.prisma.io/" target="_blank">
    <img src="https://img.shields.io/badge/ORM-Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma">
  </a>

  <a href="https://www.digitalocean.com/" target="_blank">
    <img src="https://img.shields.io/badge/Cloud-DigitalOcean-0080FF?style=for-the-badge&logo=digitalocean&logoColor=white" alt="DigitalOcean">
  </a>
  <a href="https://pm2.keymetrics.io/" target="_blank">
    <img src="https://img.shields.io/badge/Process_Manager-PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white" alt="PM2">
  </a>
</p>

<br>

<h2 align="center">📸 Vistazo al Sistema</h2>

<table width="100%" style="border: none;">
  <tr>
    <td width="50%" align="center" valign="top" style="border: none;">
      <p align="center"><b>💳 Punto de Venta Ágil</b></p>
      <img src="https://github.com/user-attachments/assets/bdc647b3-0dbd-4d03-81eb-6ca6c1f64f63" style="border-radius:10px; width: 100%;" alt="POS">
    </td>
    <td width="50%" align="center" valign="top" style="border: none;">
      <p align="center"><b>🔧 Gestión de Taller</b></p>
      <img src="https://github.com/user-attachments/assets/566a7013-4206-476c-87f6-a316053857eb" style="border-radius:10px; width: 100%;" alt="Taller">
    </td>
  </tr>
  <tr>
    <td width="50%" align="center" valign="top" style="border: none;">
      <p align="center"><b>🃏 Conciliación de Tarjetas</b></p>
      <img src="https://github.com/user-attachments/assets/74676eb5-ad09-43ef-af3a-45317980f6c8" style="border-radius:10px; width: 100%;" alt="Tarjetas">
    </td>
    <td width="50%" align="center" valign="top" style="border: none;">
      <p align="center"><b>⚙️ Configuración Admin</b></p>
      <img src="https://github.com/user-attachments/assets/1e5b5663-ddab-4d62-be91-707449cd0eb1" style="border-radius:10px; width: 100%;" alt="Config">
    </td>
  </tr>
</table>

<br>

## 📈 Próximos Pasos (Roadmap)

- [ ] **Reportes Avanzados:** Gráficos de rentabilidad mensual exportables a Power BI.
- [ ] **Automatización:** Notificaciones directas vía Email/WhatsApp del estado de reparaciones.

## ⚙️ Instalación (Dev Mode)

Requisitos: Node.js v18+ y PostgreSQL.

1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/tu-usuario/mipos-bester.git](https://github.com/tu-usuario/mipos-bester.git)
    ```

2.  **Instalar dependencias:**
    ```bash
    cd backend && npm install
    cd ../frontend && npm install
    ```

3.  **Configurar Variables de Entorno (.env):**
    Configurar `DATABASE_URL`, `JWT_SECRET` y puertos.

4.  **Iniciar Servidor:**
    ```bash
    # Backend
    npx prisma generate
    npm run dev

    # Frontend
    npm run dev
    ```

---

## 📬 Contacto / Licencia

Este proyecto es un **software comercial propietario** desarrollado por **Mario Ballester**.
El código fuente aquí expuesto es solo con fines demostrativos (Showcase).

Si te interesa adquirir una licencia de uso para tu negocio o solicitar una demo en vivo:

* 📩 **Email:** [mario_ballester@hotmail.com](mailto:mario_ballester@hotmail.com)
* 💼 **LinkedIn:** [Ver Perfil de LinkedIn](https://www.linkedin.com/in/marioballester10/)

&copy; 2026 Bester POS. Todos los derechos reservados.

<br>

<p align="center">Desarrollado con ❤️ para la optimización de negocios tecnológicos.</p>

<p align="center"><b>Bester Servicio Técnico y Soluciones Digitales a medida</b> - Corrientes, Argentina 2025</p>
