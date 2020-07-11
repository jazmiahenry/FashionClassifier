# FashionClassifier
This classifier was created to identify fashion styles between four categories: grunge, streetwear, haute couture, and preppy. It was created using Nanonets API. The Training_Model_Nanonets_API file shows the code used to deploy the Nanonets API wrapper to my training model and the Fashion styles file shows the trained model. Here's how I did it:

1. Create API using Nanonets
    >git clone https://github.com/NanoNets/image-classification-sample-python.git
    >cd image-classification-sample-python,
    >sudo pip install requests
    
2. Download 1000 photos using Fatkun Batch Download Chrome extension
    
    A. Create four folders by fashion syle:
            - Preppy
            - Streetwear
            - Grunge
            - Haute Couture
            
    B. Input code into Training_Model file
   
3. Train Model with four fashion styles using 1000 photos:

            - Preppy
            - Streetwear
            - Grunge
            - Haute Couture
 
4. API accuracy: 79.45206%

*Example:

![2Q__ (6)](https://user-images.githubusercontent.com/48301423/87227105-97423300-c366-11ea-9c09-a23e243be034.jpg)
* {"message":"Success","result":[{"message":"Success","prediction":[{"label":"streetwear","probability":0.96925855},{"label":"grunge","probability":0.21886736},{"label":"haute_couture","probability":0.01011632},{"label":"preppy","probability":0.004824163}],"file":"2Q__ (6).jpg"}]}

![images - 2020-06-29T193244 762](https://user-images.githubusercontent.com/48301423/87227275-e89ef200-c367-11ea-9c60-829798da6013.jpg)
* {"message":"Success","result":[{"message":"Success","prediction":[{"label":"grunge","probability":0.85924125},{"label":"preppy","probability":0.07808834},{"label":"haute_couture","probability":0.048710093},{"label":"streetwear","probability":0.022214254}],"file":"images - 2020-06-29T193244.762.jpg"}]}

![images - 2020-06-29T194709 118](https://user-images.githubusercontent.com/48301423/87227195-5696e980-c367-11ea-9a8e-9bf3f36ab310.jpg)
* {"message":"Success","result":[{"message":"Success","prediction":[{"label":"preppy","probability":0.9066279},{"label":"streetwear","probability":0.12773524},{"label":"grunge","probability":0.0410224},{"label":"haute_couture","probability":0.012403343}],"file":"images - 2020-06-29T194709.118.jpg"}]}

![images - 2020-06-29T195702 227](https://user-images.githubusercontent.com/48301423/87227233-a4135680-c367-11ea-9ad5-039721b37a69.jpg)
* {"message":"Success","result":[{"message":"Success","prediction":[{"label":"haute_couture","probability":0.94372743},{"label":"preppy","probability":0.048559822},{"label":"grunge","probability":0.025903732},{"label":"streetwear","probability":0.020954607}],"file":"images - 2020-06-29T195702.227.jpg"}]}
