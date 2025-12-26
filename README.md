# LiteCore – Low-Latency Java HTTP Server with React E-Commerce Frontend

LiteCore is a lightweight, low-latency Java HTTP server core built from scratch without heavy frameworks such as Spring or Netty.  
The project is designed to demonstrate how modern backend frameworks work internally, with a strong focus on performance, concurrency, and system-level understanding.

To simulate real-world usage, LiteCore includes a React-based e-commerce frontend that communicates directly with the backend APIs, making this a complete full-stack application.

---

## ⚙️ Tech Stack

### Backend
- Java  
- Raw TCP Sockets  
- Custom HTTP request parsing  
- Thread & connection pooling  
- Middleware-style request handling  
- Manual HTTP response construction (Text / JSON)

### Frontend
- React (JavaScript, JSX)  
- Single Page Application (SPA)  
- Component-based UI architecture  
- State-driven rendering  
- REST-style API communication  

---

## 📁 Project Structure

```text
LiteCore/
│
├── backend/
│   ├── Main.java          # Server entry point
│   ├── LiteCore.java      # Core HTTP server engine
│   ├── Request.java       # HTTP request parsing
│   ├── Response.java      # HTTP response builder
│   ├── Middleware.java   # Middleware handling
│   ├── Pool.java         # Thread / connection pooling
│
├── react-app/
│   ├── src/               # React components & application logic
│   ├── public/            # Static assets
│   └── package.json       # Frontend dependencies
│
├── demo/                  # Sample usage / demos
├── *.jar                  # Executable backend builds
└── README.md


