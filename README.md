# Ollama-With-Web-UI


🚀 Local AI Deployment with Ollama, Docker & WSL
---

Empowering AI Development Locally: No Cloud, No Limits!


This project demonstrates how to deploy and serve AI models locally on a Windows machine using Ollama, Docker, and WSL (Windows Subsystem for Linux). The goal is to create a fully functional, self-hosted AI system with a ChatGPT-like Web UI, accessible both locally and remotely.
  

## 🎥 Demo Video

[![Watch the video](https://raw.githubusercontent.com/HarxSan/Ollama-With-Web-UI/main/732%20Desktop%20Wallpaper.jpg)](https://github.com/HarxSan/Ollama-With-Web-UI/blob/main/Ollama%20Demo%20With%20UI.mp4)


🛠️ Key Features
---

✔ Run AI Models Locally – No cloud dependency, full control over your models.


✔ Docker-Based Deployment – Containerized AI for ease of use.


✔ ChatGPT-Like Web UI – Seamless user interaction through image-web-ui.


✔ WSL Integration – Bringing a Linux-powered development experience to Windows.


✔ Remote Access via ngrok – Temporary exposure of the local AI server to the internet.


✔ Cost-Effective – No cloud usage fees.



📌 Why This Project?
---

With AI models becoming more powerful, self-hosting AI is now a viable alternative to cloud-based solutions. This project is a blueprint for running and interacting with AI on your own machine, offering:


Better Data Privacy – Keep sensitive AI interactions offline, unless you use ngrok.


Lower Costs – No need for expensive cloud GPUs.



🖥️ Setting Up Your Local AI
---

1️⃣ Install Ollama


First, install Ollama to manage and run AI models locally.

```
curl -fsSL https://ollama.ai/install.sh | sh
```


2️⃣ Run AI Models via CLI


Once installed, you can directly serve AI models from your command line.


```
ollama run <model_name>
```


3️⃣ Deploy AI as a Web UI (Using Docker)


For a ChatGPT-like experience, pull and run the image-web-ui inside Docker.


```
docker pull ghcr.io/<repo>/image-web-ui:latest
docker run -d -p 3000:3000 ghcr.io/<repo>/image-web-ui
```


4️⃣ Enable WSL for a Linux-Like Dev Environment on Windows


WSL seamlessly integrates Linux inside Windows, making AI development smooth and efficient.


```
wsl --install
```


Once WSL is set up, you can run AI models inside a Linux terminal on Windows, unlocking better compatibility and performance.


5️⃣ Make Your AI Public with ngrok (Optional)


Want to access your AI remotely? Use ngrok to expose your local server.


```
ngrok http 3000
```


This will generate a public URL, allowing you to access your AI model from any device.


📈 The Future of Local AI
---

The ability to run AI models efficiently without the cloud is a game-changer. Whether for research, personal projects, or enterprise applications, self-hosting AI provides unparalleled flexibility.


This is just the beginning. The future of AI is not just in the cloud—it’s local. 🚀


Let’s build the next-gen AI stack together. 🛠️


📜 License
---

This project is licensed under the MIT License – feel free to modify and expand!


📩 Contributions & Feedback
---

Got ideas for improvement? PRs & discussions are welcome! Let’s push the boundaries of self-hosted AI together. 🚀

🔗 Connect & Follow


Stay updated on my work:
---

LinkedIn: https://www.linkedin.com/in/harii-sankar-s-a0b11925a/


GitHub: https://github.com/HarxSan
