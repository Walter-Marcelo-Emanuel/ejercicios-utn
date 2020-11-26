
    *Flex-Box

    --display: flex;          -- contenedor flexible a nivel bloque --
    --display: block;         -- ocupa todo el ancho del contenedor --
    --display: inline-flex;   -- contenedor flexible a nivel linea  --
    --display: inline-block;  -- ocupa solo el espacio que necesita --

        # Opciones padre (parent)   

            -flex-direction: row;                   --default--
                             row-reverse;
                             column;
                             column-reverse;

            -flex-wrap: nowrap;                     --default-- 
                        wrap;
                        wrap-reverse;

            -flex-flow: row nowrap;                 --default--
                        <flex-direction> + <flex-wrap>;
                        <flex-direction>;
                        <flex-wrap>;
    ----------------------------------------------------------------------------------------------
            -justify-content: flex-start;    --default-- 
             ----------       flex-end;
            |estos se  |      center;
            |aplican a |      space-around;
            |la linea  |      space-between;
             ----------       space-evenly;

            -align-content: stretch; 
                            flex-start;
                            flex-end;
                            center;
                            space-between;
                            space-around;           

    ----------------------------------------------------------------------------------------------
            -flex-direction:  column;
            -justify-content: flex-start;    --default-- 
             ---------        flex-end;
            |estos se |       center;
            |aplican  |       space-around;  
            |en la    |       space-between;
            |columna  |       space-evenly;  
             ---------

            -flex-direction: column;
            -align-items: stretch;            --default--
                          flex-star;
                          flex-end;
                          center;
                          baseline;
    ----------------------------------------------------------------------------------------------
        # Opciones hijo

            -order: 0;     --el valor por default del elemento a mover--
                    <numero -x(left)-- 0(base)-- +x(right)>  (where  x == number)
            --------------------------------------------------------------------------------------
            -flex-grow: 0; --el valor por default del elemento a crecer--
              <flex-grow: x;> -- 0(base)-- x(more grow) (where  x == number)
            --------------------------------------------------------------------------------------
            -flex-shrink:0; --el valor por default del elemento a achicar--
              <flex-shrink: x;> -- 0(base)-- x(more shrink)  (where  x == number)
            --------------------------------------------------------------------------------------
            -flex-basis: auto; --default--  --cuando un articulo tiene flex-basis
                      <width>;              --el navegador siempre usará el valor
                                            --establecido, no sirve si se usan
                                            --mid-width o max-width
            --------------------------------------------------------------------------------------
            -flex: 0 1 auto; --defaul--                                             
                    <flex-grow> + <flex-shrink> + <flex-basis>                    
                    <flex-grow>                                                   
                    <flex-basis>                                                  
                    <flex-grow> + <flex-basis>
                    <flex-grow> + <flex-shrink>
            --------------------------------------------------------------------------------------
            -align-self: stretch; --default--
                         flex-start;
                         flex-end;
                         center;
                         baseline;