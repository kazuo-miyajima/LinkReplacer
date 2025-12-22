# LinkReplacer: Professional Link Migration Tool

### 🛠 Visual Mapping & Batch Replacement for Complex Web Workflows
**"Don't just automate—validate."**
This tool is a specialized utility for web editors to safely migrate or update mass links within HTML/Text documents using an external URL list.

---

## 🚀 Strategic Problem Solving

- **The Challenge:** Replacing large batches of URLs in production code is high-risk. Standard "Find & Replace" can lead to mismatched indices, broken paths, and hours of manual debugging.
- **The Solution:** LinkReplacer implements a **Visual Identification System**. By assigning matched IDs (Red Badges) to both the source and the target list, editors can perform a 100% visual audit before committing any changes.

## ✨ Advanced Features

- **Robust Object-Oriented Design:** Organized into dedicated handlers (`fileHandler`, `linkHandler`, `uiHandler`) for high maintainability and scalability.
- **Hybrid Input Methods:** Supports **Drag & Drop**, **Excel (XLSX) parsing**, and **Direct Clipboard Paste**—optimized for fast-paced editorial workflows.
- **Accessibility & UX Focus:**
    - Full keyboard navigation support via `tabindex` and `Focus/Blur` event handling.
    - Real-time link counting and status reporting.
    - HTML Preview vs. Source Code toggle for instant visual verification.
- **Safety-First Output:** Final code is generated via DOMParser to ensure HTML structural integrity, with a built-in "Copy to Clipboard" success feedback.

## 💻 Technical Excellence

- **Core:** Vanilla JavaScript (ES6+), HTML5, CSS3.
- **Data Handling:** - [SheetJS] for Excel-to-JSON processing.
    - Regex-based link detection for both HTML and raw text formats.
    - `FileReader` & `Blob` API for asynchronous file processing.

---

## 👤 Developer's Philosophy

**Technical Editor | Master of Mechanical Engineering**

My tools are built on the principle of **"Safety Engineering for Content."** Just as a machine requires fail-safes, a content workflow requires visual checkpoints to eliminate human error. I bridge the gap between "Raw Data" and "Final Product" with code that values precision over speed alone.
