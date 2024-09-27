# mi_pagina

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Tablas </title>
    <style>
        col {
            background-color: blueviolet;
        }
    </style>

</head>
<body>
    <h1>TABLAS</h1> 
    <table>
        <caption>HORARIO DE CLASES</caption>
        <colgroup>
             <col>
             <col>

        </colgroup>
        <thead>
        <tr>
            <th>HORAS</th>
            <th>LUNES</th>
            <th>MARTES</th>
            <th>MIERCOLES</th>
            <th>JUEVES</th>
            <th>VIERNES</th>
        </thead>
        <tbody>

            <td>8:00 a 9:00 </td>
            <td>Matematicas</td>
            <td>Matematicas</td>
            <td>Sociales</td>
            <td>Matematicas</td>
            <td>Matematicas</td>
        </tr>
        <tr>
            <td>9:00 a 10:30 </td>
            <td>Ingles</td>
            <td>Ingles</td>
            <td>Ciencias</td>
            <td>Biologia</td>
            <td>Sociales</td>
        </tr>
        <tr>
            <td>10:30 a 11:30 </td>
            <td>Educacion Fisica</td>
            <td>Ciencias</td>
            <td>Ingles</td>
            <td>Tecnologia</td>
            <td>Educacion Fisica</td>
        </tr>
        <tr>
            <td>11:30 a 12:30 </td>
            <td colspan="5">R E C E S O</td>
        </tr>
        <tr>
            <td>12:30 a 13:30 </td>
            <td>Ingles</td>
            <td>Musica</td>
            <td>Fisica</td>
            <td>Fisica</td>
            <td>Fisica</td>
        </tr>
        <tr>
            <td>13:30 a 14:30 </td>
            <td>Musica</td>
            <td>Educacion Fisica</td>
            <td>Musica</td>
            <td>Tauto</td>
            <td rowspan="2">Ingles</td>
        </tr>
        <tr>
            <td>14:30 a 15:30 </td>
            <td>Tecnologia</td>
            <td>Tauto</td>
            <td>Tauto</td>
            <td>Ciencias</td>
            
        </tr> 
    </tbody>
    <tfoot>
        <tr>
            <td colspan="5">Total de Materias</td>
            <td>12</td>
        </tr>
    </tfoot>
    </table>
</body>
</html>
