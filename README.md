# Tran Quang Huy — Portfolio

Personal portfolio website — AI Researcher & Engineer.

**Live features:**
- Dark / Light mode toggle (persisted in localStorage)
- Neural network canvas animation (dark mode)
- Floating geometric shapes (light mode)
- Typing effect, scroll reveal animations, custom cursor
- Sections: Experience · Projects · Research · Skills · Awards · Education · Contact

## Run with Docker

```bash
docker pull trhuyyy13/portfolio:latest
docker run -p 8080:80 trhuyyy13/portfolio:latest
```

Open `http://localhost:8080`

## Build locally

```bash
docker build -t portfolio .
docker run -p 8080:80 portfolio
```

## Docker Hub

`hub.docker.com/r/trhuyyy13/portfolio`

---

Built with vanilla HTML/CSS/JS · Served by nginx:alpine
