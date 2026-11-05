# property-scan
AI-driven property analysis starts by uploading an image (interior or exterior) into a computer vision or real estate intelligence platform to automatically extract condition scores, room types, structural features, and valuation insights

## Openai-api style image analysis using ollama or openai 
Computer Vision Analysis: Image Analytics scan the image to tag room types, detect finishes, evaluate property condition (such as GSE C1–C6 ratings), and spot repairs or upgrades. 

## Data Conversion
The visual data is converted into structured metrics (such as JSON data or investment scores covering curb appeal, renovations, safety, and unique features).

## Customer Record
when uploading a image a Customer Record is created or extended a custommer can maintain multiple properties a Image upload results in a new customer record and s propert record within the customer subsequent uploads will have to be assosiated with existing properties of the customer or s new property record for the customer

## Upload storage 
Minio s3 api needs be configured by app admin each customer has a bucket with sub buckets based on the number of objects 
image uploads are stored in those buckets 

## Configurations
for the beginning all records are stored in local storage
ollama config
openai config
unknown users are processed via a default user 

