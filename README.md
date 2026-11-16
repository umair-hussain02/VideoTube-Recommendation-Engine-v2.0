# VideoTube Recommendation Engine (v2.0)

> Status: In development (started November 2026)

## Overview
This project extends VideoTube, my final year project (a full-stack video-sharing platform built with the MERN stack), with a recommendation feature.

The goal is to suggest relevant videos to each user based on their activity on the platform.

Main project: https://github.com/umair-hussain02/Video-Tube-fullstack

## Planned features
- Personalised "For You" recommendations based on:
  - Watch history
  - Liked videos
  - Subscribed channels
- "Similar videos" suggestions on the video watch page
- Trending videos based on recent views and likes
- A REST API endpoint that the VideoTube backend can call

## Planned approach
- Content-based filtering using video titles, descriptions and categories
- Collaborative filtering using patterns in user interactions
- A simple combination of both methods for the final ranking

## Planned tech stack
- Python, pandas, scikit-learn
- FastAPI for the recommendation API
- MongoDB (shared with VideoTube)

## Roadmap
- [ ] Export and prepare interaction data from VideoTube
- [ ] Content-based recommendations
- [ ] Collaborative filtering
- [ ] Trending videos logic
- [ ] API integration with the VideoTube backend
- [ ] Evaluate recommendation quality
