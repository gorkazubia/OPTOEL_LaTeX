# PLANTILLA EN LATEX PARA COMUNICACIONES DEL COMITÉ DE OOPTOELECTRÓNICA (OPTOEL) DE LA SOCIEDAD ESPAÑOLA DE ÓPTICA (SEDOPTICA), 
 Análisis exhaustivo y modelo simplificado de un sensor de fibra óptica para desplazamiento angular  
**XIV REUNIÓN OPTOELECTRÓNICA, 2 – 4 julio 2025**  

**Autores:**  
Gorka Zubia
¹ Dpto. Expresión Gráfica y Proyectos de Ingeniería, University of the Basque Country UPV/EHU
**Contacto:** gorka.zubia@ehu.eus  

---

## 📖 Resumen  

---

## 📄 Manuscrito
- `optoel_plantilla.tex` – Fuente LaTeX completa (preambulo con fancyhdr, geometry, newtx, fontspec, etc.)  
- `Zubia25_OPTOEL.pdf` – Ejemplo de Versión final en PDF  

---

## 🔧 Cómo compilar  
1. **Requisitos**  
   - TeX Live 2024 (o MikTeX) con paquetes: `newtx`, `fontspec`, `fancyhdr`, `geometry`, `babel`, `biblatex`, etc.  
2. **Compilar**  
   ```bash
   pdflatex manuscript.tex
   bibtex    manuscript      # si usas BibTeX
   pdflatex manuscript.tex
   pdflatex manuscript.tex
   
o bien

  latexmk -pdf manuscript.tex
