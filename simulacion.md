# =========================
# PERSONA A
# =========================

echo "## Funcionalidades implementadas:" >> README.md
echo "- Catalogo de productos" >> README.md

git add README.md

git commit -m "Actualiza README con funcionalidades"

git push origin main


# =========================
# PERSONA B
# =========================
# (SIN hacer git pull antes)

echo "## Caracteristicas:" >> README.md
echo "- Sistema de pago" >> README.md

git add README.md

git commit -m "Agrega sistema de pago al README"


# Intentar subir cambios
# Aqui aparecera el conflicto

git push origin main


# =========================
# RESOLVER CONFLICTO
# =========================

git pull origin main


# Luego editar README.md manualmente
# y combinar ambas partes


git add README.md

git commit -m "Resuelve conflicto en README"

git push origin main