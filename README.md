# ArcGIS Pro QA Toolkit v0.1

[العربية](README.ar.md)

30 geoprocessing tools for ArcGIS Pro in 5 Python toolboxes (`.pyt`): data quality checks, data management, spatial analysis, cartography and workspace administration. They are designed for a **Basic** licence and need no extension.

## Install

1. Download and unzip this folder.
2. In ArcGIS Pro, open the **Catalog** pane and go to **Toolboxes**. Right-click it, choose **Add Toolbox**, and pick the `.pyt` files in `toolboxes/`.
3. Expand a toolbox and double-click a tool to open it.

Keep each `.pyt.xml` file next to its `.pyt`. These files hold the tool help.

## Tools

**Stable** tools were run in ArcGIS Pro 3.3.2 for v0.1 and passed. **Experimental** tools work, but were not part of the v0.1 validation. Check their results.

| Toolbox | Stable | Experimental |
|---|---|---|
| Data Quality & Validation | Arabic-English Name Check, Positional Accuracy Report (NSSDA/ASPRS), Domain Audit, Multi-Value Code Validator, Near-Miss Value Checker, Join Key Diagnostics | Geometry Quality Checker, QC Scorecard Report, Tile Edge Match Check, Topology Check (Lite), Broken Text Encoding Detector |
| Data Management & Productivity | Dataset Change Report, Excel Import with Field Types, Spatial Numbering, Rule-Based Attribute Update | Coordinate Notation Converter, Pivot Table to Columns, Disperse Stacked Points |
| Spatial Analysis | Thiessen Polygons (Clipped), Polygon Holes and Parts, Boundary Description (Metes and Bounds) | Line Network Rule Check, Vertex Extractor, Rose Diagram, Polygon Shape and Width Metrics, Point Thinning by Priority |
| Cartography & Layout | Map Series Index Check | Map Book Index, Time Series Layout Export |
| Project Automation & Administration | Workspace and CRS Inventory | none |

## Before you rely on it

- Tested with **ArcGIS Pro 3.3.2 on an Advanced licence**. No run on a Basic licence has been done yet.
- Enterprise geodatabase outputs were not tested. Write outputs to a file geodatabase or a folder.
- Each tool's help (in ArcGIS Pro, hover over a parameter or open the tool's help) says what it writes and whether it changes anything.

## Licence

MIT. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md).
