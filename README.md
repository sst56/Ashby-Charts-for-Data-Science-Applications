# Ashby-Chart
A python script for creating Ashby charts using the matplotlib library

Initially, the smooth convex hull (https://en.wikipedia.org/wiki/Convex_hull) that surrounds the data points is calculated. This is done by use of the sklearn machine learning library. Then from the calculated hull points, the smooth hull can be calulated by interpolation. Here, quadratic interpolation is used which requires at least 3 initial data points. Then, the hull is drawn around the data points. Several properties of the hull line can be changed as color, fill transparency and thickness. A rounded hull can also be drawn around the normal hull with differ
