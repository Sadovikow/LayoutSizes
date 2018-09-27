# LayoutSizes
Размеры рабочих областей и переломных точек для вёрстки при определенных размерах экрана


<table>
 <tr>
    <td><№/td>
    <td><Размер экрана /td>
    <td><Устройство/td>
     <td><Рабочая область/td>
  </tr>
      <tbody>
  <tr>
   <td>
1
   </td>
   <td>
320px - 479px
   </td>
   <td>
 <b>Mobile</b> 
   </td>
   <td>
Workarea: 100% + 10px padding
   </td>
   </tr>
     <tr>
   <td>
2
   </td>
   <td>
480px - 767px
   </td>
   <td>
Mobile M, Mobile L
   </td>
   <td>
Workarea: 100% + 10px padding
   </td>
   </tr>
     <tr>
   <td>
3
   </td>
   <td>
768px - 1023px
   </td>
   <td>
<b>Netbook, Tablet</b>
   </td>
   <td>
Workarea: 750px + 15px padding
   </td>
   </tr>
     <tr>
   <td>
4
   </td>
   <td>
1024px - 1199px
   </td>
   <td>
<b>Netbook, Tablet</b>
   </td>
   <td>
Workarea: 960px + 15px padding
   </td>
   </tr>
     <tr>
    <td>
5
   </td>
   <td>
    больше 1200px
   </td>
   <td>
    <b>Desktop</b>
   </td>
Workarea: 1170px + 15px padding
   <td>

   </td>
   </tr>
   </tbody>
 </table>



 
 1ый и 2ой размер в основном объединяется.<br>
 3ий и 4ый размер тоже можно объеденить<br>
 Тогда получится:<br>
 1, 2 – <b>Mobile</b> (320px-767px) (Workarea: 100% + 10px padding) <br>
 3, 4 – <b>Tablet</b> (768px-1199px) (Workarea: 750px + 15px padding) <br>
 5 – <b>Desktop</b> (больше 1200px) (Workarea: 1170px + 15px padding) <br>
 
 
