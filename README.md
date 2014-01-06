Referencia-CSS2
===============

Tabla de referencia para todas las propiedades de CSS 2 con soporte de navegadores.

	<table border="0" cellpadding="2" cellspacing="0">
		<tbody>
			<tr>
				<td style="text-align:left;" width="118">

*   [Fondos](#background)
*   [Bordes](#border)
*   [Clasificación](#classification)
*   [Dimensión](#dimension)
*   [Fuentes](#font)
				</td>
				<td style="text-align:left;" width="169">

*   [Contenido Generado](#generatedcontent)
*   [Listas and Viñetas ](#list)
*   [Margen](#margin)
*   [Outlines](#outlines)
*   [Padding (relleno) ](#padding)
				</td>
				<td style="text-align:left;" width="209">

*   [Posicionamiento](#positioning)
*   [Tablas](#table)
*   [Texto](#text)
*   [Pseudo-clases](#pseudoclasses)
*   [Pseudo-elementos](#pseudoel)
				</td>
			</tr>
		</tbody>
	</table>

**Soporte de Navegadores:** **IE**: Internet Explorer, **F**: Firefox, **N**: Netscape.

**W3C:** El número en la columna "W3C" indica la recomendacion de W3C para los CSS estan definidas las propiedades. (CSS1 o CSS2).

## Fondos

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<thead>
			<tr>
				<th width="25%">Propiedad</th>
				<th width="30%">Descripción</th>
				<th width="25%">Valores</th>
				<th width="5%">IE</th>
				<th width="4%">F</th>
				<th width="4%">N</th>
				<th width="7%">W3C</th>
			</tr>
		</thead>
		<tbody>
			<tr>
				<th>[background](http://www.w3schools.com/css/pr_background.asp)</th>
				<td>Fondo. Se usa de esta forma para definir todos los estilos del fondo en una sola declaración.</td>
				<td>_background-color
background-image
background-repeat background-attachment background-position_</td>
				<td>4</td>
				<td>1</td>
				<td>6</td>
				<td>1</td>
			</tr>
			<tr>
				<td>[background-attachment](http://www.w3schools.com/css/pr_background-attachment.asp)</td>
				<td>Define si una imagen de fondo es fija, o si se mueve con el contenido al hacer scroll.</td>
				<td>scroll
fixed</td>
				<td>4</td>
				<td>1</td>
				<td>6</td>
				<td>1</td>
			</tr>
			<tr>
				<td>[background-color](http://www.w3schools.com/css/pr_background-color.asp)</td>
				<td>Define el color de fondo de un elemento.</td>
				<td>_color-rgb
color-hex
color-name
_transparent</td>
				<td>4</td>
				<td>1</td>
				<td>4</td>
				<td>1</td>
			</tr>
			<tr>
				<td>[background-image](http://www.w3schools.com/css/pr_background-image.asp)</td>
				<td>Define una imagen como fondo de un elemento.</td>
				<td>_url_
none</td><td>4</td><td>1</td><td>4</td><td>1</td>
			</tr>
			<tr><td>[background-position](http://www.w3schools.com/css/pr_background-position.asp)</td><td>Define la posición inicial de la imagen de fondo.</td><td>top left
top center
top right
center left
center center
center right
bottom left
bottom center
bottom right
_x-% y-%_
_x-pos y-pos_</td><td>4</td><td>1</td><td>6</td><td>1</td>
			</tr>
			<tr><td>[background-repeat](http://www.w3schools.com/css/pr_background-repeat.asp)</td><td>Define si se repite y como s ereepite una imagen en el fondo.</td><td>repeat
repeat-x
repeat-y
no-repeat</td><td>4</td><td>1</td><td>4</td><td>1</td>
			</tr>
		</tbody>
	</table>

[volver arriba](#up)

## Bordes

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[border](http://www.w3schools.com/css/pr_border.asp)</td><td>Borde. Usado de esta forma para definir todos los atributos en una sola declaración.</td><td>_border-width
border-style
border-color_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[border-bottom](http://www.w3schools.com/css/pr_border-bottom.asp)</td><td>Define los atributos para el borde inferior.</td><td>_border-bottom-width
border-style
border-color_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[border-bottom-color](http://www.w3schools.com/css/pr_border-bottom_color.asp)</td><td>Define el color del borde inferior.</td><td>_border-color_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-bottom-style](http://www.w3schools.com/css/pr_border-bottom_style.asp)</td><td>Define el estilo del borde inferior.</td><td>_border-style_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-bottom-width](http://www.w3schools.com/css/pr_border-bottom_width.asp)</td><td>Define el grosor del borde inferior.</td><td>thin
medium
thick
_length_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[border-color](http://www.w3schools.com/css/pr_border-color.asp)</td><td>Define el color de todos los bordes.</td><td>_color_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[border-left](http://www.w3schools.com/css/pr_border-left.asp)</td><td>Define todos los atributos para el borde izquierdo.</td><td>_border-left-width
border-style
border-color_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[border-left-color](http://www.w3schools.com/css/pr_border-left_color.asp)</td><td>Define el color del borde izquierdo.</td><td>_border-color_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-left-style](http://www.w3schools.com/css/pr_border-left_style.asp)</td><td>Define el estilo del borde izquierdo.</td><td>_border-style_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-left-width](http://www.w3schools.com/css/pr_border-left_width.asp)</td><td>Define el grosor del borde izquierdo.</td><td>thin
medium
thick
_length_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[border-right](http://www.w3schools.com/css/pr_border-right.asp)</td><td>Define todos los atributos del borde derecho.</td><td>_border-right-width
border-style
border-color_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[border-right-color](http://www.w3schools.com/css/pr_border-right_color.asp)</td><td>Define el color del borde derecho. </td><td>_border-color_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-right-style](http://www.w3schools.com/css/pr_border-right_style.asp)</td><td>Define el estilo del borde derecho . </td><td>_border-style_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-right-width](http://www.w3schools.com/css/pr_border-right_width.asp)</td><td>Define el grosor del borde derecho. </td><td>thin
medium
thick
_length_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[border-style](http://www.w3schools.com/css/pr_border-style.asp)</td><td>Define el estilo para todos los bordes.</td><td>none
hidden
dotted
dashed
solid
double
groove
ridge
inset
outset</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[border-top](http://www.w3schools.com/css/pr_border-top.asp)</td><td>Define todos los atributos del borde superior. </td><td>_border-top-width
border-style
border-color_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[border-top-color](http://www.w3schools.com/css/pr_border-top_color.asp)</td><td>Define el color del borde superior. </td><td>_border-color_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-top-style](http://www.w3schools.com/css/pr_border-top_style.asp)</td><td>Define el estilo del borde superior. </td><td>_border-style_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[border-top-width](http://www.w3schools.com/css/pr_border-top_width.asp)</td><td>Define el grosor del borde superior. </td><td>thin
medium
thick
_length_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[border-width](http://www.w3schools.com/css/pr_border-width.asp)</td><td>Define el grosor de todos los bordes d eun elemento. </td><td>thin
medium
thick
_length_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr>
		</tbody>
	</table>

[volver arriba](#up)

## Clasificación

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[clear](http://www.w3schools.com/css/pr_class_clear.asp)</td><td>Define sobre qué lados de un elemento pueden posicionarse otros elementos flotados.</td><td>left
right
both
none</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[cursor](http://www.w3schools.com/css/pr_class_cursor.asp)</td><td>Especifica el tipo de cursor mostrado para el elemento. </td><td><span class="value-inst-uri noxref">_url_
</span>auto
crosshair
default
pointer
move
e-resize
ne-resize
nw-resize
n-resize
se-resize
sw-resize
s-resize
w-resize
text
wait
help</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[display](http://www.w3schools.com/css/pr_class_display.asp)</td><td>Define cómo un elemento es mostrado. </td><td>none
inline
block
list-item
run-in
compact
marker
table
inline-table
table-row-group
table-header-group
table-footer-group
table-row
table-column-group
table-column
table-cell
table-caption</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[float](http://www.w3schools.com/css/pr_class_float.asp)</td><td>Define donde un elemento es posicionado dentro d eotro. (izquierda o derecha).</td><td>left
right
none</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[position](http://www.w3schools.com/css/pr_class_position.asp)</td><td>Coloca un elemento en una posición estática, absoluta, relativa o fija.</td><td>static
relative
absolute
fixed</td><td>4</td><td>1</td><td>4</td><td>2</td></tr><tr><td>[visibility](http://www.w3schools.com/css/pr_class_visibility.asp)</td><td>Define si un elemento es visible o invisible </td><td>visible
hidden
collapse</td><td>4</td><td>1</td><td>6</td><td>2</td></tr>
		</tbody>
	</table>

[volver arriba](#up)<a></a>

## Dimensión

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[height](http://www.w3schools.com/css/pr_dim_height.asp)</td><td>Define la altura de un elemento. </td><td>auto_
length
%_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[line-height](http://www.w3schools.com/css/pr_dim_line-height.asp)</td><td>Define la altura entre lineas </td><td>normal
_number
length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[max-height](http://www.w3schools.com/css/pr_dim_max-height.asp)</td><td>Define la altura máxima permitida para un elemento. </td><td>none
_length
%_</td><td>-</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[max-width](http://www.w3schools.com/css/pr_dim_max-width.asp)</td><td>Define el ancho máximo permitido para un elemento </td><td>none
_length
%_</td><td>-</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[min-height](http://www.w3schools.com/css/pr_dim_min-height.asp)</td><td>Define la altura mínima permitida para un elemento. </td><td>_length
%_</td><td>-</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[min-width](http://www.w3schools.com/css/pr_dim_min-width.asp)</td><td>Define el ancho mínimo permitido para un elemento.</td><td>_length
%_</td><td>-</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[width](http://www.w3schools.com/css/pr_dim_width.asp)</td><td>Define el ancho de un elemento. </td><td>auto
_%
length_&nbsp;&nbsp;</td><td>4</td><td>1</td><td>4</td><td>1</td></tr>
		</tbody>
	</table>

[volver arriba](#up)

## Fuentes

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[font](http://www.w3schools.com/css/pr_font_font.asp)
    </td><td>Fuente. Se usa para cambiar todos los atributos de la fuente. </td><td>_font-style
font-variant
font-weight
font-size/line-height
font-family
_caption
icon
menu
message-box
small-caption
status-bar</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[font-family](http://www.w3schools.com/css/pr_font_font-family.asp)
    </td><td>Una lista prioritaria de nombres de famiias de fuentes o d efamilias genericas de fuentes para un elemento.</td><td>_family-name
generic-family_</td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[font-size](http://www.w3schools.com/css/pr_font_font-size.asp)
    </td><td>Define el tamaño de la fuente para un elemento. </td><td>xx-small
x-small
small
medium
large
x-large
xx-large
smaller
larger_
length
%_</td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[font-size-adjust](http://www.w3schools.com/css/pr_font_font-size-adjust.asp)    </td><td>Especifica el valor del aspecto de un elemento que preservará la altura de la primera fuente.</td><td>none
_number_</td><td>-</td><td>-</td><td>-</td><td>2</td></tr><tr><td>[font-stretch](http://www.w3schools.com/css/pr_font_font-stretch.asp)    </td><td>Condensa o expande la fuente.</td><td>normal
wider
narrower
ultra-condensed
extra-condensed
condensed
semi-condensed
semi-expanded
expanded
extra-expanded
ultra-expanded</td><td>-</td><td>-</td><td>-</td><td>2</td></tr><tr><td>[font-style](http://www.w3schools.com/css/pr_font_font-style.asp)
    </td><td>Define el estilo de la fuente </td><td>normal
italic
oblique</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[font-variant](http://www.w3schools.com/css/pr_font_font-variant.asp)
    </td><td>Muestra el texto en small-caps o normal.</td><td>normal
small-caps</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[font-weight](http://www.w3schools.com/css/pr_font_weight.asp)
    </td><td>Define el grosor de la fuente. </td><td>normal
bold
bolder
lighter
100
200
300
400
500
600
700
800
900</td><td>4</td><td>1</td><td>4</td><td>1</td></tr>
		</tbody>
	</table>

[volver arriba](#up)

	<a name="generatedcontent"></a>

## Contenido Generado 

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[content](http://www.w3schools.com/css/pr_gen_content.asp)    </td><td>Genera contenido en un documento. Se usa con los pseudo elementos :before y :after .</td><td>_string_
_url
_counter(_name_)
counter(_name, list-style-type_)
counters(_name, string_)
counters(_name, string, list-style-type_)
attr(X)
open-quote
close-quote
no-open-quote
no-close-quote</td><td>&nbsp;</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[counter-increment](http://www.w3schools.com/css/pr_gen_counter-increment.asp)    </td><td>Define en cuanto aumentará el contador en cada sentencia de un selector.</td><td>none
_identifier number_</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>2</td></tr><tr><td>[counter-reset](http://www.w3schools.com/css/pr_gen_counter-reset.asp)    </td><td>Define el valor del contador para cada sentencia en un selector.</td><td>none
_identifier number_</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>2</td></tr><tr><td>[quotes](http://www.w3schools.com/css/pr_gen_quotes.asp)    </td><td>Define el tipo de marca del contador.</td><td>none
_string string_</td><td>-</td><td>1</td><td>6</td><td>2</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="list"></a>

## Listas and Viñetas

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[list-style](http://www.w3schools.com/css/pr_list-style.asp)</td><td>Define los atributos de una lista.</td><td>_list-style-type
list-style-position
list-style-image_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[list-style-image](http://www.w3schools.com/css/pr_list-style-image.asp)</td><td>Define una imagen como viñeta para elementos de lista.</td><td>none
_url_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[list-style-position](http://www.w3schools.com/css/pr_list-style-position.asp)</td><td>Define la posiciójn para las viñetas en los elementos de lista.</td><td>inside
outside</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[list-style-type](http://www.w3schools.com/css/pr_list-style-type.asp)</td><td>Define el tipo de viñeta para los elementos de lista.</td><td>none
disc
circle
square
decimal
decimal-leading-zero
lower-roman
upper-roman
lower-alpha
upper-alpha
lower-greek
lower-latin
upper-latin
hebrew
armenian
georgian
cjk-ideographic
hiragana
katakana
hiragana-iroha
katakana-iroha&nbsp;</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>marker-offset</td><td>&nbsp;</td><td>auto
_length_</td><td>&nbsp;</td><td>1</td><td>7</td><td>2</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="margin"></a>

## Margen

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[margin](http://www.w3schools.com/css/pr_margin.asp)    </td><td>Define los atributos de todos los margenes de un elemento.</td><td>_margin-top
margin-right
margin-bottom
margin-left_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>

[margin-bottom](http://www.w3schools.com/css/pr_margin-bottom.asp)      
    </td><td>Define el margen inferior de un elemento.</td><td>auto
_length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>

[margin-left](http://www.w3schools.com/css/pr_margin-left.asp)      
    </td><td>Define el margen izquierdo de un elemento.</td><td>auto
_length
%_</td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>

[margin-right](http://www.w3schools.com/css/pr_margin-right.asp)      
    </td><td>Define el margen derecho de un elemento.</td><td>auto
_length
%_</td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[margin-top](http://www.w3schools.com/css/pr_margin-top.asp)    </td><td>Define el margen superior de un elemento.</td><td>auto
_length
%_</td><td>3</td><td>1</td><td>4</td><td>1</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="outlines"></a>

## Outlines

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[outline](http://www.w3schools.com/css/pr_outline.asp)    </td><td>Define todos los atributos de la linea externa de un elemento.</td><td>_outline-color
outline-style
outline-width_</td><td>-</td><td>-</td><td>-</td><td>2</td></tr><tr><td>[outline-color](http://www.w3schools.com/css/pr_outline-color.asp)    </td><td>Define el color de la linea externa de un elemento.</td><td>_color
_invert</td><td>-</td><td>-</td><td>-</td><td>2</td></tr><tr><td>[outline-style](http://www.w3schools.com/css/pr_outline-style.asp)    </td><td>Define el estilo de la linea eterna de un elemento.</td><td>none
dotted
dashed
solid
double
groove
ridge
inset
outset</td><td>-</td><td>-</td><td>-</td><td>2</td></tr><tr><td>[outline-width](http://www.w3schools.com/css/pr_outline-width.asp)    </td><td>Define el grosor de la linea externa de un elemento.</td><td>thin
medium
thick
_length_</td><td>-</td><td>-</td><td>-</td><td>2</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="padding"></a>

## Padding (relleno) 

[On-line examples](http://www.w3schools.com/css/css_padding.asp)

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Property</th><th width="30%">Description</th><th width="25%">Values</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[padding](http://www.w3schools.com/css/pr_padding.asp)</td><td>Define todos los atributos de relleno para un elemento.</td><td>_padding-top
padding-right
padding-bottom
padding-left_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>

[padding-bottom](http://www.w3schools.com/css/pr_padding-bottom.asp)
    </td><td>Define el relleno inferior de un elemento.</td><td>_length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>

[padding-left](http://www.w3schools.com/css/pr_padding-left.asp)
    </td><td>Define el relleno izquierdo de un elemento.</td><td>_length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>

[padding-right](http://www.w3schools.com/css/pr_padding-right.asp)
    </td><td>Define el relleno derecho de un elemento.</td><td>_length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[padding-top](http://www.w3schools.com/css/pr_padding-top.asp)</td><td>Define el relleno superior de un elemento.</td><td>_length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="positioning"></a>

## Poscionamiento

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Propiedad</th><th width="30%">Descripción</th><th width="25%">Valores</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[bottom](http://www.w3schools.com/css/pr_pos_bottom.asp)</td><td>Define la distancia entre el borde inferior de un elemento en relación al elemento padre. </td><td>auto
_%
length_</td><td>5</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[clip](http://www.w3schools.com/css/pr_pos_clip.asp)</td><td>Define la forma de un elemento. El elemento es cortado segun esta forma, y mostrado.</td><td>_shape
_auto</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[left](http://www.w3schools.com/css/pr_pos_left.asp)</td><td>Define la distancia entre el borde izquierdo de un elemento y el elemento padre.</td><td>auto
_%
length_</td><td>4</td><td>1</td><td>4</td><td>2</td></tr><tr><td>[overflow](http://www.w3schools.com/css/pr_pos_overflow.asp)
    </td><td>Define el comportamiento del contenido de un elemento, si este se desborda de su área.</td><td>visible
hidden
scroll
auto</td><td>4</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[position](http://www.w3schools.com/css/pr_class_position.asp)</td><td>Posiciona un elemento de forma estática, relativa, absoluta o fija.</td><td>static
relative
absolute
fixed</td><td>4</td><td>1</td><td>4</td><td>2</td></tr><tr><td>[right](http://www.w3schools.com/css/pr_pos_right.asp)</td><td>Define la distancia entre el borde derecho de un elemento y el elemento padre.</td><td>auto
_%
length_</td><td>5</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[top](http://www.w3schools.com/css/pr_pos_top.asp)</td><td>Define la distancia entre el borde superior de un elemento y el eleento padre.</td><td>auto
_%
length_</td><td>4</td><td>1</td><td>4</td><td>2</td></tr><tr><td>[vertical-align](http://www.w3schools.com/css/pr_pos_vertical-align.asp)</td><td>Define la alineaión vertical de un elemento.</td><td>baseline
sub
super
top
text-top
middle
bottom
text-bottom
_length_
_%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[z-index](http://www.w3schools.com/css/pr_pos_z-index.asp)</td><td>Define el orden de apilamiento de un elemento.</td><td>auto
_number_</td><td>4</td><td>1</td><td>6</td><td>2</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="table"></a>

## Tabla

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Property</th><th width="30%">Description</th><th width="25%">Values</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[border-collapse](http://www.w3schools.com/css/pr_tab_border-collapse.asp)</td><td>Define el modelo de borde de una tabla.</td><td>collapse
separate</td><td>5</td><td>1</td><td>7</td><td>2</td></tr><tr><td>border-spacing</td><td>Define la distancia entre el borde de celdas adyacentes. (solo para modelos "separated borders").</td><td>_length length_</td><td>-</td><td>1</td><td>6</td><td>2</td></tr><tr><td>caption-side    </td><td>Define la posición del elemento "caption" en relación a la tabla.</td><td>top
bottom
left
right</td><td>-</td><td> 1</td><td>6</td><td> 2</td></tr><tr><td>empty-cells    </td><td>Define si las celdas sin ontenido visible tendrán bordes o no. (solo para el modelo "separated borders").</td><td>show
hide</td><td>-</td><td> 1</td><td>6</td><td> 2</td></tr><tr><td>table-layout    </td><td>Define el algoritmo uado para formatear la tabla.</td><td>auto
fixed</td><td>5</td><td> 1</td><td>6</td><td> 2</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="text"></a>

## Texto

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Property</th><th width="30%">Description</th><th width="25%">Values</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>[color](http://www.w3schools.com/css/pr_text_color.asp)</td><td>Define el color del texto. </td><td>_color_</td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[direction](http://www.w3schools.com/css/pr_text_direction.asp)</td><td>Define la direción del texto.</td><td>ltr
rtl</td><td>6</td><td>1</td><td>6</td><td>2</td></tr><tr><td>[letter-spacing](http://www.w3schools.com/css/pr_text_letter-spacing.asp)</td><td>Incrementa o Disminuye el espacio entre caracteres.</td><td>normal
_length_</td><td>4</td><td>1</td><td>6</td><td>1</td></tr><tr><td>[text-align](http://www.w3schools.com/css/pr_text_text-align.asp)</td><td>Define la alineación del texto en un elemento.</td><td>left
right
center
justify</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[text-decoration](http://www.w3schools.com/css/pr_text_text-decoration.asp)</td><td>Añade decoración al texto.</td><td>none
underline
overline
line-through
blink</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[text-indent](http://www.w3schools.com/css/pr_text_text-indent.asp)</td><td>Define la tabulación de la primera inea de texto en un elemento.</td><td>_length
%_</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[text-transform](http://www.w3schools.com/css/pr_text_text-transform.asp)</td><td>Controla los caracteres en un elemento.</td><td>none
capitalize
uppercase
lowercase</td><td>4</td><td>1</td><td>4</td><td>1</td></tr><tr><td>unicode-bidi</td><td>&nbsp;</td><td>normal
embed
bidi-override</td><td>5</td><td>&nbsp;</td><td>&nbsp;</td><td>2</td></tr><tr><td>[white-space](http://www.w3schools.com/css/pr_text_white-space.asp)</td><td>Define cuanto espacio en blanco es manejado dentro de un elemento.</td><td>normal
pre
nowrap</td><td>5</td><td>1</td><td>4</td><td>1</td></tr><tr><td>[word-spacing](http://www.w3schools.com/css/pr_text_word-spacing.asp)</td><td>Incrementa o disminuye el espaciado entre palabras en un elemento.</td><td>normal
_length_</td><td>6</td><td>1</td><td>6</td><td>1</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="pseudoclasses"></a>

## Pseudo-clases

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Pseudo-clase</th><th width="55%">Proposito</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>:active</td><td>Añade atributos especificos al vínculo seleccionado.</td><td>4</td><td>1</td><td>&nbsp;</td><td>1</td></tr><tr><td>:hover</td><td>Añade atributos al vínculo con el ratón encima.</td><td>4</td><td>1</td><td>7</td><td>1</td></tr><tr><td>:link</td><td>Añade atributos a un vínculo no visitado. </td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>:visited</td><td>Añade atributos a un vínculo visitado </td><td>3</td><td>1</td><td>4</td><td>1</td></tr><tr><td>:first-child</td><td>Añade atributos específicos a un elemento que es el primer "hijo" de otro elemento.</td><td>&nbsp;</td><td>1</td><td>7</td><td>2</td></tr><tr><td>:lang</td><td>Especifica el lenguaje a ser usado en un elemento.</td><td>&nbsp;</td><td>1</td><td>&nbsp;</td><td>2</td></tr>
		</tbody>
	</table>

	[volver arriba](#up)<a name="pseudoel"></a>

## Pseudo-elementos

	<table class="ex" border="0" cellpadding="2" cellspacing="0" width="100%">
		<tbody>
			<tr><th width="25%">Pseudo-elemento</th><th width="55%">Proposito</th><th width="5%">IE</th><th width="4%">F</th><th width="4%">N</th><th width="7%">W3C</th></tr><tr><td>:first-letter</td><td>Añade atributos específicos a la primera letra deun texto.</td><td>5</td><td>1</td><td>&nbsp;</td><td>1</td></tr><tr><td>:first-line</td><td>Añade atributos específicos a la primera linea de un texto.</td><td>5</td><td>1</td><td>&nbsp;</td><td>1</td></tr><tr><td>:before</td><td>Inserta contenido antes de un elemento.</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>2</td></tr><tr><td>:after</td><td>Inserta contenido despues de un elemento.</td><td>&nbsp;</td><td>&nbsp;</td><td>&nbsp;</td><td>2</td></tr>
		</tbody>
	</table>  			
