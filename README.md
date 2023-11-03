Dataset: https://www.dropbox.com/s/p51wpvtpf9to438/SROIE.zip?dl=1


In order for a machine to extract data from physical documents, optical character recognition (OCR) technologies are used. The most common OCR engine before the development of neural networks was the Tesseract engine. In addition to it, popular products from ABBYY, such as ABBYY FineReader, are also widely used. However, there are other OCR tools that are less known to the general public.

There is also the development of the Chinese search engine Baidu PaddleOCR. This library is written in Python and provides access to a large number of models for text recognition in various languages.
![image](https://github.com/AILogoSkill/Check_Reader/assets/144710374/75e990b1-fc06-4df8-9b40-de0f250f87af)
![image](https://github.com/AILogoSkill/Check_Reader/assets/144710374/6453b34e-e1a3-4eac-ac25-c61634c9db7d)

Practically the entire receipt was recognized with high confidence. Some of the errors include: the account number was not found, and an opening bracket in the number was missed

Let's check the receipt recognition in Russian:
![image](https://github.com/AILogoSkill/Check_Reader/assets/144710374/3bafc3ba-e058-467d-b11e-4fcbeefc08f0)
![image](https://github.com/AILogoSkill/Check_Reader/assets/144710374/bf7330b8-ec7f-495d-a3b9-927f1ce1e711)
![image](https://github.com/AILogoSkill/Check_Reader/assets/144710374/d057d812-4f78-41d4-a6c2-14f94b5ea2da)


Based on the results obtained, it seems that the Russian PaddleOCR model is unable to recognize not only Russian text but also numbers. An interesting fact is that the English model recognized all the digits and correctly assembled all the semantic blocks (e.g., "Transaction Amount" and others).

![image](https://github.com/AILogoSkill/Check_Reader/assets/144710374/090719dd-eeb5-4290-b224-33b139e6500a)





