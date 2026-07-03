# prueba2
prueba2
mkdir in-the-block
 cd in-the-block cat > index.html <<'EOF' <!DOCTYPE html> <html lang="es">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width,initial-scale=1">
    <title>In The Block</title>
    <link rel="stylesheet" href="styles.css">
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; img-src 'self' data:; style-src 'self' 'unsafe-inline'">
  </head>
  <body>
    <header>
      <h1>In The Block</h1>
      <p>Mi primer sitio publicado con GitHub Pages.</p>
    </header>
    <main>
      <section>
        <h2>Sobre</h2>
        <p>Aquí puedes poner información sobre el proyecto.</p>
      </section>
    </main>
    <footer>
      <p>© 2026 Tu nombre — contacto: placeholder</p>
    </footer>
  </body>
  </html>
  EOF cat > styles.css <<'EOF'
 body { font-family: Arial, sans-serif; margin: 20px; line-height: 1.6; }
 header { background:#f0f0f0; padding:20px; border-radius:6px; }
 h1 { margin:0 0 8px 0; }
 EOF cat > .gitignore <<'EOF'
 .env
 node_modules/
 .key
 EOF cat > SECURITY.md <<'EOF' # Política de seguridad  echo "# In The Block" > README.md
 echo "MIT License" > LICENSE
