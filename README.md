# VisitExpressions
useful expressions for visualization of Nek5000/NekRS outputs in Visit (Reynolds stress tensor, anisotropy maps, etc.)

Expressions include:
* Reynolds stress tensor (Rij)
* Turbulent kinetic energy (TKE)
* Anisotropy tensor (aij)
* Eigenvalues of anisotropy tensor (aijeigs)
* Various barycentric mappings for the anisotropy invariants, as in Emory and Iaccarino (2014)...each "colors*.xml" is a different color scheme

NOTES ON USAGE:
This is based on the standard naming convention from avg_all, i.e. "avg<case>.f*", "rms<case>.f*", "rm2<case>.f*". The files should be read in before applying the expressions.
Most of the expressions can be plotted using a Pseudocolor plot, but the "colors*.xml" expressions should be plotted as TrueColor plots.
