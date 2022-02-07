# SF Housing Rentals
 
An application for analyzing and visualizing the housing prices in the San Francisco area..

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [hvplot](https://hvplot.holoviz.org/) for more interactive data visualization.

* [geoviews](https://geoviews.org/) for geographical data visualization.

---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install hvplot

pip install geoviews

```
---

## Usage

The App imports data from from the csv files and creates a distribution showing the housing units per year:

![Distribution](https://user-images.githubusercontent.com/96391748/152716444-3c15c543-d9a8-4313-b7a0-4dd05f91c892.PNG)

The data is then filtered and a line plot is generated overlaying the sale price per sqare foot and gross rent over time:

![Overlay](https://user-images.githubusercontent.com/96391748/152716527-4716971c-7fe7-4c01-bb68-38a12ae076ff.PNG)

A groupby option is then added to the graph so the user can see the statistics for each neighborhood individually:

![groupby](https://user-images.githubusercontent.com/96391748/152716659-54228c06-fff4-4e3a-be07-2acefa8ec3ff.PNG)

Finally, longitudes and latitudes are added to the data and a geographical visualization is generated:

![geodata](https://user-images.githubusercontent.com/96391748/152716754-336db621-4d51-42db-b8d2-df0f7f34efb9.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE