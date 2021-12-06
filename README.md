# D3_magic

https://prabusiva.github.io/D3_magic/

## Reading Interactive Data Visualization for the Web with D3 by Scott Murray

Simple http server: python -m http.server 9263

@93
/280
### Issues

  d3.select("body").selectAll("div")
					.data(dataset)
					.enter()
					.append("div")
					.attr("class", "bar");
					
   d3.select("body").selectAll("div")
					.data(dataset)
					.enter()
					.append("div")
					.attr("class", "bar");

The second command isn't executed
