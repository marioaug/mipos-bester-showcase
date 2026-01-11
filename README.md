<p align="center">
  <a href="https://github.com/marioaug/mipos-bester">
    <img src="frontend/public/assets/logo.jpg" alt="Logo Bester" width="220">
  </a>
</p>

<h1 align="center">miPOS Bester</h1>

<p align="center">
  <strong>Sistema Integral de Punto de Venta y Gestión de Servicio Técnico</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-En%20Producción-0078D4?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/AWS-EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="AWS">
  <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

📖 Descripción

miPOS Bester es una solución profesional diseñada para optimizar negocios de tecnología. Permite un control exhaustivo de stock, seguimiento de reparaciones y balances de caja en tiempo real, todo bajo una infraestructura escalable en la nube.

🚀 Características Principales

💳 Punto de Venta (POS): Facturación ágil con soporte para Efectivo, Tarjeta y QR.

🔧 Servicio Técnico: Gestión completa de reparaciones con estados (Pendiente, Proceso, Entregado).

📦 Inventario Inteligente: Alertas de stock bajo y organización por categorías.

💰 Control de Caja: Registro detallado de ingresos, egresos y conciliación de tarjetas.

🔐 Seguridad: Autenticación por roles para administradores y vendedores.

🛠️ Stack Tecnológico

<p align="left"> <a href="https://reactjs.org/" target="_blank"> <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"> </a> <a href="https://tailwindcss.com/" target="_blank"> <img src="https://img.shields.io/badge/UI-Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind"> </a>


<a href="https://nodejs.org/" target="_blank"> <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="NodeJS"> </a> <a href="https://expressjs.com/" target="_blank"> <img src="https://img.shields.io/badge/Framework-Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"> </a>


<a href="https://www.postgresql.org/" target="_blank"> <img src="https://img.shields.io/badge/Database-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"> </a> <a href="https://www.prisma.io/" target="_blank"> <img src="https://img.shields.io/badge/ORM-Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" alt="Prisma"> </a>


<a href="https://aws.amazon.com/ec2/" target="_blank"> <img src="https://img.shields.io/badge/Cloud-AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white" alt="AWS"> </a> <a href="https://pm2.keymetrics.io/" target="_blank"> <img src="https://img.shields.io/badge/Process_Manager-PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white" alt="PM2"> </a> </p>

📸 Vistazo al Sistema

<table width="100%"> <tr> <td width="50%"> <p align="center"><b>💳 Punto de Venta Ágil</b></p> <img src="https://github.com/user-attachments/assets/bdc647b3-0dbd-4d03-81eb-6ca6c1f64f63" style="border-radius:10px;"> </td> <td width="50%"> <p align="center"><b>🔧 Gestión de Taller</b></p> <img src="https://github.com/user-attachments/assets/566a7013-4206-476c-87f6-a316053857eb" style="border-radius:10px;"> </td> </tr> <tr> <td width="50%"> <p align="center"><b>🃏 Conciliación de Tarjetas</b></p> <img src="https://github.com/user-attachments/assets/74676eb5-ad09-43ef-af3a-45317980f6c8" style="border-radius:10px;"> </td> <td width="50%"> <p align="center"><b>⚙️ Configuración Admin</b></p> <img src="https://github.com/user-attachments/assets/1e5b5663-ddab-4d62-be91-707449cd0eb1" style="border-radius:10px;"> </td> </tr> </table>

📈 Próximos Pasos (Roadmap)

[ ] Integración Mercado Pago: Webhooks para conciliación automática de QR.

[ ] Reportes Avanzados: Gráficos de rentabilidad mensual en power BI.

[ ] Automatización: Notificaciones directas vía Email/SMS del estado de reparaciones.

⚙️ Instalación Rápida
Requisitos: Node.js v24.11.1+ y PostgreSQL 15.15+.

Backend:

Bash
npm install && npx prisma generate && npm run build
pm2 start dist/server.js --name "mipos-backend"

<p align="center">Desarrollado con ❤️ para la optimización de negocios tecnológicos.</p>

<p align="center"><b>Bester Servicio Técnico</b> - Corrientes, Argentina 2025</p>
