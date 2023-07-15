Lo siguiente es el readme oficial del proyecto de Next js, mas adelante se encuentran los pasos que se siguieron durante la construccion del proyecto:

---

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

---

## configuracion del proyecto:
para configurar el proyecto se siguieron los siguientes pasos:

- Generar el proyecto con npx create-next-app
- Integrar el workflow Node.js
- Configurar el runner (este paso se hizo desde linux)
- Instalar y configurar pm2 para iniciar automaticamente el runner
- Integrar `pm2 reload 0` en el node.js.yml para ejecutar automaticamente el runner en cada `push`

### Implementación y Pruebas en Producción

Para implementar y probar el sitio web en producción, se utilizó Netlify. Puedes acceder al sitio implementado en https://neon-mermaid-f83e7f.netlify.app/.

---

### Recursos Adicionales
- Tutorial: https://www.youtube.com/watch?v=pgoZFKgoiDk
- Next.js: https://nextjs.org/
- create-next-app: https://github.com/vercel/next.js/tree/canary/packages/create-next-app
- Documentación de Next.js: https://nextjs.org/docs
- Aprende Next.js: https://nextjs.org/learn
- Repositorio de Next.js en GitHub: https://github.com/vercel/next.js/
- Plataforma Vercel: https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme
- Documentación de Implementación de Next.js: https://nextjs.org/docs/deployment
