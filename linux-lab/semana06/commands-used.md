# Comandos Usados - Semana 6

## Condicionales
- ‘[ -d dir ]‘     Verificar que existe y es undirectorio
- ‘[ -f archivo ]‘ Verificar que existe y es un archivo regular
- ‘[ -r ruta ]‘    Verificar permiso de lectura
- ‘[ -s archivo ]‘ Verificar que el archivo no est á vacío
- ‘[ -e ruta ]‘    Verificar que existe ( cualquier tipo )
- ‘[ -z " $var " ]‘Verificar que la cadena est á vac í a
- ‘[ -n " $var " ]‘Verificar que la cadena no está vacía
- ‘[ $a - eq $b ]‘ Comparar n ú meros : igual
- ‘[ $a - lt $b ]‘ Comparar n ú meros : menor que
- ‘[ $a - gt $b ]‘ Comparar n ú meros : mayor que

## Estructura de control
- ‘if/elif/else/fi‘ Estructura condicional
- ‘case/esac‘       Comparaci ó n contra múltiples patrones
- ‘return 0|1‘      Código de salida de una función
- ‘local var‘       Variable local a una función

## Logging y salida
- ‘tee -a archivo‘  Escribir en pantalla y agregar alarchivo
- ‘printf "[%s]..." ‘ Formato estructurado de log

## Tamaño y tiempo de archivos
- ‘du -sm dir ‘Tamaño del directorio en MB ( solo total )
- ‘du -sh dir ‘ Tamaño en formato legible
- ‘find -mtime -1 ‘Archivos modificados en las ú ltimas 24 h
- ‘find - mtime +7 ‘Archivos modificados hace más de 7 días
- ‘find - maxdepth 1 ‘ No descender a subdirectorios
- ‘find ... | sort | tail -1‘ Obtener el archivo más reciente

## Combinaciones lógicas
- ‘&&‘    AND : ambas condiciones deben ser verdaderas
- ‘||‘     OR : al menos una condición verdadera
- ‘!‘     NOT : niega la condición
