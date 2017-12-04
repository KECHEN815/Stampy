# Stampy
Easy mustache templating with Java for generating excel reports and spreadsheets

## How it works 

In a spreadsheet cell use the mustache brackets

{{name}}

In your java code, create a map of names to values: 


```map.put("name", "John Doe")```

"Stamp" the template

```
stampy.executeTemplateMustaches(
    outputPath,
    map
); 
```

See **StampyTest.java** or **Main.java** for a working example
        

## Dependencies 
Java 7 or higher (Java 9 recommended)

poi and poi-ooxml

## Usage

See Main.java for an example

