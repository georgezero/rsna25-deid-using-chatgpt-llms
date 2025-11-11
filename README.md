# RSNA 2025 - DeID using ChatGPT and LLMs

### Deep Learning Lab Session - DLL02
### Sunday Nov 30th
#### 2:30-3:30 PM CST

## Speakers

- George Shih
- Errol Colak
- Lisa Adams
- Sonali Sharma
- Adam Flanders

## Outline

### 1. Session Intro 

### 2. DICOM Deid 

#### 2a. DICOM Intro (Errol)

#### 2b. DICOM DeID and ChatGPT? (George / Adam)

#### 2c. RSNA Anonymizer (Adam)

### 3. Radiology Reports and LLMs + Reasoning (Lisa)

- Finding PHI in reports
- Finding errors in reports

### 4. Vision Language Models in Radiology (Sonali)

---
### Additional Examples


:bulb: Example prompts:

**DICOM Metadata**

```
Tell me about a bit about the patient and the exam performed.
```
```
Analyze the DICOM metadata and give me all the values that contain personal health information.

Show this in a table format.
```
```
Identify all the DICOM metadata containing potential personal health information (PHI).
These can be directly identifying information (such as name, unique ID, etc)or indirectly
identifying information (such as demographic, other ID, etc).

Do not include fields that does not have a PHI risk such as technical details.

Show this in table format with the field name and value.
```
```
Deidentify the DICOM metadata containing personal health information using fake information.

Show the values before and after in table format.
```
```
Anonymize all the potential personal health information in the DICOM metadata.

Show the values before and after in table format.
```
     
**Radiology Report**
```
Analyze the radiology report and give me a list of all the personal health information.
```
```
Anonymize all the potential personal health information on the radiology report.
```

---

### Contact

`george5@xsd.ai`
