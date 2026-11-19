## Archivos KiCad ##

Proyecto realizado con **KiCad 10.0**. Abrir `CESE RABG.kicad_pro`.

* `CESE RABG.kicad_pro`: proyecto.
* `CESE RABG.kicad_sch`: esquemático. Cada símbolo tiene sus campos *Datasheet* y *MPN*.
* `CESE RABG.kicad_pcb`: PCB (pendiente de diseño).
* `lib/CESE_RABG.kicad_sym`: biblioteca de símbolos propia (TPS61023), registrada en `sym-lib-table` con la ruta relativa `${KIPRJMOD}`.
* `salidas/`: archivos generados.
  * `BOM.csv`: lista de materiales agrupada por valor y MPN.
  * `esquematico.pdf`: esquemático en PDF.

Las huellas y los modelos 3D son los de las bibliotecas estándar de KiCad. Si se agregan modelos o huellas propias, irán en `lib/` (por ejemplo `lib/3d/`).
