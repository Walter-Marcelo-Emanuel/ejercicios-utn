# HTML5 CSS3

    *Maquetacion

        -semantica html
        -semantica css
        -estructura

    *seccion interna-navegacion

        -float
        -img
        -breadcrumb

    *Formularios

        -chekbox
        -email
        -radio
        -select-option
        -textarea
        -form

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

            -justify-content: flex-start;    --default-- 
             ----------       flex-end;
            |estos se  |      center;
            |aplican a |      space-around;
            |la linea  |      space-between;
             ----------       space-evenly;

            -flex-direction:  column;
            -justify-content: flex-start;    --default-- 
             ---------        flex-end;
            |estos se |       center;
            |aplican  |       space-around;  
            |en la    |       space-between;
            |columna  |       space-evenly;  
             ---------

            -flex-direction: column;
            -align-items: strech;            --default--
                          flex-star;
                          flex-end;
                          center;
                          baseline;

            -align-content: strech; 
                            flex-start;
                            flex-end;
                            center;
                            space-between;
                            space-around;           

        # Opciones hijo
            -order:
            -flex-grow:
            -flex-shrink:
            -flex-basis:
            -flex:
            -align-self:
                
    *Font css
    *icons
    
