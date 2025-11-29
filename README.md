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

## Quickstart

Use these preconfigured ChatGPT conversations to run the lab without creating an API key:

- [DICOM header explanation and deidentification](https://chatgpt.com/share/692b2713-2300-8002-8085-8ac8c59e7756)
- [Radiology report PHI detection and graded deidentification](https://chatgpt.com/share/692b2828-355c-8002-a551-3b70a893d9c4)
- [Combined header and report audit after partial deidentification](https://chatgpt.com/share/692b2903-e210-8002-b572-99aad8908ccf)

## Interactive notebooks

Interactive Notebooks
- [PHI identification on DICOM images](https://colab.research.google.com/drive/1694fyXblSNPVu0b4UXt7EQPOgJb7IBAe?usp=drive_link)
- [PHI identification in report texts](https://colab.research.google.com/drive/1Bh0kKnDTGYxFX3drJren51d5lgo8Y020#scrollTo=C_DwF8uKDzzp)
- [Error detection in report texts](https://colab.research.google.com/drive/1CGbaoSeOHIpPg_ar5Myv3vcHh8WLF6ZE#scrollTo=398eb4a8)

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
