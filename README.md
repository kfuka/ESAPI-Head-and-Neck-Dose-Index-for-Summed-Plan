# ESAPI-Head-and-Neck-Dose-Index-for-Summed-Plan
This is the script written in C# which is intended to use in Eclipse(Varian, Inc.)
This works like,

1. Pick summed plan, structure set and dose in scope
2. Calculate dose the indices (maximum dose or mean dose or D**% or etc.)
3. Calculate Lyman-Kutcher-Burman's NTCP using DVH and trapezoidal integration.
4. Visualize these indices and judge (O or X) according to the criteria which is determined by the user.
