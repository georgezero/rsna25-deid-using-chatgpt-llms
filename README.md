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

[DICOM DeID Intro](https://docs.google.com/presentation/d/e/2PACX-1vTGlnzq3YexTETD_o0HlK-yxzZGN4wLaWpoHX0FsM_suCIeB4W2IBepnErUsdgEIcx8DifzXQg9ei0O/pub)

[DICOM DeID Intro PDF](./2a-DICOM_DeID_Intro_Slides-Errol.pdf)

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

#### Quickstart

Use these preconfigured ChatGPT conversations to run the lab without creating an API key:

- [DICOM header explanation and deidentification](https://chatgpt.com/share/692b2713-2300-8002-8085-8ac8c59e7756)
- [Radiology report PHI detection and graded deidentification](https://chatgpt.com/share/692b2828-355c-8002-a551-3b70a893d9c4)
- [Combined header and report audit after partial deidentification](https://chatgpt.com/share/692b2903-e210-8002-b572-99aad8908ccf)

#### Interactive notebooks

- [PHI identification on DICOM images](https://colab.research.google.com/drive/1694fyXblSNPVu0b4UXt7EQPOgJb7IBAe?usp=drive_link)
- [PHI identification in report texts](https://colab.research.google.com/drive/1Bh0kKnDTGYxFX3drJren51d5lgo8Y020#scrollTo=C_DwF8uKDzzp)
- [Error detection in report texts](https://colab.research.google.com/drive/1CGbaoSeOHIpPg_ar5Myv3vcHh8WLF6ZE#scrollTo=398eb4a8)

### 4. Vision Language Models in Radiology (Sonali)

#### Using chain-of-thought prompting to gain more explainable VLMs 

https://chatgpt.com/share/692ca218-d9e8-8004-941b-ef7323e4d763 

#### Using visual cue prompting to gain more visually grounded explanations 

https://chatgpt.com/share/692ca291-38e8-8004-b293-ac2ebe1f0136

#### Using structured, section-by-section comparison prompting between inputted X-rays and normal chest X-rays to see key deviations 

https://chatgpt.com/share/692ca351-97a8-8004-bc55-48ceec0eb6cf 

#### Pixel deid using ChatGPT

https://chatgpt.com/share/692c5959-0a80-8003-b121-13d6469b982f

| Chest Xray  |  Ultrasound   |  CT Abdomen  |
|:-----------:|:-------------:|:------------:|
|[![chest-xray](images/4b.%20[Hands-On]%20DICOM%20Image%20exploration/chest-xray.png)](images/4b.%20[Hands-On]%20DICOM%20Image%20exploration/chest-xray.png) | [![ultrasound](images/4b.%20[Hands-On]%20DICOM%20Image%20exploration/ultrasound.png)](images/4b.%20[Hands-On]%20DICOM%20Image%20exploration/ultrasound.png) | [![ct-abdomen](images/4b.%20[Hands-On]%20DICOM%20Image%20exploration/ct-abdomen.png)](images/4b.%20[Hands-On]%20DICOM%20Image%20exploration/ct-abdomen.png) |


---

### Contact

`george5@xsd.ai`
