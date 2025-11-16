rimary language: **Python**  
Future: Optional **MATLAB bindings**

---

## 🗂 Repository Structure (Current, Post-Legacy Cleanup)

The legacy QUANTUS backend and GUI repositories have been removed.  
The active codebase now follows a **plugin-based architecture**:

### **1. QUANTUS Core (GUI)**   
**Role:**  
- Main user interface  
- Central integration layer for all plugins  
- Unified GUI for QUS, CEUS, and future modules  

---

### **2. QUANTUS QUS Plugin**  
**Role:**  
- Core QUS algorithms and processing  
- GUI components are merged into the main QUANTUS GUI  
- Internal-only components (TUL/Sirlin separation) removed where needed  

---

### **3. QUANTUS CEUS Plugin**  
**Role:**  
- CEUS-specific analysis and processing  
- GUI parts are merged into core QUANTUS  
- Follows the same plugin interface as the QUS module  
