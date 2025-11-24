# TikZ

[TikZ](https://www.overleaf.com/learn/latex/TikZ_package) is a popular package for creating data visualizations in LaTeX. It also allows for graph and network visualizations. In 2018, Jürgen Hackl published the [TikZ-network](https://ctan.org/pkg/tikz-network?lang=en) extension, which simplifies the creation of network images ([GitHub](https://github.com/hackl/tikz-network), [Manual](https://mirror.szerverem.hu/ctan/graphics/pgf/contrib/tikz-network/tikz-network.pdf)). 

For the \Vertices the following options are available:

| Option | Default | Type | Definition |
| :---         |     :---:      |     :---:      | :---       |
| size | {} | measure | diameter of the circles |
| color | {} | color | fillcolor of vertices |
| opacity | {} | number | opacity of the fill color |
| style | {} | string | additional TikZ styles |
| layer | {} | number | assigned layer of the vertices |
| NoLabel | false | Boolean | delete the labels |
| IdAsLabel | false | Boolean | uses the Names as labels |
| Math | false | Boolean | displays the labels in math mode |
| RGB | false | Boolean | allow RGB colors |
| Pseudo | false | Boolean | create a pseudo vertices |

For the \Edges the following options are available:

| Option | Default | Type | Definition |
| :---         |     :---:      |     :---:      | :---       |
| lw | {} | measure | line width of the edge |
| color | {} | color | edge color |
| opacity | {} | number | opacity of the edge |
| style | {} | string | additional TikZ styles |
| vertices | {} | file | vertices were the edges are assigned to |
| layer | {} | number | edges in specific layers |
| Direct | false | Boolean | allow directed edges |
| Math | false | Boolean | displays the labels in math mode |
| NoLabel | false | Boolean | delete the labels |
| RGB | false | Boolean | allow RGB colors |
| NotInBG | false | Boolean | edges are not in the background layer |

