---
layout: page
title: Estado actual de la empresa
subtitle: Que datos tenemos de la producción actual

--- 

<style>
 .filaOculta {
  display: none;
}
table {
  border-collapse: collapse;
}
tr {
  cursor: pointer;
}
td {
  text-align: center;
}
td:first-child {
  border: 1px solid #000;
  border-right: none;
}
td:not(:first-child):not(:last-child) {
  border: 1px solid #000;
  border-left: none;
  border-right: none;
}
td:last-child {
  border: 1px solid #000;
  border-left: none;
}
td[colspan] {
  border-left: 1px solid #000;
}
.anchoCeldas {
  width: 150px;
}
</style>
Discutiendo con el personal y con los administradores de la empresa tenemos los siguientes datos de producción:
 
<table>
  <tr class="filaParaPulsar">
    <td class="anchoCeldas">
      celda 1
    </td>
    <td>
      celda 2
    </td>
    <td>
      celda 3
    </td>
    <td>
      celda 4
    </td>
  </tr>
  <tr class="filaOculta">
    <td colspan="4">Esta es la fila oculta</td>
  </tr>
  
</table>
 
| Dia(s) de la semana | Producción | 
| :------: |:----: | 
| Lunes-Jueves | 1000 |
| Viernes | 600 |
| Sábado-Domingo | 800 |


En el aspecto de maquinaria solo se encuentra un horno asador de arepas con una capacidad de 5 arepas cada 3 minutos aproximadamente (sin contar tiempos de ajuste iniciales como lo es el precalentamiento)

<div style="text-align:center">
  <img src="/Trabajo-final/assets/img/horno.jpg" alt="Image" style="width:300px;height:200px;">
</div>

![fabrica](/assets/img/horno.jpg){: .mx-auto.d-block :}




