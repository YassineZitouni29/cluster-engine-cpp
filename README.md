# Mini Cloud Orchestrator (C++)

A simulation of a Kubernetes-style cluster built to practice **modern C++**, including custom exceptions, templates, lambdas, file I/O, and clean OOP design.

---

## ✨ Features

- **Custom exception classes** (`AllocationException`, `FileException`, etc.)
- **Server / Pod / Container** classes with resource allocation logic
- **Cluster deployment** with error handling (inactive nodes, insufficient resources)
- **Metrics export** to a text file using file streams
- **Template-based logger** (`MetricLogger<T>`)
- **Lambda expressions** for:
  - Filtering inactive servers
  - Sorting pods by container count
  - Iterating over all containers
- **Formatted output** using `std::setw`, `std::ostringstream`

---

## 🧠 What This Project Demonstrates

- Modern C++17/20 features (smart pointers, templates, lambdas)
- Exception-safe design and error propagation
- File management
- Clean, modular architecture for system simulation
- Use of STL algorithms (`sort`, `function`, `vector`, etc.)

---

## 📁 Structure

```
CloudExceptions.h
Cloud_Util.cpp
Cloud_Util.h
Container.cpp
Container.h
KubernetesCluster.cpp
KubernetesCluster.h
Makefile
MetricLogger.h
Pod.cpp
Pod.h
Resource.cpp
Resource.h
Server.cpp
Server.h

```

---

## ▶️ Build & Run

```bash
make
./main
```
