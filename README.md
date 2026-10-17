# Easy Step

Free, in-browser **STL → STEP** converter. Your file never leaves your device.

- Repairs the mesh (weld, remove junk triangles, fix winding, fill small holes)
- Merges flat connected triangles into single planar faces (holes preserved)
- Exports a closed STEP solid for Fusion 360, FreeCAD, SolidWorks

## Limits
- Only **planes** are recognised. Cylinders, fillets and freeform surfaces stay as small flat facets.
- Best for mechanical, mostly flat parts. Organic/scanned models export but remain dense.
- STL has no units; the STEP is labelled mm and numbers are unchanged.
- Verify results in your CAD tool before manufacturing. Provided as is, no warranty.

## Dev
Single static `index.html`. Open `index.html#test` and check the console for the self-check.
