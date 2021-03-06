# Wearable


-  `isOwnedBy`: Identifies Person/Fitbit account
   -  Attribute type: **Relationship**. [Person](http://schema.org/Person)
   -  Optional
-  `description`: A description of the item
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
   -  Normative References: http://purl.org/dc/elements/1.1/description
-  `bloodPressure`: Blood Pressure
   -  Attribute type: **Property**. [Integer](https://schema.org/Integer)
   -  Required
   -  Meta Data: 
       -  `providedBy`: The device that sent this reading
           -  Attribute type: **Relationship**. [URL](https://schema.org/URL)
       -  `observedAt`: A timestamp which denotes when the reading was taken
           -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
       -  `unitCode`: A string representing the measurement unit corresponding to the Property value. It shall be encoded using the UN/CEFACT Common Codes for Units of Measurement
           -  Attribute type: **Property**. [Text](https://schema.org/Text)
-  `oxygenSaturation`: Oxygen Saturation
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
   -  Meta Data: 
       -  `providedBy`: The device that sent this reading
           -  Attribute type: **Relationship**. [URL](https://schema.org/URL)
       -  `observedAt`: A timestamp which denotes when the reading was taken
           -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
       -  `unitCode`: A string representing the measurement unit corresponding to the Property value. It shall be encoded using the UN/CEFACT Common Codes for Units of Measurement
           -  Attribute type: **Property**. [Text](https://schema.org/Text)
-  `temperature`: temperature
   -  Attribute type: **Property**. [Number](https://schema.org/Number)
   -  Required
   -  Meta Data: 
       -  `providedBy`: The device that sent this reading
           -  Attribute type: **Relationship**. [URL](https://schema.org/URL)
       -  `observedAt`: A timestamp which denotes when the reading was taken
           -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
       -  `unitCode`: A string representing the measurement unit corresponding to the Property value. It shall be encoded using the UN/CEFACT Common Codes for Units of Measurement
           -  Attribute type: **Property**. [Text](https://schema.org/Text)
-  `heartRate`: Heart rate of of the Person being measured
   -  Attribute type: **Property**. [Integer](https://schema.org/Integer)
   -  Required
   -  Meta Data: 
       -  `providedBy`: The device that sent this reading
           -  Attribute type: **Relationship**. [URL](https://schema.org/URL)
       -  `observedAt`: A timestamp which denotes when the reading was taken
           -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
       -  `unitCode`: A string representing the measurement unit corresponding to the Property value. It shall be encoded using the UN/CEFACT Common Codes for Units of Measurement
           -  Attribute type: **Property**. [Text](https://schema.org/Text)



# Person


-  `dateCreated`: Entity's creation timestamp.
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Read-Only. Automatically generated.
-  `dateModified`: Update timestamp of this entity.
   -  Attribute type: **Property**. [DateTime](https://schema.org/DateTime)
   -  Read-Only. Automatically generated.
-  `id`: URN holding the id of the attribute
   -  Attribute type: **Property**. 
   -  Required
-  `type`: The entity type
   -  Attribute type: **Property**. 
   -  Required
-  `additionalName`: An additional name for a Person, can be used for a middle name.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `address`: The mailing address.
   -  Attribute type: **Property**. [address](https://schema.org/address)
   -  Optional
   -  Normative References: https://schema.org/address
-  `email`: Email address.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `familyName`: Family name. In the U.S., the last name of an Person. This can be used along with givenName instead of the name property.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `faxNumber`: The fax number.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `gender`: Gender of something, typically a Person, but possibly also fictional characters, animals, etc. While http://schema.org/Male and http://schema.org/Female may be used, text strings are also acceptable for people who do not identify as a binary gender. The gender property can also be used in an extended sense to cover e.g. the gender of sports teams. As with the gender of individuals, we do not try to enumerate all possibilities. A mixed-gender SportsTeam can be indicated with a text value of "Mixed".. One of : `female`, `male`.
   -  Attribute type: **EnumProperty**. [GenderType](https://schema.org/GenderType)
   -  Optional
-  `givenName`: Given name. In the U.S., the first name of a Person. This can be used along with familyName instead of the name property.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `honorificPrefix`: An honorific prefix preceding a Person's name such as Dr/Mrs/Mr.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `honorificSuffix`: An honorific suffix preceding a Person's name such as M.D. /PhD/MSCSW.
interactionStatistic  InteractionCounter  The number of interactions for the CreativeWork using the WebSite or SoftwareApplication. The most specific child type of InteractionCounter should be used. Supersedes interactionCount.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `isicV4`: The International Standard of Industrial Classification of All Economic Activities (ISIC), Revision 4 code for a particular organization, business person, or place.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `jobTitle`: The job title of the person (for example, Financial Manager).
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `name`: The name of the item
   -  Attribute type: **Property**. 
   -  Optional
-  `taxID`: The Tax / Fiscal ID of the organization or person, e.g. the TIN in the US or the CIF/NIF in Spain.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `telephone`: The telephone number.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `vatID`: The Value-added Tax ID of the organization or person.
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
-  `ownsAccount`: Identifies Person/Fitbit account
   -  Attribute type: **Relationship**. [URL](http://schema.org/URL)
   -  Optional
-  `hasApp`: Identifies Person/Fitbit account
   -  Attribute type: **Relationship**. [Person](http://schema.org/Person)
   -  Optional



# App


-  `hasInfoAbout`: Identifies Person/Fitbit account
   -  Attribute type: **Relationship**. [Person](http://schema.org/Person)
   -  Optional
-  `description`: A description of the item
   -  Attribute type: **Property**. [Text](https://schema.org/Text)
   -  Optional
   -  Normative References: http://purl.org/dc/elements/1.1/description
-  `dyspnoea`: Indication if the Person has dyspnoea
   -  Attribute type: **Property**. [Boolean](https://schema.org/Boolean)
   -  Required
-  `cough`: Indication if the Person has been coughing
   -  Attribute type: **Property**. [Boolean](https://schema.org/Boolean)
   -  Required
-  `anosmia`: Indication if the Person has anosmia
   -  Attribute type: **Property**. [Boolean](https://schema.org/Boolean)
   -  Required
-  `contactCovid`: Indication if the Person has dyspnoea
   -  Attribute type: **Property**. [Boolean](https://schema.org/Boolean)
   -  Required
-  `diarrhea`: Indication of the number of times a Person suffered from diarrhea throughout the day
   -  Attribute type: **Property**. [Integer](https://schema.org/Integer)
   -  Required



## Examples

### OK


