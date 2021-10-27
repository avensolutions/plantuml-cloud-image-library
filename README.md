# PlantUML Mutli Cloud Resource Library

> PlantUML Multi Cloud and SaaS Diagramming Image Library

This repository can be used to draw multi cloud architecture using PlantUML.  Unlike other PlantUML icon libraries, this library does not use sprites, instead it uses the icons sourced from the various providers directly as images.  This results in cleaner, more colorful and interesting diagrams.  

## Usage

Import the resources you want to use in component or sequence diagrams, using the following syntax:  

```
@startuml

!$imgroot = "https://github.com/avensolutions/plantuml-cloud-image-library/raw/main/images"

' declare the component instances for use in your diagram

!unquoted procedure $AwsGlue($alias, $label, $techn, $descr="", $stereo="AWS Glue")
    rectangle "==$label\n\n<img:$imgroot/aws/Analytics/Glue.png>\n//<size:12>[$techn]</size>//" <<$stereo>> as $alias #white
!endprocedure

'use the component

$AwsGlue(gluejob, ETL Job, AWS Glue)

' define other components and relationships...

@enduml
```

Full examples are provided below:  

## Component Diagram

the code in [example-component.puml](example-component.puml) generates ...  
