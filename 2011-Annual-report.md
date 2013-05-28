---
layout: report
report_title: The 2011 Lorem Ipsum Report
report_abstract: Here is some text about the article - something like an abstract ...
report_date: June 2012
meta_title: Annual Report
meta_subtitle: 2011
contents:
  - section: Introduction
    subsections: [Cras lorem est mattis ac justo]
  - section: Methods
    subsections: [Mathematical Equations, Curabitur ac Volutpat Nunc]
  - section: Results
  - section: More Tables and Figures
    subsections: [Images from the Web, More HTML Tables, Tables in LaTeX]
  - section: References
---

# Introduction <a id="Introduction"></a>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur lobortis lectus et tellus pharetra sodales. Duis eget sapien quis urna sagittis facilisis. Ut aliquam dui ut est euismod a mattis magna semper. Curabitur nec magna turpis. Etiam suscipit lectus vel lacus dignissim sollicitudin non at nisi. Proin ut nibh non magna vulputate laoreet in eget felis. Vivamus eget turpis nulla. Aliquam erat volutpat. Suspendisse potenti. Nullam viverra diam sit amet risus fermentum iaculis. Integer vitae purus eu urna ultrices sodales vel sed nisl.

1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
2. Phasellus quis sem a tortor tempus faucibus.
3. Nam eget velit at odio imperdiet congue ut sed nisl.
 

## Cras lorem est mattis ac justo <a id="Introduction + Cras lorem est mattis ac justo"></a>
Cras lorem est, ultrices sed vulputate in, mattis ac justo. Donec vulputate risus id augue condimentum tempus. Vivamus tempus luctus metus, eu egestas massa bibendum quis. Donec fermentum nulla sit amet mauris ullamcorper at accumsan urna dapibus. Vestibulum vel elit at tortor sodales condimentum euismod in ligula. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Donec auctor fringilla leo pharetra ullamcorper. Integer venenatis ipsum vitae nisl feugiat imperdiet. Vivamus ante libero, scelerisque ut vestibulum vitae, sagittis ut lorem.

* Mauris in ligula ipsum, at vehicula turpis.
* Duis at erat non enim fringilla posuere sed non dolor.

# Methods <a id = "Methods"></a>

## Mathematical Equations are Supported  <a id="Methods + Mathematical Equations"></a>
When "kramdown" flavor of Markdown is specified in the _config.yml file, it is possible to produce beatiful mathematics equations, either inline or as a seperate "display" line.  Equations are writen in LaTeX form.  For example, to include an inline LaTeX equation you enclose the equation in $ delimiters, for example: `$\frac{1}{n} \sum_{i=1}^{n} x_{i}$` produces $\frac{1}{n} \sum _{i=1}^{n} x _{i}$ inline.  This, of course, is the equation for the Arithmetic mean.  Other, more complex equations may need their own line, or "display".  Equations that are displayed are also numbered according to order of presentation.  For example:

$$ MSE = \frac{1}{n} \sum_ {i=1}^n (\widehat{\theta}_ {i} - \theta_i)^2$$

$$ MSE(\hat{\theta}) = \mathbb{E}[(\hat{\theta} - \theta)^2]$$

## Curabitur ac Volutpat Nunc <a id="Methods + Curabitur ac Volutpat Nunc"></a>
In hac habitasse platea dictumst. Donec et purus at lacus rutrum aliquet. Nullam dictum lectus vitae mi ultrices viverra sed sit amet odio. Mauris egestas tincidunt odio in blandit. Integer odio neque, eleifend vitae accumsan pellentesque, sagittis id felis. Etiam at sem quam, nec malesuada mauris. Nulla ut diam a leo dignissim volutpat non quis nunc. Suspendisse potenti.

|----------------------+-------------+-------------+-------------+-------------+---------------+-------------|
|***Table 1.***         |             |             |             |             |               |             |
|                      |             | **Aliquam Leo Lorem** |       |        |        | **Varius Nec Nibh** |
|:---------------------|------------:|------------:|------------:|------------:|--------------:|------------:|
|                      |...............|............................|...............|      |       |         |
|                      |  Nec Nibh   |  Ultricies  | Cras Purus  |   Nec Nibh  | Ultricies   |  Cras Purus   |
| Pellentesque         |   362.980   |    0.019    |    False    |   393.244   |   -0.107    |       True    |
| Pellentesque Nec     |   360.795   |   -0.001    |    True     |   379.277   |    0.088    |      False    |
|----------------------+-------------+-------------+-------------+-------------+---------------+-------------|

### Proin eu ligula nisl
In eget lorem felis. Aliquam leo lorem, blandit vel ultricies eu, varius nec nibh. Cras Purus tristique massa convallis convallis. Sed consectetur ultrices molestie. Sed risus eros, bibendum nec feugiat sed, condimentum nec orci. Proin orci augue, lobortis non mattis sit amet, porta in magna. Cras non eros risus, non fringilla elit. Proin sit amet dui metus, vitae rutrum est. Nullam viverra, sem id malesuada molestie, est erat tempus ipsum, a gravida arcu leo sit amet est. Aenean rutrum, ipsum eget suscipit sollicitudin, lacus felis convallis justo, ac aliquet eros arcu ut orci. 

*Figure 1. From a File in the Local Directory*

<img src="img/Fig_1.png" alt="Fig.1" style="width: 600px;"/>

### Donec sed lacus eget odio feugiat euismod
In nibh dui, rutrum sit amet egestas eu, dapibus imperdiet lectus. Quisque urna augue, eleifend sit amet elementum vel, fringilla non libero. Aenean urna felis, ultrices vel vehicula egestas, dictum a turpis. Integer eleifend viverra massa, non varius leo pellentesque nec. Nullam sit amet justo sapien. Ut sit amet lorem ut mi hendrerit auctor. 

# Results <a id="Results"></a>
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut placerat, dui sit amet placerat tincidunt, nibh ligula faucibus elit, nec adipiscing sapien lacus ullamcorper risus. Vivamus vitae tortor id lectus hendrerit aliquet. Nulla sit amet arcu ac velit consequat vulputate et non magna. Mauris quis metus sapien. Ut elit erat, semper vitae pharetra eleifend, ornare a augue. Suspendisse sed sapien nunc. Praesent dolor tellus, euismod bibendum eleifend eu, faucibus sed metus. Sed sed elit quis nibh accumsan congue nec vel ligula.

{% comment %}<!--  Markdown Version of Table 2
|----------------------+-------------+-------------+-------------+-------------+---------------+-------------|
|**Table 2.**          |             |             |             |             |             | Varius Nec Nibh|
|                      |             | Aliquam Leo Lorem |       |             |           | Vel Ultricies Eu|
|:---------------------|------------:|------------:|------------:|------------:|--------------:|------------:|
|                      |...............|............................|...............|      |       |         |
|                      | Nec Nibh   |  Ultricies  |   Cras Purus   |  Nec Nibh  |   Ultricies   |   Cras Purus   |
| Pellentesque    |   362.980   |    0.019    |     8.004   |   248.836   |     -0.428    |     5.652   |
| Pellentesque Nec |   360.795   |   -0.001    |     7.512   |   287.078   |     -0.057    |     6.225   |
|----------------------+-------------+-------------+-------------+-------------+---------------+-------------|
-->{% endcomment %}

**Table 2.  A Table Produced Using HTML Code Directly within the Document**
<div>
<table class='gmisc_table' style='border-collapse: collapse;'>
	<a name='Table 2.'></a>
	<thead>
	<tr>
		<th style='font-weight: 900; border-top: 4px double grey;'></th>
		<th align='center' colspan='3' style='font-weight: 900; border-bottom: 1px solid grey; border-top: 4px double grey;'>Aliquam Leo Lorem</th><th style='border-top: 4px double grey;'>&nbsp;</th>
		<th align='center' colspan='3' style='font-weight: 900; border-bottom: 1px solid grey; border-top: 4px double grey;'>Varius Nec Nibh Vel Ultricies Eu</th>
	</tr>
	<tr>
		<th style=';'>&nbsp;</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Nec Nibh</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Ultricies</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Cras Purus</th>
		<th style='border-bottom: 1px solid grey;'>&nbsp;</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Nec Nibh</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Ultricies</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Cras Purus</th>
	</tr>
	</thead><tbody>
	<tr><td align='left' style='border-bottom: 1px solid grey; font-weight: 900;'>Analysis</td></tr>
	<tr>
		<td align='right' style=';'>Pellentesque</td>
		<td align='right' style=';'>362.98</td>
		<td align='right' style=';'> 0.02</td>
		<td align='right' style=';'> 8.00</td>
		<th style=';'>&nbsp;</th>
		<td align='right' style=';'>287.78</td>
		<td align='right' style=';'>-0.428</td>
		<td align='right' style=';'> 5.65</td>
	</tr>
	<tr>
		<td align='right' style='border-bottom: 1px solid grey;'>&nbsp;&nbsp;Pellentesque Nec</td>
		<td align='right' style='border-bottom: 1px solid grey;'>360.80</td>
		<td align='right' style='border-bottom: 1px solid grey;'>-0.00</td>
		<td align='right' style='border-bottom: 1px solid grey;'> 7.51</td>
		<th style='border-bottom: 1px solid grey;'>&nbsp;</th>
		<td align='right' style='border-bottom: 1px solid grey;'>379.28</td>
		<td align='right' style='border-bottom: 1px solid grey;'>-0.57</td>
		<td align='right' style='border-bottom: 1px solid grey;'> 6.23</td>
	</tr>
	</tbody>
</table>
</div>

In consectetur metus et eros auctor a vehicula erat sollicitudin. Ut venenatis aliquet ante vitae ultricies. Nunc vitae arcu dui. Nullam ut libero laoreet felis accumsan posuere. Suspendisse ac nisi enim. Suspendisse vel eros vel urna blandit tempus a in ligula. Nam at ante purus, ut consectetur lorem. Pellentesque laoreet euismod libero, et rutrum neque pulvinar sit amet. Quisque imperdiet scelerisque nulla, eget feugiat justo imperdiet quis. In porta commodo placerat. Curabitur quis ante dapibus enim euismod fermentum. 

# More Tables and Figures <a id="More Tables and Figures"></a>

## Images can also be read in from a URL <a id="More Tables and Figures + Images from the Web"></a>

*Figure 2.*

<img src="http://www.placekitten.com/400/400" alt="Fig.2"/>

## More HTML Tables <a id="More Tables and Figures + More HTML Tables"></a>
HTML Provides the most flexible table presentation I've found.  Here is another example

**Table 3. Another Table Produced Using HTML Directly** 
<div>
<table class='gmisc_table' style='border-collapse: collapse;'>
	<a name='Table 3.'></a>
	<thead>
	<tr>
		<th style='font-weight: 900; border-top: 4px double grey;'></th>
		<th align='center' colspan='3' style='font-weight: 900; border-bottom: 1px solid grey; border-top: 4px double grey;'>Man Amet egestas</th><th style='border-top: 4px double grey;'>&nbsp;</th>
		<th align='center' colspan='3' style='font-weight: 900; border-bottom: 1px solid grey; border-top: 4px double grey;'>Median Amet egestas</th>
	</tr>
	<tr>
		<th style=';'>&nbsp;</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Nec Nibh</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Ultricies</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Cras Purus</th>
		<th style='border-bottom: 1px solid grey;'>&nbsp;</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Nec Nibh</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Ultricies</th>
		<th align='center' style='border-bottom: 1px solid grey;'>Cras Purus</th>
	</tr>
	</thead><tbody>
	<tr><td align='left' style='border-bottom: 1px solid grey; font-weight: 900;'>Pellentesque</td></tr>
	<tr>
		<td align='right' style=';'>Without Dictumst </td>
		<td align='right' style=';'>5.57</td>
		<td align='right' style=';'> -0.20</td>
		<td align='right' style=';'> 2.36</td>
		<th style=';'>&nbsp;</th>
		<td align='right' style=';'>26.37</td>
		<td align='right' style=';'>-0.10</td>
		<td align='right' style=';'> 5.14</td>
	</tr>
	<tr>
		<td align='right' style=';'>With Dictumst </td>
		<td align='right' style=';'>4.74</td>
		<td align='right' style=';'>-0.08</td>
		<td align='right' style=';'> 2.18</td>
		<th style=';'>&nbsp;</th>
		<td align='right' style=';'>28.36</td>
		<td align='right' style=';'> 0.03</td>
		<td align='right' style=';'> 5.33</td>
	</tr>
	<tr><td align='left' style='border-bottom: 1px solid grey; font-weight: 900;'>Pellentesque Nec</td></tr>
	<tr>
		<td align='right' style=';'>Without Dictumst </td>
		<td align='right' style=';'>5.95</td>
		<td align='right' style=';'>-0.26</td>
		<td align='right' style=';'> 2.43</td>
		<th style=';'>&nbsp;</th>
		<td align='right' style=';'>27.10</td>
		<td align='right' style=';'>-0.27</td>
		<td align='right' style=';'> 5.20</td>
	</tr>
	<tr>
		<td align='right' style=';'>With Dictumst </td> 
		<td align='right' style=';'>4.52</td>
		<td align='right' style=';'> 0.09</td>
		<td align='right' style=';'> 2.13</td>
		<th style=';'>&nbsp;</th>
		<td align='right' style=';'>25.68</td>
		<td align='right' style=';'> 0.08</td>
		<td align='right' style=';'> 5.06</td>
	</tr>
	</tbody>
</table>
</div>

{% comment %}<!--  Markdown Version of Table 3
|----------------------+-------------+-------------+-------------+-------------+-------------+-------------|
|**Table 3.**          |             |             |             |             |             |             |
|                      |         | Mean Amet egestas |             |             |       | Median Amet egestas |
|:---------------------|------------:|------------:|:------------|------------:|------------:|------------:|
|                      |...............|.......................|...............|       |     |             |
|                      | Nec Nibh   |  Ultricies  |   Cras Purus   |  Nec Nibh  |  Ultricies  |   Cras Purus   |
|                      |             |             |             |             |             |             |
| Pellentesque
| Without Dictumst        |    5.574    |    -0.196   |    2.360    |   26.366    |   -0.104    |    5.137    |
| With Dictumst           |    4.741    |    -0.075   |    2.177    |   28.364    |    0.034    |    5.329    |
|===
|                      |             |             |             |             |             |             |
| Pellentesque Nec
| Without Dictumst        |    5.948    |    -0.263    |   2.433    |   27.101    |   -0.266    |    5.199    |
| With Dictumst           |    4.519    |     0.094    |   2.125    |   25.679    |    0.084    |    5.060    |
|----------------------+-------------+-------------+-------------+-------------+---------------+-----------|
-->{% endcomment %}

## Tables in LaTeX <a id="More Tables and Figures + Tables in LaTeX"></a>

Tables can also be produced using the "array" environment.  LaTeX math code can be interpreted using Math Jax, and array is a math mode analog to the tabular environment.  Most of the functionality of the tabular is available in array.  However, not everything is available.  For example, Table 3 would require the use of '\multicolumn' to do the job of HTML codes 'colspan'.  

Like [display LaTeX math functions](http://www.rstudio.com/ide/docs/authoring/using_markdown_equations), the array is enclosed in double dollar sign, `$$`, enclosures in the markdown text. Here is an example of a simple LaTeX array used in markdown.

**Table 4.  Disply Math Function (Centered, but puts equation number in)**

$$
\begin{array}{lcr}
\textbf{What} & \textbf{Variable} & \textbf{Integer}\\
\mbox{First number} & x & 8\\
\mbox{Second number} & y & 15\\
\mbox{Sum} & x + y & 23\\
\mbox{Difference} & x - y & -7\\
\mbox{Product} & xy & 120 \end{array}
$$

[Inline LaTeX math](http://www.rstudio.com/ide/docs/authoring/using_markdown_equations) can also be used.  Here the array is enclosed in single dollar sign, `$` in the markdown text.

**Table 5.  Inline Math Function (Alligned Left)**

$\begin{array}{lcr} \textbf{What} & \textbf{Variable} & \textbf{Integer}\\\mbox{First number} & x & 8\\\mbox{Second number} & y & 15\\\mbox{Sum} & x+y & 23\\\mbox{Difference} & x-y & -7\\\mbox{Product} & xy & 120\end{array}$

# References  <a id="References"></a>

<div id="citation" markdown="1">
Doe, J. (2010). *First Book*. Cambridge: Cambridge University Press.

Doe, J. (2012). Article. *Journal of Generic Studies*, *6*, 33–34.

Doe, J., Smith, S., & Roe, J. (2007). Why Water Is Wet:  A study in the science of the obvious and collection of simulation studies meant to create a really long citation entry for this example. In S. Smith (Ed.), *Third Book*. Oxford: Oxford University Press.
	
</div>
