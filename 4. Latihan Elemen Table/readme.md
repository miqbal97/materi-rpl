## Latihan elemen table
  - Pembuatan table data dengan memanfaatkan elemen table agar data yang di tampilkan menjadi lebih rapih dan tersusun
  - Cara implementasi elemen table yang mudah dengan menggunakan syntax pembuka `<table>` dan penutup `</table>`
  - dengan memanfaatkan beberapa elemen tambahan dalam table seperti :

  | Syntax | Fungsi     |
  | :------------- | :------------- |
  | `<thead> ... </thead>`      | Untuk membuat baris pembuka / header pada table       |
  | `<tbody> ... </tbody>`      | Untuk membuat content atau isi dari table      |
  | `<tfoot> ... </tfoot>`      | Untuk membuat baris penutup / footer pada table       |
  | `<tr> ... </tr>`      | Untuk membuat baris baru pada table       |
  | `<td> ... </td>`      | Untuk membuat kolom pada table       |

### Contoh script membuat table

```html
<table>

	...

</table>
```

### Contoh script membuat header, content, dan footer pada table

```html
<table>

	<!-- header -->
	<thead>

		...

	</thead>

	<!-- content -->
	<tbody>

		...

	</tbody>

	<!-- footer -->
	<tfoot>

		...

	</tfoot>

</table>
```
### Contoh script membuat baris dan kolom pada table

```html
<table>

	<!-- baris -->
	<tr>

		<!-- kolom -->
		<td> Konten </td>

	</tr>

</table>
```