# Cloud Ebook Server

A cloud-hosted ebook server built using Oracle Cloud, Docker, Calibre-Web, Google Drive, and rclone.

## Features

- Cloud-hosted ebook library
- Google Drive storage backend
- Dockerized deployment
- Accessible from browser, tablet, and Kindle
- Automated synchronization with Google Drive

## Technology Stack

- Oracle Cloud Infrastructure
- Ubuntu 24.04
- Docker
- Docker Compose
- Calibre-Web
- rclone
- Google Drive

## Architecture

Google Drive
    ↓
rclone sync
    ↓
Ubuntu VM
    ↓
Docker
    ↓
Calibre-Web
    ↓
Web Browser

## Deployment

1. Create Oracle Cloud VM
2. Install Docker
3. Configure Google Drive using rclone
4. Deploy Calibre-Web with Docker Compose
5. Configure networking and firewall rules

## Lessons Learned

- Docker volume management
- Linux networking
- Cloud firewall troubleshooting
- Persistent storage integration
- SSH tunneling
