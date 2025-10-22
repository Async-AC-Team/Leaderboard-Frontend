# Real-time Leaderboard

A full-stack system that provides real-time leaderboard tracking for users across multiple games or activities. The project demonstrates real-time data management, ranking logic, and scalable architecture using modern web technologies.

## Table of Contents

- [Overview](#overview)
- [Features](#features)

## Overview

The **Real-time Leaderboard** project provides a platform where users can:

- Register and authenticate securely.
- Submit scores for various games or activities.
- View a global leaderboard that updates dynamically.
- Track their own ranking in real time.
- Generate reports of top players for a specific time period.

The system leverages Redis sorted sets for efficient real-time leaderboard management, making it scalable and performant.

## Features

- **User Authentication:** Secure user registration and login with session or JWT-based auth.
- **Score Submission:** API endpoints to submit and update user scores.
- **Leaderboard Storage:** Uses Redis sorted sets for storing and ranking scores.
- **Real-Time Updates:** Automatic leaderboard refresh on score changes.
- **User Rankings:** Query user rank and score efficiently.
- **Top Players Report:** Generate reports for top players within a given date range.
- **Dockerized Environment:** Full stack runs via Docker for consistent setup across environments.
