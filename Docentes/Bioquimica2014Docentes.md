# Docentes - Bioquímica 2014
## Descripción
Aquí presentamos los resultados de las encuestas de `evaluación institucional` llevada a cabo en agosto del 2014 en la que se recabaron datos de los `docentes de la carrera de Bioquímica` de la Facultad de Química de la Universidad del Norte. La encuesta consistió en un formulario de `92 preguntas` evaluando cada una de las siguientes dimensiones:

* __Dimensión 1: Organización & Gestión__
    * 1.1: Organización
    * 1.2: Gestión
* __Dimensión 2: Proyecto Académico__
    * 2.1: Objetivos de carrerra y Perfil del Egresado
    * 2.2: Plan de estudios
    * 2.3: Proceso enseñanza-aprendizaje
    * 2.4: Evaluación del proceso enseñanza-aprendizaje
    * 2.5: Investigación y extensión
* __Dimensión 3: Personas__
    * 3.1: Directivos
    * 3.2: Docentes
    * 3.3: Estudiantes
    * 3.4: Personal administrativo y de apoyo
* __Dimensión 4: Recursos__
    * 4.1: Infraestructura, equipamientos e insumos
    * 4.2: Financiamiento
* __Dimensión 5: Resultados & Impacto__
    * 5.1: Egresados
    * 5.2: Impacto social

Se obtuvieron `26` formularios de respuestas, los cuales fueron cargados en una base de datos en formato `.csv` para su análisis estadístico. Los datos fueron procesados y analizados con [R](http://www.r-project.org) versión 3.1.1. Este documento fue redactado utilizando MarkDown en [RStudio](http://www.rstudio.com) versión 0.98.932 y el paquete [knitr](http://cran.r-project.org/web/packages/knitr/index.html) versión 1.6 de [Yihui Xie](http://yihui.name/knitr).


```r
# Establecemos las opciones globales
require(knitr)
opts_chunk$set(warning = FALSE, echo = FALSE, message = FALSE, fig.height = 8, fig.width = 14)
```



***

## Resultados

### Dimensión 1.1 - Organización
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q11](figure/Q111.png) ![plot of chunk Q11](figure/Q112.png) ![plot of chunk Q11](figure/Q113.png) ![plot of chunk Q11](figure/Q114.png) ![plot of chunk Q11](figure/Q115.png) ![plot of chunk Q11](figure/Q116.png) 

***
### Dimensión 1.2 - Gestión
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q12](figure/Q121.png) ![plot of chunk Q12](figure/Q122.png) ![plot of chunk Q12](figure/Q123.png) ![plot of chunk Q12](figure/Q124.png) ![plot of chunk Q12](figure/Q125.png) ![plot of chunk Q12](figure/Q126.png) ![plot of chunk Q12](figure/Q127.png) ![plot of chunk Q12](figure/Q128.png) ![plot of chunk Q12](figure/Q129.png) ![plot of chunk Q12](figure/Q1210.png) ![plot of chunk Q12](figure/Q1211.png) ![plot of chunk Q12](figure/Q1212.png) ![plot of chunk Q12](figure/Q1213.png) 

***
### Dimensión 2.1 - Objetivos de la carrera y Perfil del Egresado
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q21](figure/Q211.png) ![plot of chunk Q21](figure/Q212.png) ![plot of chunk Q21](figure/Q213.png) ![plot of chunk Q21](figure/Q214.png) ![plot of chunk Q21](figure/Q215.png) ![plot of chunk Q21](figure/Q216.png) 

***
### Dimensión 2.2 - Plan de Estudios
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q22](figure/Q221.png) ![plot of chunk Q22](figure/Q222.png) ![plot of chunk Q22](figure/Q223.png) ![plot of chunk Q22](figure/Q224.png) ![plot of chunk Q22](figure/Q225.png) ![plot of chunk Q22](figure/Q226.png) ![plot of chunk Q22](figure/Q227.png) ![plot of chunk Q22](figure/Q228.png) 

***
### Dimensión 2.3 - Proceso enseñanza-aprendizaje
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q23](figure/Q231.png) ![plot of chunk Q23](figure/Q232.png) ![plot of chunk Q23](figure/Q233.png) ![plot of chunk Q23](figure/Q234.png) ![plot of chunk Q23](figure/Q235.png) ![plot of chunk Q23](figure/Q236.png) ![plot of chunk Q23](figure/Q237.png) 

***
### Dimensión 2.4 - Evaluación del proceso enseñanza-aprendizaje
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q24](figure/Q241.png) ![plot of chunk Q24](figure/Q242.png) ![plot of chunk Q24](figure/Q243.png) ![plot of chunk Q24](figure/Q244.png) 

***
### Dimensión 2.5 - Investigación & extensión
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q25](figure/Q251.png) ![plot of chunk Q25](figure/Q252.png) ![plot of chunk Q25](figure/Q253.png) ![plot of chunk Q25](figure/Q254.png) ![plot of chunk Q25](figure/Q255.png) ![plot of chunk Q25](figure/Q256.png) ![plot of chunk Q25](figure/Q257.png) ![plot of chunk Q25](figure/Q258.png) 

***
### Dimensión 3.1 - Directivos
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q31](figure/Q311.png) ![plot of chunk Q31](figure/Q312.png) ![plot of chunk Q31](figure/Q313.png) ![plot of chunk Q31](figure/Q314.png) 

***
### Dimensión 3.2 - Docentes
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q32](figure/Q321.png) ![plot of chunk Q32](figure/Q322.png) ![plot of chunk Q32](figure/Q323.png) ![plot of chunk Q32](figure/Q324.png) ![plot of chunk Q32](figure/Q325.png) ![plot of chunk Q32](figure/Q326.png) 

***
### Dimensión 3.3 - Estudiantes
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q33](figure/Q331.png) ![plot of chunk Q33](figure/Q332.png) ![plot of chunk Q33](figure/Q333.png) ![plot of chunk Q33](figure/Q334.png) 

***
### Dimensión 3.4 - Personal administrativo y de apoyo
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q34](figure/Q341.png) ![plot of chunk Q34](figure/Q342.png) ![plot of chunk Q34](figure/Q343.png) ![plot of chunk Q34](figure/Q344.png) 

***
### Dimensión 4.1 - Infraestructura, equipamientos e insumos
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q41](figure/Q411.png) ![plot of chunk Q41](figure/Q412.png) ![plot of chunk Q41](figure/Q413.png) ![plot of chunk Q41](figure/Q414.png) ![plot of chunk Q41](figure/Q415.png) ![plot of chunk Q41](figure/Q416.png) ![plot of chunk Q41](figure/Q417.png) ![plot of chunk Q41](figure/Q418.png) ![plot of chunk Q41](figure/Q419.png) ![plot of chunk Q41](figure/Q4110.png) 

***
### Dimensión 4.2 - Financiamiento
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q42](figure/Q421.png) ![plot of chunk Q42](figure/Q422.png) ![plot of chunk Q42](figure/Q423.png) 

***
### Dimensión 5.1 - Egresados
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q51](figure/Q511.png) ![plot of chunk Q51](figure/Q512.png) ![plot of chunk Q51](figure/Q513.png) ![plot of chunk Q51](figure/Q514.png) 

***
### Dimensión 5.2 - Impacto social
Los resultados de esta dimensión son los siguientes:
![plot of chunk Q52](figure/Q521.png) ![plot of chunk Q52](figure/Q522.png) ![plot of chunk Q52](figure/Q523.png) ![plot of chunk Q52](figure/Q524.png) 
