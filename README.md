# 🖥 Netdata System Monitoring using Docker

## 🚀 Live Dashboard
> Access your system metrics at: [http://localhost:19999](http://localhost:19999)

---

## 📂 Project Structure

```bash
📁 netdata-monitoring/
├── screenshots/
│   ├── dashboard-1.png
│   ├── dashboard-2.png
│   └── docker-command.png
├── docker-run-command.txt
└── README.md

---

## 🎯 Task Objective

- Install Netdata using Docker  
- Monitor system resources: *CPU, **RAM, **Disk, **Docker containers*
- Visualize performance metrics via dashboard  
- Capture screenshots and submit as proof

---

## ⚙ Tools & Technologies Used

- *Netdata* (open-source monitoring tool)
- *Docker* (container runtime)
- *Command Line Interface* (Windows CMD/PowerShell)
- *Git & GitHub* (version control and hosting)

---

## 📸 Screenshots

> Dashboard views and running metrics:

- Dashboard Overview  
- System Metrics (CPU, RAM, Disk, Kernel)  
- Docker Run Command Output  

---

## ✍ Docker Command Used

```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata

## Author
  diyadevi21
