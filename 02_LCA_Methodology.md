# LCA Methodology

## 1. System Boundary Definition

This study applies a cradle-to-construction Life Cycle Assessment (LCA) approach covering modules A1–A5, using the modular framework established by EN 15804+A2.

The assessment focuses on selected structural components and construction activities associated with a hypothetical underground metro station in Copenhagen.

### 1.1 A1–A3: Product Stage

Includes:

- A1: Raw material extraction and processing.
- A2: Transportation of raw materials to manufacturing facilities.
- A3: Manufacturing of construction products.

Environmental impacts will be calculated using product-specific Environmental Product Declarations (EPDs), where available.

**Calculation:**

GWP(A1–A3) = Σ (Material Quantity × EPD Emission Factor)

### 1.2 A4: Transportation to Construction Site

Includes:

- Transportation of ready-mix concrete to the construction site.
- Transportation of reinforcing steel to the construction site.
- Transportation of other included construction materials, where applicable.

**Calculation:**

GWP(A4) = Σ (Material Mass in tonnes × Transport Distance in km × Emission Factor in kgCO₂e/tonne-km)

Transport modes, distances, and emission factors will be documented for each material.

### 1.3 A5: Construction and Installation

Includes:

- On-site construction machinery energy consumption.
- Construction-site electricity consumption.
- Installation-related material losses.
- Relevant construction waste transportation and processing.

**Calculation:**

GWP(A5) = Construction Energy Emissions + Material Loss Emissions + Construction Waste Management Emissions

Excavation activities will be represented using documented simplified assumptions.

### 1.4 Excluded Modules

The following modules are excluded:

- B1–B7: Use stage, maintenance, and operational energy/water.
- C1–C4: Demolition, end-of-life transport, processing, and disposal.
- D: Potential benefits and loads beyond the system boundary.

Consequently, results represent a partial construction-stage assessment, not a complete cradle-to-grave station LCA.

## 2. Double Counting Prevention

To prevent double counting:

1. Product manufacturing emissions will be taken from EPD A1–A3 results without separately adding already included manufacturing processes.
2. Product delivery to the construction site will be calculated under A4, unless included in an applicable EPD module already used.
3. Construction energy, material losses, and construction waste processes will be assigned consistently to A5.
4. Purchased material quantities will include documented installation losses where applicable.
5. Emissions associated with additional material production due to losses will not be counted twice.
6. All emission factors will be checked for declared units, geographical applicability, indicator definitions, and module coverage.

## 3. Environmental Impact Indicator

The primary impact indicator will be Global Warming Potential (GWP), expressed in kgCO₂e.

When comparing EPD products, consistent EN 15804+A2 GWP indicator definitions will be used. Where applicable, GWP-total will be the primary comparison metric.

Results will be reported by:

- Life-cycle module (A1–A3, A4, A5).
- Construction material.
- Construction element.
- Design scenario.

## 4. Data Transparency and Assumptions

Each model input will be classified as:

- **EPD-derived:** Environmental impact data extracted from a documented EPD.
- **Public secondary data:** Data from publicly available technical references.
- **Synthetic:** Hypothetical construction quantities or scenario values.
- **Assumed:** Simplifying parameters used when measured data are unavailable.

Each calculation will retain its source reference, unit, assumption, and applicable life-cycle module.