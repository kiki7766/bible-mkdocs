# Contextos Bíblicos - Libros de la Biblia 

## **Antiguo Testamento**
``` mermaid
stateDiagram-v2
    state "Antiguo Testamento" as at1{
        state "El Pentateuco" as at2{ 
            Génesis --> Éxodo 
            Éxodo --> Levítico
            Levítico --> Números 
            Números --> Deuteronomio
        }  
        
        state "Libros Históricos" as at3{
            Josué --> Jueces
            Jueces --> Rut 
            Rut --> 1_Samuel
            1_Samuel --> 2_Samuel 
            2_Samuel --> 1_Reyes
            1_Reyes --> 2_Reyes
            2_Reyes --> 1_Crónicas
            1_Crónicas --> 2_Crónicas
            2_Crónicas --> Esdras
            Esdras --> Nehemías
            Nehemías --> Ester
        }
        
        state "Libros Poéticos" as at4{
            Job --> Salmos
            Salmos --> Proverbios
            Proverbios --> Eclesiastés
            Eclesiastés --> Cantares
        }
        
        state "Profetas Mayores" as at5{
            Isaías --> Jeremías
            Jeremías --> Lamentaciones
            Lamentaciones --> Ezequiel
            Ezequiel --> Daniel
        }   

        state "Profetas Menores" as at6{
            Oseas --> Joel
            Joel --> Amos
            Amos --> Abdías
            Abdías --> Jonás 
            Jonás --> Miqueas
            Miqueas --> Nahúm
            Nahúm --> Habacuc
            Habacuc --> Sofonías
            Sofonías --> Hageo
            Hageo --> Zacarías
            Zacarías --> Malaquías
        }             
    }
```
## **Nuevo Testamento**
``` mermaid
stateDiagram-v2
    state "Nuevo Testamento" as nt1{
        state "Evangelios" as nt2{ 
            Mateo --> Marcos 
            Marcos --> Lucas
            Lucas --> Juan 
        }  


        state "Libro Històrico" as nt3{ 
            Hechos
        }  

        state "Epístolas Paulinas" as nt4{ 
            Romanos --> 1_Corintios 
            1_Corintios --> 2_Corintios
            2_Corintios --> Gálatas 
            Gálatas --> Efesios
            Efesios --> Filipenses
            Filipenses --> Colosenses 
            Colosenses --> 1_Tesalonisesnses
            1_Tesalonisesnses --> 2_Tesalonisenses
            2_Tesalonisenses --> 1_Timoteo 
            1_Timoteo --> 2_Timoteo
            2_Timoteo --> Tito
            Tito --> Filemón         
        }  

        state "Epístolas Generales" as nt5{ 
            Hebreos --> Santiago
            Santiago --> 1_Pedro
            1_Pedro --> 2_Pedro 
            2_Pedro --> 1_Juan
            1_Juan --> 2_Juan
            2_Juan --> 3_Juan
            3_Juan --> Judas
        } 

        state "Libro Profético" as nt6{
            Apocalipsis
        }   
    }
```