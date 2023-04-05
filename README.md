# WorldCup-Fixture
Hey there! Today we gonna see how we build a World Cup group stage table data storage. This site has four groups of contestants and we can automatically generate countries to each division of the group. After all countries are generated, we'll give them the points they got based on their performances. Then after we finished all this thing, we gonna found a button that says Create Chart!, and the last part is clicking on that button and watch the analysis made with bar and pie charts.

# Generating random countries!
This site is built by fetching APIs from other providers and that makes our work easy, more flexable and understandable for other users. The first API we fetched was that gave us full countries list around the globe. As we stated on the above phrase, the countries that'll participate on the world cup were automatically choosen from this list.

# Creating chart!
Here also we use same mechanism as the above. A chart API is fetched by calling its URL and we'll give the collected points of the contestants to the chart's data storage. And just like that we can create a chart by changing all the data like we want.
