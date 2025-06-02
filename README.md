# DevOps Project: Peppermint Ticketing + LibreNMS Monitoring

This project automates the deployment of the open-source **Peppermint** ticketing system on an Ubuntu server using **Ansible**, along with setting up **LibreNMS** on a second server to monitor the first.

The system is secured with **Let’s Encrypt SSL certificates** for both Peppermint and LibreNMS, and the first server is integrated into LibreNMS monitoring using an **API key**.

---

## 🚀 Features

✅ Automated deployment of Peppermint ticketing system via Ansible  
✅ Separate LibreNMS monitoring server setup  
✅ Secure web interfaces (HTTPS) using Let’s Encrypt SSL  
✅ LibreNMS monitors Peppermint server via API integration  
✅ Scalable, reproducible infrastructure setup

---

## 🏗️ Stack

- **Peppermint** (open-source ticketing system)  
- **LibreNMS** (network and server monitoring)  
- **Ansible** (automation)  
- **Ubuntu Server**  
- **Let’s Encrypt** (SSL certificates)

---

## 🔑 API & Monitoring Integration

- The Peppermint server is added to LibreNMS using an API key.
- SSL ensures secure communication between services.

---

## 🛡️ Security

- Let’s Encrypt free SSL certificates set up on both servers.

---

## 🤝 Contributions

Feel free to open issues or pull requests to improve the automation or add features.

---

## 📄 License

MIT License (or whichever license applies to your project)
