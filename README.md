# PLANTILLA EN LATEX PARA OPTOEL
 Plantilla en latex para comunicaciones enviadas a Reuniones del Comité de Optoelectrónica (OPTOEL) de la Sociedad Española de Óptica (SEDOPTICA).
**XIV REUNIÓN OPTOELECTRÓNICA, 2 – 4 julio 2025**  

**Autores:**  
Gorka Zubia Garea¹[![ORCID](https://img.shields.io/badge/orcid-0000-0002 1825 0097-green.svg?logo=orcid&logoColor=white)](https://orcid.org/0000-0002-1825-0097)

¹ Dpto. Expresión Gráfica y Proyectos de Ingeniería, University of the Basque Country UPV/EHU

**Contacto:** gorka.zubia@ehu.eus  

---

## 📄 Manuscrito
- `optoel_plantilla.tex` – Fuente LaTeX completa (preambulo con fancyhdr, geometry, newtx, fontspec, etc.)  
- `optoel_plantilla.pdf` – Ejemplo de Versión final en PDF  

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
