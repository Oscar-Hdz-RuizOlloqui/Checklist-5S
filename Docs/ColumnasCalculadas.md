| TableID | Column Name          | Expression                                                                        | FormatString |
| ------- | -------------------- | --------------------------------------------------------------------------------- | ------------ |
| 13      | Año                  | YEAR(Calendario[Date])<br>                                                        | 0            |
| 13      | Semana               | WEEKNUM(Calendario[Date], 2)  // El '2' indica que la semana empieza el lunes<br> | 0            |
| 114195  | Ponderación_Numérica | VALUE([Ponderación])<br>                                                          | 0%;-0%;0%    |
| 114195  | Semana               | WEEKNUM(REGISTRO_5S[FECHA DE REGISTRO])                                           | 0            |
