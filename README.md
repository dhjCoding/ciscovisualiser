Cisco Network Topology Visualizer
A web-based, interactive tool for creating, visualizing, and managing network diagrams. Built with HTML, Tailwind CSS, and D3.js, this project provides an intuitive drag-and-drop interface to map out network infrastructures, making it ideal for network engineers, students, and IT professionals.

✨ Features
Drag & Drop Interface: Easily add devices like routers, switches, and PCs to the canvas.

Device Connectivity: Create links between network devices to represent physical or logical connections.

Dynamic Layout: Utilizes the D3.js force simulation library to automatically arrange the topology in a clean, organic layout.

Interactive Elements:

Drag nodes to manually adjust their position.

Click on any device or link to view its properties.

Right-click a device for a context menu to quickly view info or delete it.

Information Panel: A dedicated panel displays details of the selected element (e.g., name, type, IP address).

Live Editing: Modify device properties like hostname and IP address directly from the UI, with changes instantly reflected on the diagram.

Responsive Design: The interface is built with Tailwind CSS to be usable across different screen sizes.

Simply open the index.html file in any modern web browser (like Chrome, Firefox, or Edge). No web server is required for the basic functionality.

🛠️ Technologies Used
HTML5: The core structure of the web page.

Tailwind CSS: A utility-first CSS framework for rapid UI development and a clean, modern look.

JavaScript (ES6+): Powers all the interactive logic and functionality.

D3.js (v7): A powerful JavaScript library for data visualization, used here for managing the network graph and running the physics-based force simulation.

Font Awesome: Provides the icons for devices and UI elements.

🔮 Future Enhancements
This project has a solid foundation that can be extended with many professional features. Here are some ideas for future development:

💾 Save & Load Topology: Implement functionality to export the current network diagram to a JSON file and import it back into the application.

📝 Export Configuration: Add a feature to generate basic Cisco IOS configuration commands based on the diagram (e.g., setting hostnames, IP addresses on interfaces).

🌐 Real-Time Status: Integrate with a backend service (e.g., using Python and WebSockets) to perform ICMP pings and display the live up/down status of links and devices.

🧩 More Device Types: Expand the toolbar with additional network elements like Firewalls, Servers, Wireless Access Points, and Cloud icons.

** VLAN & Subnetting:** Add features to color-code different VLANs or to include a subnetting calculator tool.

📝 Annotations: Allow users to add text notes and labels directly onto the canvas to better document the topology.

🤝 Contributing
Contributions are welcome! If you have ideas for new features or improvements, feel free to fork the repository, make your changes, and submit a pull request.

