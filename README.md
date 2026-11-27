
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

The platform uses **perceptual image hashing (pHash)** to identify visually similar images, even when they have undergone modifications such as resizing or cropping.

Users can register multiple original images for monitoring. The backend automatically scans selected Reddit communities, processes images found in posts, and compares them against registered content. Potential matches are presented through a centralized dashboard with similarity scores and links to their source posts.

By combining image registration, automated content monitoring, image similarity detection, and backend processing, TraceIt aims to make digital content monitoring more accessible and organized.

## Key Features

### 1. Content Registration
- Upload multiple original images for monitoring.
- Generate perceptual hashes for registered content.
- Maintain information about uploaded content for subsequent comparisons.

### 2. Perceptual Image Matching
- Uses perceptual hashing (pHash) for image fingerprinting.
- Compares image fingerprints using Hamming distance.
- Identifies potentially similar images, including modified versions.

### 3. Automated Reddit Monitoring
- Automatically scans selected Reddit communities for images.
- Processes collected images for comparison against registered content.
- Identifies potential matches without requiring users to manually search through posts.

### 4. Detection Dashboard
- Centralized interface for reviewing registered content.
- Displays original images alongside potential matches.
- Provides similarity scores to help evaluate detected matches.
- Includes links to the corresponding Reddit posts for source verification.

## How It Works

1. **Content Upload:** Users register their original images on the platform.
2. **Hash Generation:** The system generates perceptual hashes (pHash) for registered images.
3. **Automated Scanning:** The backend automatically scans selected Reddit communities and collects images from posts.
4. **Image Processing:** Collected images are processed using the same perceptual hashing technique.
5. **Similarity Comparison:** Generated hashes are compared using Hamming distance to identify visually similar images.
6. **Match Identification:** Potential matches are identified and associated with similarity scores.
7. **Review:** Results are displayed on the dashboard along with the original image and source Reddit post links.

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

The project involved working with image-processing techniques, perceptual hashing, automated Reddit monitoring, backend development, external data sources, and deployment within a competitive hackathon environment.

Following the hackathon, the platform underwent further deployment work, with the frontend hosted on Vercel and the backend deployed on Render.

## Team Members

Developed collaboratively by:

| Team Member | GitHub Profile |
|---|---|
| Kushal Pureti | [@PuretiKushal](https://github.com/PuretiKushal) |
| Pilla Sai Mohit | [@mohitttt06](https://github.com/mohitttt06) |
| Siriki Taman | [@taman30](https://github.com/taman30) |
| Yandamuri Harshith Soma Sai | [@harshithyandamuri](https://github.com/harshithyandamuri) |

---

*TraceIt is a collaborative hackathon project exploring image-based approaches to digital content protection. Detected matches indicate potential similarities and should be reviewed before drawing conclusions about copyright infringement.*
