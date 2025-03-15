# ASSIGNMENT 1

## Architectural Styles and their Use Cases

### Gangireddy Bala Akshay  
100522729017  
B.E AIML - VI SEM  

---

## Architectural Styles and their Use Cases

### Layered
Components are organized in a layered fashion, where each layer provides services to the layer above and acts as a client to the layer below.

#### Use Cases:
- **Operating Systems:** Windows handles hardware via kernel interaction and provides user-facing applications like MS Word.
- **Web Applications:** Netflix uses this architecture to separate UI (React), services (Java-based microservices), and data (AWS DynamoDB).

---

### Client-Server
In this model, processes are divided into two groups:
- A **server** is a process implementing a specific service.
- A **client** is a process that requests a service from a server.

#### Use Cases:
- **Web Browsers and Servers:** Firefox (client) communicates with YouTube servers to stream videos.
- **Email Systems:** Microsoft Outlook (client) interacts with Exchange Server (server) to send/receive emails.
- **Database Systems:** Applications like Salesforce (client) query a central database server (e.g., Oracle or PostgreSQL).

---

### Peer-to-Peer (P2P)
A P2P architecture consists of decentralized networks of peers, where nodes act as both clients and servers.

#### Use Cases:
- **File Sharing:** BitTorrent is a P2P protocol used for sharing large files (e.g., movies, software).
- **Blockchain Networks:** Bitcoin is a P2P cryptocurrency without any central monetary authority.

---

### Batch-Sequential
Processes data in discrete steps, where each step must complete before the next begins.

#### Use Cases:
- **Scientific Simulations:** NASA weather models process collected satellite data in sequential steps like calibration, analysis, and prediction.
- **ETL Pipelines:** Companies like Walmart use batch-processing pipelines to analyze sales data overnight.

---

### Pipes and Filters
Data flows through a series of filters connected by pipes, where each filter transforms data and passes it to the next.

#### Use Cases:
- **Compilers:** GCC uses pipes & filters for lexical analysis, parsing, and code generation.
- **Image Processing:** Photoshop plugins process images in a pipeline (e.g., filter, resize, enhance).

---

### Publish-Subscribe (Pub/Sub)
Publishers send messages to a topic, and subscribers receive messages based on their interests.

#### Use Cases:
- **Real-Time Notifications:** Twitter uses Pub/Sub to push tweets to followers in real-time.
- **IoT Systems:** Smart home devices (e.g., Amazon Echo) use Pub/Sub to communicate state changes (e.g., lights on/off).
- **Stock Market Updates:** Bloomberg Terminal uses Pub/Sub to deliver real-time stock prices to traders.

---

### Model-View-Controller (MVC)
Separates the application into Model (data), View (UI), and Controller (logic).

#### Use Cases:
- **Web Frameworks:** Shopify’s admin panel separates the product catalog (model), dashboard interface (view), and user input logic (controller).
- **Mobile Apps:** Spotify’s playlist feature uses MVC to manage song data, UI interactions, and playback logic.

---

### Service-Oriented Architecture (SOA)
System is composed of loosely coupled, reusable services that communicate through APIs.

#### Use Cases:
- **Enterprise Systems:** Salesforce uses SOA to integrate CRM marketing and analytics services.
- **E-Commerce Platforms:** Amazon uses SOA to manage services like product catalog, payment, and shipping.
- **Cloud Applications:** Netflix uses SOA to manage microservices for streaming, recommendations, and user profiles.

---

### Blackboard
A shared knowledge (blackboard) base where multiple components work together to solve complex problems.

#### Use Cases:
- **Speech Recognition:** Google Assistant uses a blackboard architecture to process audio input, language models, and context.
- **Self-Driving Cars:** Tesla uses a blackboard to process sensor data, route planning, and real-time navigation.

---

### Universal Plug and Play (UPnP)
Enables devices to dynamically join a network and communicate seamlessly.

#### Use Cases:
- **Smart Home Systems:** Philips Hue lights use UPnP to connect with home automation systems.
- **Gaming Consoles:** PlayStation and Xbox automatically detect UPnP-compatible routers for seamless multiplayer gaming.
