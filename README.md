# ManikantaPortfolio

## [Project1: OCR and Tesseract : Project overview](https://github.com/manikantamaka/OCR)
.Extracting text from Images and pdf etc
.you must know the difference between OCR and PyTessract
##### OCR
.OCR is a technology to convert handwritten, typed, scanned text, or text inside images to machine-readable text
.You can use OCR on any image files containing text or a PDF document or any scanned document, printed document, or handwritten document that is legible to extract text
.Eliminating manual data entry by digitizing printed documents like reading passports, invoices, bank statements, etc.
.Create secure access to sensitive information by digitizing Id cards, credit cards, etc
.you can use any pdf's
##### Extracting text from Images
.Reading a Text from an Image
.You will use pytesseract, which a python wrapper for Google’s tesseract for optical character recognition (OCR), to read the text embedded in images.
.You will need to understand some of the configuration options that can be applied using pytesseract
.You can refer this https://pypi.org/project/pytesseract/

## [Project2: Overview for to create a Simple ChatBot from scratch : Project Overview](https://github.com/manikantamaka/ChatBot)
.Import necessary libraries
.Downloading and installing NLTK
.Reading in the corpus( Here I'm using the Wikipedia page for chatbots as our corpus. Copy the contents from the page and place it in a text file named ‘chatbot.txt’. However, you can use any corpus of your choice)
#### Next step, Need to convert all text into Machine readable language:
.Converting the entire text into uppercase or lowercase
.Tokenization
.Removing Noise 
.Stop words
.Stemming,Lemmatization(This is Normalisation)
.Keyword matching(we shall define a function for a greeting by the bot i.e if a user’s input is a greeting, the bot shall return a greeting response.ELIZA uses a simple .keyword matching for greetings. We will utilize the same concept here)
.Bag of Words
#### TF-IDF Approach
.Term Frequency: is a scoring of the frequency of the word in the current document.

.TF = (Number of times term t appears in a document)/(Number of terms in the document)
Inverse Document Frequency: is a scoring of how rare the word is across documents.

IDF = 1+log(N/n), where, N is the number of documents and n is the number of documents a term t has appeared in.
#### Cosine Similarity
.Tf-idf weight is a weight often used in information retrieval and text mining. This weight is a statistical measure used to evaluate how important a word is to a document in a collection or corpus.
.To generate a response from our bot for input questions, the concept of document similarity will be used. We define a function response which searches the user’s utterance for one or more known keywords and returns one of several possible responses. If it doesn’t find the input matching any of the keywords, it returns a response:” I am sorry! I don’t understand you”
#### Finally the basic chatbot is ready :)
 .we will feed the lines that we want our bot to say while starting and ending a conversation depending upon user’s input.


## [Project3:  Yolo v3 Object-Detection: Project overview](https://github.com/manikantamaka/Object-Detection)

Important Note:
I Assume you know know what is Object-Detection and Object-Recognition and their Algorithms, Archiechtures(VGG16, AlexNet, ResNet etc), and Pre-Trained Weigths models(COCO, CIFAR-10 etc) we are using those models in Transfer Learning.

### Please Download Yolo3.Weigths, I cannot upload the file here, coz its too large

.Object Detection tells you which objects are present in the image, it also outputs bounding boxes (x, y, width, height) to indicate the location of the objects inside the image.
.Before Going to this, first of all you should know about what is Object Detection and Object recognition
.The difference between object detection algorithms and classification algorithms is that in detection algorithms, we try to draw a bounding box around the object of interest to locate it within the image. Also, you might not necessarily draw just one bounding box in an object detection case, there could be many bounding boxes representing different objects of interest within the image and you would not know how many beforehand.
#### Object Recognition:
.An object recognition algorithm identifies which objects are present in an image. It takes the entire image as an input and outputs class labels and class probabilities of objects present in that image. For example, a class label could be “dog” and the associated class probability could be 97%.
#### Object Recognition
.Object Detection algorithm not only tells you which objects are present in the image, it also outputs bounding boxes (x, y, width, height) to indicate the location of the objects inside the image.
.And most important you must know about, Sliding Window Algorithm, Region Proposal Algorithms, Selective Search for Object Recognition
