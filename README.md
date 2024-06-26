# 🚚 Courier  	
The program finds a path from the selected city (logistics center) to all other cities contained in the text file, as long as there is a connection between them.
I used Dijkstra's algorithm to solve the shortest path problem.

### 💬 Context of the project:
This was my main project from the first semester of my studies.
I developed it as part of a computer programming course.

### 🚀 My motivation:
I chose this project because I was interested in how the Google Maps application can so efficiently find the optimal route between two points.

## 📌 To run the program:
1. Clone the repository
2. Change your working directory to the `Source` by cd `Courier/Source`
3. Compile with g++ by `g++ *.cpp *.h -o courier`
4. Run the executable:
- On Linux by `./courier -i dataSet.txt -o output.txt -c Poznan`
- On Windows by `courier -i dataSet.txt -o output.txt -c Poznan`
5. Open output.txt file to check the program output

Feel free to change the content of the dataset.txt file or change the central city instead of Poznan to test my program ^^

Remember to place the data in the right order:<br>
[city1] [city2] [distance1]<br>
[city2] [city3] [distance2]<br>
etc.<br>

### 📷 Galery:

![pict1](https://github.com/karlikp/Courier/assets/115083597/8d5a4aeb-752e-4e1f-9bdf-80db7963124b)
<br>pict.1 Content of dataSet.txt file<br><br>

![pict2](https://github.com/karlikp/Courier/assets/115083597/e7354d03-606c-44a2-80f4-b0bb6ea4c16a)
<br>pict.2 Content of output.txt file which are create after program execution<br><br>




