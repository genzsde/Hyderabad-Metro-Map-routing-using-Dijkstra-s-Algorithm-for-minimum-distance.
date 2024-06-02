# Getting started with this Project:-
This project was incredibly enjoyable to complete, and I gained substantial knowledge, particularly in understanding Python Flask for generating servers to run my application on a web browser.

# Step 1: Download and Set Up
First, download the project files from my GitHub repository. Extract the folder and open it in your preferred Integrated Development Environment (IDE). You should use Visual Studio Code (VSCode) for this purpose.

# Step 2: Install Dependencies and Run the Application
Navigate to the project directory where app.py is located. Open your terminal or command prompt and run the following commands to install the necessary dependencies and start the application:

![Screenshot 2024-06-02 at 7 51 02 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/40a44eda-03a1-4061-9409-cb5caff2aef6)

# Step 3: Enjoy the Application
Once the server is up and running, open your web browser and navigate to the specified local host address to start using the application.

![Screenshot 2024-06-02 at 3 27 06 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/535ef764-6e6e-4c1a-b97a-8886b4fc1760)
![Screenshot 2024-06-02 at 3 27 13 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/a84a0044-438c-45c0-8ee2-6ffc89b7de9d)
![Screenshot 2024-06-02 at 3 27 58 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/175a0b7a-0ce9-4aa4-b0f2-7133bf78da7e)
![Screenshot 2024-06-02 at 3 28 10 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/0af8fc2b-55fb-4108-9a38-fc5f194f234a)
![map](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/289a0600-eb34-447e-907c-bf725e0b3742)


# Technologies and Code Details
This project incorporates various technologies and methodologies to achieve its objectives. Here is a detailed overview of the technologies used and the core logic behind the project:

Frontend Technologies
The frontend of this project is built using the following technologies:

React: For building a dynamic and responsive user interface.
HTML: To structure the web pages.
CSS: For styling the web pages.
JSS: To apply styles in a more dynamic way within the React components.
Backend Technologies
For the backend, the project leverages Python Flask for server-side operations and integrates a crucial algorithm written in C++.

# Dijkstra Algorithm Implementation
The Dijkstra algorithm, known for finding the shortest path between nodes in a graph, is the backbone of this project. Here’s how it is implemented:

Graph Representation: The project constructs a graph representing the Hyderabad Metro Lines and their stations. This includes writing all driver code from scratch to create the nodes and edges of the graph.
Station Mapping: Stations are mapped into three sections corresponding to the metro lines (Red, Green, Blue). Each station is assigned a unique number, and these numbers are used to create connections between stations.
Pathfinding: The Dijkstra function is developed to calculate the shortest path between the user-defined source and destination. The user inputs these locations, and the function processes the input to generate the minimum path.
Output Processing: The algorithm’s output, initially in the form of station numbers, is translated back into station names. Additionally, the output specifies which metro line (Red, Green, or Blue) the path involves, providing a clear and user-friendly route.

![Screenshot 2024-06-02 at 3 28 57 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/4c1af5ad-99a3-45bc-b006-29dbd264abc9)
![Screenshot 2024-06-02 at 3 29 03 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/112dff69-d50a-41e0-a35b-b82add761f66)
![Screenshot 2024-06-02 at 3 29 11 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/d7a0739c-e170-4aea-b528-e7f641bda441)
![Screenshot 2024-06-02 at 3 29 32 PM](https://github.com/keys7/Hyderabad-Metro-Map-Minimum-Distance-Using-Dijkstra-Algorithm/assets/101874897/9982df53-6fb0-47d5-a42c-2f4bb7cae5db)


Integration with Web Browser
To bridge the gap between the C++ backend and the web interface, Flask serves as the intermediary, handling requests and responses. This allows the results of the Dijkstra algorithm to be displayed seamlessly in the web browser.

# Conclusion
By following the steps outlined above, you will be able to download, set up, and run this project efficiently. The combination of React, HTML, CSS, JSS, Python, and C++ ensures a robust and dynamic application capable of calculating and displaying the shortest paths in the Hyderabad Metro system. Enjoy exploring and using the project!
