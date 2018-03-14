# Diamond Kata

## Objectif
 * Le kata diamond prend comme entrée une lettre, et la sort en forme de losange.
 * Il s'agit donc d'afficher un diamant/losange en partant de la lettre A jusqu'à la lettre fournie en paramètre.

## Règles
 * La première ligne contient un seul A
 * La dernière ligne contient un seul A
 * Toutes les lignes, à l'exception de la première et de la dernière ont exactement 2 lettres identiques
 * Toutes les lignes ont le même nombre d'espace au début et à la fin
 * Le diamant/losange est horizontalement symétrique
 * Le diamant/losange est verticalement symétrique
 * Le diamant/losange a une forme carrée (la largeur est égale à la hauteur)
 * Les lettres forment le diamant/losange
 * La moitié supérieure contient les lettres dans l'ordre croissant
 * La moitié inférieure contient les lettres dans l'ordre descendant
 * Les 4 coins contenant les espaces sont des triangles

## Tests
 * diamond('A') retourne :
```
A
```

 * diamond('B') retourne :
```
 A 
B B
 A 
```

 * diamond('C') retourne :
```
  A  
 B B 
C   C
 B B 
  A  
```  

 * diamond('D') retourne :
```
   A   
  B B  
 C   C 
D     D
 C   C 
  B B  
   A   
```

 * diamond('Z') retourne :
``` 
                         A                         
                        B B                        
                       C   C                       
                      D     D                      
                     E       E                     
                    F         F                    
                   G           G                   
                  H             H                  
                 I               I                 
                J                 J                
               K                   K               
              L                     L              
             M                       M             
            N                         N            
           O                           O           
          P                             P          
         Q                               Q         
        R                                 R        
       S                                   S       
      T                                     T      
     U                                       U     
    V                                         V    
   W                                           W   
  X                                             X  
 Y                                               Y 
Z                                                 Z
 Y                                               Y 
  X                                             X  
   W                                           W   
    V                                         V    
     U                                       U     
      T                                     T      
       S                                   S       
        R                                 R        
         Q                               Q         
          P                             P          
           O                           O           
            N                         N            
             M                       M             
              L                     L              
               K                   K               
                J                 J                
                 I               I                 
                  H             H                  
                   G           G                   
                    F         F                    
                     E       E                     
                      D     D                      
                       C   C                       
                        B B                        
                         A                         
```
                         