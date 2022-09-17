This is a submission for Monash University's Module 6 challenge. Within are both VactationPy and WeatherPy notebooks.

WeatherPy, collects a list of cities and grabs the weather in that city. From that I have extrapolated data and made
scatterplots representing that data. At the end of the file I have included 3 observations from the dataset.

VacationPy, takes the city data from WeatherPy and creates a heatmap of the humidity from the cities. Then it finds
the most comfortable weather from those cities, then finds the closest hotel and puts a marker on the map.

In the output_data folder are all of the scatterplots from WeatherPy as well as the cities csv file. For VacationPy
I had added two extra .png files. heatmap_max.png was created as I had used the max humidity as the max_intensity, which I felt
did not represent the data as well as setting the max_intensity to 300, thus I created a second map. The other extra file I had made was hotel_map_screenshot.png since the save functions within the googlemaps widget was not
saving the display from the description boxes, which I had wanted to include to prove I had met the requirements of the task.