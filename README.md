# 🚇 Hyderabad Metro Route Finder

A C++ console-based application that finds the shortest route between two stations in the Hyderabad Metro using Dijkstra’s Algorithm. The program outputs both the minimum travel time and total distance between any two stations in the network.

## 📌 Features

- ✅ Models a realistic Hyderabad Metro network with 55+ stations
- 🧠 Uses Dijkstra's Algorithm to compute the shortest time route
- 🕒 Calculates total travel time
- 📏 Calculates total travel distance
- 🖥️ Simple and clean CLI interface
- ⚡ Fast and efficient using C++ STL containers

## 🛠 Technologies Used

- C++17
- STL Containers: unordered_map, vector, priority_queue, etc.
- Graph Representation: Adjacency List
- Dijkstra’s Algorithm for shortest path

## 🚀 How to Run the Project

1. Clone the Repository:

   git clone https://github.com/<ShravanBhangdiya>/hyderabad-metro-route-finder.git
   cd hyderabad-metro-route-finder

2. Compile the Code:

   g++ -std=c++17 metro.cpp -o metro

3. Run the Application:

   ./metro

## 📖 Sample Usage

Enter the start station: Miyapur  
Enter the end station: Ameerpet

Shortest path from Miyapur to Ameerpet:  
Miyapur JNTU College KPHB Colony Kukatpally Balanagar Moosapet Bharat Nagar Erragadda ESI Hospital SR Nagar Ameerpet  
Time: 25 minutes  
Distance: 11.8 km

## 📍 List of Some Available Stations

The network includes all major stations across the Red, Blue, and Green lines such as:

- Miyapur
- Ameerpet
- LB Nagar
- Raidurg
- Parade Grounds
- Nagole
- Secunderabad East
- Musarambagh
- Dilsukhnagar
- Hitec City
- Begumpet
- Khairatabad  
... and many more (total: 55+ stations)

⚠️ Make sure to type station names exactly as in the list (case-sensitive).

## 🙋 Author

**Shravan Bhangdiya**  
Email: shravanbhangdiya45@gmail.com  



## 🤝 Contributing

Pull requests are welcome! If you’d like to:

- Add new stations  
- Improve the algorithm  
- Extend features (e.g., fare calculation, line colors, transfer stations)  

Feel free to fork this repo and contribute.

## ⭐ Show Your Support

If you find this project useful, don’t forget to ⭐ star the repository!
