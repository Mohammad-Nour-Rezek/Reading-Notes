# **04/01/2021**

A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.

<table>
<tr>
<td>15</td>
<td>15</td>
<td>30</td>
</tr>
<tr>
<td>45</td>
<td>60</td>
<td>45</td>
</tr>
<tr>
<td>60</td>
<td>90</td>
<td>90</td>
</tr>
</table>

<thead>
The headings of the table should
sit inside the <thead> element.
<tbody>
The body should sit inside the
<tbody> element.
<tfoot>
The footer belongs inside the
<tfoot> element.

---

CREATING OBJECTS USING CONSTRUCTOR SYNTAX
var hotel = new Object();
hotel.name= 'Park';
hotel.rooms = 120;
hotel .booked = 77;
hotel .checkAvailability = function()
return this . rooms - this.booked;
} ;
