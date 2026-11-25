# Dynamo Structural Generator (V1)

An automated tool for generating structural elements (Grids, Columns, Beams, Floors) in Autodesk Revit using Dynamo and an Excel data-driven approach.

## 🎯 The Problem
Creating structural models manually in Revit is time-consuming and prone to human errors. Modifying grid dimensions requires manually updating multiple elements.

## 💡 The Solution
This Dynamo script reads parameters (Length, Width, Spacing, Height) from an external Excel file and automatically generates:
- A parametric grid system.
- Structural columns at every intersection.
- Structural beams connecting columns.
- A floor slab at the top level.

## 🛠️ Tools Used
- Autodesk Revit 2025
- Dynamo 3.3
- Microsoft Excel

## 🚀 How to use
1. Open Revit and launch Dynamo.
2. Open the `Structural_Generator_V1.dyn` file.
3. Modify the `Parametres_Batiment.xlsx` file to change dimensions.
4. Click "Run" in Dynamo to generate the structure.
