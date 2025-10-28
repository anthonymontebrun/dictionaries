# GLPI Dictionaries Rules

## Description
This repository provides a **set of preconfigured dictionary rules** for GLPI. These rules can be imported directly via the **`Administration > Dictionaries`** menu to standardize or modify data entered in GLPI (e.g., software names, manufacturers, or titles).

---

## Features
- **Ready-to-use rules** : XML files for common use cases (software, manufacturers, etc.).
- **Extensible** : Rules can be customized or extended to fit specific needs.

---

## Installation
### Step-by-Step Guide
1. **Download the XML file(s)** :
   - Navigate to the [`xml_import/`](xml_import/) directory in this repository.
   - Download the file(s) corresponding to the dictionary rules you need.

2. **Import into GLPI** :
   - Go to **`Administration > Dictionaries`**.
   - Click the **`Import`** button.
   - Select the downloaded XML file and confirm the import.

3. **Verify the import** :
   - After importing, check that the rules appear in the list and are **active**.
   - Test the rules by creating or updating an item (e.g., a software entry) to ensure the dictionary applies as expected.
