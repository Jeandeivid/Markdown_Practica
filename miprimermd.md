cat > miprimermd.md <<EOF
# Título principal

## Subtítulo

Este es un párrafo con **negrita**, *cursiva* y \`código\`.

\`\`\`python
print("Hola Markdown")
\`\`\`

1. Elemento ordenado 1  
2. Elemento ordenado 2  
3. Elemento ordenado 3  

- Elemento desordenado A  
- Elemento desordenado B  
- Elemento desordenado C  

[Visitar GitHub](https://github.com)  

[Enlace a otro archivo](otroarchivo.md)  

![Logo Markdown](https://markdown-here.com/img/icon256.png)  

| Nombre | Edad | Ciudad |
|--------|------|--------|
| Ana    | 23   | Madrid |
| Luis   | 30   | Sevilla |
| Marta  | 27   | Valencia |
EOF

cat > otroarchivo.md <<EOF
# Archivo secundario

Este es el **otro archivo Markdown** que sirve para comprobar el enlace interno desde \`miprimermd.md\`.

Puedes volver al archivo principal aquí:  
[Volver a miprimermd.md](miprimermd.md)
EOF
