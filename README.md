# 1. Clona el repo (si no lo tienes local)
git clone https://github.com/JCGT1976/Deadpool.git
cd Deadpool

# 2. Edita el README.md con el nuevo contenido
cat > README.md << 'EOF'
# Deadpool

Repositorio del proyecto **Mi Technologies** — Sistema de acceso a reporte financiero confidencial.

## 📁 Archivos

| Archivo | Descripción | Ver en GitHub |
|---|---|---|
| `index.html` | Pantalla de login principal con encriptación AES | [Ver archivo](https://github.com/JCGT1976/Deadpool/blob/main/index.html) |
| `index_4.html` | Versión alternativa del index | [Ver archivo](https://github.com/JCGT1976/Deadpool/blob/main/index_4.html) |
| `MiTech_Reporte_Protegido.html` | Reporte financiero protegido | [Ver archivo](https://github.com/JCGT1976/Deadpool/blob/main/MiTech_Reporte_Protegido.html) |

## 🔗 Vista rápida
- 📄 **index.html:** https://github.com/JCGT1976/Deadpool/blob/main/index.html

## 🛠 Tecnologías
- HTML5 / CSS3 / JavaScript
- Supabase (autenticación)
- SheetJS / xlsx
- Encriptación AES
EOF

# 3. Sube el cambio
git add README.md
git commit -m "docs: actualizar README con rutas de archivos"
git push origin main# Deadpool
