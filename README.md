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

#### 2a. DICOM DeID Intro (Errol)

[DICOM DeID Intro Slides](./2a-DICOM_DeID_Intro_Slides-Errol.pdf)

#### 2b. DICOM DeID and ChatGPT? (George / Adam)

DICOM DeID Attempt Using ChatGPT 5.1:

https://chatgpt.com/share/69286108-b39c-8003-999b-a14601f33e1e

```
For de-identification of DICOM files, what are the safe harbor tags we should make sure to remove PHI from?

Please examine the attached DICOM file:

1. Remove any PHI from the tags

2. Look for any PHI in the pixels (burned into the image)

3. Provide a summary of what you found and performed
```

Video 4x:

https://drive.google.com/file/d/1ZfKl0sSd57rbeA9M2ja4CLsI6UchJWNR/view

Video 1x:

https://drive.google.com/file/d/1FkEWbxpXZjn79U-a4kZN-7U1wrFatL-d/view

#### 2c. RSNA Anonymizer (Adam / Errol)

[RSNA Anonymizer Intro](https://docs.google.com/presentation/d/e/2PACX-1vTAQfrdufd_2TjqiMnwZIYKBnhXUQE1DVrUW7CQ_Va7CteSdIb5ziEO3yxWPnCtaopw0VvvfevNhTt8/pub)

Github: https://github.com/RSNA/Anonymizer


### 3. Radiology Reports and LLMs + Reasoning (Lisa)

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
