# Co.Carter Stock - MVP

Aplicación web privada para gestionar stock de ropa de bebés.

## Cómo ejecutarlo en tu netbook

1. Instalá Node.js LTS desde nodejs.org.
2. Abrí CMD dentro de esta carpeta.
3. Ejecutá:

```bash
npm install
npm run dev
```

4. Abrí el link que aparece, normalmente:

```bash
http://localhost:5173
```

## Usuarios demo

- admin / admin123
- vendedor / venta123
- deposito / stock123

## Subir a GitHub

```bash
git init
git add .
git commit -m "MVP Co.Carter Stock"
git branch -M main
git remote add origin TU_URL_DE_GITHUB
git push -u origin main
```

## Subir a Vercel

1. Subí el proyecto a GitHub.
2. Entrá a Vercel.
3. Importá el repositorio.
4. Framework: Vite.
5. Build command: `npm run build`
6. Output directory: `dist`

## Importante

Esta versión guarda datos en el navegador con localStorage para probar el MVP.
Para producción real con varios usuarios, base de datos y actualización en vivo, el próximo paso es conectar Supabase.
