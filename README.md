
# 🕵️‍♂️ **CyberSentinel** 🕵️‍♂️

![Docker](https://img.shields.io/badge/docker-ready-blue)
![Node.js](https://img.shields.io/badge/node.js-v14-green)
![MongoDB](https://img.shields.io/badge/mongodb-ready-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)

```
 ___           _   _             _              _   _
 / __| __ _  __| | (_) _ _   __  | | ___   __ _  | | (_) __
 \__ \/ _` |/ _` | | || ' \ / _| | |/ -_) / _` | | | | |/ _
 |___/\__,_|\__,_| |_||_||_|\__| |_|\___| \__,_| |_| |_|\__|

```

---

## 📜 **Overview**

**CyberSentinel** is a cybersecurity monitoring tool that leverages the power of Docker, Node.js, Express, and MongoDB to detect and manage cyber threats. It provides a sleek web interface for real-time threat visualization.

---

## 💻 **Installation**

### Prerequisites

- Docker
- Docker Compose

### Steps

1. **Clone the repository**:

    ```sh
    git clone https://github.com/yourusername/CyberSentinel.git
    cd CyberSentinel
    ```

2. **Ensure you have a `.env` file** in the root directory with the following content:

    ```
    MONGO_URI=mongodb://mongo:27017/cybersentinel
    ```

3. **Build and start the services**:

    ```sh
    docker-compose up --build
    ```

---

## 🚀 **Usage**

- **Backend API**: Accessible at `http://localhost:5000/api/threats`
- **Frontend Dashboard**: Accessible at `http://localhost:3000`

### Adding Threats

Use a tool like Postman to send a POST request to `http://localhost:5000/api/threats` with a JSON body:

```json
{
  "type": "DDoS",
  "severity": 5,
  "description": "Distributed Denial of Service attack detected."
}
```

### Viewing Threats

Open your web browser and navigate to `http://localhost:3000` to see the list of detected threats.

---

## 🛠️ **Project Structure**

```
CyberSentinel/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── app.js
│   ├── config.js
│   ├── Dockerfile
│   ├── package.json
│   ├── package-lock.json
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   ├── Dockerfile
│   ├── package.json
├── .env
├── docker-compose.yml
└── README.md
```

---

## 🧑‍💻 **Contributing**

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request.

---

## 📄 **License**

This project is licensed under the MIT License.

---

## 🎬 **Matrix Effect**

```shell
$ echo $(curl -s "https://artii.herokuapp.com/make?text=CyberSentinel&font=block")
```

```
  ____        _   _             _             _    _ _            _ _  __ _
 / ___|  ___ | |_| |_ __ _  ___| |_ __ _ _ __| | _(_) | ___      / | |/ _| | ___
 \___ \ / _ \| __| __/ _` |/ __| __/ _` | '__| |/ / | |/ _ \     | | | |_| |/ _ \
  ___) | (_) | |_| || (_| | (__| || (_| | |  |   <| | |  __/     | | |  _| |  __/
 |____/ \___/ \__|\__\__,_|\___|\__\__,_|_|  |_|\_\_|_|\___|     |_|_|_| |_|\___|
```

### ASCII Art Generator

```shell
$ echo $(curl -s "https://artii.herokuapp.com/make?text=Your+Text&font=block")
```

```
 ___           _   _             _              _   _
 / __| __ _  __| | (_) _ _   __  | | ___   __ _  | | (_) __
 \__ \/ _` |/ _` | | || ' \ / _| | |/ -_) / _` | | | | / _
 |___/\__,_|\__,_| |_||_||_|\__| |_|\___| \__,_| |_| |_|\__|

```

---

> _“The greatest glory in living lies not in never falling, but in rising every time we fall.”_ - Nelson Mandela

**Stay Secure, Stay Vigilant!**

![Matrix](https://media.giphy.com/media/3o7aD4oP8lZCi4PSA4/giphy.gif)


