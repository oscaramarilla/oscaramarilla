<div align="center">

# Oscar Amarilla

### Sistemas comerciales B2B que reemplazan Excel, cotizan solos y cierran por WhatsApp

**Fundador de [AYCweb](https://aycweb.com)** · Infraestructura digital B2B · Asunción, Paraguay 🇵🇾

[![WhatsApp](https://img.shields.io/badge/WhatsApp-Diagn%C3%B3stico%20gratis-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/595985864209?text=Hola%20Oscar%2C%20vengo%20de%20GitHub%20y%20quiero%20un%20diagn%C3%B3stico)
[![AYCweb](https://img.shields.io/badge/aycweb.com-Ver%20soluciones-0B1220?style=for-the-badge&logo=vercel&logoColor=white)](https://aycweb.com)
[![Email](https://img.shields.io/badge/Email-Escribime-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:oscaramarillacaceres@gmail.com)

</div>

---

**Si tu empresa cotiza a mano, pierde pedidos en WhatsApp o depende de un Excel que solo entiende una persona, eso es exactamente lo que construyo.**

No vengo del diseño. Vengo del piso: años como operador en logística, manufactura y compras antes de escribir la primera línea de código. Además dirijo una fábrica de mobiliario con 15 años de historia y contratos públicos — los sistemas que entrego los uso yo primero.

> **8 sistemas en producción · ~670 commits · 1 arquitectura reutilizable** — cotizadores, catálogos, CRMs livianos y automatizaciones de WhatsApp, todos en Next.js + Supabase + Vercel.

---

## 🛠 Qué resuelvo

| Problema del negocio | Lo que entrego | Resultado esperado |
|---|---|---|
| Cotizar lleva horas y cada vendedor calcula distinto | **Motor cotizador** multi-moneda (PYG/USD/BRL), fletes, márgenes, PDF numerado | Cotización en minutos, con un único criterio de precio |
| Los pedidos llegan por WhatsApp y se pierden | **Captura automática de pedidos** con webhooks, allow-list y registro idempotente | Cero pedidos sin registrar, historial por cliente |
| Nadie hace seguimiento después de la venta | **Nurturing y recompra automatizados** (cron + Edge Functions + WhatsApp) | Seguimiento constante sin depender de la memoria del vendedor |
| La web se ve bien pero no genera contactos | **Sitios de captación** con SEO técnico, Schema.org y CTA a WhatsApp | Visitas que se convierten en conversaciones de venta |
| El Excel ya no escala | **Panel interno a medida** (stock, leads, catálogo, presupuestos) | Datos ordenados, sin licencias mensuales por usuario |

---

## 📂 Casos en producción

<table>
<tr>
<td width="50%" valign="top">

### 🏭 [Oriplast Paraguay](https://oriplastpy.com)
**Mobiliario escolar inyectado · Distribución B2B**

Cotizador mayorista multi-moneda con cálculo de fletes, generación de PDF y envío de la cotización por WhatsApp. Catálogo técnico por proveedor.

`Next.js` `TypeScript` `jsPDF` `Vercel`

</td>
<td width="50%" valign="top">

### 🪑 [MetalMadeas](https://www.metalmadeas.com)
**Fabricación nacional de mobiliario escolar e institucional**

Catálogo industrial, cotizador, calculadora de proyectos, showroom y **asistente comercial con IA** que responde consultas técnicas. Blog SEO y sitemap dinámico.

`Next.js` `AI SDK (Gemini)` `SEO` `Vercel Analytics`

</td>
</tr>
<tr>
<td valign="top">

### ⚙️ [AYCweb](https://aycweb.com) — plataforma propia
**Infraestructura agéntica para operaciones B2B**

API de cotización, asistente web con IA, webhooks de cotizaciones, nurturing automático por cron, integración WhatsApp (Kapso), panel de leads, funnels por vertical, i18n y app Android.

`Next.js` `Supabase` `Claude API` `Resend` `Capacitor`

</td>
<td valign="top">

### 🔌 [Shopping AYC Electrónica](https://www.shoppingaycelectronica.com)
**Marketplace de electrónica · Mercado 4**

Directorio de locales con catálogo SEO/GEO y **pedidos automáticos por WhatsApp**: endpoints autenticados (timing-safe), allow-list de contactos y captura idempotente de pedidos. Tests con Vitest.

`Next.js` `Supabase` `Kapso` `Vitest`

</td>
</tr>
<tr>
<td valign="top">

### 💪 [ProteínaSmart](https://proteinasmart.com)
**E-commerce de proteínas y suplementos**

Carrito multi-producto con checkout por WhatsApp, catálogo híbrido (Supabase + fallback local), landings por objetivo y automatización de recompra a 25 días con Edge Function + `pg_cron`.

`Vanilla JS` `Supabase` `Edge Functions` `Schema.org`

</td>
<td valign="top">

### 🧾 [Emprendimientos La Roca](https://emprendimientoslaroca.vercel.app)
**Servicios para hogar, comercio y obra**

Tienda de cámaras y equipos + **generador de presupuestos numerados** con PDF y envío por WhatsApp. Carga masiva de precios desde CSV.

`Next.js` `TypeScript` `PDF` `CSV import`

</td>
</tr>
<tr>
<td valign="top">

### 🦷 [Dra. Bianca Amarilla](https://drabiancapy.com)
**Odontología**

Sitio de captación con solicitud de turnos y agendamiento por WhatsApp.

`Next.js` `Vercel`

</td>
<td valign="top">

### 🩺 Dr. José Lahaye
**Medicina familiar y preventiva**

Sitio para consulta online y presencial, orientado a prevención y longevidad. Construido sobre la plantilla configurable de AYCweb.

`Next.js` `Config-driven`

</td>
</tr>
</table>

---

## 🧱 Una arquitectura, muchos clientes

Todos los proyectos comparten el mismo principio. Por eso un sistema nuevo arranca en días, no en meses, y el cliente puede cambiar precios, textos o teléfonos sin tocar código.

```
Configuración define  →  precios, monedas, teléfonos, textos, reglas por cliente
Dominio decide        →  cálculos comerciales, validaciones, márgenes
Servicios ejecutan    →  PDF, WhatsApp, emails, integraciones, cron
Presentación muestra  →  Next.js: solo dibuja, nunca decide
```

---

## ⚙️ Stack

![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?style=flat-square&logo=vercel)
![WhatsApp API](https://img.shields.io/badge/WhatsApp%20API-25D366?style=flat-square&logo=whatsapp&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

- **Frontend:** Next.js (App Router, Server Components) · TypeScript · Tailwind · shadcn/ui · Core Web Vitals y SEO técnico (Schema.org, sitemaps, i18n)
- **Backend y datos:** Supabase (Postgres, Edge Functions, `pg_cron`) · Zod · webhooks seguros
- **Automatización:** WhatsApp (Kapso / Meta Cloud API) · Resend · generación de PDF · cron jobs
- **IA aplicada:** asistentes comerciales con Claude y Gemini · desarrollo con agentes especializados y skills propios

---

## 🧭 Cómo trabajo

1. **Diagnóstico gratuito (30 min por WhatsApp).** Entender si tu cuello de botella se resuelve con software. Si no, te lo digo.
2. **Propuesta cerrada.** Alcance, precio fijo y plazo. Sin "depende".
3. **Sprints visibles.** Ves avances reales en cada deploy, no presentaciones.
4. **Entrega y soporte.** El sistema queda funcionando y soy responsable de que siga funcionando.

**Buen fit:** *"perdemos 4 horas por día cotizando"*, *"los pedidos se nos pierden en WhatsApp"*, *"el Excel de precios ya no da más"*.
**No es fit:** una web "linda" sin un objetivo comercial claro.

> *El código que no factura no existe. Hecho, deployado y en uso es la única definición de terminado.*

---

<details>
<summary><b>🌎 English summary</b></summary>

<br>

Full-stack engineer (Next.js · TypeScript · Supabase · Vercel) and founder of **AYCweb**, a B2B digital infrastructure firm in Paraguay. I build quoting engines, WhatsApp order automation, internal dashboards and conversion-focused sites for industrial, distribution and healthcare businesses. Background in logistics, manufacturing and procurement — I design software around real commercial operations. 8 production systems built on one reusable, config-driven architecture. Open to LATAM projects and technical collaborations.

</details>

---

<div align="center">

**¿Tu empresa pierde plata por procesos manuales?**

[![Hablemos por WhatsApp](https://img.shields.io/badge/Hablemos%20por%20WhatsApp-%2B595%20985%20864%20209-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/595985864209?text=Hola%20Oscar%2C%20vengo%20de%20GitHub%20y%20quiero%20un%20diagn%C3%B3stico)

<sub><b>AYCweb</b> — Infraestructura digital B2B · Paraguay · Expansión LATAM</sub>

</div>
