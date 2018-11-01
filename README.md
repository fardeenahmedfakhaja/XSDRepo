# XSDRepo
This Repo  have code related to creation of XSD along with various components that can be used in it.


## XSD
XSD stands for XML Schema Definition. It is used to properly define an XML. XSD is used to validate over data, datatype, conditions etc over an XML element. It basically helps to create well-formed and valid  XMLs.  
This Repo has Folders:  
1. SimpleType
2. ComplexType
   
   
## SimpleType Folder:   
1. **SimpleElement.xsd:**   
               It consists of a basic representation of a simple element in xsd.    
2. **Employee.xsd:**  
                It consists of complete usage of simple type element along with various restriction like enumeration, minInclution,  length etc.  
           
           
## ComplexType Folder:  
1. **ComplexElement.xsd:**   
               It consists of a basic representation of a Complex element in xsd which consists of combinations of simple elements, sttributes  and other complex elements.  
2. **ComplexTypeComponent.xsd:**  
                It consists of usage of complex type element. An element can also be made as complex type by just  by creating  a complexType component and creating an element  of type of the corresponding complexType.As seen in the xsd , we  have an EmployeeType of compleType  and this is used as type for EmployeeData.  
3. **ElementAny.xsd:**  
                  Usage of any type component which  helps in creating element of No Schema.  
4. **GroupElement.xsd:**  
                  Usage of group component which creates a group of elements and can be refered in other element.  
5. **PersonalData.xsd:**  
                  Usage of include tag which helps one schema to be used in the other but the case is that both the schemas should be of similar namespace (In this example an element off  InccludeXSD.xsd is reffered in PersonalData.xsd).  
6. **Person.xsd:**   
                  Complex Type element in combination of attribute and elements.  
7. **Employee.xsd:**  
                   A complete Usage Of Complex type, cimple type, various restrictions, groups, list etc.  All and all this xsd cconists of mix of all the above xsds.  
           
               
