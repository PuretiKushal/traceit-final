
# TraceIt – Sports Content Piracy Detection Platform

**Helping sports organizations and content creators identify unauthorized use of their digital media.**

<p align="center">
  <a href="https://traceit-protect-your-content-create-and-test.vercel.app/">
    <img src="https://img.shields.io/badge/Live%20Demo-Explore%20TraceIt-2ea44f?style=for-the-badge" alt="Live Demo"/>
  </a>
</p>

<p align="center">
  **5th Place | SusHacks 2026 | 100+ Participating Teams**
</p>

## About the Project

TraceIt is a digital content protection platform designed to help sports organizations and content creators identify potential unauthorized usage of their original media across online platforms.

The platform uses perceptual image hashing (pHash) to identify visually similar images, even when they have undergone modifications such as resizing or cropping.

By combining image registration, image similarity detection, backend processing, and a centralized dashboard, TraceIt aims to make digital content monitoring more accessible and organized.

## Key Features

### 1. Content Registration
- Upload original images for monitoring.
- Generate perceptual hashes for registered content.
- Maintain information about uploaded content.

### 2. Perceptual Image Matching
- Uses perceptual hashing (pHash) for image fingerprinting.
- Compares image fingerprints using Hamming distance.
- Identifies potentially similar images, including modified versions.

### 3. Content Monitoring
- Designed to identify potential unauthorized usage of registered sports media.
- Includes backend functionality for processing and monitoring content.
- Supports reviewing potential matches and their sources.

### 4. Detection Dashboard
- Centralized interface for reviewing registered content.
- Displays detected matches and associated information.
- Helps organize potential copyright infringement findings.

## How It Works

1. **Content Upload:** Users register their original media.
2. **Hash Generation:** The system generates a perceptual hash for each image.
3. **Image Processing:** Images collected for comparison are processed using the same hashing technique.
4. **Similarity Comparison:** Hashes are compared using Hamming distance.
5. **Match Identification:** Potentially similar images are identified.
6. **Review:** Results can be examined through the platform.

## Tech Stack

| Category | Technologies |
|---|---|
| Frontend | Next.js, TypeScript, React |
| Styling | Tailwind CSS |
| Backend | Python, Flask |
| Database | Supabase (PostgreSQL) |
| Storage | Supabase Storage |
| Image Processing | Pillow, ImageHash |
| Detection Algorithm | Perceptual Hashing (pHash), Hamming Distance |
| Frontend Deployment | Vercel |
| Backend Deployment | Render |

## Project Repositories

The project is organized into separate frontend and backend repositories.

- **Frontend:** [imaginecup-traceit-frontend](https://github.com/mohitttt06/imaginecup-traceit-frontend)
- **Backend:** [imaginecup-traceit-backend](https://github.com/mohitttt06/imaginecup-traceit-backend)

## Hackathon Achievement

**SusHacks 2026 – April 4–5, 2026**

TraceIt was developed during SusHacks 2026, where our team secured **5th place among 100+ participating teams**.

The project involved working with image-processing techniques, backend development, external data sources, and deployment within a competitive hackathon environment.

Following the hackathon, deployment challenges were addressed and the platform was subsequently deployed.

## Team Members

Developed collaboratively by:

| Team Member | GitHub Profile |
|---|---|
| Kushal Pureti | [@PuretiKushal](https://github.com/PuretiKushal) |
| Pilla Sai Mohit | [@mohitttt06](https://github.com/mohitttt06) |
| Siriki Taman | [@taman30](https://github.com/taman30) |
| Yandamuri Harshith Soma Sai | [@harshithyandamuri](https://github.com/harshithyandamuri) |

---

*TraceIt is a collaborative hackathon project exploring image-based approaches to digital content protection.*
