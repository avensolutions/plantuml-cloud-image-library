# PlantUML Mutli Cloud Resource Library

> PlantUML Multi Cloud and SaaS Diagramming Image Library

This repository can be used to draw multi cloud arhchitecture using PlantUML.  Unlike other PlantUML icon libraries, this library does not use sprites, instead it uses the icons sourced from the various providers directly as images.  This results in cleaner, more colorful and interesting digrams.  

## Usage

Import the resources you want to use in component or sequence diagrams, using the following syntax:  

```
@startuml

!define Library https://raw.githubusercontent.com/infraql/plantuml-cloud-resource-library/main
' include the components you wish to use...
!includeurl Library/aws/AWSS3.puml

' optionally include any other skinparam config...

' declare the component instances for use in your diagram
$AwsS3(s3landing, Landing Bucket, AWS S3 Bucket)

' define other components and relationships...

@enduml
```

Full examples are provided below:  

## Component Diagram

The following code:  

```
fred
```
creates the following diagram:  

## Sequence Diagram

The following code:  

```
fred
```
creates the following diagram: 

