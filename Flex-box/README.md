#leeme FlexBox

-se debe configurar y  entender la relacion padre e hijo.

-el padre es el contenedor flexible y todo lo que contiene son elementos secundarios o flexibles.

-se puede establecer un flexbox siempre que exista relacion padre e hijo.

  -un hijo puede ser el contenedor flexible para sus hijos, pero sera un contenedor separado y no transfiere las propiedades de los abuelos.

   PADRE----->HIJO-->HIJO             ABUELO---->PADRE---->HIJO---
            (PADRE-->HIJO)           |  hijo no hereda de abuelo  |
                                      <------<-----<-----<----<---

-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
#Flexbox opera en 2 ejes
        eje principal  : es la direccion que define como se colocan los elementos (flexible) en el contenedor (caja).
        eje transversal:es el eje perpendicular (que cruza) a su eje principal.

    EJES FLEXBOX --lineal--                                             EJES FLEXBOX --columna--

        0                          |                                    0                        |
        |                          |                                    |                        |
        |                          |                                    |                        |
+--------------} EJE PRINCIPAL      > row :                      +==============} Eje transversal  > column:
        |                          |                                    |                        |
        |                          |                                    |                        |
       \ /                         |                                   \ /                       |                                       
        |   Eje transversal        |                                    |   EJE PRINCIPAL        |


++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

                      0            |                                    |   EJE PRINCIPAL        |
                      |            |                                   / \                       |
                      |            |                                    |                        |
EJE PRINCIPAL  {--------------+     > row-reverse:              +==============} Eje transversal  > column-reverse:
                      |            |                                    |                        |
                      |            |                                    |                        |
                     \ /           |                                    0                                                   
      Eje transversal |            |                                         
 
-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------

   
  
