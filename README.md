# Fake-news-detection-using-ML-and-NLP
                                                         ABSTRACT 
 
 
                      In today’s digital era, information dissemination has become rapid and accessible through 
                      various online platforms. However, this ease of sharing information has also led to the 
                      widespread circulation of fake news, causing significant impacts on public opinion, social 
                      stability, and political processes. The detection and prevention of fake news have become 
                      critical to maintaining the integrity of information in society. This project aims to develop 
                      a machine learning-based system capable of detecting fake news from both typed text and 
                      image-based news content. To address real-world scenarios where news is often shared as 
                      images (such as screenshots and posters), the system integrates Optical Character 
                      Recognition (OCR) using pytesseract to extract textual data from images. The extracted 
                      or directly entered text is then pre-processed using a TfidfVectorizer, converting it into 
                      numerical features, and classified as real or fake using a Linear Support Vector Classifier 
                      (Linear SVC) model. A lightweight and user-friendly Flask web application is developed 
                      to facilitate easy user interaction, allowing users to either type the news content or upload 
                      an image for verification. Additionally, a simple user authentication system using SQLite 
                      is implemented to manage user registration and login functionalities. The results 
                      demonstrate that combining OCR with machine learning techniques offers an effective 
                      approach to detecting fake news across multiple input formats. The system provides a 
                      scalable and practical solution, bridging the gap between traditional text-only detection 
                      systems and the diverse formats of misinformation encountered in real-world digital 
                      communication.
