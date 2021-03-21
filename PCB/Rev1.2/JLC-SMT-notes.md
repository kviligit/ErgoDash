# Documentation
 * "How to generate the BOM and Centroid file from KiCAD"
 https://support.jlcpcb.com/article/84-how-to-generate-the-bom-and-centroid-file-from-kicad
 * "KiCad 5.0 - Editing multiple symbol fields (pre-BOM)"
 https://www.youtube.com/watch?v=uv-lobszo9M
 

# Useful functions in Kicad
1. Click the "table"-symbol named "edit symbol fields"
2. Clicking an element in the footprint-collumn will reveal a library symbol. Click it. 
3. Locate the type of element you are looking for



# Finding parts from JLC 
1. Locate JLC's xls parts library (hereby called JLC parts library):
  jlcpcb.com/parts 
  Located here: 
  <img width="590" alt="Screenshot 2021-03-21 at 20 25 23" src="https://user-images.githubusercontent.com/56066509/111918056-9203bf00-8a83-11eb-8ece-4575b17f3a27.png">
2. Sort by First Category
3. Sort by Second Cat.
4. Sort by Package.
5. Locate the cheapest part (in stock).
6. In Kicad: Locate "edit symbol fields" (see pt. about useful functions in Kicad)
  6.2: Click "add field" in leftmost bottom corner. Important: name it exactly: LCSC
  6.3: Fill in the value from the "LCSC part" collumn in the JLC parts library of the part you chose in pt 5. 
