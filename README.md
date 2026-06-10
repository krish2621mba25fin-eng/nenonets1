# Invoice Data Extraction Pipeline

An automated data extraction system that parses unstructured invoice images and structuralizes specific fields into an Excel format.

---

## 📸 Execution Results

The pipeline successfully processes the input document and maps the targeted fields into a structured spreadsheet layout.

### 1. Input Document (`Screenshot 2026-06-10 145608.png`)
Below is the source invoice processed by the pipeline:

<p align="left">
  <img src="Screenshot 2026-06-10 145608.png" alt="Source Invoice" width="550">
</p>

### 2. Output Generated (`Screenshot 2026-06-10 145700.png`)
Below is the resulting Excel spreadsheet containing the extracted data:

<p align="left">
  <img src="Screenshot 2026-06-10 145700.png" alt="Extracted Excel Output" width="650">
</p>

---

## 🛠️ Extraction Schema Mapping

The following table defines how visual fields from the invoice are structured into the final Excel document:

| Target Field | Source Location | Value Extracted (Example) |
| :--- | :--- | :--- |
| **Invoice Number** | Top Right Header | `USF-INV-10234` |
| **Buyer Company** | Buyer Section | `Cloud Kitchens` |
| **Item Description** | Main Table Rows | `Chilled Poultry Fillets`, `Organic Fresh Spinach`, etc. |

---

## 🚀 Getting Started

1. **Place your source images** in the root directory.
2. **Ensure filenames match exactly**:
   * Input: `Screenshot 2026-06-10 145608.png`
   * Output: `Screenshot 2026-06-10 145700.png`
3. Push the changes to GitHub, and the images will render automatically above.
