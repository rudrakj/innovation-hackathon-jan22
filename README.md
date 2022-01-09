# innovation-hackathon-jan22 - Team Soochee

### Services
 - Frontend - [README.md](/frontend/README.md)
 - Backend - [README.md](/backend/README.md)
 - VoiceToText - [README.md](/voiceToTextService/README.md)


## `Architecture Diagram`
![Architecture Diagram](/frontend/docs/images/architecture-diagram-FrontEnd.jpg)

### Schema

#### Store
 - id
 - name
 - contactNumberList
 - location
 - catalog

#### Master Catalogue Item
 - id
 - barcode
 - sku
 - weight
 - unit
 - mrp
 - image128
 - image256
 - parentCategory
 - subCategory
 - additionalInfo

#### Master Added Store catalog Item
 - id
 - masterId
 - price
 - quantity

#### Manual Added Store Catalogue Item
 - id
 - barcode
 - sku
 - weight
 - unit
 - mrp
 - image128
 - image256
 - parentCategory
 - subCategory
 - additionalInfo
 - price
 - quantity
